FROM debian:latest

RUN apt-get update && apt-get upgrade -y && apt-get install -y \
    curl \
    wget \
    git \
    build-essential \
    nano \
    vim \
    unzip
    
ENTRYPOINT ["tail", "-f", "/dev/null"]

CMD ["/bin/bash"]