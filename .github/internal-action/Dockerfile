ARG IMAGE_TAG=$INPUT_IMAGE_TAG
# 17-jdk, 11-jdk
FROM openjdk:$IMAGE_TAG
COPY ./entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT [ /entrypoint.sh ]
