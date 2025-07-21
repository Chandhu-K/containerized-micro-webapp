FROM mysql:8.0.33
LABEL Author="Chandhu K"
LABEL Version="1.0"
LABEL Description="Dockerfile for MySQL database for micro-project"

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=vprodbpass
ENV MYSQL_DATABASE=accounts

# ADD the database backup into the container
ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

# The .sql file in /docker-entrypoint-initdb.d/ will be automatically imported at container startup

# Expose MySQL port
EXPOSE 3306