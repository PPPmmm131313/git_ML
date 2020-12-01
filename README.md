# Домашнее задание
## Простая нейронная сеть с двумя скрытыми слоями

![ui_glow](./doc/pic.png)

## Функция активации нейронов 

Сигмоида: 
  
$f(x)={{1}\over{1+exp(-x)}}$


![ui_glow_up](./doc/sigmoid.JPG)

## Функция потерь

Запишем функцию потерь как функцию от параметров

![pic1](./doc/pic1.JPG)

Будем рассматривать частную производную ошибки по весам 

![pic2](./doc/pic2.JPG)

Мы можем рассчитать ![pic3](./doc/pic3.JPG) принимаем ![pic4](./doc/pic4.JPG)

![pic5](./doc/pic5.JPG)

Как быть с ![pic6](./doc/pic6.JPG)

![pic7](./doc/pic7.JPG)

Поскольку ![pic8](./doc/pic8.JPG) , мы можем снова использовать цепное правило и записать:

![pic9](./doc/pic9.JPG)

Мы можем сделать то же самое для ![pic10](./doc/pic10.JPG) и тд

Вычислим значение ![pic11](./doc/pic11.JPG)

![pic12](./doc/pic12.JPG)

Финально 

![pic13](./doc/pic13.JPG)

Такой метод расчета частных производных "от конца к началу" называется методом обратного распространения.