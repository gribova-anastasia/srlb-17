# Домашнее задание к занятию «Кеширование Redis/memcached» - Грибова Анастасия

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*

---
Запросы к базам данных могут быть медленными и требовать серьёзных системных ресурсов, так как серверу баз данных, для формирования ответа, нужно выполнять некие вычисления. Если запросы повторяются, кэширование их средствами базы данных поможет уменьшить время её отклика. Кроме того, кэширование полезно в ситуациях, когда несколько компьютеров работают с базой данных, выполняя одинаковые запросы.
Кэшировать нужно данные, которые медленно генерируются и часто запрашиваются

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

---
![Название скриншота 1](https://github.com/gribova-anastasia/srlb-17/blob/ee8efd84a28e52187540a44150c7d6b0aff8efcd/memcached.png)

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

---
![Название скриншота 2](https://github.com/gribova-anastasia/srlb-17/blob/1f1040250738fdf06b23f2ec25be34cb73fe4aa9/memcached2.png)


### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

---
![Название скриншота 3](https://github.com/gribova-anastasia/srlb-17/blob/1f1040250738fdf06b23f2ec25be34cb73fe4aa9/redis.png)
![Название скриншота 4](https://github.com/gribova-anastasia/srlb-17/blob/1f1040250738fdf06b23f2ec25be34cb73fe4aa9/redis2.png)

