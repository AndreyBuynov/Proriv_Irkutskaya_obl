# Цифровой прорыв Иркутская область
Решение задачи чемпионата Цифровой прорыв Иркутская область

В основе решения лежит классификация и детекция персон, затем по координатам детекции и истории движения классифицируется тип действия пользователей.

Get_persons - ноутбук по созданию датасета персон из видео.
Classify_model - ноутбук с обучением классификатора персон.
Predict - ноутбук с пайплайном по предсказанию итогового результата.

Используемые моеди:
yolov5 для детекции персон (как есть без тюнинга)
resnet18 - для классификации персон, дообученная на полученном датасете.
