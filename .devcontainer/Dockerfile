FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && apt-get install -y git curl && \
    curl -fsSL https://bootstrap.pypa.io/get-pip.py | python3 && \
    pip install planemo
