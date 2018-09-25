# golang
Docker image for Go development

# run 
docker run --name golang -ti fitz4815162342/golang /bin/bash

If you want share data transfer between host and container:
docker run --name golang -v $(pwd)/persistent:/go/src/persistent -ti fitz4815162342/golang /bin/bash
