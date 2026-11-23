# 📡 ESP32 Cloud Sensors Portfolio

Colección progresiva de proyectos de **Internet de las Cosas (IoT)** desarrollados con microcontroladores **ESP32**, distintos tipos de sensores (digitales, analógicos e I2C) e integración en tiempo real con plataformas en la nube.

---

## 🎯 Objetivo del repositorio
Documentar mi evolución práctica en el desarrollo de sistemas embebidos conectados: desde la lectura básica de variables ambientales hasta la automatización bidireccional y el envío de alertas instantáneas.

---

## 🗺️ Hoja de ruta de proyectos

| # | Proyecto | Sensores / Actuadores | Conceptos clave | Estado |
| :--- | :--- | :--- | :--- | :---: |
| **01** | [`01-ClimaLab-ESP32`](./01-ClimaLab-ESP32) | Sensor digital **DHT11 / DHT22** (Temperatura y Humedad) | Conexión WiFi, envío periódico de datos, *dashboard* móvil y gráficas históricas. | 🚧 En progreso |
| **02** | [`02-AlertaPresencia-IoT`](./02-AlertaPresencia-IoT) | Sensor **PIR HC-SR501** + Sensor magnético de puerta | Lectura digital por eventos, interrupciones y notificaciones *push* en tiempo real. | ⏳ Pendiente |
| **03** | [`03-PlantCare-ESP32`](./03-PlantCare-ESP32) | Sensor capacitivo de humedad de suelo + Fotorresistencia (**LDR**) | Entradas analógicas (`ADC1`), calibración de rangos y conversión a porcentajes. | ⏳ Pendiente |
| **04** | [`04-EcoAir-Quality`](./04-EcoAir-Quality) | Sensor barométrico **BME280** + Sensor de gases **MQ-135** | Comunicación por bus **I2C**, integración multisensor y umbrales de alarma. | ⏳ Pendiente |
| **05** | [`05-SmartRelay-Automation`](./05-SmartRelay-Automation) | Sensor **DHT11** + **Módulo Relé** (1 canal) | Control bidireccional desde la nube, automatización por reglas y control manual. | ⏳ Pendiente |

---

## 🛠️ Stack tecnológico y herramientas

* **Hardware:** ESP32 DevKit V1 (30 pines, arquitectura dual-core de 32 bits con WiFi/Bluetooth).
* **Lenguajes / Entornos:** C++ (Arduino IDE / PlatformIO) y MicroPython.
* **Plataformas Cloud IoT:** Arduino Cloud / Blynk IoT.
* **Protocolos de comunicación:** WiFi (HTTP/REST, MQTT), I2C, One-Wire.

---

## 📂 Estructura de cada proyecto

Cada carpeta sigue una estructura estándar para facilitar su replicación:

```text
nombre-del-proyecto/
├── src/          # Código fuente (.ino o .py)
├── docs/         # Diagramas de conexión, pinout y capturas de la nube
└── README.md     # Materiales, esquema de pines y guía paso a paso
```

---

## 🚀 Cómo replicar estos proyectos

1. Clona este repositorio:
   ```bash
   git clone https://github.com
   ```
2. Entra en la carpeta del proyecto que quieras probar.
3. Revisa su `README.md` interno para ver el esquema de conexión de pines y las librerías necesarias.
4. Configura tus credenciales WiFi y el token de tu plataforma en la nube antes de subir el código a la placa.

---
📫 **Contacto:** [GitHub @LucPinheiro](https://github.com)
