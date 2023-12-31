# Тестовое задание на фронтенд-разработчика
Необходимо разработать javascript-компонент таблицы с данными о пользователях. Можно с использованием React, но не используя готовые react-компоненты.
### Формат таблицы
```
+----------+-----------+------------------+----------------+------------+------------------+----------------------+
| Имя      | Фамилия   | Email            | Телефон        | Логин      | Дата регистрации | Последняя активность |
+----------+-----------+------------------+----------------+------------+------------------+----------------------+
| Иван     | Иванов    | ivanov@gmail.com | +79995566554   | ivan       | 01.01.2020       | 11.02.2022           |
+----------+-----------+------------------+----------------+------------+------------------+----------------------+
| Петр     | Петров    | petrov@gmail.com | +79854698459   | petr       | 21.11.2021       | 21.03.2022           |
+----------+-----------+------------------+----------------+------------+------------------+----------------------+
```
### Функционал
* Сортировка загруженных данных по любой из колонок.
* Перенос записей - на строку вверх/вниз соотвествующей кнопкой.
* Постраничная подгрузка данных.
* Поиск по загруженным данным (по имени, фамилии, email, телефону, логину) - с определением колонки на основе введенных данных в строке поиска.
* Клик на строку открывает карточку пользователя, в которой дополнительно показываем данные о месте проживания (страна, город, адрес) и дополнительное текстовое описание.
* В карточке пользователя добавить возможность редактирования данных пользователя.
* Добавить возможность открытия карточки в режиме редактирования из таблицы - нажатием соотвествующей кнопки.

### Загрузка данных
Данные загружать с сервиса filltext.com по адресу
http://www.filltext.com/?rows=10&fname={firstName}&lname={lastName}&tel={phone}&address={streetAddress}&city={city}&country={country}&pretty=true&registration_date={date%7C10-10-2020,01-01-2023}&activity_date={date%7C10-10-2020,01-01-2023}&uname={username}&email={email}&description={lorem}

### Требования к выполнению задания
* Выложить код в свой публичный репозиторий на github.com с возможностью продемонстрировать работу
* Оформление интерфейса на усмотрение разработчика. **Важно** чтобы все элементы были выровнены относительно друг друга, соблюдались отступы между элементами и границами окон
* Наличие комментариев в коде на основных процедурах
* Осознанные названия переменных
* Соблюдать codestyle
