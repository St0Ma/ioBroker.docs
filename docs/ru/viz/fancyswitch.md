---
translatedFrom: de
translatedWarning: Если вы хотите отредактировать этот документ, удалите поле «translationFrom», в противном случае этот документ будет снова автоматически переведен
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/ru/viz/fancyswitch.md
title: Fancyswitch
hash: DFXagUdr/ZV0Iv1rR8AXrE035qtjVkn9+FGKRExwK0M=
---
# Fancyswitch
Этот набор представляет некоторые переключатели, которые работают в основном одинаково.
Они представляют булевы состояния и также могут их переключать.

| Виджет | Изображение | Описание |
|------------------------|-------|--------------|
| Включить / выключить свет | ![переключатель](../../de/viz/media/fancyswitch-1.png) | Светло-серый тумблер |
| Слайд темный вкл / выкл | ![переключатель](../../de/viz/media/fancyswitch-3.png) | Ползунок с надписью «вкл. / Выкл.» |
| Ползунок темный выключен / включен | ![переключатель](../../de/viz/media/fancyswitch-4.png) | Ползунок с надписью «выкл.» / «Вкл.» |
| Рокер темный выкл / вкл | ![switch] (media / fancyswitch-5.png)! [switch](../../de/viz/media/fancyswitch-6.png) | Темный тумблер с надписью «выкл.» / «Вкл.»; опционально также в легком стиле |
| Giva Labs iButton | ![переключатель](../../de/viz/media/fancyswitch_givalabsibutton.png) | Белый слайдер с надписью «вкл» / «выкл» |
| Taitem jqui Toggleswitch | ![переключатель](../../de/viz/media/fancyswitch_taitem.png) | Белый слайдер с надписью «включено» / «выключено» вне слайдера |
| Taitem jqui Toggleswitch | ! [Switch] (СМИ / fancyswitch_taitem.png) | Белый слайдер с надписью «включено» / «выключено» вне слайдера |

## Описание недвижимости
| Атрибут | Описание | Тема |
|----|----|---|
| ObjectId | Идентификатор отображаемого объекта, содержащий HTML | Switch, Slider, Slider, Rocker |
| Инвертировать | Инвертировать состояние переключения | Switch, Slider, Slider, Rocker |
| False-value | значение, которому является состояние false / off / off | переключатель, ползунок, ползунок, качелька |
| Истинное значение | Значение, до которого состояние ложно / выключено / выключено | Переключатель, ползунок, ползунок, качелька |
| Автоотключение | Представляет собой функцию кнопки: по истечении заданного времени переключатель возвращается в исходное состояние | Switch, Slider, Slider, Rocker |
| Светлый стиль | Более светлый дисплей переключателя | Рокер темный выключен / включен |
| Размер рычага || Giva Labs iButton |
| Размер контейнера || Giva Labs iButton |
| Drag Allowed | Переключатель можно перетаскивать (не просто нажимать) | Giva Labs iButton |
| Анимация | Переключение анимированное | Giva Labs iButton |
| Переключение | Задержка передачи данных | Giva Labs iButton |
| Подсветка переключателя | Скользящая область переключателя также показана цветом | Taitem jqui Toggleswitch |
| Ширина виджета | Ширина переключателя вне зависимости от заголовка | Taitem jqui Toggleswitch |
| Prepend html | HTML-код для отображения перед объектом | Taitem jqui Toggleswitch |
| Добавить HTML | HTML-код для отображения после объекта | Taitem jqui Toggleswitch |

** Пример: ** ![009](../../de/viz/media/fancyswitch_all.gif)