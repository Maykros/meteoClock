# meteoClock

Исправление неподдерживаемых ascii-символов в новых версия lcd2004 дисплея прошивки метеостанции от Norovl

## Краткое описание:
Установив прошивку Norovl (доработанная прошивка AlexGyver'а) столкнулся с такой проблемой: 
![1](https://github.com/Maykros/meteoClock/blob/master/media/некорректные_символы_1.jpg)
![2](https://github.com/Maykros/meteoClock/blob/master/media/некорректные_символы_2.jpg)
Дисплей неверно отображает символы. 
Сделал вывод, что в новой версии lcd2004 дисплеев сократили поддерживаемое количество ascii-символов. Заменил их.

Также поменял относительную влажность на абсолютную (грамм воды в кубическом метре воздуха), т.к. это в большей степени отображает реальную ситуацию с влажностью. 
![3](https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_граф.jpg)

![4](https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_время.jpg)
![5](https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_влажность_1.jpg)
![6](https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_влажность_2.jpg)

Проверял только на русской версии, английскую не смотрел.

