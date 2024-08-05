# Помощник огородника
### _Пет-проект, который ждет прекрасное будущее (надеюсь)_

**Возможности:**

✔ создание/удаление пользователя, реадактрирование данных пользователя.

**<details><summary>Дока</summary>**

```java
Главная страница

http://localhost:8080/garden
```

```java
User:

{
"id":"id",
"name":"name",
"age":"age",
"climate_zone":"climate_zone",
"geolocation":"geolocation",
"description":"description",
"lastVisit":"lastVisit",
}
```

**`GET`**
> **/garden/user?id** - вывести информацию о пользователе по **id**

**`POST`**
> **/garden/user** - создать нового пользователя

**`PUT`**
> **/garden/user?id** - изменить информацию о пользователе по **id**

**`DELETE`**
> **/garden/user?id** -удалить пользователя по **id**


</details>

**<details><summary>Запуск приложения</summary>**

- Открыть приложение через Idea.

- Прикрепить БД к нашему приложению:
    - Создать в PostgreSql БД <<имя бд>>.
    - Поменять параметры в application.yml:
<p align="center"><img  src="./assets_README/application.PNG" width="70%"></p>
- Запустить `GardenerApplication.java.`

</details>

**Стек технологий**

Java 21, Spring JPA, Maven, PostgresSQL, Thymeleaf, Postman.