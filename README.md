# SCP-SL-Text-Features
Мануал по тегам в TMP: https://docs.unity3d.com/Packages/com.unity.textmeshpro@3.2/manual/RichTextFont.html

Перенос строки: ```\n```; (максимум 4 строки в broad cast)

Сделать жирным: ```<b>Some Text</b>```

Написать курсивом: ```<i>Some Text</i>```

Подчеркнуть: ```<u>Some Text</u>```

Измененить цвет: ```<color=red>Some Text</color>```; (шаблон: #rrggbbaa)\
Стандартные цвета:
|Имя в теге|Hex Значение|Превью|
|---|---|---|
|aqua/cyan|#00ffffff||

Изменить размер: ```<size=50>Some Text</size>```; (стандарт ~ 20, максимальный ~ 170, для предложений ~ 150)

Добавить задний фон: ```<mark=#FF00FF padding="10,10,0,0">Some Text</mark>```; где ```padding``` - опционально, значения означают отсупы наружу слева, справа, сверху и снизу; стандартные цвета не работают\
Чтобы текст не перекрывался фоном, изменить шрифт текста: ```<font="LiberationSans SDF">Some Text</font>```\
Пример: ```<font="LiberationSans SDF"><mark=#000000 padding="5000,5000,100,2260">Some Text</mark></font>```; (2260 – высота экрана в у.е.)

Использование материалов (пока не работает):\
Тени: ```<font="LiberationSans SDF" material="LiberationSans SDF - Drop Shadow">Some Text</font>```\
Обводка: ```<font="LiberationSans SDF" material="LiberationSans SDF - Outline">Some Text</font>```

Сдвинуть относительно середины: ```<pos=50%>Some Text</pos>```

Сместить по вертикали: ```<voffset=-100>Some Text</voffset>```

Повернуть: ```<rotate="45">Some Text</rotate>```; где "45" – градусы по часовой стрелке ("-45" – против)

Нарисовать смайлик: ```<sprite=0>```; где 0 – индекс спрайта в атласе (всего их 16)

```bc 5 8=<rotate="-74"><voffset=-9>=</rotate></voffset><rotate="-82"><voffset=-37>=</rotate></voffset><rotate="-85"><voffset=-82>=</rotate></voffset><rotate="-86"><voffset=-146>></rotate></voffset>```
