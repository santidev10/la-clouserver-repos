FROM ubuntu
RUN apt-get update && apt-get install -y nginx
# ENTRYPOINT ["nginx", "-g", "daemon off;"]
ENTRYPOINT nginx -g “daemon off;”
