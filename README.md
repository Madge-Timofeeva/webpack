Webpack Static Site Starter Kit
Требования к проекту
Node 14.18.3
NVM/MacOC
NVM/Windows Если Windows то установка только от имени администратора
Yarn
Использование
Клонировать репозиторий

git clone https://github.com/alex-karo/webpack-static-template block7
В папке block7 перейти в папку проекта

cd block7
Удалить папку .git

rm -rf .git
Если создаете новый проект в github.com
нужно будет инициализировать git проект, если данная команда не сработает значит версия git установлена старая, нужно обновить её

git init -b main
добавить все изменения и сделать первый коммит

git add . && git commit -m "initial commit"
соединить git удаленный с локальным, USER (пользователь) и REPO (репозиторий)

git remote add origin https://github.com/USER/REPO.git
проверить на то что есть соединение

git remote -v
отправить изменения в удаленный репозиторий

git push origin main
Проверка версии ноды
Должно вывести версию ноды 14.18.3

node -v
Два метода установки зависимостей
Установка зависимостей через NPM

npm install
Установка зависимостей через Yarn

yarn
Два метода запуска приложения
Для запуска веб-сервера через NPM

npm run start
Для запуска веб-сервера через Yarn

yarn start
Два метода загрузки на Github Pages
Ваш репозиторий должен быть связан с github.com репозиторием, после этого выполняем
Загрузка на Github Pages через NPM

npm run deploy
Загрузка на Github Pages через Yarn

yarn deploy
Основано на этой статье
