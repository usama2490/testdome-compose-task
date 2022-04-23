FROM nginx

RUN rm -f /etc/nginx/nginx.conf

# Add main nginx.conf to default location
ADD nginx.conf /etc/nginx/nginx.conf

RUN service nginx restart

EXPOSE 80