FROM ubuntu:focal
RUN echo 'Start Nginx image build!'
Run apt update && apt upgrade -y
Run apt install nginx -y
COPY dockerfiles/files/nginx/lb/default /etc/nginx/sites-available/default
CMD ["nginx", "-g", "daemon off;"]