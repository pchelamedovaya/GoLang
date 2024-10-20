FROM golang:1.23-alpine

WORKDIR /app

RUN go install github.com/air-verse/air@latest

COPY ./app .

EXPOSE 8089

CMD [ "air" ]
