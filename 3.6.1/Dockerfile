FROM alpine:edge
MAINTAINER Carlos Lopes "cmplopes67@gmail.com"

RUN apk add --no-cache bash bash-doc bash-completion
RUN apk add --no-cache R
RUN apk add --no-cache R-dev
RUN apk add --no-cache R-doc

WORKDIR /app
CMD R --version
