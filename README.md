<h4>Реализованная функциональность</h4>
<ul>
    <li>Авторизация и регистрация</li>
    <li>Просмотр точек с достопримечательностями</li>
    <li>Просмотр точек с семьями, готовыми принять людей</li>
    <li>Страница с информацией о пользователе</li>
    <li>Страница с информацией о месте</li>
</ul> 
<h4>Особенность проекта в следующем:</h4>
<ul>
 <li>Пользователи могут находить семьи, которым нужна помощь, взамен они предоставляют жилье, питание, экскурсии</li>
 <li>Можно оставлять отзывы о пользователях</li>
 <li>Красивая и легко адаптивная карта</li>  
 </ul>
<h4>Основной стек технологий:</h4>
<ul>
    <li>React JS</li> 
    <li>Node.js(express)</li> 
    <li>PostgreSQL</li> 
 </ul>
<h4>Демо</h4>
<p>Посмотреть можно склонив и запустив проект, инструкция ниже</p>

СРЕДА ЗАПУСКА
------------
1) развертывание сервиса производится на любой ОС;
2) требуется установленный node;
3) требуется установленная СУБД postgreSQL;


## Установка 
Склонируйте весь проект
### Фронтенда

Выполните 
~~~
cd frontend(находясь в главной директории)
npm i
npm start
~~~

### Бэкэнда

Выполните 
~~~
cd backend(находясь в главной директории)
npm i
npm start
~~~
### База данных

Необходимо создать пустую базу данных, выполните
~~~
CREATE USER postgres WITH password 'root';
CREATE DATABASE nov.legend;
~~~
### Выполнение миграций

После создание базы sequelize сам подтянет таблицы

### Установка зависимостей проекта

Установка зависимостей осуществляется с помощью команды `npm i` как для фронтенда, так и для бэкэнда

### РАЗРАБОТЧИКИ

<h4>Гарнов Кирилл frontend разработчик https://t.me/kirusha_nom1 </h4>
<h4>Дмитрий Сурдин frontend разработчик https://t.me/dimasurdin </h4>
<h4>Карен Григорян backend разработчик grigoryan.67@inbox.ru </h4>
<h4>Юрий Ксюк дизайнер mksuk@mail.ru </h4>