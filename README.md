# Todo App

Модерно и интуитивно Todo приложение, създадено с Next.js 15, React 19, TypeScript и shadcn/ui.

## Функционалности

- ✅ Добавяне на нови задачи
- ✅ Маркиране на задачи като завършени
- ✅ Изтриване на задачи
- ✅ Преброител на общо и завършени задачи
- ✅ Респонсивен дизайн
- ✅ Красив градиентен UI с индиго тема
- ✅ Keyboard shortcuts (Enter за добавяне на задача)

## Технологии

- **Next.js 15** - React framework
- **React 19** - UI библиотека
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **shadcn/ui** - UI компоненти
- **Lucide React** - Икони

## Инсталация

1. Клонирайте repository-то:
```bash
git clone https://github.com/AtanasG6/todo-app.git
cd todo-app
```

2. Инсталирайте dependencies:
```bash
npm install
```

3. Стартирайте development server:
```bash
npm run dev
```

4. Отворете [http://localhost:3000](http://localhost:3000) в браузъра.

## Използване

- Въведете задача в полето и натиснете **Enter** или бутона **Добави**
- Кликнете на checkbox-а, за да маркирате задача като завършена
- Използвайте иконата за кошче, за да изтриете задача
- Виждайте статистиката за общо и завършени задачи в долната част

## Scripts

```bash
npm run dev      # Стартира development server
npm run build    # Build за production
npm run start    # Стартира production server
npm run lint     # Проверява кода за грешки
```

## Структура на проекта

```
todo-app/
├── app/
│   ├── page.tsx          # Главна страница с Todo логика
│   ├── layout.tsx        # Root layout
│   └── globals.css       # Global styles
├── components/
│   └── ui/               # shadcn/ui компоненти
├── lib/
│   └── utils.ts          # Utility функции
└── public/               # Static assets
```

## Лиценз

MIT

## Автор

Atanas Gyulchev
