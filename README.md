# Домашнее задание №1 к лекции «Формы»

[![Build status](https://ci.appveyor.com/api/projects/status/pmkuibmi24vmwkns?svg=true)](https://ci.appveyor.com/project/yuriyvyatkin/ra-hw-4-1-color-converter)

[Ссылка на Github Pages](https://yuriyvyatkin.github.io/ra-hw-4.1-color-converter/)

Конвертер цветов из HEX в RGB
===

Вам необходимо разработать конвертер цветов из HEX в RGB.

![Конвертер цветов](./assets/preview.png)

## Интерфейс конвертера

При правильном вводе цвета он показывает его представление в формате RGB и меняет цвет фона на заданный цвет:
![Цвет](./assets/color.png)

Конвертер при вводе неправильного цвета в формате HEX должен сообщать об ошибке:
![Ошибка](./assets/error.png)

Необходимо дожидаться ввода всех 7-ми символов (включая решётку), чтобы принимать решение о том, показывать ошибку или менять цвет фона.
