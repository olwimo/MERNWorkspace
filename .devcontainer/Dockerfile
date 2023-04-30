FROM mcr.microsoft.com/devcontainers/typescript-node:0-18-bullseye

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    pandoc wkhtmltopdf

# WORKDIR /workspace/src
