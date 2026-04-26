FROM nginx:alpine

# Eliminar contenido por defecto
RUN rm -rf /usr/share/nginx/html/*

# Copiar archivos estáticos
COPY . /usr/share/nginx/html

COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

