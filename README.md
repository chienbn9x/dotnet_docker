# dotnet_docker

# Step 1: build dockerfile generate image
docker build -t dotnet_docker .
# Step 2: Run images build code
docker run -it dotnet_docker
