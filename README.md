# django_sprint4-1

## Установка и запуск проекта

1. Клонируйте репозиторий:
   ```
   git clone <repository-url>
   cd django_sprint4_Morozov
   ```

2. Создайте виртуальное окружение:
   ```
   python -m venv venv
   source venv/bin/activate  # На Windows: venv\Scripts\activate
   ```

3. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```

4. Перейдите в папку проекта:
   ```
   cd blogicum
   ```

5. Примените миграции:
   ```
   python manage.py migrate
   ```

6. Загрузите тестовые данные:
   ```
   python manage.py loaddata db
   ```

7. Запустите сервер разработки:
   ```
   python manage.py runserver
   ```

Теперь сайт доступен по адресу http://127.0.0.1:8000/ с загруженными данными.
