FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:16

# Install additional tools
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends git-lfs

# Install global node packages
RUN npm install -g npm@latest

# Set up environment
WORKDIR /workspace

# Set up git config
RUN git config --global pull.rebase true \
    && git config --global core.autocrlf input