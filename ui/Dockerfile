# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Set the working directory
WORKDIR /usr/share/nginx/html

# Copy the frontend code (HTML, CSS, JS) into the container
COPY . .

# Expose port 80 for the web server
EXPOSE 80

# Nginx will automatically start the server in the background
CMD ["nginx", "-g", "daemon off;"]
