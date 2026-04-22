<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0000&height=220&section=header&animation=twinkling" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=8B0000&height=80&text=Análisis+de+Congestión+en+TransMilenio&fontSize=32&fontColor=ffffff" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=B22222&height=50&text=Movilidad+urbana+basada+en+datos&fontSize=20&fontColor=ffffff" width="100%"/>

<br/>

<img src="https://bogota.gov.co/sites/default/files/2025-12/transmilenio-presenta-ruta-y-mejoras-en-servicios-diciembre-bogota.jpg" width="90%" style="border-radius:14px;"/>

<br/><br/>

<img src="https://img.shields.io/badge/Proyecto-TransMilenio-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Ruta-FJ23-darkred?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Estado-En%20desarrollo-orange?style=for-the-badge"/>

<br/><br/>

> *Optimizar el transporte es optimizar la vida urbana.*

<br/>

<p>
<b>Valeria Colmenares Moreno</b> · 
<b>Miguel Colmenares Rodríguez</b> · 
<b>María Gabriela Martín Avila</b> · 
<b>Sebastián David Moreno Bustos</b>
</p>

</div>

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=300&lines=Problema" />
</div>

Las estaciones **Las Aguas** y **Museo del Oro** dependen exclusivamente de la ruta **FJ23**, lo que genera un sistema vulnerable ante fallas operativas y picos de demanda.

<p align="center">
<img src="https://media.istockphoto.com/id/1331658886/es/foto/bus-p%C3%BAblico-en-una-estaci%C3%B3n-de-pasajeros-de-la-ciudad-de-bogot%C3%A1.jpg?s=612x612&w=0&k=20&c=9WV-Vi-CrL_mf7o1fNVB6xOtox62P2sRE6tdUvu8aGo=" width="65%" style="border-radius:12px;">
</p>

En horas pico, la demanda supera la capacidad del sistema, generando congestión, aumento en tiempos de espera y saturación del servicio.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=400&lines=Pregunta+clave" />
</div>

<div align="center">
<i>¿Cuándo la oferta del sistema no alcanza la demanda?</i>
</div>

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=450&lines=Información" />
</div>

<div align="center">

| Tipo | Variable | Descripción |
|------|----------|-------------|
| **Principal** | Validaciones | Ingreso de pasajeros |
| **Principal** | Flujo horario | Usuarios por hora |
| **Principal** | Frecuencia | Buses FJ23 |
| **Complementario** | Carril único | Impacto operativo |
| **Complementario** | Regularidad | Consistencia |
| **Complementario** | Factores externos | Condiciones externas |

</div>

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=420&lines=Sistema" />
</div>

```mermaid
flowchart LR
A[Demanda] --> B[Estaciones]
B --> C[Ruta FJ23]
C --> D[Frecuencia]
D --> E[Capacidad]
E --> F[Congestión]
```

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=420&lines=Procedimientos" />
</div>

Los datos se obtienen desde Datos Abiertos Bogotá y los canales oficiales de TransMilenio, siguiendo una metodología de tres etapas:

<div align="center">

| Etapa | Acción | Resultado |
|-------|--------|-----------|
| **1. Recolección** | Datos abiertos y registros | Datos por estación |
| **2. Limpieza** | Depuración | Datos organizados |
| **3. Agrupación** | Clasificación horaria | Patrones |
| **4. Indicador** | Oferta vs demanda | Brecha |
| **5. Diagnóstico** | Identificación de picos | Momentos críticos |

</div>

La capacidad de transporte = frecuencia de buses × capacidad por bus. Si capacidad < validaciones → congestión identificada.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=350&lines=Producto" />
</div>

El entregable final es un tablero interactivo que integra análisis de validaciones, capacidad operativa y patrones de congestión para las estaciones del Eje Ambiental (Troncal J).

<div align="center">

| Funcionalidad | Descripción |
|---------------|-------------|
| Validaciones por día | Patrones semanales de demanda |
| Filtro por hora | Demanda desagregada por franja horaria |
| Oferta vs Demanda | Comparación directa del sistema |
| Escenarios | Simulación de mejoras operativas |

