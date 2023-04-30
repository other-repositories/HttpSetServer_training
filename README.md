# HttpSetServer_training

## Установка и зависимости
C++17 Boost

Чтобы установить библеотеку boost достаточно просто можно тут:
  https://gist.github.com/zrsmithson/0b72e0cb58d0cb946fc48b5c88511da8

## Описание
- Сервер на одну комнату
- все запросы отсюда, кроме несколькоих комнат -> https://github.com/Krushiler/com.krushiler.set-game-server/blob/master/Readme.md
   + /set/room/enter -> /set/enter *вход в главную комнату*
- Немного изменил вывод JSON, заметил много лишней возвращаемой информации, возвращал исключения в каждом сообщении.

## Запуск
Пример моих аргументов запуска из консоли, я открывал сервер по статическому IP и портам, можно просто localhost
- `./http-server-sync 192.168.0.200 80 .` 


