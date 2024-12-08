IMAGE = quay.io/note_minamoto/helloweb
TAG   = v1.0

all: build push

build:
	podman build -t $(IMAGE):$(TAG) .

push:
	podman push $(IMAGE):$(TAG)

clean:
	podman rmi $(IMAGE):$(TAG)

	
