FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/sunilsurya0112/dockerfiles/blob/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r index.html
CMD ["nginx", "-g", "daemon off;"]