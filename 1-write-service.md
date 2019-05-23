1. Написать сервис, который будет раз в 30 секунд мониторить лог 
на предмет наличия ключевого слова. Файл и слово должны задаваться в `/etc/sysconfig`

Действия
	1) создать файл конфиг в `/etc/sysconfig`, из которого будут браться настройки (переменные)  
	2) создать скрипт `/opt/watchlog.sh`  
	3) написать юнит сервиса в `/etc/systemd/system/watchlog.service`  
	4) тест, что всё работает без `timer`  
	5) создать юнит для таймера и запустить его  
  
vim /etc/sysconfig/watchlog
```php
# Configuration file for my watchdog service
# Place it to /etc/sysconfig
# File and word in that file that we will be monit
WORD="ALERT"
LOG=/var/log/watchlog.log
```
Создать  /var/log/watchlog.log и написать строки,
плюс ключевое слово ‘ALERT’
