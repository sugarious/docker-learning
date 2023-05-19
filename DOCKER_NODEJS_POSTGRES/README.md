# Create a Postgres Configuration
see DockerFile

# Build Container
docker build -t my-postgres-image .

# Run the Container
docker run -p 5433:5432 -d postgres-image

# Now run psql to contact the postgres
psql -h localhost -p 5433 -U postgres

# For Stopping Docker Services
docker stop <NAME>