# 🧠⚡ EEG CEGS – Sistema de Captura y Procesamiento de Señales Cerebrales 🧠⚡

> Proyecto desarrollado por estudiantes de Ingeniería Electrónica – UCEVA  
> ¡Captura, procesa y analiza la actividad eléctrica del cerebro con ESP32-S3 y PCB personalizada!

---

## 📋 Descripción del Proyecto

Este proyecto tiene como objetivo el diseño e implementación de un sistema funcional de **electroencefalograma (EEG)**, capaz de capturar y procesar señales cerebrales en tiempo real mediante una **ESP32-S3** y una PCB diseñada a medida.

El sistema opera mediante una **máquina de estados finita (FSM) tipo Moore**, controlada a través de entradas táctiles (`Touch 1` y `Touch 2`). Estas transiciones permiten pasar entre las fases: reposo, captura, procesamiento y visualización del resultado.

---



---

## 🖼️ Imágenes asociadas al desarrollo del proyecto

A continuación se presentan algunas imágenes que ilustran el proceso de desarrollo del sistema EEG, desde la etapa de diseño de la PCB hasta la programación de la ESP32-S3 y la integración final del hardware.

Estas imágenes permiten comprender mejor la evolución del proyecto y cómo se fueron incorporando cada uno de los componentes tanto físicos como lógicos.

### Diseño de la PCB

![EEG_PCB](https://github.com/user-attachments/assets/cf16b983-8e7f-4a75-8311-91af731f5f32)

### Implementación física

![Captura de pantalla 2025-05-31 153307](https://github.com/user-attachments/assets/c6e89321-6307-485e-95c0-b0126e7185db)

### Pruebas con ESP32-S3

![ESP32_FFT](https://github.com/user-attachments/assets/c1f6f97e-029d-485d-85c3-90b580b70a7e)

---








## 🧩 Características principales

- ✅ Captura de señales EEG por entrada analógica (ADC)
- ✅ Procesamiento interno de señales (FFT básica en desarrollo)
- ✅ Máquina de estados con 4 fases: **reposo**, **captura**, **procesamiento**, **resultado**
- ✅ Control mediante sensores táctiles capacitivos (`Touch 1`, `Touch 2`)
- ✅ Visualización del resultado mediante pantalla OLED
- ✅ Código desarrollado en **PlatformIO (VSCode)** usando lenguaje **C++**
- ✅ PCB diseñada y **archivos GERBER listos para fabricación**

---

## 🛠️ Tecnologías y herramientas usadas

- 🔹 **ESP32-S3** (WiFi + Touch + ADC + potencia de procesamiento)
- 🔹 **PlatformIO** sobre **VSCode**
- 🔹 Diseño de PCB con **Autodesk EAGLE**
- 🔹 Procesamiento de señales EEG (FFT)
- 🔹 Pantalla **OLED**
- 🔹 FSM implementada en **C++**

---

## 🚀 Estado del proyecto

> ✅ **Proyecto finalizado** – FSM operativa, código funcional, y PCB lista para fabricación mediante archivos Gerber.

---

## 🤝 Aportaciones

¿Tienes experiencia en neurotecnología, diseño de filtros o visualización de señales EEG?  
¡Puedes contribuir al proyecto! 😄

---

## 📜 Licencia

Este proyecto está bajo licencia **MIT**.  
Puedes usar, modificar y compartir el código libremente, siempre dando crédito a los autores.

---

**Proyecto académico desarrollado por estudiantes de Ingeniería Electrónica – UCEVA**
