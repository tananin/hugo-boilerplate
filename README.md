# Hugo Static Website Boilerplate
> Шаблон для создания статических сайтов с использованием Hugo, Tailwind CSS, Alpine.js и DatoCMS.

## Технологии

- [Hugo](https://gohugo.io/) — статический генератор сайтов.
- [Tailwind CSS](https://tailwindcss.com/) — утилитарный CSS-фреймворк.
- [Alpine.js](https://alpinejs.dev/) — легковесный JS-фреймворк для интерактивности.
- [DatoCMS](https://www.datocms.com/) — headless CMS для управления контентом.

## Быстрый старт

```bash
# Клонировать проект
git clone https://github.com/tananin/hugo-boilerplate.git my-site
cd my-site
rm -rf .git
git init
git remote add origin https://gitlab.com/you/client-project.git
git add .
git commit -m "Init from boilerplate"
git push -u origin master
```

# Локальная разработка
Запускаем из Powershell, из WSL не работает LiveReload

## Установить зависимости
```bash
npm install
```
## Запустить локальный сервер
```bash
hugo server
```
[Открываем:](http://localhost:1313/)

## Запаскаем DecapCMS
```bash
npx decap-server
```
[Админка](http://localhost:1313/admin/)



# TODO
