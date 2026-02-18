# docker build -t arg:v1 --build-arg course=docker .

#1
# FROM almalinux:9
# ARG course="DevOps with AWS" \
#     duration="120hrs"
# RUN echo "course:${course}, duration: ${duration}"
# CMD ["sleep", "100"]


#2
# FROM almalinux:9
# ENV course="DevOps with AWS" \
#     duration="120hrs"
# RUN echo "course:${course}, duration: ${duration}"
# CMD ["sleep", "100"]

#3
ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120hrs"
RUN echo "course:${course}, duration:${duration}, version:$version"
CMD ["sleep", "100"]


# how can i access ARG values inside container?

# ARG version
# FROM almalinux:${version:-9}
# ARG course="DevOps with AWS" \
#     duration="120hrs"
# ENV duration=$duration
# RUN echo "course:${course}, duration:${duration}, version:$version"
# CMD ["sleep", "100"]