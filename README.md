# Friends Names API 👋🧑👩

## Introduction

- An API that will return random Friends Names 🕵️🕵️‍♀️👨‍🔬
- Dedicated To All Friends Lovers ❤️

## Usage

- ### [`https://friendsnameapi.herokuapp.com/`](https://friendsnameapi.herokuapp.com/) to get the documentation.
- ### [`https://friendsnameapi.herokuapp.com/api/Friends-Name/all`](https://friendsnameapi.herokuapp.com/api/Friends-Name/all) to get all the Friends Names at once.
- Change `all` to parameter `?number=` to specify the number of Friends Names you want to receive.
- Change `all` to parameter `?index=` to specify the index of the Friends Name you are targeting.

This project is hosted on [Heroku](https://www.heroku.com/) with zenomodiffofficial@gmail.com

## Rebuild the project

1. Clone the repo.
2. Run `python -m venv .env` to create a virtual environment.
3. Run `source .env/bin/activate` to activate the virtual environment.
4. Run `pip install requirements.txt`.
5. Run `python app.py`.
6. App starts at `http://localhost:5000` by default, but can be configured with a `.env` file.


4. Visit the URL localhost/ in the browser to view the data.

## Example

- ### [https://friendsnameapi.herokuapp.com/api/Friends-Name?number=1](https://friendsnameapi.herokuapp.com/api/Friends-Name?number=1) returns: ↓

```JSON
[
  {
    "Place_Name": "Jangoos"
  }
]
```

- ### [https://friendsnameapi.herokuapp.com/api/Friends-Name?number=2](https://friendsnameapi.herokuapp.com/api/Friends-Name?number=2) returns: ↓

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
