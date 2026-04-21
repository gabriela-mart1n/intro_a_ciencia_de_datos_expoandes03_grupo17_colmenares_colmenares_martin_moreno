<!-- TITULO CON ESTILO -->
<h1 align="center">🚍 Análisis de Congestión en TransMilenio</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-yellow">
  <img src="https://img.shields.io/badge/Python-3.x-blue">
  <img src="https://img.shields.io/badge/Datos-TransMilenio-red">
  <img src="https://img.shields.io/badge/Proyecto-Académico-green">
</p>

<p align="center">
  <i>Evaluación del flujo de pasajeros y la capacidad operativa en estaciones críticas del sistema de transporte de Bogotá</i>
</p>

---

## 📸 Vista General

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/TransMilenio_bus.jpg/800px-TransMilenio_bus.jpg" width="500">
</p>

---

## 📌 Descripción

Este proyecto analiza el comportamiento del flujo de pasajeros en las estaciones **Las Aguas** y **Museo del Oro** de TransMilenio, con el objetivo de identificar fallas en la relación entre la **demanda real** y la **capacidad del sistema**.

Actualmente, ambas estaciones dependen exclusivamente de la ruta **FJ23**, lo que genera problemas de congestión, riesgo operativo y baja eficiencia en la movilidad.

---

## 🚨 Problema

⚠️ Las estaciones presentan:

- Dependencia de una única ruta  
- Congestión alta en horas pico  
- Alta afluencia incluso en horas valle  
- Incremento en tiempos de espera  

📉 Además:

No existe un modelo específico que analice la relación entre **demanda vs oferta** por franja horaria en estas estaciones.

---

## 🎯 Objetivo

Identificar los momentos del día en los que la capacidad del sistema es insuficiente frente a la demanda, para proponer mejoras como:

- 📈 Ajuste de frecuencias  
- 🚌 Nuevas rutas  
- ⏱️ Reducción de tiempos de espera  
- 🌱 Optimización del sistema de transporte  

---

## 📊 Datos Utilizados

### 🔹 Datos principales
- Validaciones de pasajeros por hora  
- Frecuencia de buses (ruta FJ23)  
- Variación operativa por franja horaria  

### 🔹 Datos complementarios
- Impacto del carril único  
- Factores externos de operación  

---

## ⚙️ Metodología

```mermaid
flowchart TD
    A[Recolección de datos] --> B[Procesamiento]
    B --> C[Análisis de demanda]
    C --> D[Análisis de oferta]
    D --> E[Comparación]
    E --> F[Identificación de congestión]
