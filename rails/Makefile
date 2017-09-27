IMAGE_NAME=alvlapo/rails
VERSION=`git describe --tags`

build:
	docker build -t $(IMAGE_NAME):$(VERSION) --rm .

push:
	docker push $(IMAGE_NAME)
