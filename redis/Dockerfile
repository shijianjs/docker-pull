# 这个镜像里面已经有tzdata，并且工具比精简版的debian的那个更齐全，包括ps，vi，ls带颜色，tzdata等
FROM redis:5-alpine

# dig命令
RUN apk add --no-cache -U bind-tools

