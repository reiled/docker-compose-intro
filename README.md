# docker-compose-intro
## Итоговое дз:
Развернуть influx и grafana в докер контейнерах (берите готовые образы, они есть в интернете, официальные).
## Для этого вам нужно:
1) Написать docker-compose, где вы опишите как вам билдить контейнеры, в каком порядке и так далее
2) Все версии должны быть в отдельном .env файле
3) При поднятии контейнера с grafana должен создаваться админский пользователь
4) Для обоих контейнеров должны быть настроены volumes
5) Контейнеры должны уметь общаться между собой (т.е. я должен зайти в grafana и мочь подключиться к influx в соседнем контейнере).
6) Сначала должен подниматься influx, и только потом grafana 
7) Это все должно работать независимо от вашей операционной системы, т.е. я должен на своем компьютере иметь возможность это запустить тоже
8) Сделайте простенький jmx с запросом, например, в яндекс (не важно вообще), выберите стандартный dashboard для jmeter и запустите тест. Данные должны нормально сохраняться в influx и отображаться в grafana.
9) Все это (jmx и docker-compose) вам нужно запихнуть в гитхаб
10) Нужно в гитхаб все это поместить не разом, а несколькими коммитами - сначала инит коммит без всего этого (с пустым репозиторием), после коммит на докер-композ, после на jmx файл.
11) Везде должны быть осознанные коммит мессаджы.
