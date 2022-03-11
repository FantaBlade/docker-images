FROM ubuntu:focal

RUN apt-get update \
    && apt-get install -y tzdata libcurl4 libssl-dev openssl \
    && rm -r /var/lib/apt/lists/* \
    && apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false