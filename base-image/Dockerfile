FROM ubuntu:18.04
RUN apt-get update \
    && apt-get install -y --no-install-recommends curl bash ca-certificates iproute2 \
    && rm -rf /var/lib/apt/lists/*
RUN curl -LO http://releases.cilium.io/v1.1.1/cilium-x86_64 && \
    chmod +x cilium-x86_64 && \
    mv cilium-x86_64 /usr/bin/cilium
CMD []
