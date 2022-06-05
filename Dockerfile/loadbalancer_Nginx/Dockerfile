FROM ubuntu:focal
ENV DEBIAN_FRONTEND=noninteractive
RUN echo 'Start Nginx image build!'
RUN apt update && apt upgrade -y
RUN apt install nginx -y
COPY dockerfiles/files/nginx/lb/default /etc/nginx/sites-available/default
CMD ["nginx", "-g", "daemon off;"]
