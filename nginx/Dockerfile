# Étape de production
FROM nginx:stable-alpine

# Copier la configuration de NGINX
COPY nginx/nginx.conf /etc/nginx/nginx.conf

# Copier le résultat du build dans le bon répertoire de NGINX
COPY client/build /usr/share/nginx/html

# Exposer le port 80
EXPOSE 80