# Парсинг цены биткоина и загрузка данных в PostgreSQL

Этот проект демонстрирует процесс парсинга цены биткоина с использованием Jupyter Notebook, обработки данных и загрузки их в базу данных PostgreSQL, запущенную в Docker-контейнере.

## Описание проекта

1. **Парсинг данных**: Используется библиотека `requests` для получения данных о цене биткоина с публичного API (например, CoinGecko или Binance).
2. **Обработка данных**: Данные обрабатываются с помощью библиотеки `pandas` для анализа и преобразования.
3. **Загрузка в PostgreSQL**: Обработанные данные сохраняются в базу данных PostgreSQL, запущенную в Docker-контейнере.

## Требования

Для запуска проекта вам понадобятся:
- Python 3.8+
- Установленные библиотеки: `pandas`, `requests`, `psycopg2` (для работы с PostgreSQL), `jupyter`
- Docker (для запуска PostgreSQL)

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-username/ваш-репозиторий.git
   cd ваш-репозиторий
