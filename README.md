# Docker-xenial

Ubuntu 17.04 64bits
From official source
## build

launch the script to get the source image

	scripts/get-tar-amd64.sh

Build the docker image
	
	docker build -t myrepo/docker-xenial .

Push to dockerhub

	docker login
	
	docker push myrepo/docker-xenial

and Voila !
