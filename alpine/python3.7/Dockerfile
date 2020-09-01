# 43.5M
# 如果需要使用numpy,则需要加上apk add g++
FROM python:3.7.9-alpine3.12
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.ustc.edu.cn/g' /etc/apk/repositories && apk update
COPY pip.conf /etc
