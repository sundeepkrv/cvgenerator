# Teacher Resume Builder
A one-of-a-kind online resume builder for teaching professionals to build their online presence and professional reach out (developed in flask)

## Demo

You can go to https://skrv-cvgenerator.onrender.com for live working website.

## Screenshots

### Homepage
![Homepage](https://raw.githubusercontent.com/sundeepkrv/cvgenerator/main/screenshots/homepage.png)

### Sample Resume
![Sample Resume](https://raw.githubusercontent.com/sundeepkrv/cvgenerator/main/screenshots/samplresume.png)

## Development

This app has been developed in flask using python.

## Deployment

### For Unix/MacOS

Clone the project

```bash
  git clone https://github.com/sundepkrv/cvgenerator.git
```

Go to the project directory

```bash
  cd cvgenerator
```

Create a virtual environment and install requirements

```bash
  python3 -m venv venv
  source ./venv/bin/activate
  pip install -r requirements.txt
```

Start the server for local deployment

```bash
  python3 flask_app.py
```

Using gunicorn for production deployment

```bash
  gunicorn --workers:2 flask_app:app
```

### For Windows

Clone the project

```bash
  git clone https://github.com/sundepkrv/cvgenerator.git
```

Go to the project directory

```bash
  cd cafe42
```

Create a virtual environment and install requirements

```bash
  python -m venv venv
  .\venv\Scripts\activate
  pip install -r requirements.txt
```

Start the server for local deployment

```bash
  python3 flask_app.py
```

Using gunicorn for production deployment

```bash
  gunicorn --workers:2 flask_app:app
```

### Running behind a proxy network
If you are trying to install the dependencies behind a proxy network, run the following - 

```bash
  pip --proxy=http://xxx.xxx.xxx.xxx:yyyy install -r requirements.txt
```
## Tech Stack

**Client:** HTML, Bootstrap, Javascript, jQuery

**Server:** Flask

## Errors

The app may run into errors and you can debug the same using references from error traceback calls.

## Feedback and contact

[@sundeepkrv](https://github.com/sundeepkrv)
