Задание 1
Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.


<img width="1920" height="1020" alt="Снимок экрана 2026-07-31 184524" src="https://github.com/user-attachments/assets/404f63aa-aec1-42bf-a0cf-6b14e51b132b" />
<img width="1920" height="1020" alt="Снимок экрана 2026-07-31 184315" src="https://github.com/user-attachments/assets/7cec3850-6459-4570-bb80-8aba3a1f7016" />
<img width="1920" height="1020" alt="Снимок экрана 2026-07-31 183842" src="https://github.com/user-attachments/assets/3d217d8d-5a1b-45ec-9eec-05733fdca4c0" />
<img width="1920" height="1020" alt="Снимок экрана 2026-07-31 183546" src="https://github.com/user-attachments/assets/0d657381-9cee-4794-99d4-3d04ce60aaa1" />
<img width="1920" height="1020" alt="Снимок экрана 2026-07-31 192127" src="https://github.com/user-attachments/assets/5a9900a8-6c6a-410a-b465-6bc8ea91aab7" />


Задание 2
Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

