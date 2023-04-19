# CLOCK_ESP8266

Updated multilingual version

This version of the watch is a continuation of the previous version with updates:
- the web interface has been changed
- optimized server requests
- changed the file system to LittleFS
- code ported to PlatfpormIO
- added clock languages (Ukrainian, Polish, English, German, Russian)

Deleted:
- LED lighting control
- work under popular monitoring.

Times can:
- get time from the Internet
- receive time from the time module (if available)
- get forecast and current weather from weather servers
- exchange notifications via MQTT, Thingspeak
- receive temperature, humidity, pressure from local sensors DS18B20, BMP180, BME280, SI7021, ATH10-20
- receive air quality data from the SGP30 sensor
- display information on an 8x8 display from 4 to 10 modules in one line or 4x2 modules (large numbers)
- adjust the brightness of the screen either by time or through the sensor
- display information about the weather in a running line
- receive and display information from external sensors/devices on the screen
- you can set alarms, memorable dates and reminders
- sound reproduction of events
- the infrared bullet (if available) can be used to control the display styles of the clock, etc.
- settings can be saved on the computer and restored if necessary.

To start work, only two modules are enough: a NodeMCU type board (ESP8266) and an indicator board on MAX7219

The firmware file should be downloaded at the address 0x00, and the LittleFS file system at the address 0x200000

Оновлена мультимовна версія

Ця версія годинника - є продовженням попередньої версії з оновленнями:
- змінено web інтерфейс
- оптимізовано запроси серверу
- змінено файлову систему на LittleFS
- код перенесено на PlatfpormIO
- додані мови годинника (Українська, Польстка, Англійська, Німецька, Російська)

Видалено:
- керування світлодіодною підсвіткою
- робота за народним моніторінгом.

Часи вміють:
- отримувати час з мережі інтерет
- отримувати чаз з часового модулю(при наявності)
- отримувати прогноз та поточну погоду з погодних серверів
- обмінюватися сповіщеннями через MQTT, Thingspeak
- отримувати температуру, влажність, тиск з локальних датчиків DS18B20, BMP180, BME280, SI7021, ATH10-20
- отримувати дані якості повітря з датчику SGP30
- виводити інформацію на дисплей 8х8 від 4 до 10 модулів в один рядок або 4х2 модулі (великі цифри)
- регулювати яскравістю екрану або по часу або через сенсор
- виводити інформацію про погоду в бегучому рядку
- отримувати та виводити інформацію від зовнішніх датчиків/пристроїі на екран
- можна встановити будильники, пам'ятні дати та нагадування
- звукове відтворення подій
- інфрачервоним пульном (при наявності) можна керувати стилями відображення годинника та інш. 
- налаштування можна сберегти на компютері і в разі необхідності відновити.

Для початку праці, достатньо тільки двох модулів: плата типу NodeMCU(ESP8266) та плати індікатора на MAX7219

Файл прошивки треба завантажити за адресою 0х00, а файлову систему LittleFS за адресою 0х200000

<a href="https://ibb.co/23wNZb2"><img src="https://i.ibb.co/hFkfYq5/123.jpg" alt="123" border="0"></a>

<a href="https://ibb.co/TLgKBty"><img src="https://i.ibb.co/L5ZQz1K/image.jpg" alt="image" border="0"></a>

<a href="https://ibb.co/mtZmWcC"><img src="https://i.ibb.co/ft6bwxY/image.jpg" alt="image" border="0"></a>
