FROM openjdk:8-alpine

ENV TZ Asia/Shanghai

RUN apk add --no-cache -U tzdata msttcorefonts-installer fontconfig ttf-dejavu
RUN update-ms-fonts && fc-cache -f
