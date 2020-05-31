# Money-Changer

##Задача
Один стакан кофе стоит 5 фунтов.
Покупатели стоят в очереди, чтобы купить у вас кофе.
Каждый покупатель хочет купить ровно один стакан и он заплатит купюрой в 5, 10 или 20 фунтов.
Вам нужно дать сдачу каждому покупателю, так чтобы в итоге он заплатил не больше 5 фунтов.
Изначально у вас нет никаких денег.
Напишите метод, который принимает на вход массив купюр, с которыми пришли покупатели, в порядке очереди и возвращает true тогда и только тогда, когда вы можете дать сдачу каждому покупателю. В противном случае метод должен возвращать false.

##Примеры
1. __Купюры:__ [5, 10, 5, 20] __Ответ:__ true
2. __Купюры:__ [10, 5] __Ответ:__ false
3. __Купюры:__ [5, 10, 5, 20, 10] __Ответ:__ false