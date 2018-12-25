[Назад](./API.md)

## Описание интерфейса IUser

Интерфейс предназначен для работы с методами класса User

### Реализация интерфейса

+ **+Del**(ID : int) : bool - функция удаления пользователя;
    * ID - номер пользователя в БД

+ **+Validation**(Login:string, Password:string) : bool - функция проверки сущетвования в БД логина и пароля, вводимых пользователем и предоставления прав пользрвателю в соответсвии со статусом пользователя;
    * Login - логин пользователя;
    * Password - пароль пользователя.

## Описание класса User

Данный класс является предком классов Client и Trainer. Класс предназначен для работы с данными пользователей.

### Атрибуты класса
* **#ID** : Int - номер пользователя в БД;
* **#Login** : String - логин пользователя;
* **#Password** : String - пароль пользователя;
* **#Email** : String - эл. почта.

[Назад](./API.md)