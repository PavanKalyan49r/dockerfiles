FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/PavanKalyan49r/devops-practice/master/example.txt /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]