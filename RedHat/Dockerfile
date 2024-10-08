FROM registry.access.redhat.com/ubi8/ubi:latest


RUN dnf update -y && dnf install -y \
    curl \
    vim \
    git \
    && dnf clean all


WORKDIR /app


CMD ["bash"]
