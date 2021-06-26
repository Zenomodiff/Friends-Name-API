# Friends Names API 👋🧑👩

+ An API that will return random Friends Names 🕵️🕵️‍♀️👨‍🔬
+ + Dedicated To All Friends Lovers ❤️

## Usage:

+ `https://friends-names-api.herokuapp.com` to get the documentation.
+ `https://friends-names-api.herokuapp.com/api/Friends-Names/all` to get all the Friends Names at once.
+ Change `all` to parameter `?number=` to specify the number of Friends Names you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Friends Name you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/)

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ `https://friends-names-api.herokuapp.com/api/Friends-Names?number=1` returns: ↓
```JSON
[
  {
    "Place_Name": "Jangoos"
  }
]
```

+ `https://friends-names-api.herokuapp.com/api/Friends-Names?number=2` returns: ↓
```JSON
[
  {
    "Place_Name": "Ahammed"
  }, 
  {
    "Place_Name": "Joel"
  }
]
```
