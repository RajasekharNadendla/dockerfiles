FROM nginx
WORKDIR /usr/share/nginx/html/
RUN echo "this is from workdir" > index.html
CMD ["nginx", "-g", "daemon off;"]