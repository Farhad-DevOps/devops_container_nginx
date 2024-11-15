# Use the official Nginx image as the base
FROM nginx:latest

# Remove the default Nginx index page
RUN rm /usr/share/nginx/html/index.html

# Copy the custom index.html into the Nginx web directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 for Nginx
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
