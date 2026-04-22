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

### 🔥 Mapas de calor: Validaciones y Capacidad

<p align="center">
<img src="heatmap.jpeg" width="90%" style="border-radius:12px;"/>
</p>

Los mapas de calor revelan una **desalineación clara entre demanda y capacidad** en las estaciones Las Aguas y Museo del Oro. Mientras las validaciones muestran picos intensos y recurrentes —especialmente marcados en Museo del Oro—, la frecuencia de buses se mantiene relativamente constante a lo largo del día. Esto provoca que en horas pico la demanda supere la oferta, generando congestión y mayores tiempos de espera.

Lo más relevante es que estos patrones son **predecibles y repetitivos**: el problema no es la falta total de recursos, sino una inadecuada distribución de la capacidad frente a la variabilidad temporal de la demanda.

---

### 📊 Dashboard: Visualización de Afluencia y Eficiencia

<p align="center">
<img src="dashboard.png" width="90%" style="border-radius:12px;"/>
</p>

<p align="center">
<img src="validaciones_vs_capacidad.png" width="48%" style="border-radius:10px; margin:4px;"/>
<img src="suficiencia.png" width="48%" style="border-radius:10px; margin:4px;"/>
</p>

<p align="center">
<img src="validaciones_hora.png" width="48%" style="border-radius:10px; margin:4px;"/>
<img src="hora_linea.png" width="48%" style="border-radius:10px; margin:4px;"/>
</p>

<p align="center">
<img src="capacidad_hora.png" width="60%" style="border-radius:10px;"/>
</p>

El dashboard consolida los hallazgos en visualizaciones accionables. Las principales conclusiones son:

- **65% de suficiencia operativa:** Solo 6 de cada 10 horas del día presentan capacidad suficiente para atender la demanda. El 35% restante corresponde a franjas donde el sistema opera por debajo de lo necesario.

- **Pico crítico entre las 4:00 p.m. y las 6:00 p.m.:** El gráfico de validaciones por hora evidencia que la demanda escala hasta ~700 usuarios/hora en este intervalo, mientras que la capacidad disponible no crece proporcionalmente, generando el mayor punto de congestión del día.

- **Capacidad irregular a lo largo del día:** El gráfico de capacidad por hora muestra una oferta que oscila entre 500 y 680 unidades sin un patrón que responda a los picos de demanda conocidos, lo que confirma que la programación de frecuencias no está alineada con el comportamiento real de los usuarios.

- **Días con mayor presión:** El 4 de marzo de 2026 registró el mayor volumen de validaciones del período analizado (21,8 mil en un solo día), con una demanda diaria que supera los 25.000 usuarios en varios días de la semana, poniendo en evidencia la necesidad de reforzar la oferta en días hábiles.

- **Brecha sistémica, no puntual:** La comparación entre validaciones y capacidad diaria muestra que el desajuste no es un evento aislado, sino una condición estructural del servicio en este tramo de la Troncal J.

<div align="center">

<img src="https://img.shields.io/badge/Herramienta-Dashboard-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Enfoque-Optimización-darkred?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Impacto-Movilidad+Sostenible-orange?style=for-the-badge"/>

</div>

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=20&pause=1000&color=FF4C4C&center=true&vCenter=true&width=900&lines=Datos+que+explican+la+ciudad;Movilidad+basada+en+evidencia;Optimizar+es+entender" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0000&height=140&section=footer&animation=twinkling" width="100%"/>

</div>
