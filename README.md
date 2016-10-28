# zabbix_agent
Installation script for Zabbix agent (Windows 32/64)

Скрипт для установки Zabbix агента.

Основыные функции:
 
 ⋅ Определение разрядности ОС и установка подходящей версии агента.
 
 ⋅ Создание конфигурационного файла на основе настроек скрипта:
 
 нужно указать адрес сервера и и постфикс домена
 
 ⋅ Определение имени хоста для активных проверок.
 
 ⋅ Создание правил файерволла.

# Установка

 Распакуйте архив в папку zabbix_agent. Структура каталогов должна быть такой:
  
 zabbix_agent
 
 |_bin
 
 |_conf
 
 В корень положите скрипт.
 
 [Cкачайте Zabbix agent LTS отсюда] (http://www.zabbix.com/download) и распакуйте в ту же папку.
