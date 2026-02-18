# we are not giving root access to container if we give it will access the host volume means security issues
#1
# FROM almalinux:9
# RUN dnf install nginx -y
# CMD ["nginx", "-g", "daemon off;"]

#2
FROM almalinux:9
RUN useradd expense
USER expense
CMD ["sleep", "100"]