build-image:
	docker build -t riqueps/nameko-example-gateapi:$(TAG) .;

docker-tag:
	docker tag riqueps/nameko-example-gateapi:$(FROM_TAG) \
	riqueps/nameko-example-gateapi:$(TAG)

push-image:
	docker push riqueps/nameko-example-gateapi:$(TAG)
