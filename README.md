# Команды для выполнения домашнего задания
1. docker stats - Просмотр сколько ресурсов система использует контейнер Grafana файл stats.txt
2. docker logs <container_id> > log.txt - Сохранение лога запуска контейнера Grafana в файл log.txt
3. docker exec <container_id> env > env.txt - Сохранение переменных окружения контейнера Grafana в файл env.txt

### Домшнее задание с работой контейнером
1. docker exec -it <container_id> bash - зайти внутрь контейнер
2. grafana cli admin - Посмотреть список админов
3. grafana cli admin reset-admin-password <new_password>