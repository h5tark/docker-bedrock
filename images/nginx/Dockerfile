FROM nginx:alpine

RUN rm -f /etc/nginx/conf.d/default.conf\
    && echo "daemon off;" >> /etc/nginx/nginx.conf
    
ADD default /etc/nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx"]