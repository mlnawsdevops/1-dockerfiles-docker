# user can this image example- onbuild:v1 is image of this Dockerfile and user use base os as FROM
# user must pass ONBUILD instruction without this user can't create image
# custom image created for others 
# This ONBUILD instruction runs only, when any user uses your image
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD copy index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]