```
docker build -t lorensetticaio/my-nginx:latest .
```

```
docker run -p 8080:80 lorensetticaio/my-nginx:latest
```

To publish on Docker Hub
```
docker push lorensetticaio/my-nginx:latest
```