build-image:
	docker build -t riqueps/nameko-example-gateway:$(TAG) .;

docker-tag:
	docker tag riqueps/nameko-example-gateway:$(FROM_TAG) \
	riqueps/nameko-example-gateway:$(TAG)

push-image:
	docker push riqueps/nameko-example-gateway:$(TAG)
