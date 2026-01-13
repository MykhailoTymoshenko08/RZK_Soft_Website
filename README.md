# RZK Soft Website
## Цілі покращення:
- Перехід на Framework (React та Next.js)
- Використання Tailwind CSS
- Анімації (Framer Motion або GSAP)
- Централізоване керування даними
- ООП
- 
## Структура проєкту:
```text
rzk-website/
├── app/                # Основна логіка, сторінки та роутинг (App Router)
│   ├── layout.js       # "Скелет": тут будуть Header та Footer (спільні для всіх сторінок)
│   ├── page.js         # Головна сторінка (твій Landing)
│   ├── globals.css     # Гглобальні стилі та Tailwind директиви
│   └── team/           # (Опційно) окрема сторінка для кожного члена команди
├── components/         # "Цеглинки" (багаторазові частини сайту)
│   ├── Header.jsx
│   ├── Hero.jsx        # Верхня частина (Freelance Software...)
│   ├── Services.jsx    # Блок з послугами
│   ├── Team/           # Папка для блоку команди
│   │   ├── TeamSection.jsx
│   │   └── MemberCard.jsx
│   └── Footer.jsx
├── data/               # "Мізки" проекту
│   ├── teamData.js     # Об'єкт з інформацією про команду
│   └── services.js     # Опис послуг
├── public/             # Картинки, іконки, шрифти
│   └── images/
├── next.config.js      # Конфігурація Next.js
├── tailwind.config.js  # Налаштування кольорів та шрифтів
└── package.json        # Список встановлених бібліотек
```
