# Сокращение ссылок

## Описание
Проект создан для сокращения или подчёта кликов по ссылке. Для получения сокращенной ссылки необходимо передать программе ссылку для сокращения. В ином случае, если вы хотите узнать сколько раз переходили по вашей ссылке, необходимо передать сокращенную ссылку.

### Переменные окружения
Часть настроек проекта берётся из переменных окружения. Переменные окружения - это переменные, значение которых присваиваются программе Python извне. Чтобы их определить создайте файл .env рядом с main.py и запишите туда данные в таком формате: ПЕРЕМЕННАЯ=значение.

Пример содержания файла .env:

BITLY_TOKEN=21ecde8d68b8e54395928e7e4199dd7e27f9e78

## Установка

Скачайте необходимые файлы затем используйте pip (или pip3, если есть конфликт с Python2) для установки зависимостей и установить зависимости. Зависимости можно установить командой, представленной ниже.

Установите зависимости командой: 

`pip install -r requirements.txt`

## Пример запуска скрипта

Для запуска скрипта у вас должен быть установлен Python3.

Для получения сокращенной ссылки, необходимо написать команду в таком формате:

`python main.py --url https://translate.google.ru`

После агрумента --url необходимо указать ссыллку для работы кода, документацию можно найти на сайте 

Для получения количества кликов необоходимо написать команду в таком формате:

`python main.py --url bit.ly/3uujaSR`   
