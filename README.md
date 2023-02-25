# Lab7
## Лабораторная работа - Анализ трафика
### Цель:Вам предложен дамп трафика, необходимо изучить его с помощью любого анализатора трафика и понять, что происходило при данном сетевом взаимодействии.
#### Сеанс ssh  по 22 порту
![image](https://user-images.githubusercontent.com/122459067/221358898-b8037494-ceed-4930-b0aa-81bdc3b6d97b.png)
![image](https://user-images.githubusercontent.com/122459067/221358949-e9fc6c80-cd62-43ea-a238-750a5c94bb78.png)
![image](https://user-images.githubusercontent.com/122459067/221358953-a861d45d-9cbb-4fda-becb-10d369388365.png)
#### Шифрование ключей алгоритмом деффи-хеллмана
![image](https://user-images.githubusercontent.com/122459067/221358959-31e51d54-f8b6-450c-9a8a-cc21e1965770.png)
#### ARP-спуфинг
![image](https://user-images.githubusercontent.com/122459067/221358970-2e40de8b-e51d-4f8c-91f6-107f4715c6b4.png)
![image](https://user-images.githubusercontent.com/122459067/221358975-a5976e91-bbf5-4557-ab4f-b2589fef4008.png)
#### TFTP — протокол передачи файлов 
![image](https://user-images.githubusercontent.com/122459067/221358992-de85b5a1-476d-4784-a751-4410dce554fe.png)
#### Была передача файла
![image](https://user-images.githubusercontent.com/122459067/221358998-182d2508-8912-45ee-b3d9-4567574ab6c7.png)
#### 2 DNS-сервера
![image](https://user-images.githubusercontent.com/122459067/221359000-1f55b473-3875-436a-b91b-66a9ae373af2.png)
![image](https://user-images.githubusercontent.com/122459067/221359014-76f649a5-a3cb-4165-85a7-22b14f17e1b4.png)
![image](https://user-images.githubusercontent.com/122459067/221359018-014c62b9-4d82-4588-92ed-b5ec01ea25f9.png)
#### 1 DHCP – сервер
![image](https://user-images.githubusercontent.com/122459067/221359030-17cb44c7-aa43-4fa8-8832-fa23c526ad8c.png)
#### Учетные данные – пароль
![image](https://user-images.githubusercontent.com/122459067/221359034-5e8f359f-016a-4285-86f0-afcb5c1e36d1.png)
#### Карта сети
![image](https://user-images.githubusercontent.com/122459067/221359046-a3a7f6df-2e97-4dc6-bd94-dc68f005cf66.png)
![image](https://user-images.githubusercontent.com/122459067/221359050-03dd73fc-be5f-4527-833d-b420a129ab27.png)
#### UDLD — протокол уровня 2, который инициализирует устройства, подключенные через оптоволоконные кабели или кабели Ethernet с витой парой. Отслеживает физическое соединение для обнаружения однонаправленных соединений.
![image](https://user-images.githubusercontent.com/122459067/221359069-fe8c6656-5140-4b71-80c4-b1bdb497eced.png)
#### Магистральный протокол VLAN
![image](https://user-images.githubusercontent.com/122459067/221359098-fd32b6a6-3df9-4e5a-807e-b9368f46dfa0.png)
#### Разрыв соединения TCP
![image](https://user-images.githubusercontent.com/122459067/221359113-08471e57-196c-45b6-b901-ed23e7eac2f0.png)
#### Пакеты с ошибками
![image](https://user-images.githubusercontent.com/122459067/221359119-d9c8e7d1-b231-490e-9d84-11b25c5a0317.png)
#### STP — обеспечивает топологию без петель для любой локальной сети Ethernet с мостовым соединением.
![image](https://user-images.githubusercontent.com/122459067/221359129-cdfc983d-1582-4b9f-b4f4-53a48025ebc7.png)
#### Простой протокол управления сетью ( SNMP )
![image](https://user-images.githubusercontent.com/122459067/221359140-4a36348f-c6c9-4b9a-8f9a-973d9cbadf72.png)
#### Протокол тестирования конфигурации
![image](https://user-images.githubusercontent.com/122459067/221359154-e0d22977-7cc8-4e49-8f1f-0027361f35bd.png)

Доработать скрипт packet_sniff.py, написанный на занятии, чтобы он выводил URL-адреса, которые запрашивал пользователь (для этого можно использовать http.HTTPRequest: /path, Host)
3*. Познакомиться с утилитой SSLStrip (https://blog.desdelinux.net/ru/sslstrip-espiando-trafico-ssl/, https://github.com/moxie0/sslstrip). Запустить по инструкции "обход https", приложенной к материалам занятия.

### Описание/Пошаговая инструкция выполнения домашнего задания:
Необходимо описать ход своих рассуждений, а также скриншоты анализатора трафика, по которым вы делали выводы относительно происходящего.
Результатом станет доработанный скрипт, а также скриншот с результатом работы скрипта, где виден вывод запрашиваемых пользователем URL-адресов.
