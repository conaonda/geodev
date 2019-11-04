FROM mcr.microsoft.com/dotnet/core/sdk:2.2

RUN apt-get update \
    && apt-get install -y --quiet --no-install-recommends build-essential libeigen3-dev libgdal-dev libtiff-dev python-dev swig \
    && rm -rf /var/lib/apt/lists/*