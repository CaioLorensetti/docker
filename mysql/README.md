```
docker build -t lorensetticaio/my-mysql . 
```

```
docker run -p 3306:3306 lorensetticaio/my-mysql:latest
```

Tips
In need use snap instead of apt-get to install mysql-shell
```snap install mysql-shell```
