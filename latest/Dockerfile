FROM alpine:3.13
LABEL maintainer="Carlos Lopes (cmplopes67@gmail.com)"

RUN apk add --no-cache bash bash-doc bash-completion
RUN apk add --no-cache R
RUN apk add --no-cache R-dev

WORKDIR /app
CMD R --version
