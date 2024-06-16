# Dokumentasi FP Integrasi Sistem

Anggota Kelompok 8

| Nama                 | NRP        |
| -------------------- | ---------- |
| Samuel Yuma Krismata | 5027221029 |
| M. Harvian Dito S.   | 5027221039 |

## Project 1

### Setup Hardware

Berikut adalah hardware yang diperlukan

-   NodeMCU ESP8266
-   Sensor DHT22
-   Kabel Jumper
-   Breadboard

Berikut adalah konfigurasi hardware

-   DHT22 Pin **OUT** - ESP8266 Pin **D1** (GPIO5)
-   DHT22 pin **(+)** - ESP8266 pin **3V**
-   DHT22 pin **(-)** - ESP8266 pin **GND**

### Setup MQTT Broker

Kode untuk NodeMCU & Sensor DHT22 dapat dilihat pada [file berikut](./project-1/MQTT.ino)

Kode untuk menampilkan output dari MQTT melalui website dapat dilihat pada [file berikut](./project-1/index.html)

### Dokumentasi

Berikut adalah dokumentasi selama pengerjaan proyek ini

![1](https://github.com/harvdt/Project-FP-MQTT-Integrasi_Sistem/assets/118542326/78f7f947-d4e8-4cd7-b48a-8da8ad2df23c)

![2](https://github.com/harvdt/Project-FP-MQTT-Integrasi_Sistem/assets/118542326/da5fed03-2271-4312-b2e9-ecbce00e513e)

### Video Penjelasan

Video penjelasan terkait dengan proyek ini dapat dilihat pada [link berikut](https://youtu.be/8HK9N1a3S1U)

## Project 2

### Setup Hardware

Berikut adalah hardware yang diperlukan

-   NodeMCU ESP8266
-   Sensor DHT22
-   Kabel Jumper
-   Breadboard
-   Raspberry Pi
-   Led

Berikut adalah konfigurasi hardware

-   DHT22 Pin **OUT** - ESP8266 Pin **D1** (GPIO5)
-   DHT22 pin **(+)** - ESP8266 pin **3V**
-   DHT22 pin **(-)** - ESP8266 pin **GND**
-   Led pin **(-)** - Rasberry Pi pin **GND**
-   Led pin **(+)** - Raspberry Pi pin **12**

### Setup MQTT Broker

Kode untuk NodeMCU & Sensor DHT22 dapat dilihat pada [file berikut](./project-2/ino-Code/MQTT.ino)

Kode untuk Raspberry Pi mqtt Publisher dapat dilihat pada [file berikut](./project-2/Python-Code/mqtt_pub.py)

Kode untuk Raspberry Pi mqtt Subscriber dapat dilihat pada [file berikut](./project-2/Python-Code/mqtt_sub.py)

Kode untuk menampilkan output suhu dari sensor DHT 22 dan melakukan on/off LED melalui website dapat dilihat pada [file berikut](./project-2/Web/index.html)

### Dokumentasi

Berikut adalah dokumentasi selama pengerjaan proyek ini

![1](https://github.com/harvdt/Project-FP-MQTT-Integrasi_Sistem/assets/115382618/72508b72-e0e0-46a6-a055-1143f78342a3)

![2](https://github.com/harvdt/Project-FP-MQTT-Integrasi_Sistem/assets/115382618/e100e5dc-e199-4d1a-9c3b-bc04518b0eea)

![3](https://github.com/harvdt/Project-FP-MQTT-Integrasi_Sistem/assets/115382618/cf887aae-0d69-4e7d-b3cf-b0b95a29ebcf)

### Video Penjelasan

Video penjelasan terkait dengan proyek ini dapat dilihat pada [link berikut](https://youtu.be/oH-x2QYfXsM?si=RSHeB1j34df-oyhb)