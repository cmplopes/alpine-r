# cmplopes/alpine-r
Docker R over Alpine Linux

```
$ docker pull -t cmplopes/alpine-r:[TAG]
```

## Suported Tags

[3.6.0, latest - (R 3.6.0-r1 over alpine:3.10) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.6.0/Dockerfile)

[3.5.1 - (R 3.5.1-r1 over alpine:3.9) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.5.1/Dockerfile)

[3.5.0 - (R 3.5.0-r1 over alpine:3.8) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.5.0/Dockerfile)

[3.4.2 - (R 3.4.2-r0 over alpine:3.7) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.4.2/Dockerfile)

[3.3.3 - (R 3.3.3-r0 over alpine:3.6) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.3.3/Dockerfile)

[3.3.2 - (R 3.3.2-r0 over alpine:3.5) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.3.2/Dockerfile)


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
