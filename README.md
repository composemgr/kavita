# Kavita

A self-hosted application for managing kavita.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/kavita/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/kavita" ~/.local/srv/docker/kavita
cd ~/.local/srv/docker/kavita
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install kavita
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
