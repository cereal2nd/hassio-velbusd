FROM ghcr.io/hassio-addons/base:stable

RUN \
    apk add --no-cache python3 git py3-wheel py3-pip py3-pyserial py3-typing-extensions

# extract
RUN git clone https://github.com/velbus/python-velbustcp.git velbus
RUN cd /velbus && pip install .
RUN rm -rf velbus

# Coppy rootfs
COPY rootfs /

# Build arguments
ARG BUILD_ARCH
ARG BUILD_DATE
ARG BUILD_DESCRIPTION
ARG BUILD_NAME
ARG BUILD_REF
ARG BUILD_VERSION

LABEL \
    io.hass.name="${BUILD_NAME}" \
    io.hass.description="${BUILD_DESCRIPTION}" \
    io.hass.arch="${BUILD_ARCH}" \
    io.hass.type="addon" \
    io.hass.version=${BUILD_VERSION} \
    maintainer="Maikel Punie <maikel.punie@gmail.com>" \
    org.opencontainers.image.title="${BUILD_NAME}" \
    org.opencontainers.image.description="${BUILD_DESCRIPTION}" \
    org.opencontainers.image.authors="Maikel Punie <maikel.punie@gmail.com>" \
    org.opencontainers.image.created=${BUILD_DATE} \
    org.opencontainers.image.revision=${BUILD_REF} \
    org.opencontainers.image.version=${BUILD_VERSION}
