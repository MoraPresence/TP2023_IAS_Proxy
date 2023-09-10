FROM golang:1.21

WORKDIR /app
COPY bin .
RUN go mod download
RUN go build cmd/bin/main.go

EXPOSE 8080
