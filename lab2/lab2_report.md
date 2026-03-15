University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)  
Year: 2025/2026  
Group: K66666  
Author: Lastovskaia Anna Alexandrovna  
Lab: Lab1  
Date of create: 15.03.2026  
Date of finished: 16.03.2026    
## Подготовка
Зарегистрировалась на Hub Docker и создала репозиторий `https://hub.docker.com/repository/docker/lastovich/lastovichlab3/general`  
Также создала новый репозиторий для проекта:   
`https://github.com/lastovich/cicdlab`    
## Выполнение 
Подключила Github Actions, добавив в репозиторий `.github/workflows/`.  
В файле `docker-build.yml` описала pipeline, по которому в результате push происходят следующие действия:  
* "сгружает" данные с репозитория
* логинится на Docket Hub
* собирает и публикует контейнер
* деплой завершается строчкой "Deploy step completed!"
Создала token для подключения к репозиторию в Docker Hub, позже на ошибочном запуске Actions поняла, что не дала достаточно прав.
![1](1.png)

