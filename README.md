**Лабораторная работа #3**
Задание по анализу защищенности с использованием Kali Linux и Damn Vulnerable Linux (DVL)
Выполнил студент группы ББМО-01-23, Белов Владимир Станиславович

1. Установка ВМ (Виртуальных Машин):
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/18394cbb-51f4-4ca6-9f01-03d8f0319924)
   
2. Сканирование Сети и Уязвимостей:
   
Обновление nmap

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/32206988-b6d2-4eed-b61b-b9fdc7bbd605)
   
C помощью ifconfig узнаем ip-адрес DVL и просканируем его на kali с помощью nmap

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/05e90abf-b470-4f3b-9ace-12938db00b95)
   
Установка Openvas

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/ffa82083-2fa3-4fe5-a36a-983a5e6704c1)
   
Проверим запущена ли служба Redis

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/b0b6347e-088b-423e-8eeb-6c48ef6eb264)
   
Сгенерируем пользователя для openvas/gvm

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/a4eefcdf-d87d-4193-aa6c-dc5aaed41a7c)
   
С помощью логина и пароля зайдём в личный кабинет по адресу https://127.0.0.1:9392/

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/c5c4b342-e8ec-42a3-92c4-334d79ea1ae0)
   
Зададим новую задачу с нашей 2ой виртуальной машиной

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/453276a3-c88d-48d6-b97f-a9985a523b7e)
   
Результат

   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/933c7064-1fa6-49b8-8757-4014532e6206)
   
3. Пентестинг Веб-Приложений:
   
   XSS Тестируем приложение
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/5dfcb07f-659e-48bf-82ae-c6253e71491f)
   
   Перехватываем и меняем запрос
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/dd62bb71-6548-40f1-8de3-6e207525697c)
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/dab2c1e4-1239-4efe-9c20-023e58788a69)
   
4. Анализ Безопасности Системы:
   
   Войдём в Metasploit
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/78dee0c7-c272-4736-8a87-ed7f938db646)
   
   Проверим настройку через show options и через set зададим нужный адрес, порт, путь к файлу с паролями
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/9ab0bf4b-d52d-4d97-ad30-804fb9e562ac)
   
   запускаем (run)
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/1bf44ef5-342b-4f0c-8cd7-74a0288bf11e)
   
5. Сетевая Защита и Защита От Вторжений
   
   Мониторинг сетевого трафика с помощью Wireshark
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/955ca867-e79f-45ab-bf5b-66c682838dc1)
   
   Использование Snort как системы обнаружения вторжений (IDS) для мониторинга и алертинга о попытках взлома.
   
   ![image](https://github.com/V0vochka/Lab-3/assets/70959108/6afc0fc1-3e6f-44a1-bced-21a0343b6898)

   






   

   

   











