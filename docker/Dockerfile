FROM nginx:alpine
COPY . /usr/share/nginx/html
COPY docker/nginx.conf /etc/nginx/

EXPOSE 80
EXPOSE 443
EXPOSE 3000
CMD ["nginx","-g","daemon off;"]