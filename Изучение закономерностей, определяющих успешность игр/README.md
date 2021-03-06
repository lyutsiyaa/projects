# Анализ игровых платформ
## Данные

В данном проекте использовались следующие данные:

- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Задача

Необходимо выявить определяющие успешность игры закономерности. Для того, чтобы сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. У нас есть данные до 2016 года. Нужно спланировать кампанию на 2017-й.

## Вывод

Проанализировав данные, выявили, что самые популярные жанры: экшн, шутер, спорт и ролевые игры;
Лучшие продажи у платформ: PS4, XOne, 3DS;
Продолжительности жизни платформ составляет примерно 13 лет.

Проверили две гипотезы одну опровергли, что средние пользовательские рейтинги жанров Action и Sports одинаковые и одну удалось подтвердить средние пользовательские рейтинги платформ Xbox One и PC одинаковые.

## Используемые библиотеки

Pandas, Seaborn, Matplotlib, Scipy