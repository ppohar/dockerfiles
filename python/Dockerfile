# docker run   \
#   -it \
#   --rm \
#   -v $(pwd):/git \
#   prpohar/python:3 \
#   python    

FROM alpine
LABEL maintainer "Praveen praveen.pohar@gmail.com"

RUN apk -v --update add \
        --no-cache \
        python3 \
        py3-pip \
        && \
        pip install mkdocs

CMD /bin/bash
