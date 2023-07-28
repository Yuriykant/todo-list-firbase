# Todo list

## Привет!

Это описание проекта "Todo list", где я расскажу о его функциональности, технологическом стеке и других деталях.

## Функциональность

- Авторизация пользователей, включая возможность использовать учетные записи GitHub и Google.
- Защита приватности: каждый пользователь видит только свои задачи.
- Создание новых задач с обязательным указанием текста.
- Удаление задач.
- Изменение текста задач.
- Отметка задачи как выполненной. Автоматическое удаление выполненных задач через 2 секунды.
- Предложение создать новую задачу, когда список задач пуст.

## Технологический стек

### Фронтенд

- Webpack
- React ^18.2.0
- React Router DOM ^6.14.1
- TypeScript ^5.1.6
- MUI Material-UI ^5.14.0
- Emotion ^11.11.1

### Бэкенд

- Firebase ^10.0.0

## Установка и запуск

1. Склонируйте репозиторий: `git clone https://github.com/your/repository.git`
2. Перейдите в папку проекта: `cd project-directory`
3. Установите зависимости: `npm install`
4. Запустите приложение в режиме разработки: `npm run start`
5. Откройте приложение в браузере по адресу: [http://localhost:3000](http://localhost:3000)

## CI/CD

Для этого проекта используется CI/CD, чтобы осуществлять пул-реквесты в удаленный репозиторий. Код проходит проверку через инструменты Prettier, ESLint и Stylelint, чтобы обеспечить согласованный стиль кодирования.

## Демо

Вы можете просмотреть демонстрацию проекта, перейдя по ссылке: [Todo list](https://kantcodetodo.karpovdns.net)
## Авторизация

Для авторизации в приложении вы можете использовать OAuth-авторизацию через учетные записи GitHub и Google.

## Сервер и SSL-сертификат

Приложение развернуто на сервере Nginx и размещено на хостинге "Karpov" (https://kantcodetodo.karpovdns.net.).
SSL-сертификат был успешно получен и настроен для обеспечения безопасного соединения, обеспечивая безопасную передачу данных между клиентом и сервером.
