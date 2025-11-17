# Домашнее задание к занятию 2 `«Кластеризация и балансировка нагрузки»` - `Чеботников М.Б.`

### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.
<img width="1247" height="229" alt="11" src="https://github.com/user-attachments/assets/ce87a248-4795-429b-9e1e-9ab7f9c5d97c" />
<img width="1280" height="800" alt="12" src="https://github.com/user-attachments/assets/77fdbf1a-008d-461a-a0b4-df7dfedd478f" />
<img width="1280" height="800" alt="13" src="https://github.com/user-attachments/assets/e5335717-d700-4611-9032-f85e44ba2102" />
<img width="1280" height="800" alt="16" src="https://github.com/user-attachments/assets/02042b00-4cac-42a5-9b24-e95a21e77342" />
<img width="1280" height="767" alt="17" src="https://github.com/user-attachments/assets/35277d13-488e-4131-9525-7d0e74e8aff6" />
<img width="1280" height="800" alt="18" src="https://github.com/user-attachments/assets/2c97ac7a-8e78-46cb-806e-44e3102bcf0e" />

### Ссылка файл HAProxy
https://github.com/makscebotnikov-cmd/Claster-and-Balance/blob/main/haproxy.cfg

  ### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
<img width="347" height="333" alt="21" src="https://github.com/user-attachments/assets/d60b197b-6c7c-431e-8a7f-467a04358ffe" />
<img width="1277" height="434" alt="22" src="https://github.com/user-attachments/assets/6456f105-c808-4d62-a90d-cd41e81b9cb7" />

### Ссылка файл HAProxy
https://github.com/makscebotnikov-cmd/Claster-and-Balance/blob/main/haproxy_2.cfg
