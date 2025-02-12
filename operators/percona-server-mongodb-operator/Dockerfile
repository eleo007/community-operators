FROM scratch
LABEL operators.operatorframework.io.bundle.mediatype.v1=registry+v1
LABEL operators.operatorframework.io.bundle.manifests.v1=manifests/
LABEL operators.operatorframework.io.bundle.metadata.v1=metadata/
LABEL operators.operatorframework.io.bundle.package.v1=percona-server-mongodb-operator
LABEL operators.operatorframework.io.bundle.channels.v1=stable
LABEL operators.operatorframework.io.bundle.channel.default.v1=stable
LABEL operators.operatorframework.io.metrics.builder=operator-sdk-v1.2.0
LABEL operators.operatorframework.io.metrics.mediatype.v1=metrics+v1
LABEL operators.operatorframework.io.metrics.project_layout=helm.sdk.operatorframework.io/v1
LABEL org.opencontainers.image.authors=info@percona.com
LABEL org.opencontainers.image.url=https://percona.com
LABEL org.opencontainers.image.vendor=Percona
LABEL com.redhat.openshift.versions="v4.14-v4.17"
LABEL com.redhat.delivery.backport=true
LABEL com.redhat.delivery.operator.bundle=true
COPY 1.19.1/manifests /manifests/
COPY 1.19.1/metadata /metadata/