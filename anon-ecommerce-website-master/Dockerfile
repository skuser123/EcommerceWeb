# Use an official Nginx image as the base image
FROM nginx:latest

# Copy website files into the container
COPY ./my-website /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]
