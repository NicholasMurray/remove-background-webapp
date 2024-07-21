# Remove background image

A simple flask app to remove the background of an image with [Rembg](https://github.com/danielgatis/rembg)

## Run it locally

```
pip install -r requirements.txt
python app.py
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
docker run -p 6006:6006 removebg
```

## URL

```
http://localhost:8000/
```

or

```
http://127.0.0.1:8000/
```
