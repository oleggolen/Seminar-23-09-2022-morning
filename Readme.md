# Инструкция по работе с удалёнными репозиториями Git
## Команда Pull
**Pull** - это скачивание данных с сервера. Похоже на клонирование репозитория, но с той разницей, что скачиваются не все коммиты, а только новые.

Данная процедура необходима для того, чтобы получать изменения от ваших коллег, либо от себя самого, если вы работаете на разных машинах.

В терминале данная команда выглядит следующим образом:

*** 
    $ git pull origin master
***

* pull - получить данные
* origin - откуда (с сервера)
* master - с ветки мастер