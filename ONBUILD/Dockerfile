FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;"]
#ONBUILD COPY index.html /usr/share/nginx/html/index.html-->this command worked in only who are used my image