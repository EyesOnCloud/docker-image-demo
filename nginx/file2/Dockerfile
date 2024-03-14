FROM ubuntu:18.04   
RUN  apt-get -y update && apt-get -y install nginx
COPY file2/default /etc/nginx/sites-available/default
COPY file2/index2.html /usr/share/nginx/html/index2.html
EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
