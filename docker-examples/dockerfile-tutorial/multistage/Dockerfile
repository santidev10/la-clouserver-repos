FROM golang:alpine AS builder
WORKDIR /go/src/app
COPY main.go .
ENV GO111MODULE=off
RUN go build -o webserver .

FROM alpine
WORKDIR /app
COPY --from=builder /go/src/app/ /app/
CMD ["./webserver"]
