FROM golang:1.12.7-stretch
COPY example.go .
COPY bad_example.go .
RUN go run bad_example.go && go run example.go
