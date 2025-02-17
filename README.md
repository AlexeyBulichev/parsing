# Парсинг цены биткоина и загрузка данных в PostgreSQL

Этот проект автоматически парсит данные о цене биткоина и других криптовалют с сайта [Investing.com](https://ru.investing.com/crypto), обрабатывает их и сохраняет в базу данных PostgreSQL, запущенную в Docker-контейнере.

## 📌 Особенности
- Парсинг данных в реальном времени с использованием `requests` и `BeautifulSoup`.
- Обработка и преобразование данных (очистка, конвертация в числовые форматы).
- Сохранение данных в PostgreSQL с помощью `psycopg2`.
- Готовый Docker-образ PostgreSQL с настройками для быстрого запуска.

## 📋 Требования
- Python 3.8+
- Установленные библиотеки: 
  ```bash
  pandas requests beautifulsoup4 psycopg2-binary jupyter
- Наличие PostgreSQL:
    ```bash
    docker pull ghcr.io/alexeybulichev/postgres:latest
    
  
