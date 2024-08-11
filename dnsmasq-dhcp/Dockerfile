ARG BUILD_FROM
FROM $BUILD_FROM
# FROM ghcr.io/home-assistant/amd64-base:3.20

# Add env
ENV LANG C.UTF-8

# Setup base
RUN apk add --no-cache dnsmasq

# Copy data
COPY rootfs /

