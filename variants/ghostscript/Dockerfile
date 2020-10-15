FROM debian:testing-slim

RUN apt update \
    && apt install -y --no-install-recommends \
        ghostscript

COPY ./root /
RUN chmod +x /entrypoint

CMD [ "/entrypoint"]
