FROM jenkins/jenkins:lts
# if we want to install via apt
USER root
ENV TZ Asia/Shanghai

#RUN apt-get update && apt-get install -y ruby make more-thing-here
#使用挂载的docker.sock
RUN groupadd docker && gpasswd -a jenkins docker

# drop back to the regular jenkins user - good practice
USER jenkins
