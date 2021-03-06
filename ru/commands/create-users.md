# create:users
Создание фиктивных пользователей для Drupal 8.

**Использование:**
```
drupal create:users [arguments] [options]
cru
```

## Доступные параметры
Команда | Детали
-------|-------------
--limit | Сколько пользователей вы хотите создать
--password | Пароль, который будет установлен при создании пользователей
--time-range | Как далеко назад во времени пользователи должны быть датированы

## Доступные аргументы
Аргумент | Детали
---------|-------------
roles | Роли, которые будут использованы при создании пользователей

## Примеры
* Создает пользователей на основе указанной роли.
```
drupal create:users role
```
* Создает указанное количество пользователей с паролем и датой создания.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
