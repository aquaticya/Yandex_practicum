# Построение модели определения стоимости автомобиля

## Описание проекта

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.
Задачи проекта: 
Разработка системы рекомендации стоимости автомобиля на основе его описания

## Данные

Признаки
1.	DateCrawled — дата скачивания анкеты из базы
2.	VehicleType — тип автомобильного кузова
3.	RegistrationYear — год регистрации автомобиля
4.	Gearbox — тип коробки передач
5.	Power — мощность (л. с.)
6.	Model — модель автомобиля
7.	Kilometer — пробег (км)
8.	RegistrationMonth — месяц регистрации автомобиля
9.	FuelType — тип топлива 
10.	Brand — марка автомобиля
11.	Repaired — была машина в ремонте или нет
12.	DateCreated — дата создания анкеты
13.	NumberOfPictures — количество фотографий автомобиля
14.	PostalCode — почтовый индекс владельца анкеты (пользователя)
15.	LastSeen — дата последней активности пользователя

Целевой признак

1.	Price — цена (евро)

## Инструменты

Pandas, Python, lightgbm


