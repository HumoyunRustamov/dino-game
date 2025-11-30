# Dockerfile
FROM nginx:alpine

# Nginx konfiguratsiyasini o'rnatish
COPY nginx.conf /etc/nginx/nginx.conf

# Static fayllarni nginx papkasiga ko'chirish
COPY index.html /usr/share/nginx/html/


# Portni ochish
EXPOSE 80

# Nginx ni ishga tushirish
CMD ["nginx", "-g", "daemon off;"]
