# documentation_devman

# Функция play(word)
Пользователю задается 6 попыток, также происходит инициализация пустых списков.
Добавляем в словарь с буквами пробелы, на месте пробелов в слове, а на месте букв ставим None.
Пока у пользователя есть попытки выводится загаданное слово, если в словаре с буквами не осталось None, пользователь выигрывает.
Выводится список с отгаданными буквами и отгаданные буквы в загаданном слове. Затем проверяется нахождение введенной пользователем буквы в загаданном слове, если такая буква есть, то в список с буквами на месте, где должна стоять данная буква, она показывается. В список угаданных букв добавляется введенная буква.
Если введена буква, которой нет в слове, то она добавляется в список букв, которых нет в слове, и количество попыток пользователя уменьшается.
Когда попыток не осталось выводится надпись о поражении и загаданное слово.

# Функция get_rand_word
Возвращает, случайное слово, взятое из файла со словами.

# print_game
Выводится список с отгаданными буквами и отгаданные буквы в загаданном слове
![image](https://github.com/Kukvid/documentation_devman/assets/80471950/64e1bdac-0148-44a0-be90-92e60abc62db)

# get_letter
Функция просит у пользователя ввести букву, если буква не введена или не в таблице ascii, то просит ввести букву еще раз. Если буква уже была угадана, то пользователь будет об этом уведомлен, если же такой буквы не было, то возвращает введенную пользователем букву.
