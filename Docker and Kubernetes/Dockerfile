#  Nginx image
FROM nginx:latest
WORKDIR /usr/share/nginx/html
COPY my-web-app.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
