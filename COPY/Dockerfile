FROM almalinux:8
RUN yum install nginx -y 
rm -rf /usr/share/nginx/html/index.html
COPY index.html
CMD ["nginx","-g","daemon off;"]