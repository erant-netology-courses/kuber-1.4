# kuber-1.4

## Задание 1

Отошел от задания: сделал multitool на 1180, т.к. обычно 8080 у других сервисов и приложений, поэтому решил не использовать типичный порт.

<img width="760" height="860" alt="image" src="https://github.com/erant-netology-courses/kuber-1.4/blob/main/1-clusterip.jpg?raw=true" />

<img width="960" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-1.4/blob/main/1-nodeport.jpg?raw=true" />


## Задание 2

<img width="960" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-1.4/blob/main/2.jpg?raw=true" />

По умолчанию в MicroK8s стоит теперь traefik, поэтому нотация не работает. Менять путь не захотел. Поэтому получаем 404 уже от мультитула внутри (поэтому ответ nginx).

<img width="960" height="560" alt="image" src="https://github.com/erant-netology-courses/kuber-1.4/blob/main/2_404.jpg?raw=true" />

Вот пример работы, так вроде тоже ок:

<img width="960" height="860" alt="image" src="https://github.com/erant-netology-courses/kuber-1.4/blob/main/2_multitool.jpg?raw=true" />