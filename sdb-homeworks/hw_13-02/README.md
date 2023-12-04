# Домашнее задание к занятию  «Защита хоста» - Комиссаров Игорь

### Задание 1

1. Установите **eCryptfs**.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.


*В качестве ответа  пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.*  

### Решение 1

Исходя из лекции есть 2 варианта:

1) Или ,используя команду   **sudo adduser --encrypt-home  cryptouser**,  сразу создать пользователя с зашифрованным домашним катологом.

![1.png](./img/1.png)

2) Или создать пользователя  **sudo adduser cryptouser**, а уже потом зашифровать  домашний католог.

![2.png](./img/2.png)

![3.png](./img/3.png)

### Задание 2

1. Установите поддержку **LUKS**.
2. Создайте небольшой раздел, например, 100 Мб.
3. Зашифруйте созданный раздел с помощью LUKS.

*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*

### Решение 2
![5.png](./img/5.png)
![6.png](./img/6.png)
![4.png](./img/4.png)



### Задание 3 *

1. Установите **apparmor**.
2. Повторите эксперимент, указанный в лекции.
3. Отключите (удалите) apparmor.

*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*

### Решение 3

![7.png](./img/7.png)

