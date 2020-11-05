docker/build:
	git clone https://github.com/opendistro-for-elasticsearch/opendistro-build || (cd opendistro-build ; git pull); \
	helm package opendistro-build/helm/opendistro-es;

helm/index:
	helm repo index .