# Use the lightweight Alpine version of Nginx
FROM nginx:alpine

# Copy all your static files into Nginx's web root
COPY . /usr/share/nginx/html

# Optional: Copy a custom nginx config (recommended for better performance & SPA support)
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 80
EXPOSE 81 1112

# Nginx runs by default
CMD ["nginx", "-g", "daemon off;"]