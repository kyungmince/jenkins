FROM ubuntu:latest
LABEL matainer tom.hong
LABEL contect tom.hong@bespinglobal.com
ENV DEBIAN_FRONTEND=noninteractive
ENV TZ=Asia/Seoul
RUN apt-get update
RUN apt-get install -y curl nginx
COPY index.html /var/www/html/index.html

CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
