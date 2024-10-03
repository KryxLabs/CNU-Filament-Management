FROM grafana/grafana-oss AS grafana


# Use the official Nginx image as a base image
FROM nginx:alpine

# Expose port 80 for the web server
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
