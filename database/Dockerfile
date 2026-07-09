FROM mysql:5.7

# Copy SQL initialization script
COPY init.sql /docker-entrypoint-initdb.d/

# Expose MySQL port
EXPOSE 3306

# Environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=admin123
ENV MYSQL_DATABASE=bloodbank
ENV MYSQL_USER=admin
ENV MYSQL_PASSWORD=admin123

# MySQL will start automatically via the official image's entrypoint
