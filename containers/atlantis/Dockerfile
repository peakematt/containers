FROM ghcr.io/runatlantis/atlantis:dev-debian

USER root


RUN add-apt-repository ppa:deadsnakes/ppa && \
  apt update -y && \
  apt install -y python3.13 python3.13-pip && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/*

USER 100
