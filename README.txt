Запуск: в папке anatomy-site выполните  python3 -m http.server 8000
и откройте http://localhost:8000  (двойным щелчком по index.html модели не загрузятся).
Для публикации загрузите всю папку на хостинг (Netlify, GitHub Pages, Cloudflare Pages и т.п.).
Авторов моделей укажите в index.html: у каждого органа есть поле a:'' (например a:'Имя автора, Sketchfab, CC BY').
Нужен интернет: three.js подгружается с CDN.
