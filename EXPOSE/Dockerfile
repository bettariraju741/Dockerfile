FROM almalinux:9
RUN dnf -y update && \
    dnf install -y nginx
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]