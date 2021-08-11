## Serve static file using nginx container
docker run -p7777:80 --name static -v /root/static:/usr/share/nginx/html:ro -d nginx
