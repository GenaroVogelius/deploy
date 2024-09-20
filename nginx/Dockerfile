FROM nginx:latest


# Instala Certbot
RUN apt-get update && apt-get install -y certbot python3-certbot-nginx

# Copia tu archivo de configuración nginx.conf
# COPY nginx.conf /etc/nginx/nginx.conf

# # Asegúrate de que el contenedor exponga el puerto 80 y 443
# EXPOSE 80 443

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d