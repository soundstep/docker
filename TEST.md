### Remove containers:

	docker rm $(docker ps -a -q)

### Remove images

	docker rmi $(docker images -q)
