FROM nginx:alpine
# Copy the static frontend code into Nginx's default public directory
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
