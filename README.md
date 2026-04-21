# Домашнее задание к занятию "Zabbix-2" - Валик Александр



### Задание 1


1. В веб-интерфейсе Zabbix Servera в разделе Templates создан новый шаблон "Задание 1"

2. В шаблоне "Задание 1" создан Item, который будет собирать информацию об загрузке CPU в процентах  

3. В шаблоне "Задание 1" создан Item, который будет собирать информацию об загрузке RAM в процентах

![screen1](./img/screen1.png)



### Задание 2

1. Установлен Zabbix Agent на локальную ВМ и на Yandex Cloud

```bash
wget https://repo.zabbix.com/zabbix/7.4/release/ubuntu/pool/main/z/zabbix-release/zabbix-release_latest_7.4+ubuntu24.04_all.deb  
```

```bash
dpkg -i zabbix-release_latest_7.4+ubuntu24.04_all.deb  
```

```bash
apt update  
```

```bash
apt install zabbix-agent
```

2. Отредектированы файлы /etc/zabbix/zabbix_agentd.conf

3. Добавлены Zabbix Agent в раздел Configuration > Hosts Zabbix Servera

![screen2](./img/screen2.png)

![screen3](./img/screen3.png)

![screen4](./img/screen4.png)

![screen5](./img/screen5.png)

![screen6](./img/screen6.png)
