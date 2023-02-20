NAMESPACE=GAIAD
PROJECT=cosmoshub
PROJECT_BIN=gaiad
PROJECT_DIR=.gaia
VERSION=v8.0.1
REPOSITORY=https://github.com/cosmos/gaia

.PHONY: build

build:
	docker build -t shapeshiftdao/${PROJECT}:${VERSION} \
		--build-arg NAMESPACE=${NAMESPACE} \
		--build-arg PROJECT=${PROJECT} \
		--build-arg PROJECT_BIN=${PROJECT_BIN} \
		--build-arg PROJECT_DIR=${PROJECT_DIR} \
		--build-arg VERSION=${VERSION} \
		--build-arg REPOSITORY=${REPOSITORY} ../ \
