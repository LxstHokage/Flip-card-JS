# Переворачивающаяся карточка
# Софт
- **Visual Studio Code**
# Описание
Проект представляет собой flip-карточку ( с англ. flip - "переворот ) с изображениями на обоих сторонах. На одной из сторон расположена кнопка, при наведении на которую активируется подсветка её краев и основного тела.


<img src="https://github.com/LxstHokage/Flip-card-JS/assets/109164076/d3a5d53a-aeb8-448f-a2a6-18520a5e053a" width=60%>

# Как это работает

На каждой стороне тела карточки находятся изображения, закреплённые ниже.

![card1](https://sun9-17.userapi.com/impg/mSE4gB97HCpecWJEfqiqC8C4A_U7Kxj2CeXcKQ/38b7i1Mz5yY.jpg?size=600x600&quality=95&sign=538658903641237ba48fce1629e0ec76&type=album)
![card2](https://sun7-21.userapi.com/impg/xpq4lKQHLaTfO4bwJPzyWfEL-lJxQK4ZhH08Ow/gm89jeCbWrU.jpg?size=600x600&quality=95&sign=62caa2349d63c4f887d16c884e54c40d&type=album)

При наведении курсора на тело карточки, она переворачиватся на другую сторону. На обороте карточки расположена кнопка. При наведении на неё активируется подсветка и обводка тела кнопки.
Это реализовано благодаря методу "card:hover", позволяющему производить манипуляции с телом объекта. С помощью углов поворота можно выполнить анимацию вращения.

Кнопка на одной из сторон карточки активируется если навести на неё курсор мыши. Это так же реализовано с помощью "button:hover".

Анимания движущихся линий выполнена с помощью методов "button__line--", в котором указываются параметры и цвет анимации, и "button:hover .button__line--", где указывается время действия и размер анимации.

```
.button__line--left{
    bottom: -100%;
    left: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(0deg,transparent,#8c0f91);
    }
 ```

```
.button:hover .button__line--left{
        bottom: 100%;
        transition: 1s;
        -webkit-transition: 1s;
        -moz-transition: 1s;
        -ms-transition: 1s;
        -o-transition: 1s;
        transition-delay: 0s;    
}
```

Ссылки на файлы с содержанием карточки находятся в репозитории. [И здесь :)](https://lxsthokage.github.io/Flip-card-JS/)

Удачи!

Контакты автора:

[VK](https://vk.com/lxsthokage)
[Telegram](https://t.me/lasthxkage)
