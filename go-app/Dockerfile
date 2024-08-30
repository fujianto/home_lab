# go-app/Dockerfile
FROM golang:1.23-alpine

WORKDIR /app

COPY . .

# Download necessary Go modules
RUN go mod tidy

RUN go build -o main .

CMD ["./main"]
