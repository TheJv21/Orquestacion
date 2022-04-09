FROM nginx:alpine
VOLUME /tmp
RUN rm -rf /usr/share/nginx/html/*
COPY nginx.conf /etc/nginx/nginx.conf
COPY billingApp /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
