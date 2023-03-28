# local-library-python-django

## Описание

Выполнение демонстрационного проекта сайта библиотеки из курса "Веб-фреймворк Django (Python)" на MDN
Ссылка на заглавный урок https://developer.mozilla.org/ru/docs/Learn/Server-side/Django/Tutorial_local_library_website

В процессе были реализованы такие фичи, как
- добавление, изменение, удаление автора
- добавление, изменение, удаление книги
- добавление, изменение, удаление экземпляра книги
- навигация по сайту
- вывод списка авторов с пагинацией
- вывод списка книг/экземпляров с пагинацией
- авторизация пользователей, сессии
- разделение пользователей на группы с различными правами (Читатель, Библиотекарь)

## Инструкция по установке

Чтобы запустить приложение, следуйте инструкции (для систем на базе Ubuntu и Python версии 3.10; для других систем или версий Python описанные шаги могут отличаться):

1. Скачайте файлы и распакуйте в отдельную папку.
2. В терминале перейдите в папку с файлами приложения.
3. Создайте виртуальную среду при помощи команды `python3 -m venv env` , где env - название виртуальной среды
4. Активируйте созданную виртуальную среду при помощи команды `source env/bin/activate` , где env - название виртуальной среды
5. Установите библиотеки, необходимые для работы приложения, при помощи команды `pip install -r requirements.txt`
6. Запустите приложение на локальном сервере - команда `python3 manage.py runserver` в терминале.


### Примечание

Данное приложение использует SQLite.
Регистрация новыъ пользователей через интерфейс сайта в данном приложении не реализована.
Для тестирования функционала сайта можно использовать следующих пользователей:

Логин reader
Пароль read1pass
Категория доступа - пользователи библиотеки (library members)

Логин anotherlibrarian
Пароль read2books
Категория доступа - библиотекарь (librarian) с доступом к админскому функционалу

Логин thechief
Пароль readallthembooks
Категория доступа - суперпользователь
