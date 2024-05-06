# Start the Services
docker-compose up -d

# Verify the Containers are Running
docker-compose ps

# Access the Applications
## WordPress
http://localhost:8000
## phpMyAdmin
http://localhost:8080

# Make Changes or Debug
docker-compose down
docker-compose up -d

# Stopping the Services
docker-compose down
docker-compose down --volumes

# Checking Logs
docker-compose logs

