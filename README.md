# 1-8-SystemD-SysV-nspawn
Домашнее задание
Systemd
1. Написать сервис, который будет раз в 30 секунд мониторить лог на предмет наличия ключевого слова. Файл и слово должны задаваться в /etc/sysconfig
2. Из epel установить spawn-fcgi и переписать init-скрипт на unit-файл. Имя сервиса должно так же называться.
3. Дополнить юнит-файл apache httpd возможность запустить несколько инстансов сервера с разными конфигами
4*. Скачать демо-версию Atlassian Jira и переписать основной скрипт запуска на unit-файл

Задание необходимо сделать с использованием Vagrantfile и proviosioner shell (или ansible, на Ваше усмотрение)
