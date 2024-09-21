# Улучшение личного кабинета банка.

## Виджет, который показывает несколько последних успешных
   банковских операций клиента.
## Функции, которые мы будем использовать в этой версии кода:
- Функция скрывающая номер карты и счета
- Функция сортировки по дате
- Функция фильтрации в операциях по счетам

## Установка:

- клонируйте репозиторий:
```
git clone https://github.com/SarasonAndrey/training.git
```
- установите зависимости:
```
pip install -r requirements.txt
```
## Структура проекта:
- tests/ - папка с тестами
- src/ - папка с функциями проекта
- .venv - виртуальное окружение

## Тестирование:
- Все функции протестированы через pytest, для запуска выполните команду:
```
pytest
```
- Чтобы посмотреть на сколько процентов функциональный код покрыт тестами, наберите команду:
```
poetry run pytest --cov
```

## Команда проекта:

- Сарасон Андрей и Skypro

## документация:
- данные любезно предоставлены Skypro

## лицензия:

- Проект распространяется под [лицензией MIT](LICENSE).