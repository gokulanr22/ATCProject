FROM nginx:alpine

# Copy static content to the NGINX html directory
COPY ./static /usr/share/nginx/html

# Expose the HTTP port
EXPOSE 80


# Start NGINX
CMD ["nginx", "-g", "daemon off;"]

