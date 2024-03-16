# Go Dockerfile
FROM golang:1.22.1-bookworm

WORKDIR /app
COPY . .

# Build your Go application
RUN go build -o my-go-app

EXPOSE 8080

CMD ["./my-go-app"]
