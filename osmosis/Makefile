GOLANG_VERSION=1.19-buster
NAMESPACE=OSMOSISD
PROJECT=osmosis
PROJECT_BIN=osmosisd
PROJECT_DIR=.osmosisd
VERSION=v15.1.2
REPOSITORY=https://github.com/osmosis-labs/osmosis

.PHONY: build

build:
	docker build -t shapeshiftdao/${PROJECT}:${VERSION} \
		--build-arg GOLANG_VERSION=${GOLANG_VERSION} \
		--build-arg NAMESPACE=${NAMESPACE} \
		--build-arg PROJECT=${PROJECT} \
		--build-arg PROJECT_BIN=${PROJECT_BIN} \
		--build-arg PROJECT_DIR=${PROJECT_DIR} \
		--build-arg VERSION=${VERSION} \
		--build-arg REPOSITORY=${REPOSITORY} ../ \
