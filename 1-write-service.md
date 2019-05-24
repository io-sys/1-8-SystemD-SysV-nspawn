8-1. Написать сервис, который будет раз в 30 секунд мониторить лог 
на предмет наличия ключевого слова. Файл и слово должны задаваться в `/etc/sysconfig`

Действия:  
	1) создать файл конфиг в `/etc/sysconfig`, из которого будут браться настройки (переменные)  
	2) создать скрипт `/opt/watchlog.sh`  
	3) написать юнит сервиса в `/etc/systemd/system/watchlog.service`  
	4) тест, что всё работает без `timer`  
	5) создать юнит для таймера и запустить его  

Проверка:
```php
# show all timers
[root@linux]# systemctl list-timers --all
# Show log 
[root@linux]# tail -15 /var/log/messages
```
