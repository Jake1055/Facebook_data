Проект содержит два файла с анализом метрик различных групп пользователей соц. сети Facebook

Метрики:
1) Количество лайков поставленных за день (likes_pday)
2) Количество друзей (friend_count)
3) Количество полученных лайков в день (received_likes_pday)

В файле Facebook_analisis_1 проверяются гипотезы:
1. Выборки взяты из одного распределения (Критерий Пирсона и тест Манна_Уитни)
2. Совпадение медиан (Критерий Знаков)
Для проверки критерия знака в конце строится эфронов доверительны интвервалы для медиан (с помощью бутстрапа)

В файле Facebook_analisis_2 проверяются гипотезы:
1. Равенство математических ожиданий функций распределений, пораждающих выборки (тест Фишера, двувыборочный тест Стьюдента)
2. Проверка на нормальность генеральной совокупности (Тест Шапиро-Уилка)
3. Выборки взяты из одного распределения (тест Манна_Уитни)
В конце строятся точные и эфроновы доверительные интвервалы (с помощью бутстрапа) для математических ожиданий
