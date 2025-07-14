FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/shar/nginx/html/index.html
ADD https://github.com/daws-84s/notes/blob/main/session-50.txt /usr/shar/nginx/html/index.html
RUN chmod +r /usr/shar/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]