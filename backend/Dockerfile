FROM golang:1.20

WORKDIR /app

COPY . .

RUN go mod download
RUN go build -o /app/9o3o/backend *.go

CMD ["/app/9o3o/backend"]
