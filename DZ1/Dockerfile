#Загрузить базовый образ nginx
FROM nginx

#Установить nginx
WORKDIR /home/svv/myimages

#Заменяем стандартную страницу приветствия
COPY ./index.html /usr/share/nginx/html/index.html

#Указываем порт по умолчанию
EXPOSE 80 80
