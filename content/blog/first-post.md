---
title: 'Vue.js - це круто!'
description: 'Це моя перша стаття!'
img: 'img/cover (1).JPG'
tags: [Пізнавальне, перший]
---

## Мій перший блог

Ласкаво просимо до мого першого блогу з використанням [модуля content v2](https://content.nuxtjs.org/)

> Привіт! 👋🏾 Це мій перший запис у блозі, в якому я вивчаю новий контент.

Наразі я створюю його, використовуючи наступне:

- Nuxt.js
- Модуль Nuxt Content
- TailwindCSS
  - Типографіка TailwindCSS

## Nuxt.js

[Nuxt](https://nuxtjs.org/) - це потужний фреймворк Vue, який пропонує чудові можливості для розробки, такі як рендеринг на стороні сервера.

```bash
npx nuxi init nuxt-app
cd nuxt-app
yarn install
yarn dev -o
```

```ts
// ./nuxt.config.ts

export default defineNuxtConfig({
  // Мій конфіг Nuxt
})
```

::InfoBox{type="warning"}
Ось корисна інформація для вас!

#details
Це буде відображено всередині слоту `description`. Дуже важливо побачити, як це **працює**.
[Більше інформації можна знайти тут](#)
::

## Модуль вмісту Nuxt

Розширюйте можливості вашого NuxtJS-додатку за допомогою [@nuxt/content module](https://content.nuxtjs.org/): записуйте в директорію content/ та отримуйте файли Markdown, JSON, YAML, XML та CSV через API, подібний до MongoDB, діючи як Git-based Headless CMS.

Ви можете розпочати роботу з Nuxt Content, встановивши свіжий проект

```bash
npx nuxi init content-app -t content
```

## TailwindCSS

Швидко створюйте сучасні веб-сайти, не залишаючи HTML. [TailwindCSS](https://tailwindcss.com/) - це утилітарний CSS-фреймворк, що містить такі класи, як `flex`, `pt-4`, `text-center` та `rotate-90`, які можна компонувати для створення будь-якого дизайну безпосередньо у вашій розмітці.

### Типографіка TailwindCSS

[Typography](https://tailwindcss.com/docs/typography-plugin) - це плагін, який надає набір прозаїчних класів, які можна використовувати для додавання красивих типографічних налаштувань за замовчуванням до будь-якого ванільного HTML, який ви не контролюєте (наприклад, HTML, відрендерений з Markdown, або витягнутий з CMS).
