# Amur2022
RegionalChampionship
Представлено решение в модуле lgp аналитической платформы Логином в бесплатной общедоступной версии Community Edition v.6.5.1 (дистрибутив можно свободно получить по адресу https://loginom.ru/download).
Выполняется кластеризация (основной применяемый метод ML в данном случае) по тесту и трейну, на большом объеме кластеров по типу билета, дню недели (будни,выходные) на показатель времени (в минутах от начала суток). Затем данные разбираются по тесту и трейну, в трейне присваивается время (среднее по кластеру) и метка (по метке наибольшего числа людей при группировке по кластеру, типу билета, станции). Полученные значения передаются записям теста при группировке по ключевым полям.
Предполагается, что метод может быть доработан и имеет практическую применимость.
Лучшая сабмиссия прилагается в наборе.
