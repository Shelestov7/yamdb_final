# api_yamdb Docker 

![badge](https://github.com/Shelestov7/yamdb_final/workflows/YAMDB_workflow/badge.svg)

## Описание 
Проект выполнен в учебных целях в работе с API (DRF).  
Проект YaMDb собирает отзывы пользователей на произведения. Произведения делятся на категории: «Книги», «Фильмы», «Музыка». 
В каждой категории есть произведения: книги, фильмы или музыка. Произведению может быть присвоен жанр из списка предустановленных Новые жанры может создавать только администратор. 
Благодарные или возмущённые читатели оставляют к произведениям текстовые отзывы и выставляют произведению рейтинг (оценку в диапазоне от одного до десяти). Из множества оценок автоматически высчитывается средняя оценка произведения.  
 
## Этапы развертывания Docker контейнера 
1. Склонировать репозиторий 
2. В корневой директории проекта создать файл `/api_yatube/.env` с переменными: 
  * `DB_NAME`=... 
  * `DB_USER`=... 
  * `DB_PASSWORD`=... 
  * `DB_HOST`=... 
  * `DB_PORT`=... 
   
3. Выполнить команду `docker-compose up` 
 
##### Остальное за вас выполнит скрипт. 
 
Проект достуен по адресу http://84.201.128.150/api/v1/ 