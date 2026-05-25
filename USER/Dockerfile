FROM almalinux:9
RUN dnf install nginx -y
RUN useradd robo
USER robo
CMD ["nginx","-g","daemon off;"]