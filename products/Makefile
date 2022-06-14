build-image:
	docker build -t riqueps/nameko-example-products:$(TAG) .;

docker-tag:
	docker tag riqueps/nameko-example-products:$(FROM_TAG) \
	riqueps/nameko-example-products:$(TAG)

push-image:
	docker push riqueps/nameko-example-products:$(TAG)
