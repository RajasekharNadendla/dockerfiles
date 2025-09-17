FROM nginx
# RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-78s/notes/main/session-01.txt /tmp/session-01.txt
ADD sample-2.tar /tmp/
CMD [ "nginx" , "-g" , "daemon off;"]