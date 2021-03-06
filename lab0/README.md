# Лабораторная работа №0

## Сбор и анализ данных

Для просмотра ноутбука: https://nbviewer.org/github/TheGravityZero/MAI-Machine-Learning/blob/main/lab0/lab0_eda.ipynb


### Описание датасета

Модификация обучающего датасета "Титаник", в котором нужно определить смог ли пассажир перемеситься в другое пространственно-временное измерение.

Ссылка на датасет: https://www.kaggle.com/competitions/spaceship-titanic/overview

#### Признаки

* PassengerId — уникальный идентификатор для каждого пассажира. Каждый идентификатор принимает форму gggg_pp, где gggg указывает группу, с которой путешествует пассажир, а pp — его номер в группе. Люди в группе часто являются членами семьи, но не всегда.
* HomePlanet — планета, с которой вылетел пассажир, обычно планета его постоянного проживания.
* CryoSleep - указывает, решил ли пассажир быть переведен в режим анабиоза на время рейса. Пассажиры, находящиеся в криосонном состоянии, находятся в своих каютах.
* Cabin — номер каюты, в которой находится пассажир. Принимает форму палуба/число/сторона, где сторона может быть либо P для левого борта, либо S для правого борта.
* Destination — планета, на которую будет высаживаться пассажир.
* Age - возраст пассажира.
* VIP - оплатил ли пассажир специальное VIP-обслуживание во время рейса.
* RoomService, FoodCourt, ShoppingMall, Spa, VRDeck — сумма, которую пассажир выставил в счет за каждое из многочисленных роскошных удобств космического корабля «Титаник».
* Name - имя и фамилия пассажира.
* Transported — был ли пассажир перенесен в другое измерение. Это цель, столбец, который вы пытаетесь предсказать.
