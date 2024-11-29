ARG VARIANT=20-bullseye
FROM mcr.microsoft.com/devcontainers/typescript-node:1-${VARIANT}
RUN apt update && apt install -y python3-pip jq 
# install esbuild
RUN npm i -g esbuild
