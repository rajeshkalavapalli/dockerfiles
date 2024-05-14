FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
add https://raw.githubusercontent.com/daws-76s/roboshop-shared-library/main/vars/nodejsVM.groovy /usr/share/nginx/html/index.html 
CMD ["nginx","-g","daemon off;"]