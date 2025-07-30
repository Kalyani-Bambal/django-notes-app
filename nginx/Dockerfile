# Use official Nginx image
FROM nginx:1.23.3-alpine

# Remove the default Nginx config if needed (optional but good for clarity)
RUN rm /etc/nginx/conf.d/default.conf

# Copy your custom configuration file
COPY ./default.conf /etc/nginx/conf.d/default.conf
