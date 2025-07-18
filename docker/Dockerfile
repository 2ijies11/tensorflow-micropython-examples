FROM python:3.10

RUN apt-get update && apt-get install -y \
	curl \
	cmake \
	gcc \
	git \
	libusb-1.0-0 \
	make \
	&& apt-get clean \
	&& rm -rf /var/lib/apt/lists/*
