ARG NODE_VERSION="18"
FROM node:${NODE_VERSION}

# Install Zsh in a user-specific directory
RUN apt-get update && \
    apt-get install -y zsh

RUN chsh -s $(which zsh) $USERNAME