# what are the parts opened by container...no functionality
# EXPOSE instruction does not actually publish the port
FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx", "-d", "daemon off;"]