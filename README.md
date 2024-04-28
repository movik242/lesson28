# lesson28

***Домашнее задание***

настроить hot_standby репликацию с использованием слотов </br>
настроить правильное резервное копирование </br>

Для сдачи работы присылаем ссылку на репозиторий, в котором должны обязательно быть </br>
Vagranfile (2 машины) </br>
плейбук Ansible </br>
конфигурационные файлы postgresql.conf, pg_hba.conf и recovery.conf, </br>
конфиг barman, либо скрипт резервного копирования. </br>

Задание выполнялось согласно методичке.

Сначала vagrant разворачивает 3 ВМ, потом playbook устанавливаем postgresql15 barman и настраиваем репликацию, все конфиги представлены в ролях.

Проверка работы представлена на скриншотах

![image](https://github.com/movik242/lesson28/assets/143793993/4fcaaae2-0e34-4ee8-bc2e-83e6e72e32ee)

Создание первого бекапа

![image](https://github.com/movik242/lesson28/assets/143793993/e6c4e08e-1707-49d1-bb4a-5e9a90ae5eeb)

Настройка на node1

![image](https://github.com/movik242/lesson28/assets/143793993/b8e8f142-8ab5-467f-abec-6ce4c0ec8d2c)

![image](https://github.com/movik242/lesson28/assets/143793993/004deffc-d4f6-4ff2-ba25-c9348ed01808)

Восстановление из бекапа

![image](https://github.com/movik242/lesson28/assets/143793993/42741133-e885-46e9-bfb4-e5c21034787e)

Проверка на node1

![image](https://github.com/movik242/lesson28/assets/143793993/577dac46-d8a0-41e6-a760-fc707af0b905)




