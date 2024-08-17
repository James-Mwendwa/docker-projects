# Use nginx image from Docker Hub
FROM nginx:alpine

# Copy index.html file to the Nginx Html directory
COPY index.html /usr/share/nginx/html/index.html

# Expose to port 80
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]