FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://gist.github.com/lillylangtree/b55828fa05ed3470d352 /usr/share/nginx/html
CMD [ "nginx" , "-g" , "daemon off;"]