---
layout: page
title: CartPole
---

Существует набор классических [задач управления](https://gym.openai.com/envs/#classic_control),
в рамках проекта вам предлагается поработать с **CartPole**.
Устройство представляет собой вагонетку, ускорением которой мы управляем,
и свободно подвешенный маятник. Изначально маятник находится в положении равновесия,
необходимо поднять его в вертикальное положение и удерживать в неустойучивом балансе.

![CartPole](https://raw.githubusercontent.com/dasimagin/cart_pole/master/docs/model.svg)

Для управления мы используем контролер [ESP32](https://en.wikipedia.org/wiki/ESP32) и шаговый мотор.
Положение маятника регистриурется абсолютным магнитным энкодером.
Иногие части напечатаны на 3D-принтере.


Вам предстоит познакомиться с физикой устройства и научиться находить траектрию, позволяющую поднять маятник.
Затем мы попробуем обучить модель с помощью **reinforcment learning** и проведём тесты на реальном устройстве.

#### Чему студент научится?
- Освежит физику и узнает, что такое [Лагранжева механика](https://en.wikipedia.org/wiki/Lagrangian_mechanics).
- Немного познакомится с теорией управления.
- Научится находить траекторию каретки через задачу оптимизации.
- Познакомится с [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning) и обучит свою модель.
- Поработает с простым, но реальным роботом.

#### Какие начальные требования?
- Проект предназначен для студента 2-го курса.
- Базовые знания физики и хороший математический аппарат.
- Уверенное владение С/С++ и Python3, готовность работы с Unix.
- Умение читать обширные документты на английском.
- Опыт работ с электроникой приветствуется.
- Навыки в ML будут плюсом.

#### Какие будут использоваться технологии?
- Разработка будет на С/С++ и Python3.
- Для обучения будем использовать pytorch/tensorflow.