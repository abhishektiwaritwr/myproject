# Dockerfile
FROM nginx:stable-alpine
LABEL maintainer="you@example.com"

# Remove default nginx html and copy site
RUN rm -rf /usr/share/nginx/html/*
COPY ./ /usr/share/nginx/html/

# Expose default nginx port
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
