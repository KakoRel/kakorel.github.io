# CortelVPN Landing Page

Современный лендинг для VPN-бота в Telegram с использованием **Vue 3 + Vite**.

## 🚀 Особенности

- Красочный дизайн с градиентами и анимациями
- Адаптивная вёрстка (мобильные + десктоп)
- Секция с преимуществами
- Информация о технологии Vless + Reality
- CTA кнопки для перехода в Telegram бот

## 📦 Установка

```bash
npm install
```

## 🛠️ Разработка

```bash
npm run dev
```

## 🌐 Деплой на GitHub Pages

### 1. Инициализируйте Git репозиторий

```bash
git init
git add .
git commit -m "Initial commit"
```

### 2. Создайте репозиторий на GitHub

Создайте новый репозиторий с именем **kakorel.github.io** — это будет ваш пользовательский сайт на GitHub Pages.

### 3. Задеплойте

```bash
npm run deploy
```

Эта команда:
1. Соберёт проект (`npm run build`)
2. Опубликует папку `dist` через `gh-pages`

### 4. Настройте GitHub Pages

1. Зайдите в настройки репозитория на GitHub
2. Перейдите в раздел **Pages**
3. В источнике выберите **gh-pages** ветку
4. Через 1-2 минуты сайт будет доступен по ссылке: `https://kakorel.github.io/`

## 📁 Структура проекта

```
kakorel.github.io/
├── index.html              # HTML шаблон
├── package.json            # Зависимости и скрипты
├── vite.config.js          # Конфигурация Vite
├── public/
│   ├── logo.png            # Логотип
│   ├── robots.txt          # Для поисковиков
│   └── sitemap.xml         # Карта сайта
├── src/
│   ├── main.js             # Точка входа Vue
│   ├── App.vue             # Главный компонент
│   └── components/         # Vue компоненты
└── dist/                   # Собранный проект (для деплоя)
```

## 🎨 Настройки

### Изменение ссылки на бота
Откройте `src/App.vue` и найдите все ссылки `https://t.me/CortelVPNBot` — замените на нужную.

### Изменение цветов
В секции `<style>` компонента `App.vue` измените градиенты:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 📝 Скрипты

| Команда | Описание |
|---------|----------|
| `npm run dev` | Запуск локального сервера разработки |
| `npm run build` | Сборка для production |
| `npm run preview` | Предпросмотр production сборки |
| `npm run deploy` | Сборка + деплой на GitHub Pages |

---

**CortelVPN** — Ваш надёжный VPN в Telegram 🔐