</div>

### Mapas de calor: Validaciones y Capacidad

<img width="1600" height="669" alt="WhatsApp Image 2026-04-21 at 3 28 58 PM" src="https://github.com/user-attachments/assets/65c45716-16a2-454b-b59e-06e07b8b95e2" />

Los mapas de calor revelan una **desalineación clara entre demanda y capacidad** en las estaciones Las Aguas y Museo del Oro. Mientras las validaciones muestran picos intensos y recurrentes —especialmente marcados en Museo del Oro—, la frecuencia de buses se mantiene relativamente constante a lo largo del día. Esto provoca que en horas pico la demanda supere la oferta, generando congestión y mayores tiempos de espera.

Lo más relevante es que estos patrones son **predecibles y repetitivos**: el problema no es la falta total de recursos, sino una inadecuada distribución de la capacidad frente a la variabilidad temporal de la demanda.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=30&pause=1000&color=8B0000&center=true&vCenter=true&width=600&lines=Dashboard+Analítico" />
</div>

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=24&pause=1000&color=B22222&center=true&vCenter=true&width=600&lines=Vista+general+del+sistema" />
</div>

<p align="center">
<img src="https://github.com/user-attachments/assets/9dd063d9-df3e-41bc-9e29-63b73dd39af9" width="85%" style="border-radius:14px;">
</p>

El tablero consolida en una sola vista la dinámica completa del sistema: demanda, capacidad y comportamiento temporal. Esta integración permite identificar rápidamente los momentos donde la operación deja de ser eficiente y comienza la congestión.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=24&pause=1000&color=B22222&center=true&vCenter=true&width=600&lines=Patrones+de+demanda" />
</div>

<p align="center">
<img src="https://github.com/user-attachments/assets/69fae6d9-fe8f-4820-8742-501a2153440c" width="45%" style="border-radius:10px;">
<img src="https://github.com/user-attachments/assets/838bb0d3-753d-43b1-97be-70e37aa76572" width="45%" style="border-radius:10px;">
</p>

La demanda muestra un comportamiento creciente a lo largo del día, con un incremento sostenido hasta alcanzar su punto máximo en la franja de la tarde. Este patrón no presenta variaciones abruptas, lo que indica que los picos de congestión son altamente predecibles.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=24&pause=1000&color=B22222&center=true&vCenter=true&width=600&lines=Capacidad+del+sistema" />
</div>

<p align="center">
<img src="https://github.com/user-attachments/assets/40655d4e-3af1-47a0-b47e-4dd4e19902be" width="45%" style="border-radius:10px;">
<img src="https://github.com/user-attachments/assets/b75cdaa0-481f-4193-a030-74c4e3363e12" width="45%" style="border-radius:10px;">
</p>

A diferencia de la demanda, la capacidad operativa no presenta un ajuste dinámico. La frecuencia de buses se mantiene relativamente estable, generando un desfase evidente frente a las necesidades reales del sistema.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=24&pause=1000&color=B22222&center=true&vCenter=true&width=600&lines=Desbalance+operativo" />
</div>

<p align="center">
<img src="https://github.com/user-attachments/assets/d6b3e291-98ec-4530-9bfb-c51b8d9c78ff" width="60%" style="border-radius:12px;">
</p>

El cruce entre demanda y capacidad evidencia un desbalance estructural. En múltiples franjas horarias, especialmente en horas pico, la capacidad disponible resulta insuficiente, generando acumulación de pasajeros y aumento en los tiempos de espera.

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=24&pause=1000&color=B22222&center=true&vCenter=true&width=600&lines=Lectura+general" />
</div>

- La congestión no es un evento aislado, es un patrón repetitivo  
- La demanda crece de forma progresiva y predecible  
- La oferta permanece estática frente a cambios en el flujo de usuarios  
- Existe una brecha constante entre capacidad y necesidad operativa  

---

<div align="center">

<img src="https://img.shields.io/badge/Herramienta-Dashboard-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Enfoque-Optimización-darkred?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Impacto-Movilidad+Sostenible-orange?style=for-the-badge"/>

</div>

---
