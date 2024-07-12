# Use the official PHP image with Apache
FROM php:7.4-apache

# Copy the content of the current directory to the /var/www/html directory in the container
COPY . /var/www/html/

# Expose port 80 to be accessible from outside the container
EXPOSE 80

# Grant Apache user permission to write to the directory (optional, if needed)
RUN chown -R www-data:www-data /var/www/html \
    && chmod -R 755 /var/www/html

# Enable Apache mod_rewrite (optional, if needed)
RUN a2enmod rewrite

# Set the working directory
WORKDIR /var/www/html
