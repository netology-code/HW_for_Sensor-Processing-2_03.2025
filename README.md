# Домашнее задание к занятию 6. «Обработка датчиков 2»
### Инструкция по выполнению домашнего задания
**1.** Зарегистрируйтесь на сайте **[wokwi.com](https://wokwi.com/)**.<br>
**2.** Перейдите в раздел **Start from Scratch** и выберите создание нового проекта на основе платы **Arduion UNO**.<br>
**3.** После завершения проверки работоспособности сохраните проект с помощью кнопки **SAVE**.<br>
**4.** Скопируйте ссылку на проект с помощью кнопки **SHARE**.<br>
**5.** Приложите ссылку на ваше решение в поле "Ссылка на решение" и нажмите "Отправить решение".

------------

## Задача №1. Инклинометр

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, МЭМС модуля MPU6050 и жидкокристаллического индикатора 16 х 2. Подключите выводы МЭМС модуля MPU6050 к выводам интерфейса I2C платы Arduino UNO, а жидкокристаллический индикатор — к оставшимся свободным выводам.<br>

Разработайте программу, которая считывает показания трёх осей акселерометра с периодичностью 100 мс, выполняет их программную фильтрацию с помощью усреднения за 10 измерений по каждому каналу измерения и выводит на жидкокристаллический индикатор углы наклона со знаком по каждой оси.<br>

Проведите моделирование работы в симуляторе.<br>

------------

## Задача №2. Два МЭМС модуля

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, двух МЭМС модулей MPU6050 и жидкокристаллического индикатора 16 х 2. Подключите выводы МЭМС модулей MPU6050 к выводам интерфейса I2C платы Arduino UNO, задайте на выводе AD0 разных модулей разные логические уровни. Выводы жидкокристаллического индикатора подключите к оставшимся свободным выводам платы Arduino UNO.<br>

Разработайте программу, которая считывает показания всех осей каждого модуля и без знака выводит на индикатор информацию о разнице показаний двух МЭМС модулей по каждой оси.<br>

Проведите моделирование работы в симуляторе.<br>
