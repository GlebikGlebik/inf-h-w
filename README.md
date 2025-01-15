# Домашнее задание 
## Шифрование файлов и каталогов
### Введение 
Шифрование данных обеспечивает безопасность вашим данным. В данной работе нам нужно рассмотреть один из способов локальной шифровки данных, осуществить шифровку выбранного каталога и убедиться в надежности шифровки. 

Цель работы: научиться использовать файловую систему encryptfs для шифрования данных. 
 
Задачи работы: создать зищенный локальный каталог с защифрованным файлом. Добавить в этот же каталог незашифрованный файл-обманку. провести дешифровку зашифрованного файла и убедиться в сохранности его содержимого. 

### Ход работы

1. Установить ecryptfs

2. Зашифровать с его помощью выбранный каталог

3. Создать в этом же каталоге незашифрованный файл

4. Убедиться в том, что зашифрованный файл действительно зашифрован

5. Провести дешифровку и убедиться в сохранности данных