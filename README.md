# Weather-Logger-System
Environmental data logging system using Arduino and sensor
# Weather-Logger-System

## Description
Logs weather data like Temperature, Humidity, and Pressure from sensors to SD card.
Used for environmental monitoring and weather stations.

## Components Required
- Arduino Uno
- DHT11 Sensor - Temperature & Humidity
- BMP180 Sensor - Pressure
- DS3231 RTC Module - Date & Time
- SD Card Module + SD Card
- Jumper Wires

## Circuit Connections
| Sensor | Arduino Pin |
| --- | --- |
| DHT11 Data | D2 |
| BMP180 SDA | A4 |
| BMP180 SCL | A5 |
| RTC SDA | A4 |
| RTC SCL | A5 |
| SD CS | D4 |
| SD MOSI | D11 |
| SD MISO | D12 |
| SD SCK | D13 |

## Working Principle
1. Every 5 seconds sensors read data
2. RTC gives Date and Time
3. Arduino saves data to `weather.csv` in SD card
4. Data can be opened in Excel for analysis

## Real-World Application
Weather Stations, Agriculture Monitoring, Climate Research
