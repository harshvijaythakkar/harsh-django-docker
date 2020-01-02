FROM nginx
WORKDIR /etc/nginx/
RUN rm /etc/nginx/conf.d/default.conf
COPY hello.conf /etc/nginx/conf.d/
EXPOSE 80
