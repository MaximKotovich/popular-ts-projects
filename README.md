## Описание проекта

Это приложение позволяет просматривать самые популярные TypeScript проекты на GitHub, отсортированные по количеству звезд. Приложение использует GitHub REST API для получения данных о репозиториях и отображает их в удобном интерфейсе.

## Функциональные возможности

- Получение списка самых популярных TypeScript проектов с GitHub.
- Отображение основных данных о каждом проекте: название, описание, количество звезд, и ссылка на репозиторий.
- Поддержка поиска проектов по ключевым словам.
- Изменение типа сортировки по количеству звёзд.

## Архитектура проекта

В проекте используется Feature-Sliced Design (FSD) — методология проектирования фронтенд-приложений, направленная на создание понятной, гибкой и масштабируемой структуры кода.

## Стек технологий

- **React** — основной JavaScript-фреймворк для разработки пользовательского интерфейса.
- **Sass** — Для стилизации компонентов.
- **TypeScript** — язык программирования, который является надстройкой над JavaScript, обеспечивающий статическую типизацию.
- **GitHub REST API** — используется для получения данных о популярных TypeScript репозиториях.
- **Axios** и **React-Query**— для выполнения HTTP-запросов к API.

## Установка и запуск проекта на локальном компьютере

1. Клонируйте репозиторий с проектом:

    ```bash
    git clone https://github.com/MaximKotovich/popular-ts-projects.git
    ```

2. Перейдите в директорию проекта:

    ```bash
    cd popular-ts-projects
    ```

3. Установите зависимости:

    ```bash
    npm install
    ```

4. Запустите приложение в режиме разработки:

    ```bash
    npm run dev
    ```

5. Откройте браузер и перейдите по адресу [http://localhost:5173/](http://localhost:5173/), чтобы увидеть приложение в действии.
