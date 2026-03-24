FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

# Install build-essential, gdb, and other development tools
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    software-properties-common \
    && add-apt-repository -y ppa:ubuntu-toolchain-r/test \
    && apt-get update \
    && apt-get -y install --no-install-recommends \
    build-essential \
    gcc-13 \
    g++-13 \
    cppcheck \
    valgrind \
    gdb \
    cmake \
    clang-format \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
