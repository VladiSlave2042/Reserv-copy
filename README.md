# "Reserv-copy" | "Бойко Владислав"
---
## Задание 1
Если прям кратко то точка старта каждого нового бекапа, это и есть основное отличие: 
* при full backup точка старта - 0, т.е. каждый раз происходит полный бэкап системы с нуля.
* при дифференциальном первый бекап подобен fullbackup, но каждый последующий бекапит лишь изменившиеся файлы беря за точку отчета самый первый бекап
* при инкрементном происходит похожий с дифференциальным процесс, но точкой отчта для нового бекапа будит всегда самый последний бекап.
---
## Задание 2
Установил:
![скрин](img/2.1.png)
получается работает
![скрин](img/2.2.png)
В папочке conf.file конфиги
---
## Задание 3 
Решил сбекапить домашний каталог с debslave видно что завершился бекап
![скрин](img/3.1.png)
настройки на ноде "местере"
![скрин](img/3.2.png)
настройки на ноде "slave"
![скрин](img/3.3.png)
Конфиги все в той же попочке, отдельно мастер и слейв
---
## 
---
