# Base on offical NGINX Alpine image
FROM nginx:alpine

# Copy config files
# *.conf files in conf.d/ dir get included in main config
COPY ./nginx/nginx.conf /etc/nginx/nginx.conf

# Expose the listening port
EXPOSE 80
