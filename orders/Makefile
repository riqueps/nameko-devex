build-image:
	docker build -t riqueps/nameko-example-orders:$(TAG) .;

docker-tag:
	docker tag riqueps/nameko-example-orders:$(FROM_TAG) \
	riqueps/nameko-example-orders:$(TAG)

push-image:
	docker push riqueps/nameko-example-orders:$(TAG)
