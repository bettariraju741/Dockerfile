FROM almalinux:9
RUN dnf -y update && \
    dnf install -y nginx
CMD ["nginx", "-g", "daemon off;"]