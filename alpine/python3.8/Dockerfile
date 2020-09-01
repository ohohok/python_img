# 200M 建议使用3.7.9
# 如果需要使用numpy,则需要加上apk add g++
FROM alpine:latest
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.ustc.edu.cn/g' /etc/apk/repositories && apk update && apk add python3 gcc  libressl-dev musl-dev libffi-dev && apk add py-pip
COPY pip.conf /etc