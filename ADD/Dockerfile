FROM almalinux:9
RUN dnf install linux -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://learn.microsoft.com/en-us/windows/security/application-security/application-control/app-control-for-business/applocker/applocker-overview  /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]