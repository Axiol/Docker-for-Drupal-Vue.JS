FROM nginx:latest

COPY ./default.conf /etc/nginx/conf.d/default.conf

COPY ./run.sh /root/run.sh
RUN chmod +x /root/run.sh

RUN apt-get update && apt-get install -y git
