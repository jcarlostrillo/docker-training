FROM nginx:1.13.8

ENV PROXY_PROTOCOL=http PROXY_UPSTREAM=example.com

COPY proxy.conf /etc/nginx/conf.d/default.template
COPY start.sh /

ENTRYPOINT ["/start.sh"]
CMD ["nginx", "-g", "daemon off;"]