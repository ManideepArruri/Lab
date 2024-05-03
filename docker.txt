# Use a base image with a web server
FROM nginx:alpine

# Copy the HTML files into the web server directory
COPY . /usr/share/nginx/html
