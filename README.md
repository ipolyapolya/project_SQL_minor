# project_SQL_minor
Проект по созданию базы данных для музыкального сервиса


![Схема базы данных](https://github.com/ipolyapolya/project_SQL_minor/blob/main/%D0%B1%D0%B0%D0%B7%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.png)



Таблицы и поля, требующие пояснения:

**type_id в таблице tracks и, соответственно, таблица types с пояснениями** - тип музыкального произведения: музыкальный трек, подкаст, аудиокнига, оригинальное

**number_of_EPs** **(таблица artists)** - EP = extended play - musical recording that contains more tracks than a single but fewer than an album or LP record

**album_type (таблица albums):** album или compilation

**release_date_precision (releases_of_albums)**: конкретный день (day) или год (year)

**type_of_subscription (таблица subscriptions):** free, individual, family, plus
