# Resume Website

Мой сайт-резюме на Vue.js, размещенный на GitHub Pages.

## Стек

- Vue 3 (Options API)
- SCSS Modules
- Vue CLI

## Запуск

```bash
npm install
npm run serve
```

Сайт откроется на `http://localhost:8080`

## Деплой на GitHub Pages

```bash
npm run build:gh
git add .
git commit -m "Update"
git push
```

В настройках репозитория (Settings → Pages) выбери ветку `main` и папку `/docs`.

## Редактирование

Все данные находятся в `src/components/Resume.vue`. Стили в том же файле, переменные — в `src/styles/variables.scss`.
