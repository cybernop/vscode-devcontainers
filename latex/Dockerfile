ARG VERSION

FROM mcr.microsoft.com/devcontainers/base:$VERSION

RUN apt update \
    && apt install software-properties-common -y \
    && add-apt-repository universe \
    && apt remove software-properties-common -y

RUN apt install texlive-full -y
