# 🧠⚡ EEG CEGS – Sistema de Captura y Procesamiento de Señales Cerebrales 🧠⚡

> Proyecto desarrollado por estudiantes de Ingeniería Electrónica – UCEVA  
> ¡Captura, procesa y analiza la actividad eléctrica del cerebro con ESP32-S3 y PCB personalizada!

---

## 📋 Descripción del Proyecto

Este proyecto tiene como objetivo el diseño e implementación de un sistema funcional de **electroencefalograma (EEG)**, capaz de capturar y procesar señales cerebrales en tiempo real mediante una **ESP32-S3** y una PCB diseñada a medida.

El sistema opera mediante una **máquina de estados finita (FSM) tipo Moore**, controlada a través de entradas táctiles (`Touch 1` y `Touch 2`). Estas transiciones permiten pasar entre las fases: reposo, captura, procesamiento y visualización del resultado.

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
