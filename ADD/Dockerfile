From almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/arunnine/robot-shop/master/docker-compose.yaml /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]