# kinopoisk

ВНИМАНИЕ! Для использования на территории РФ потребуется включить VPN

Стек: React, Redux, MUI, сетевые запросы - Fetch, сборщик - Vite.
Используется бесплатный API: https://api.themoviedb.org/

Приложение представляет собой картотеку фильмов.
При входе требуется авторизация. Процесс не связан с бекендом, можно сразу переходить к вводу токена.
Токен можно получить на сайте https://developer.themoviedb.org/reference/intro/authentication.
При входе данные сохраняются в куки.

На главной странице по умолчанию выводится картотека фильмов с сортировкой по популярности.
Пользователю доступны следующие фильтры:

- по названию фильма;
- сортировка по популярности / рейтингу;
- по году релиза;
- по жанрам (мультивыбор).
  Перемещаться между страницами картотеки можно с помощью панели пагинации.

При нажатии на карточку фильма происходит переход на страницу с деталями о фильме.

Фильмы можно добавлять в избранное (кнопка в форме звезды). Данные синхронизируются с сервером.
