# Домашнее задание к занятию "`ELK`" - `Холопко Антон`



### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

# Решение 

![Задание1Скриншот1](https://github.com/Easyjetz/ELK/blob/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%821.png)


---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

# Решение 

![Задание2Скриншот1](https://github.com/Easyjetz/ELK/blob/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B52%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%821.png)


---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

# Решение 

![Задание3Скриншот1](https://github.com/Easyjetz/ELK/blob/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B53%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%821.png)


---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

# Решение 

![Задание4Скриншот1](https://github.com/Easyjetz/ELK/blob/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B54%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%821.png)
![Задание4Скриншот2](https://github.com/Easyjetz/ELK/blob/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B54%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%822.png)
