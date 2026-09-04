ARG version
FROM almalinux:$(version:9)
ARG Course="Devops with raju" \
    duration="120hrs"
ENV duration=$duration
RUN echo "Course: $Course, duration: $duration, version: $version"
CMD [ "sleep","200" ]

