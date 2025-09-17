FROM nginx
WORKDIR /usr/share/nginx/html/
RUN echo "<h1> this is from workdir </h1>" > index.html
RUN pwd
CMD ["nginx", "-g", "daemon off; "]


