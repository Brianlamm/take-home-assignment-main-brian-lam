FROM golang:latest
ADD . /go/src/github.com/Brianlamm/take-home-assignment-main-brian-lam/dockerize
# Build the contact_registry command inside the container.
RUN go install github.com/Brianlamm/take-home-assignment-main-brian-lam/dockerize@latest
# Run the contact_registry command when the container starts.
ENTRYPOINT /go/bin/dockerize
# http server listens on port 8080.
EXPOSE 8080
