Задание:

Имеется директория с данными под названием data.
* Созание директории библиотека os.

В ней три поддиректории - dir_1, dir_2, dir_3.
* Создание поддиректорий библиотека os.

В каждой из них есть набор файлов вида file_0.txt, file_1.txt, ... , file_24.txt.
* Создание файлов с помощью цикла для автоматической подстановки названия библиотека os.

Файлы с некоторыми номерами могут отсутствовать (например, в dir_1 нет как минимум файла file_7.txt).
* Удаление некоторых документов библиотека os.

В каждом файле записано одно целое число.
* Запись чисел в файлы при помощи цикла.

Требуется сделать скрипт, который на основании этих данных сгенерирует файл out.csv (очевидно, в формате "csv"), с тремя столбцами:

id, date, sum

В столбец id записать номер файла из имени. То есть, для файла file_5.txt в столбце должно быть записано "5".

В столбце date указать сегодняшнюю дату (Да, она будет во всех строчках одинаковая) в формате "yyyy.mm.dd"

В столбце sum записать либо

а) сумму чисел, записанных в файлах с одинаковыми именами (например, dir_1/file_5.txt, dir_2/file_5.txt, dir_3/file_5.txt), если все три файла существуют

б) дефис (прочерк), если хотя бы в одной из директорий dir_1, dir_2 и dir_3 не окажется файла с таким именем.

В качестве результата работы прислать собственно скрипт и получившийся csv-файл.

* Подготовка и обработка данных производилась с помощью библиотеки Pandas.

