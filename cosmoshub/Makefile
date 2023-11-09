GOLANG_VERSION=1.20-buster
NAMESPACE=GAIAD
PROJECT=cosmoshub
PROJECT_BIN=gaiad
PROJECT_DIR=.gaia
VERSION=v13.0.2
REPOSITORY=https://github.com/cosmos/gaia

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
