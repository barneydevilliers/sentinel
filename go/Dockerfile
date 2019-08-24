FROM golang:1.12.4-alpine3.9
WORKDIR /go/src/sentinel
RUN apk --update --upgrade add --no-cache git

RUN go get -u github.com/streadway/amqp