

FROM golang:1.8.5-jessie
# create a working directory
WORKDIR /go/dockerize/app
# add source code
COPY . /dockerize
# run main.go
CMD ["go", "run", "/dockerize/webserver.go"]