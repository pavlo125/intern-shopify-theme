# Звіт з навчальної практики: Розробка та кастомізація теми Shopify

Цей репозиторій містить результати виконання 30 практичних завдань зі створення, кастомізації та оптимізації функціональних елементів для теми Shopify з використанням Liquid, CSS та JavaScript.

## Реалізовані модулі та файли

### 🧩 Секції (Sections)
* **`sections/custom-header.liquid`** — Кастомна навігація та хедер магазину.
* **`sections/custom-hero-banner.liquid`** — Головний банер з підтримкою відео та тексту.
* **`sections/custom-announcement-bar.liquid`** — Динамічний рядок оголошень.
* **`sections/custom-featured-collection.liquid`** — Блок рекомендованих товарів.
* **`sections/custom-product-grid.liquid`** — Адаптивна сітка товарів.
* **`sections/custom-cart-drawer.liquid`** — Боковий кошик (AJAX) з динамічним оновленням.
* **`sections/custom-quick-view.liquid`** — Модальне вікно швидкого перегляду товару.
* **`sections/main-collection-ajax.liquid`** — Сторінка колекції з AJAX-фільтрацією без перезавантаження.
* **`sections/custom-swatches.liquid`** — Кастомний вибір кольору та розміру (Color/Size Swatches).
* **`sections/custom-sticky-cart.liquid`** — Липка кнопка "Додати в кошик" для карток товару.
* **`sections/custom-size-guide.liquid`** — Інформаційна таблиця розмірів (Pop-up).
* **`sections/email-signup-banner.liquid`** — Банер для збору Email-підписок.
* **`sections/custom-faq-accordion.liquid`** — Акордеон для розділу поширених запитань (FAQ).
* **`sections/custom-testimonials.liquid`** — Слайдер відгуків клієнтів.
* **`sections/custom-footer.liquid`** — Розширений футер з додатковими колонками.

### ✂️ Сніпети (Snippets - перевикористовувані блоки)
* **`snippets/product-card.liquid`** — Універсальна картка товару.
* **`snippets/price.liquid`** — Логіка форматування ціни та знижок.
* **`snippets/social-icons.liquid`** — Блок іконок соціальних мереж.
* **`snippets/breadcrumb.liquid`** — Навігаційний ланцюжок (Хлібні крихти).
* **`snippets/pagination.liquid`** — Кастомна пагінація сторінок.
* **`snippets/icon-cart.liquid`** — SVG іконка кошика.
* **`snippets/icon-search.liquid`** — SVG іконка пошуку.
* **`snippets/loading-spinner.liquid`** — Анімація завантаження для AJAX-запитів.

### 🎨 Стилі та Скрипти (Assets)
* **`assets/custom-global.css`** — Глобальні кастомні стилі теми.
* **`assets/custom-cart-drawer.js`** — Логіка відкриття та оновлення бокового кошика.
* **`assets/custom-quick-view.js`** — Логіка швидкого перегляду товарів.
* **`assets/ajax-filter.js`** — Скрипт асинхронної фільтрації колекцій.
* **`assets/custom-animations.css`** — CSS-анімації для елементів інтерфейсу.

### 📄 Шаблони (Templates)
* **`templates/product.custom.json`** — Кастомний JSON-шаблон сторінки товару.
* **`templates/collection.custom.json`** — Кастомний JSON-шаблон сторінки колекції.
