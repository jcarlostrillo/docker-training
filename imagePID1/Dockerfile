FROM debian:buster-slim

RUN apt-get update

RUN apt-get install -y nginx

# CMD nginx -g 'daemon off;'

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
