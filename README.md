# BSA-3-DOM-API-Browser-
Academy 2017: DOM API/Browser API. Василий Терлецкий JS-03 Створити сторінку на якій відобразити список постів де кожен пост складається із заголовку, опису, картинки, дати створення та списку тегів.

Пости повинні бути відсортовані по даті за спаданням (найвище в списку останні додані) та тегами (пости з вибраними тегами мають вищий пріорітет та повинні бути найвище в списку).

При завантаженні сторінки перевірити localStorage на наявність збережених раніше тегів, якщо вони є - використати їх при сортуванні постів; якщо теги відcутні - дати користувачу можливість вибрати їх та вибрані теги зберегти в localStorage (теги для вибору “Sports”, “Politics”, “Food”, “Business”, “Tech”, “Culture”, “Showbiz”).

На сторінці відобразити 10 постів і як тільки користувач доскролить до 10-го додати ще 10; відповідно при досягненні 20-го, 30-го і т.д. кожного разу додавати 10 постів.

Реалізувати пошук постів. Пошук повинен бути миттєвим, тобто при кожному введені символа в поле пошуку - відображати ті пости, в заголовку яких є слово що шукається.

Надати можливість видаляти пости зі списку.

Завантажити всі пости з цього JSON файлу https://api.myjson.com/bins/152f9j на етапі завантаження сторінки, використовуючи XMLHttpRequest або fetch.
