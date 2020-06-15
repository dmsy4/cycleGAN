# cycleGAN

К сожалению, сеть выдает далеко не лучшие результаты для своей задачи (Перекраска волос светлый <=> темный)
Обучал 5+ раз по 50+ эпох, изменяя lr, коэфициенты, состав датасета. Ничего не помогло, очень малое количество изображений перекрашиваются
в необходимый оттенок, однако cycle работает всегда хорошо:

![cycle_repr](hhttps://sun9-60.userapi.com/c206816/v206816076/140bca/EfjLpELD_kA.jpg "cycle_repr")

Сэмплы fake_A и fake_B смотрите в папке test


# О других задачах
На стандартных датасетах apple2orange, horse2zebra
результаты хорошие:
![horse2zebra](https://sun9-13.userapi.com/c857028/v857028554/1b27d1/jIhgGcltAvs.jpg "horse2zebra")

Также была попытка реализовать светлый <=> цветной - результат тоже был плохой, но там был плохой датасет. Пример одного из ХОРОШИХ 
результатов
![light2colored](https://sun9-51.userapi.com/c855532/v855532534/23c8f3/nGEKDobxlyM.jpg "light2colored")


# Ссылки на веса и датасет
Ссылка на датасет для собственной задачи https://drive.google.com/file/d/1ScM8c3EqtGOq0gPOuEgDVoUjI0UKfXfI/view?usp=sharing
Веса для той же задачи https://drive.google.com/file/d/1MuzvnTIVKr7yqm2iPpoVnk7QaUC6dd_v/view?usp=sharing


Веса для задачи horse2zebra https://drive.google.com/file/d/1aH3w7tG7qtuUjIcPOzOsyfSAzy4dshYL/view?usp=sharing


