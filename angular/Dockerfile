
FROM nginx:1.27-alpine

COPY nginx/ /etc/nginx/

COPY dist/ /usr/share/nginx/html/

COPY entrypoint.sh /docker-entrypoint.d/entrypoint.sh

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
