# meteoClock

Исправление неподдерживаемых ascii-символов в новых версия lcd2004 дисплея прошивки метеостанции от Norovl

## Краткое описание:
<div>UPD 19.11.22</div>
<div>- поправил формулу абсолютной влажности</div>
<div>- добавил автоматическую плавную регулировку дисплея и светодиода от освещения</div>
<div>UPD 20.11.22</div>
-Исправил частоту обновления подсветки экрана на 2 секунды, ранее было 2 раза в секунду
<br></br>
Установив прошивку Norovl (доработанная прошивка AlexGyver'а) столкнулся с такой проблемой: 
<img src="https://github.com/Maykros/meteoClock/blob/master/media/некорректные_символы_1.jpg" width="50%" height="50%">
<img src="https://github.com/Maykros/meteoClock/blob/master/media/некорректные_символы_2.jpg" width="50%" height="50%">
Дисплей неверно отображает символы. 
Сделал вывод, что в новой версии lcd2004 дисплеев сократили поддерживаемое количество ascii-символов. Заменил их.

<img src="https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_граф.jpg" width="50%" height="50%">
<img src="https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_время.jpg" width="50%" height="50%">
Также поменял относительную влажность на абсолютную (грамм воды в кубическом метре воздуха), т.к. это в большей степени отображает реальную ситуацию с влажностью. 
<img src="https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_влажность_1.jpg" width="50%" height="50%">
<img src="https://github.com/Maykros/meteoClock/blob/master/media/корректные_символы_влажность_2.jpg" width="50%" height="50%">
Проверял только на русской версии, английскую не смотрел.

