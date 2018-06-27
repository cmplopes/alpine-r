# cmplopes/alpine-r
Docker R over Alpine Linux

```
$ docker pull -t cmplopes/alpine-r:[TAG]
```

## Suported Tags

[3.5.0, latest (over alpine:edge) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/latest/Dockerfile)

[3.4.2 (over alpine:3.7) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.4.2/Dockerfile)

[3.3.3 (over alpine:3.6) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.3.3/Dockerfile)

[3.3.2 (over alpine:3.5) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.3.2/Dockerfile)


## Check R version
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:3.4.2
```
or
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:3.4.2 R --version
```

## Run a R program
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:3.4.2 R -f test.r
```
