# DeviceСontrolAPI
Имитатор работы промышленного устройства, который осуществляет мониторинг состояния подключенных к нему приборов и по запросу отправляет пакет с данными.

## Описание файлов
DeviceControlAPI.py - содержит код основной программы.
Производится обработка сигналов, полученных с COM-порта или через сокеты; в качестве ответа на полученный сигнал производится отправка пакета с данными о текущем состоянии устройств.
Осуществляется генерация данных для отправки.
Реализован пользовательский интерфейс и обработка пользовательских команд.

ControlSumModule.py - модуль расчета контрольной суммы.

Config.ini - файл конфигурации.
В него вносятся данные по настройкам подключения, а также информация по устройствам, которые будут использованы для имитации.

Файлы socket_test_client.py и socket_test_client.py использовались для самоконтроля, для тестирования подключения по COM-порту или с помощью сокета, а также для тестового обмена пакетами.



