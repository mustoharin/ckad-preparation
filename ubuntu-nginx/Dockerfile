FROM ubuntu
RUN apt update -y && apt install nginx -y
ADD index.html /var/www/html
EXPOSE 80
CMD nginx -g "daemon off;"

