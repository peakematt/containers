FROM ghcr.io/runatlantis/atlantis:dev

USER root

RUN apt update -y && \
  apt install -y python3 python3-pip && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/*

USER 100
