FROM tomcat:8.5-alpine

ENV TZ Asia/Shanghai

RUN apk add --no-cache -U tzdata msttcorefonts-installer fontconfig ttf-dejavu
RUN update-ms-fonts && fc-cache -f
RUN rm -rf /usr/local/tomcat/webapps/*
