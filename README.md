# SCP-SL-Text-Features
Сделать жирным ```<b>Some Text</b>```\

Написать курсивом ```<i>Some Text</i>```\

Подчеркнуть ```<u>Some Text</u>```\

Измененить цвет: ```<color=red>Some Text</color>``` (шаблон: #rrggbbaa)\
Стандартные цвета:
|Имя в теге|Hex Значение|Превью|
|---|---|---|
|aqua/cyan|#00ffffff||

Изменить размер: ```<size=50>Some Text</size>``` (стандарт ~ 20, максимальный ~ 170, для предложений ~ 150)\

Добавить задний фон: ```<mark=red padding="10,10,0,0">Some Text</mark>```, где ```padding``` - опционально, значения означают отсупы наружу слева, справа, сверху и снизу\
Чтобы текст не перекрывался фоном, изменить шрифт текста: ```<font="LiberationSans SDF">Some Text</font>```\
Пример: ```<font="LiberationSans SDF"><mark=#000000 padding="5000,5000,100,5000">Some Text</mark></font>```
