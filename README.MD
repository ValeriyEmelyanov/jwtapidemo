# Spring Security REST API с использованием JWT токена

Пример использования Spring Security в простом REST API приложении. 
Аутентификация и авторизация реализованы с использованием JWT токена.

#### Используемые технологии
* Java 8
* Spring (IoC, Web, Data JPA, Security)
* MySQL
* Lombok
* JsonWebToken
* Liquibase

#### Endpoins
* `/api/v1/auth/login` аутентификация пользователя
* `/api/v1/admin/users/{id}` получение данных пользователя с правами администратора, {id} - идентификатор пользователя 
* `/api/v1/users/users/{id}` получение данных пользователя любым аутентифицированным пользователем, {id} - идентификатор пользователя 

[HTTP-запросы для Postman](src/main/resources/JwtApiDemo.postman_collection.json)

Исходный материал от Eugene Suleimanov:
<a href="https://www.youtube.com/watch?v=yRnSUDx3Y8k">Видео на Youtube</b></a>.
<a href="https://github.com/proselytear/jwtappdemo">Исходники к видео</b></a>.

