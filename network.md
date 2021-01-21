## Basics
```bash
# list networks
docker network ls

# List all containers connected to network
docker network inpsect <name>

# Create a network
docker network create <name> --driver <driver_name>

# Connect container to a network
docker network [connect | disconnect] <network> <container>

```