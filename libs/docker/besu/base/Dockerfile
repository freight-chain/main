FROM hyperledger/besu:1.4.5

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && \
    apt-get install -y build-essential libsodium-dev \
    tmux wget iperf3 curl apt-utils iputils-ping expect git git-extras \
    software-properties-common openssh-server

RUN ln -s /opt/besu/bin/besu /usr/local/bin/besu
WORKDIR /

ENTRYPOINT ["/bin/bash"]