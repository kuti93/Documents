FROM golang:alpine
WORKDIR /root/IT-Course
COPY main.go .
RUN go build -o main main.go
EXPOSE 8080
CMD ["./main"]
