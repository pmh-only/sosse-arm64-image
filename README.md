# 📦 `pydio-arm64-image`
Automatically build ARM64 container image for SOSSE server.

## Quick preview
Simply,
```
docker run -itp 8080:80 ghcr.io/pmh-only/sosse
```

## docker-compose
```yml
version: '3'

services:
  mindustry:
    image: ghcr.io/pmh-only/sosse
    restart: always
    tty: true
    stdin_open: true
    ports:
      - '8080:80'
```
