# cmplopes/alpine-r
Docker R over Alpine Linux

```
$ docker pull cmplopes/alpine-r:[TAG]
```

## Suported Tags

[4.1.2, latest - (R 4.1.2-r0 over alpine:3.15) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/4.1.2/Dockerfile)

[4.0.3 - (R 4.0.3-r0 over alpine:3.13) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/4.0.3/Dockerfile)

[3.6.3 - (R 3.6.3-r2 over alpine:3.12) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.6.3/Dockerfile)

[3.6.2 - (R 3.6.2-r0 over alpine:3.11) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.6.2/Dockerfile)

[3.5.1 - (R 3.5.1-r1 over alpine:3.9) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.5.1/Dockerfile)

[3.4.2 - (R 3.4.2-r0 over alpine:3.7) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.4.2/Dockerfile)

[3.3.3 - (R 3.3.3-r0 over alpine:3.6) (Dockerfile)](https://github.com/cmplopes/alpine-r/blob/master/3.3.3/Dockerfile)


## Check R version
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:4.1.2
```
or
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:4.1.2 R --version
```
 
## Run a R program
```
$ docker run --rm -it -v $(pwd):/app cmplopes/alpine-r:4.1.2 R -f test.r
```
