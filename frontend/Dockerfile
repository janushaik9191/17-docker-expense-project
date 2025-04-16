FROM nginx

RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
# there are two configurations are available in nginx.conf and default.conf these making a problem in loading configuration so that we can remove both of them 
COPY nginx.conf /etc/nginx/nginx.conf