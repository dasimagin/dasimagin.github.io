---
layout: page
title: Truck/planning
---

Планирование траектории робота делится на несколько этапов:
1. Глобальное планирование маршрута
2. Планирование траектории вдоль маршрута
3. Исполнение траектории

В рамках проекта вам предлагается сконцентрироваться на задаче **(2)** и **(3)**.
Необходимо спланировать траекторию для робота с [кинематической моделью велосипеда](https://dingyan89.medium.com/simple-understanding-of-kinematic-bicycle-model-81cac6420357),
который движется по плоскости и окружен статическими препятствиями
(простой случай 2-мерного мира с статическим гридом).
Далее с помощью контроллера эту траекторию необходимо исполнить.

Пока шасси робота будет в разработке разработка будет веститсь в симуляторе.
В качестве референса можно будет использовать библиотеку [OMP](https://ompl.kavrakilab.org).
В случае успеха мы попробуем запустить ваш алгоритм на реальном устройстве.

#### Чему студент научится?
- Изучит существующие подходы к планированию траектории.
- Узнает методы следования по траектории.
- Поработает с симуляцией робота.
- Поработает с ROS2.

#### Какие начальные требования?
- Проект предназначен для студентво 2-го и 3-го курсов.
- Важен хороший математический аппарат.
- Уверенное владение С/С++ и Python3, готовность работы с Unix.
- Умение читать обширные документты на английском.

#### Какие будут использоваться технологии?
- Разработка будет на С/С++, возможно, часть будет на Python3.
- Вам придется познакомиться с [ROS2](https://en.wikipedia.org/wiki/Robot_Operating_System).
- Для симуляции будем использоваться связку [gazebo](https://www.gazebosim.org) + [pybullet](https://pybullet.org).
