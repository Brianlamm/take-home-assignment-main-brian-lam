FROM golang:latest
# Set the Current Working Directory inside the container
WORKDIR $GOPATH/src/github.com/Brianlamm/take-home-assignment-main-brian-lam/dockerize

# Copy everything from the current directory to the PWD (Present Working Directory) inside the container
#COPY . .

#ENTRYPOINT /go/bin/dockerize
# This container exposes port 8080 to the outside world


COPY . .

# Build the golang-docker command inside the container.
RUN go install github.com/Brianlamm/take-home-assignment-main-brian-lam/dockerize

# Run the golang-docker command when the container starts.
ENTRYPOINT /go/bin/take-home-assignment-main-brian-lam/dockerize

EXPOSE 8080