FROM golang:latest
# Set the Current Working Directory inside the container
WORKDIR $GOPATH/src/github.com/Brianlamm/take-home-assignment-main-brian-lam/dockerize

# Copy everything from the current directory to the PWD (Present Working Directory) inside the container
COPY . .

# This container exposes port 8080 to the outside world
EXPOSE 8080

# Run the executable
CMD ["dockerize"]
