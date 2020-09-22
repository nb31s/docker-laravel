ARG DOCKER_NGINX_VERSION

FROM nginx:${DOCKER_NGINX_VERSION}-alpine

COPY ./default.conf /etc/nginx/conf.d/default.conf

WORKDIR /work/backend