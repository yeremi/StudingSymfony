
# Build for the first time
docker-compose up -d --build

# Open bash terminal 
docker exec -it php74-container bash

# Create the project
symfony new .