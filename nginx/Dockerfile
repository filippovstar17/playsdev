FROM nginx:alpine

# Устанавливаем только необходимые зависимости для image_filter
RUN apk add --no-cache gd libgd libjpeg-turbo-dev libpng-dev nginx-module-image-filter

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
