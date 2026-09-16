## Домашнее задание к занятию 7 «Жизненный цикл ПО»

## Дорожкин Артем

### Основная часть

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

    Open -> On reproduce.
    On reproduce -> Open, Done reproduce.
    Done reproduce -> On fix.
    On fix -> On reproduce, Done fix.
    Done fix -> On test.
    On test -> On fix, Done.
    Done -> Closed, Open.
    Остальные задачи должны проходить по упрощённому workflow:

    Open -> On develop.
    On develop -> Open, Done develop.
    Done develop -> On test.
    On test -> On develop, Done.
    Done -> Closed, Open.
    
Что нужно сделать

1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done.

2. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done.

3. При проведении обеих задач по статусам используйте kanban.

4. Верните задачи в статус Open.

5. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.

6. Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.

### Как оформить решение задания

Выполненное домашнее задание пришлите в виде ссылки на .md-файл в вашем репозитории.

<img width="1283" height="621" alt="1" src="https://github.com/user-attachments/assets/4c3b609d-4daa-4566-b224-5c5d55fb7654" />

<img width="1040" height="546" alt="1_1" src="https://github.com/user-attachments/assets/5628e15b-6a4b-4dca-ad3e-375ffaacea61" />

<img width="973" height="444" alt="2" src="https://github.com/user-attachments/assets/cb5b730a-aaee-4366-a051-75f40a2f125f" />

<img width="871" height="745" alt="3" src="https://github.com/user-attachments/assets/f2f202b0-160e-4cb0-9d92-7b3955558e09" />

<img width="1099" height="766" alt="4" src="https://github.com/user-attachments/assets/7d79a100-77c4-4d0a-bf02-7aae4ffb5dca" />

<img width="879" height="324" alt="5" src="https://github.com/user-attachments/assets/8ed1fc64-62af-4c2b-97ff-5c4efcb79aeb" />

<img width="1347" height="651" alt="6" src="https://github.com/user-attachments/assets/4e00e914-6330-4171-ad1a-8aa62b2a3c9c" />


![5](https://github.com/Ivan-Shkutov/ci-01-intro/blob/main/5.png)

![6](https://github.com/Ivan-Shkutov/ci-01-intro/blob/main/6.png)

![7](https://github.com/Ivan-Shkutov/ci-01-intro/blob/main/7.png)
