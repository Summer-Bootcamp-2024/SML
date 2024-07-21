FROM nginx:1.26.1

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/

CMD [ "nginx", "-g", "daemon off;" ]