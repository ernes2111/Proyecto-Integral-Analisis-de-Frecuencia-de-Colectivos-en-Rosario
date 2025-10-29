# 🚌 Proyecto Integral: Análisis de Frecuencia de Colectivos en Rosario

Este proyecto integra tres etapas complementarias para consultar, registrar y analizar datos de colectivos en Rosario, Argentina. El objetivo fue construir una herramienta completa que permita obtener información en tiempo real, almacenar históricos de datos y realizar análisis exploratorio de la calidad del servicio de transporte público.

---

## 🔹 Descripción corta
Sistema en Python que combina un bot de Telegram, un registrador automático de datos y análisis exploratorio en Jupyter Notebook, para estudiar la frecuencia y tiempos de arribo de colectivos en Rosario.

---

## 🔹 Descripción larga
Este proyecto se divide en tres etapas:

### 1️⃣ Bot de Telegram – [Bot Colectivos Rosario](https://github.com/ernes2111/bot-colectivos-rosario)
Un bot en Python que permite consultar en tiempo real la llegada de colectivos mediante la API pública de **Cuándo Llega Rosario**.  
**Funciones principales:**
- Consultar líneas y ramales (ej. 153 R, 120, 123).  
- Mostrar tiempo estimado de arribo y distancia aproximada.  
- Funciona 24/7 en Raspberry Pi con systemd.  
- Logs opcionales para seguimiento del servicio.

### 2️⃣ Registro automático – [Log Colectivos Rosario](https://github.com/ernes2111/log-colectivos-rosario)
Script en Python que consulta periódicamente la API y almacena los datos en **archivos CSV semanales**, creando un histórico de datos para análisis posterior.  
**Funciones principales:**
- Ejecución automática cada 5 minutos (configurable).  
- Almacenamiento de tiempos de arribo, distancias y frecuencias.  
- Construcción de base de datos histórica sobre transporte público.

### 3️⃣ Análisis de datos – [Análisis Colectivos Rosario](https://github.com/ernes2111/analisis-colectivos-rosario)
Análisis exploratorio de la base de datos obtenida mediante Python, Pandas, NumPy y Matplotlib en Jupyter Notebook.  
**Funciones principales:**
- Limpieza y análisis de datos.  
- Visualización de patrones de frecuencia y tiempos de espera.  
- Notebooks en español e inglés, junto a gráficos de referencia.

---

## 🔹 Resultados obtenidos / Características principales
- ✅ Sistema completo de consulta, registro y análisis automatizado.  
- 🔁 Ejecución continua 24/7 en Raspberry Pi con recopilación histórica de datos.  
- 📊 Análisis exploratorio detallado de frecuencia, tiempos de espera y patrones de disponibilidad.  
- 📱 Acceso rápido vía Telegram, complementado con notebooks y visualizaciones gráficas.

---

## 🔹 Tecnologías utilizadas
- **Python 3.10+** – Desarrollo de scripts y análisis.  
- **Telegram Bot API** – Interacción en tiempo real.  
- **Pandas & NumPy** – Limpieza, análisis y cálculos de datos.  
- **Matplotlib** – Visualización de gráficos.  
- **Jupyter Notebook** – Entorno interactivo de análisis.  
- **CSV / manejo de archivos** – Almacenamiento de datos históricos.  
- **Raspberry Pi / systemd** – Ejecución continua 24/7 de scripts.  
- **API pública de Cuándo Llega Rosario** – Fuente de datos en tiempo real.

---

## 🔹 Enlaces a repositorios
- [Bot Colectivos Rosario](https://github.com/ernes2111/bot-colectivos-rosario)  
- [Log Colectivos Rosario](https://github.com/ernes2111/log-colectivos-rosario)  
- [Análisis Colectivos Rosario](https://github.com/ernes2111/analisis-colectivos-rosario)

