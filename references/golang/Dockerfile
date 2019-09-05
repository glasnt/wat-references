FROM golang:1.12.7-stretch
ENV GO111MODULE off
RUN go get -u github.com/motemen/gore/cmd/gore
COPY intro .
CMD ./intro && gore
