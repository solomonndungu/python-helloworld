FROM golang:alpine

WORKDIR /go/src/app

# Copy from the current directory on the local host to
# the directory in the running container
ADD . .

RUN go mod init

# To build the application and specify output
RUN go build -o helloworld 

# Expose the port
EXPOSE 6111

CMD ["./helloworld"]

