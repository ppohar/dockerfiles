# docker run   \
#   -it \
#   --rm \
#   -v $(pwd):/git \
#   prpohar/java:11 \
#   java    

FROM alpine:3.14
LABEL maintainer "Praveen praveen.pohar@gmail.com"

RUN apk add openjdk11

WORKDIR /app
COPY HelloWorld.java /app/
RUN javac HelloWorld.java
CMD java HelloWorld
#ENTRYPOINT [ "java", "HelloWorld" ]

