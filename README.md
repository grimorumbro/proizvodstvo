# Production App

MVP приложения для Bitrix24 / VibeCode.

## Старт локально
1. Скопируйте `.env.example` в `.env`
2. Установите зависимости: `npm install`
3. Сгенерируйте prisma client: `npm run prisma:generate`
4. Создайте базу: `npm run prisma:push`
5. Запустите проект: `npm run dev`

## Первый сценарий
- создать сотрудников через `/api/employees`
- настроить `AppConfig` и `StageMap` в БД
- сгенерировать QR через `/api/qr/generate`
- открыть `/p/{token}`
- пройти PIN
- завершить этап
