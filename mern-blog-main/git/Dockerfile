# Use the official NGINX image to serve the React app
FROM nginx:alpine

# Copy the built React app (after running `npm run build`) to NGINX's public directory
COPY frontend/build/ /usr/share/nginx/html

# Expose port 80 for the NGINX server
EXPOSE 80

# Start the NGINX server
CMD ["nginx", "-g", "daemon off;"]
