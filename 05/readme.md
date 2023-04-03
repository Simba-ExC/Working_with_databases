
# Домашнее задание к занятию «Работа с PostgreSQL из C++»

### Цель задания

1. Научиться делать SELECT-запросы к базе данных PostgreSQL из С++ для получения данных и отображения их в C++ приложении.
2. Научиться делать INSERT-, UPDATE- и DELETE-запросы к базе данных PostgreSQL из С++ для манипуляции данными из C++ приложения.

### Инструкция по выполнению домашнего задания

-----

### Задание 1

Создайте программу для управления клиентами на C++.

Требуется хранить персональную информацию о клиентах:

- имя
- фамилия
- email
- телефон

Сложность в том, что телефон у клиента может быть не один, а два, три и даже больше. А может и вообще не быть телефона (например, он не захотел его оставлять).

Вам необходимо разработать структуру БД для хранения информации и написать класс на С++ для управления данными, со следующими методами:

1. Метод, создающий структуру БД (таблицы)
1. Метод, позволяющий добавить нового клиента
1. Метод, позволяющий добавить телефон для существующего клиента
1. Метод, позволяющий изменить данные о клиенте
1. Метод, позволяющий удалить телефон для существующего клиента
1. Метод, позволяющий удалить существующего клиента
1. Метод, позволяющий найти клиента по его данным (имени, фамилии, email-у или телефону)


