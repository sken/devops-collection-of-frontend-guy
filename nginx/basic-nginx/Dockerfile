FROM nginx

RUN apt-get update && apt-get install -y \
  nano \
  && rm -rf /var/lib/apt/lists/*

RUN rm /etc/nginx/conf.d/default.conf
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
COPY html /usr/share/nginx/html



