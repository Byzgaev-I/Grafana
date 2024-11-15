# Домашнее задание "Средство визуализации Grafana"   

---

### Обязательные задания

**Задание 1** 

1) Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.  
2) Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.  
3) Подключите поднятый вами prometheus, как источник данных.  
4) Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource.

![image.jpg](https://github.com/Byzgaev-I/Grafana/blob/main/2.png)

**Задание 2** 

Изучите самостоятельно ресурсы:
- PromQL tutorial for beginners and humans.
- Understanding Machine CPU usage.
- Introduction to PromQL, the Prometheus query language.

  Создайте Dashboard и в ней создайте Panels:

- утилизация CPU для nodeexporter (в процентах, 100-idle);
- CPULA 1/5/15;
- количество свободной оперативной памяти;
- количество места на файловой системе.
Для решения этого задания приведите promql-запросы для выдачи этих метрик, а также скриншот получившейся Dashboard.

![image.jpg](https://github.com/Byzgaev-I/Grafana/blob/main/3.png) 

