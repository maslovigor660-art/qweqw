# FoodFlow — Food Delivery UI

Полноценное демо‑приложение доставки еды на React + Vite + Tailwind.

## Возможности
- 10 блюд с картинками и ценами в рублях
- Корзина и логика оплаты
- Профиль с редактированием фото, адреса и способа оплаты
- Избранное и настройки
- Переключение языка (RU/EN) и темы (светлая/тёмная)
- Чат поддержки с анимацией печати и ответом оператора

## Запуск проекта
```bash
npm install
npm run dev
```

## Сборка
```bash
npm run build
```

## Публикация на GitHub Pages (пошагово)
1. Создайте репозиторий на GitHub.
2. В корне проекта выполните:
   ```bash
   git init
   git add .
   git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. Установите пакет `gh-pages`:
   ```bash
   npm install -D gh-pages
   ```
4. Добавьте в `package.json` скрипты:
   ```json
   "homepage": "https://<username>.github.io/<repo>",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
5. Выполните:
   ```bash
   npm run deploy
   ```
6. Откройте ссылку: `https://<username>.github.io/<repo>`

## Структура
- `src/App.tsx` — основной UI
- `src/index.css` — Tailwind

---
Made with ❤️
