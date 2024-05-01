FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/PavanKalyan49r/shell-script/main/01-hello-world.sh /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]