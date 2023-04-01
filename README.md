Задание 1.

Созданный образ ubuntu-2004-nginx-2023-03-25t18-38-16z :my custom ubuntu-2004 with nginx 

![slave](https://github.com/felimonist/05-virt-04-docker-compose/blob/main/img/1.JPG)


Задание 2.

Это задание я делал через терраформ ,но к сожалению затер скрин и не получилось уже восстановить ,так как делал данный этап несколько дней назад.

![slave](https://github.com/felimonist/05-virt-04-docker-compose/blob/main/img/2.JPG)


Задание 3

С данным этапом пришлось повозиться ,так как образ caddy который предлагается ,является нерабочим и пришлось использовать актуальный на данный момент и уже наш конфиг для этой версии является невалидным , он требовал хеш пароля , закодировав его и прописав переменную {$ADMIN_PASSWORD_HASH} , все заработало.

![slave](https://github.com/felimonist/05-virt-04-docker-compose/blob/main/img/3.JPG)

Задание 4.

 Провал в графике ,это был ручной рестарт контейнеров и из-за проблем с одним из них.
 
![slave](https://github.com/felimonist/05-virt-04-docker-compose/blob/main/img/4.JPG)
