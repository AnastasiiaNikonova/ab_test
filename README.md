# ab_test
Существует приложение с лентой новостей, инженерами были разработаны 2 новых алгоритма рекомендации постов, в связи с чем было принято решение повести А/Б тест.
Группы 0 и 1 - Конрольные, 2 и 3 - тестовые (для каждой реализован свой алгоритм рекомендации постов).
В А/Б тесте сравнивали CTR контрольных и тестовых групп
 За неделю до проведения А/Б теста был проведен А/А тест, который показал, что система сплитования работает корректно.
 
 А/Б тест: основываясь на анализе полученных данных (возможность проведения т-теста, но наличие юзеров с малым количеством просмотров)был выбран метод исследования т-тест на сглаженном CTR.
 Эксперимент показал снижение  CTR в тестовой группе, изменение распределения метрики (в контроле - одномодальное, в тестовой группе - бимодальное).По результатам сделаны выводы, даны рекомендации.
 Используемые библиотеки:
pandahouse
pandas
seaborn 
matplotlib
scipy

Статистика: т-тест, Шапиро-Уилка, бутстрап
