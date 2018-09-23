# golang
Docker image for Go development

# builld image
docker build . -t golang

# run container; persistent folder structure
#docker context

#--persistent

#-----go

#--------bin

#--------pkg

#--------src

docker run --name golang -v "$(pwd)/persistent/go":/go -it golang /bin/bash
