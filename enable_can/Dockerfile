FROM ghcr.io/home-assistant/aarch64-base:latest

# Install requirements for add-on
RUN apk add --no-cache iproute2 can-utils

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
