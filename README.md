# Calendar | API FLASK

Сервис для работы с Календарем.
— API интерфейс CRUD — Добавление / Список / Чтение / Обновление / Удаление
— модель данных "Событие": ID, Дата, Заголовок, Текст
— локальное хранилище данных
— максимальная длина заголовка — 30 символов
— максимальная длина поля Текст — 200 символов
— нельзя добавить больше одного события в день



Формат события "ГГГГ-ММ-ДД|заголовок|текст"
Postman
Для создания события 'POST' localhost:5000/api/v1/calendar/
Для просмотра созданных событий 'GET' localhost:5000/api/v1/calendar/
Для просмотра конретного созданного события 'GET' localhost:5000/api/v1/calendar/(id)/
Для изменения события 'PUT' localhost:5000/api/v1/calendar/(id)/
Для удаления события 'DELETE' localhost:5000/api/v1/calendar/(id)/
