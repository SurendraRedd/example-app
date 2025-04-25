# example-app
A sample web app that serves up a picture.

## Test locally
```console
docker build -t example-app:latest .
docker run -it --rm -p 8080:80 example-app
```

### Open browser
http://localhost:8080