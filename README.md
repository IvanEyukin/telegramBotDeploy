<h1 align="center">Deploy Телеграм Бота с системой мониторинга</h1>
<h3 align="center">Описание</h3>

Используется следующие технологии:
1. prometheus
2. node-exporter - сбор метрик с host машины
3. redis-exporter - сбор метрик с БД redis
4. alertmanager - обработка алертов
5. cadvisor - сбор метрик с Docker container
6. grafana - визуализация метрик

<h3 align="center">Deploy</h3>

1. Указать в `docker-compose.yml` свои образы для telegramBot и redis
2. Запустить deploy docker-compose `docker-compose up -d`

<h3 align="center">Минимальные системные требования</h3>

1. Процессор: 1 ядро.
2. Оперативная память: 768 MiB
3. Размер диска: 6 GiB
