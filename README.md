# Парсер для сайта VC.ru.

## Может парсить следующие данные:
1. Название статьи.
2. Ссылка статьи.
3. Тематика статьи.
4. Количество просмотров.
5. Время создания статьи.
6. Название автора статьи.
7. Ссылка на автора.
8. Количество лайков.
9. Количество комментариев.
10. Количество сделанных репостов статьи.

После получения всех этих данных, программа хранит их в БД Sqlite3.

### Файлы и их предназначения:
* parser.py — программа, которая парсит данные.
* create_db.py — создает таблицу и поля для БД.
* requirements.txt — представлены все зависимости проекта.

#### Мой тг чат по питону: https://t.me/Python_dev_meeting