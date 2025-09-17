FROM nginx
WORKDIR /usr/share/nginx/html/
RUN echo " this is from workdir" > index.html
RUN pwd
CMD ["nginx", "-g", "daemon off;"]


