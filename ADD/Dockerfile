FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-78s/dockerfiles/blob/main/COPY/index.html /usr/share/nginx/html
CMD [ "nginx" , "-g" , "daemon off;"]