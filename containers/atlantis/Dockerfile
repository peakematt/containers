FROM ghcr.io/runatlantis/atlantis:dev-debian

USER root

RUN apt-get update -y && \
  apt-get install -y python3 python3-pip && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/*

USER 100
