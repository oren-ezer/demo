ARG DOCKER_REGISTRY_URL

FROM ${DOCKER_REGISTRY_URL}/openjdk:8u181-jre-alpine3.8

COPY /myzips/downloads/demo-*.jar /opt/dckr-app/

WORKDIR /opt/dckr-app/

CMD ["java", "-jar", "demo-*.jar"]