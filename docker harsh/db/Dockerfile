# Use the official MariaDB image
FROM mariadb:latest

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=12345
ENV MYSQL_DATABASE=mydatabase

# Initialize the database
COPY ./init/init.sql /docker-entrypoint-initdb.d/

