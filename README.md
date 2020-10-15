# Мiй Будинок - единая прошивка для ESP
Это универсальная прошивка для контроллеров ESP (8266/32) для умного дома, в прошивке будет штатный MQTT клиент. 
Изначально прошивка готовится для системы автоматизации openHA2, но благодаря Нашим усилиям, мы её интегрируем под разные системы автоматизации.
Планируем Home Assistant, Domoticz, MajorDoMo.
Также будет облачный MQTT Сервер.
# Первая нашптройка:
0. Пишем класс под свой датчик, если нет его в библитеке.
1. Прошиваем ESP
2. Скачиваем приложение Мiй Будинок на Google Play (Android).
3. Запускаем.
4. Приложение подключит Ваше устройство к AP Вашего ESP.
# При наличии локального сервера системы автоматизации и MQTT сервера
5. Задаем все настройки и название системы автоматизации
6. Укажем свои датчики и пины, на которых они висят (в графическом интерфейсе, так что не нужно будет лезть и искать PinOut для Вашей ESP)
7. Вписываем настройки в систему автоматизации
8. Наслаждаемся стабильной работой!
# При подключении к облачному MQTT Серверу
5. Создаем свою учетную запись на mqttcloud.iot3.ru
6. Вписываем данные учетной записи в приложение
7. Укажем свои датчики и пины на которых они висят (в графическом интерфейсе, так что не нужно будет лезть и искать PinOut для Вашей ESP)
8. Наслаждаемся работой!
