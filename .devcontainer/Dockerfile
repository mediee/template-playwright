FROM mcr.microsoft.com/playwright:v1.49.0-jammy

RUN apt-get update && apt-get install -y git curl ca-certificates \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

CMD sleep infinity
