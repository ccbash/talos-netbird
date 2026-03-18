FROM ghcr.io/netbirdio/netbird:0.66.0 AS src

FROM scratch
COPY manifest.yaml /manifest.yaml
COPY rootfs/ /rootfs/
COPY --from=src /usr/local/bin/netbird /rootfs/usr/local/lib/containers/netbird/usr/local/bin/netbird