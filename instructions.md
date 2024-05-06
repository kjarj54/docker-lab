#  Build image
docker build -t example-node-image .

# Run a new container

docker run -d -p 3000:3000 --name example-node-container example-node-image

# Other commands
docker stop example-node-container
docker rm example-node-container

## combo
docker rm -f example-node-container