# Remove background image

A simple flask app to remove the background of an image with [Rembg](https://github.com/danielgatis/rembg)

## Run it locally

### Install dependencies and run

```
pip install -r requirements.txt
python3 app.py
```

### Local URLs

```
http://localhost:5100/
```

or

```
http://127.0.0.1:5100/
```

## Run it with docker compose

### Run docker with compose

```
sudo docker compose up --build
```

### Stop docker with compose

```
ctrl + c
```

## Run docker without compose

### Build docker

```
docker build -t removebg .
```

### Run docker

```
docker run -p 8000:5100 removebg
```

## Docker URLs

```
http://localhost:8000/
```

or

```
http://127.0.0.1:8000/
```
