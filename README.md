## 1. 
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/1.png)

## 2. 
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/2.png)

## 3. 
Нажатие Ctrl+C в терминале генерирует сигнал SIGINT, и Docker по умолчанию пересылает его основному процессу контейнера (PID 1) 
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/3.1.png)

 Мы изменили в самом приложении слушающий порт. На хосте остался старый порт, при котором мы запускали контейнер. Правило проброса осталось которое мы указали , а вот приложение уже слушает другой порт, по этому возникнет ошибка при обращению к старому порту 80 
 ![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/3.2.png)

![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/3.3.png)

## 4. 
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/4.png)

## 5. 
Файл был выбран compose.yaml - он выбирается по дефолту первый когда запускаешь docker compose up
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/5.1.png)

Задеплоенный компоуз в портейнер
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/5.2.png)

Конфиг
![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/5.3.png)

![Скрин 1](https://github.com/ultrmlvn/docker-compose/blob/main/5.4.png)

[Ссылка на compose.yaml](https://github.com/ultrmlvn/docker-compose/blob/main/compose.yaml)