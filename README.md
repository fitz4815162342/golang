# golang
Docker image for Go development

# builld 
docker build . -t golang

# run 
docker run --name golang -v "$(pwd)/persistent/go":/go -it golang /bin/bash

# folder structure for bind volume
#docker context

#--persistent

#-----go

#--------bin

#--------pkg

#--------src
