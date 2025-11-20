FROM nginx:alpine

# Copy nginx configuration
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Create necessary directories
RUN mkdir -p /var/cache/nginx/client_temp

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

