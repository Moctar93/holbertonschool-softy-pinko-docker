
FROM nginx:latest

# Copy the softy-pinko-front-end files to the appropriate directory in the Docker image
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the custom Nginx config file to the correct location
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

# Install Flask using pip3
RUN pip3 install flask

# Install flask-cors to enable CORS
RUN pip3 install flask-cors
