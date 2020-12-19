```bash
# list networks
docker network ls

# List all containers connected to network
docker network inpsect <name>

# Create a network
docker network create <name> --driver <driver_name>

# Attach a network to a container
docker network connect

# Detach a network from container
docker network disconnect

# Connect container to a network
docker network connect | disconnect <container>

```


