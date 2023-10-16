# Calendar | API FLASK

Описание:

Сервис для работы с Календарем.
- Api интерфейс CRUD - Добавление / Список / Чтение / Обновление / Удаление
- модель данных "Событие": ID, Дата, Заголовок, Текст
- локальное хранилище данных
- максимальная длина заголовка - 30 символов
- максимальная длина поля Текст - 200 символов
- нельзя добавить больше одного события в день
- формат данных: "ГГГГ-ММ-ДД|заголовок|текст"


Как запустить проект:

Клонируйте репозиторий:
- git clone git@github.com:BlackXS275/Calendar_API_Flask.git

Создайте и активируйте виртуальное окружение:
- python -3.12 -m venv venv
- source venv/scripts/activate

Обновите pip:
- python3 -m pip install --upgrade pip

Установите зависимости из requirements.txt:
- pip install -r requirements.txt

Запустите сервер:
- python server.py


Пример работы API

Для создания события 
- 'POST' localhost:5000/api/v1/calendar/

Для просмотра созданных событий 
- 'GET' localhost:5000/api/v1/calendar/

Для просмотра конретного созданного события 
- 'GET' localhost:5000/api/v1/calendar/(id)/

Для изменения события 
- 'PUT' localhost:5000/api/v1/calendar/(id)/

Для удаления события 
- 'DELETE' localhost:5000/api/v1/calendar/(id)/
