# LoggingInsideContainer

## build and run the container 
```
docker build -t my-bash-app .
docker run -d --rm my-bash-app

```
Above comments should print the container sha and remember that
## Finding logs

```
less /var/lib/docker/containers/shaofyourcontainer
```

If you want to see the live logs, do the following

```
tail -F 979a8d53469578d0dac85b250fcc181a3d08eb0d02c9cb9daca6ea160bda823d-json.log
```

