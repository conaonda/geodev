FROM mcr.microsoft.com/dotnet/core/sdk:3.0

RUN apt-get update \
    && apt-get install -y --quiet --no-install-recommends build-essential libeigen3-dev libgdal-dev libtiff-dev python-dev swig \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*