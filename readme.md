Организовать сбор о петициях с сайта petitions247.com. Сборщик должен отсылать запросы сайту по http/https, разбирать полученные ответы и сохранять полученные данные (желательно, в формате json).

Минимальный набор процедур:


получить данные о петиции по её URL
получение последних созданных петиций
поиск петиций по ключевым словам средствами сайта (так как на сайте petitions247.com используется поиск от google, предлагаю сосредоточиться в первую очередь на первых двух пунктах)


Получение петиции по URL должно предоставлять следующие данные:


заголовок
полный текст петиции
имя автора
ID автора на сайте
дата создания петиции
URL петиции
количество подписавших
требуемое количество подписей (если установлено)
количество комментариев, оставленных к петиции
список комментариев, оставленных к петиции (предусмотреть наличие опции, которая включает/отключает сбор этого типа данных. Для каждого комментария собирать текст, имя автора, ID автора, дату создания)


При поиске петиций и получении недавних петиций должна быть возможность задать ограничения:


получить только первые N петиций (максимальное количество)
получить только петиции, созданные после даты D (минимальная дата)


Поиск петиций и получение последних петиций должны предоставлять данные, аналогичные сбору по URL, для всех найденных петиций.
