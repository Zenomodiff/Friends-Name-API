# Friends Names API 👋🧑👩

## Introduction

- An API that will return random Friends Names 🕵️🕵️‍♀️👨‍🔬
- Dedicated To All Friends Lovers ❤️

## Usage

- [https://friends-names-api.herokuapp.com](https://friends-names-api.herokuapp.com/api/Friends-Names?number=1) to get the documentation.
- [https://friends-names-api.herokuapp.com/api/Friends-Names/all](https://friends-names-api.herokuapp.com/api/Friends-Names?number=1) to get all the Friends Names at once.
- Change `all` to parameter `?number=` to specify the number of Friends Names you want to receive.
- Change `all` to parameter `?index=` to specify the index of the Friends Name you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/).

## Rebuild the project

1. Clone the repo.
2. Run `python -m venv .env` to create a virtual environment.
3. Run `source .env/bin/activate` to activate the virtual environment.
4. Run `pip install requirements.txt`.
5. Run `python app.py`.
6. App starts at `http://localhost:5000` by default, but can be configured with a `.env` file.

## Run Dockerfile

1. cd into the repository.
2. Run the following command to build the docker file:-

   ```bash
   docker build -t friends-name-api:1.0.0 `pwd`
   ```

3. Run the built docker image with the following command:-

   ```bash
   docker run -d -p 80:5000 friends-name-api:1.0.0
   ```

4. Visit the URL localhost/ in the browser to view the data.

## Example

- [https://friends-names-api.herokuapp.com/api/Friends-Names?number=1](https://friends-names-api.herokuapp.com/api/Friends-Names?number=1) returns: ↓

```JSON
[
  {
    "Place_Name": "Jangoos"
  }
]
```

- [https://friends-names-api.herokuapp.com/api/Friends-Names?number=2](https://friends-names-api.herokuapp.com/api/Friends-Names?number=1) returns: ↓

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
