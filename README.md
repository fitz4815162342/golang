# golang
Docker image for Go development

# run 
docker run --name golang -ti fitz4815162342/golang /bin/bash


If you want to share data from a persistent directory on your host into the volume of the container:

docker run --name golang -v $(pwd)/persistent:/go/src/persistent -ti fitz4815162342/golang /bin/bash
