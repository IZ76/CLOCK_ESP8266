# CLOCK_ESP8266
Оновлена мультимовна версія

Ця версія годинника - є продовженням попередньої версії з оновленнями:
- змінено web інтерфейс
- оптимізовано запроси серверу
- змінено файлову систему на LittleFS
- код перенесено на PlatfpormIO
- додані мови годинника (Українська, Польстка, Англійська, Німецька, Російська)
виделено:
- керування світлодіодною підсвіткою
- робота за народним моніторінгом.

Часи вміють:
- отримувати час з інтерет мережі
- отримувати чаз з часовогомодулю(при наявності)
- отримувати прогноз та поточну погоду з серверів
- обмінюватися сповіщеннями через MQTT, Thingspeak
- отримувати температуру, влажність, тиск з локальних датчиків DS18B20, BMP180, BME280, SI7021, ATH10-20
- отримувати дані якості повітря з датчику SGP30
- виводити інформацію на дисплей 8х8 від 4 до 10 модулів в один рядок або 4х2 модулі (великі цифри)
- виводити інформацію про погоду в бегучому рядку
- отримувати та виводити інформацію від зовнішніх датчиків/пристроїі на екран
- можна встановити будильники, пам'ятні дати та нагадування
- інфрачервоним пульном (при наявності) можна керувати стилями відображення годинника та інш. 
- налаштування можна сберегти на компютері і в разі необхідності відновити.

Для початку праці, достатньо тільки двох модулів: плата типу NodeMCU(ESP8266) та плати індікатора на MAX7219


Файл прошивки треба завантажити за адресою 0х00, а файлову систему LittleFS за адресою 0х200000

<a href="https://ibb.co/23wNZb2"><img src="https://i.ibb.co/hFkfYq5/123.jpg" alt="123" border="0"></a>

<a href="https://ibb.co/TLgKBty"><img src="https://i.ibb.co/L5ZQz1K/image.jpg" alt="image" border="0"></a>

<a href="https://ibb.co/mtZmWcC"><img src="https://i.ibb.co/ft6bwxY/image.jpg" alt="image" border="0"></a>
