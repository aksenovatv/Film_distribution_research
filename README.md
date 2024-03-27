# Исследование данных о российском кинопрокате

Целью данного исследования является изучение рынка российского кинопроката и выявление текущих трендов при работе с данными, опубликованными на портале открытых данных Министерства культуры. 

Для достижения этой цели необходимо проанализировать статистические данные о российском кинопрокате за последние годы, включающие в себя информацию о количестве фильмов, показанных в кинотеатрах, общей кассовой выручке и прибыльности фильмов по жанрам.

**Описание данных**

Таблица `mkrf_movies` содержит информацию из реестра прокатных удостоверений.\
`title` — название фильма;\
`puNumber` — номер прокатного удостоверения;\
`show_start_date` — дата премьеры фильма;\
`type` — тип фильма;\
`film_studio` — студия-производитель;\
`production_country` — страна-производитель;\
`director` — режиссёр;\
`producer` — продюсер;\
`age_restriction` — возрастная категория;\
`refundable_support` — объём возвратных средств государственной поддержки;\
`nonrefundable_support` — объём невозвратных средств государственной поддержки;\
`financing_source` — источник государственного финансирования;\
`budget` — общий бюджет фильма;\
`ratings` — рейтинг фильма на КиноПоиске;\
`genres` — жанр фильма.
 
Таблица `mkrf_shows` содержит сведения о показах фильмов в российских кинотеатрах.\
`puNumber` — номер прокатного удостоверения;\
`box_office` — сборы в рублях.
