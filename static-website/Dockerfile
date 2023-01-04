FROM golang:latest

# Set the working directory to the root of the project
WORKDIR /app

# Copy the entire project into the working directory
COPY . .

# Build the Go project
RUN go build -o main .

# Run the built binary when the container is started
CMD ["./main"]