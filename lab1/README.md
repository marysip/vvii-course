[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marysip/vvii-course/blob/main/lab1/notebooks/lab1.ipynb)

# Практическое занятие 1. Рабочее окружение

Автор: Сипетина Мария Сергеевна, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv


## Сравнение сред выполнения

| | VS Code | Google Colab |
|---|---|---|
| Версия Python | 3.12.10 | 3.13.18 |
| Версия pandas | 3.1.1 | 2.2.3 |
| Где хранятся файлы | На локальном компьютере | В облачной среде Google Colab |
| Что потребовалось для запуска | Python, Git, VS Code, Jupyter и библиотеки | Браузер, Google-аккаунт и подключение к интернету |