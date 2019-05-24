# 1-8 SystemD
__Домашнее задание__  
  
✅ 1. Написать сервис, который будет раз в 30 секунд мониторить лог на предмет наличия ключевого слова. Файл и слово должны задаваться в `/etc/sysconfig`  
__Решение:__ [`(8-1)Vagrantfile`](https://github.com/io-sys/1-8-SystemD-SysV-nspawn/blob/master/(8-1)Vagrantfile) с использованием `Vagrantfile` через `Shell` `Provisioner`. План решения [ссылка](https://github.com/io-sys/1-8-SystemD-SysV-nspawn/blob/master/8-1-write-service.md).  
✅ 2. Из epel установить spawn-fcgi и переписать init-скрипт на unit-файл. Имя сервиса должно так же называться.  
__Решение:__ [`(8-2)Vagrantfile`](https://github.com/io-sys/1-8-SystemD-SysV-nspawn/blob/master/(8-2)Vagrantfile) с использованием `Vagrantfile` через `Shell` `Provisioner`.  
✅ 3. Дополнить юнит-файл apache httpd возможность запустить несколько инстансов сервера с разными конфигами.  
__Решение:__ [`(8-3)Vagrantfile`](https://github.com/io-sys/1-8-SystemD-SysV-nspawn/blob/master/(8-3)Vagrantfile) с использованием `Vagrantfile` через `Shell` `Provisioner`.  

❌ 4*. Скачать демо-версию Atlassian Jira и переписать основной скрипт запуска на unit-файл

### Задание необходимо сделать с использованием Vagrantfile и Provisioner  shell (или ansible, на Ваше усмотрение).
