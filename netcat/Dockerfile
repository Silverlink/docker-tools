FROM debian:jessie

RUN apt-get update && apt-get install -yq --no-install-recommends \
        netcat \
    && rm -rf /var/cache/apt/* /var/lib/apt/lists/*

ENTRYPOINT ["/bin/netcat"]
