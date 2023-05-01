Webpack - tool for JS application assembly

1. создаем index и module, прокидываем модули

2. npm init -y

3. npm i -D webpack webpack-cli

4. для сборки обращаемся к wp: npx webpack --mode development ./index.js
(появляется папка dist)

5. для удобства создаем конф файл webpack.config.js
в нем пишем js настройки для файла. Нужно вернуть объект и указать главные настройки

6. Добавляем скрипты в package.json

7. Расширить функционал можно с помощью плагинов для wp
npm i --save-dev html-webpack-plugin(подключаем в wp config)
с ним мы получаем при сборке html файл со скриптом

8. По умолчанию wp работает только с js и json, но можно подключить лоадеры
npm i -D style-loader css-loader(подключаем в wp config)

9. Создаем базовый css 

10. Для автоматический перезагрузки добавляем 
npm i -D webpack-dev-server