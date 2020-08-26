# 43.5M
FROM python:3.7.9-alpine3.12
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.ustc.edu.cn/g' /etc/apk/repositories && apk update
COPY pip.conf /etc
