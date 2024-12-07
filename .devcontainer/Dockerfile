FROM mcr.microsoft.com/playwright

RUN apt-get update && apt-get install -y git curl ca-certificates \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

CMD sleep infinity
