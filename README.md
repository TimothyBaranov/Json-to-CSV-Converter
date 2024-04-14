# Json-to-CSV-Converter
Конвертер JSON в CSV

Этот скрипт на Python конвертирует данные из формата JSON в формат CSV. Он считывает данные из входного JSON-файла, обрабатывает их и записывает полученные данные в файл CSV. Скрипт может быть выполнен из командной строки.

Предварительные требования
Python 3.x должен быть установлен на вашей системе.
Входной JSON-файл (input.json), содержащий данные для конвертации.
Использование
1 Разместите входной JSON-файл (input.json) в той же директории, что и скрипт.

2 Запустите скрипт с помощью следующей команды: 
```bash

python json_to_csv_converter.py
```
3 После выполнения скрипта сконвертированные данные будут сохранены в файле с названием output.csv в той же директории.

Структура файлов
json_to_csv_converter.py: Скрипт на Python, который конвертирует данные из формата JSON в формат CSV.
input.json: Входной JSON-файл, содержащий данные для конвертации.
output.csv: Выходной CSV-файл, в котором сохранены сконвертированные данные.

Принцип работы
Скрипт считывает данные из файла input.json.
Он обрабатывает JSON-данные и создает данные в формате CSV.
Сгенерированные данные CSV записываются в файл output.csv.
Если в процессе выполнения возникают ошибки, они отображаются в консоли.

Пример
Предположим, у вас есть следующие JSON-данные в файле input.json:
```json
[
    {"Name": "John", "age": 30, "birthyear": 1992},
    {"Name": "Alice", "age": 25, "birthyear": 1997}
]
```
После выполнения скрипта output.csv будет содержать:
```
Name,age,birthyear
John,30,1992
Alice,25,1997
```
