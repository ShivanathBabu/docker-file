FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index.html
COPY shiva.html /usr/share/nginx/index.html
CMD ["nginx", "-g", "daemonoff;"]