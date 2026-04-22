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

<table>
<tr><th>Tipo</th><th>Variable</th><th>Descripción</th></tr>
<tr><td><b>Principal</b></td><td>Validaciones</td><td>Ingreso de pasajeros</td></tr>
<tr><td><b>Principal</b></td><td>Flujo horario</td><td>Usuarios por hora</td></tr>
<tr><td><b>Principal</b></td><td>Frecuencia</td><td>Buses FJ23</td></tr>
<tr><td><b>Complementario</b></td><td>Carril único</td><td>Impacto operativo</td></tr>
<tr><td><b>Complementario</b></td><td>Regularidad</td><td>Consistencia</td></tr>
<tr><td><b>Complementario</b></td><td>Factores externos</td><td>Condiciones externas</td></tr>
</table>

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
<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=420&lines=Procedimientos" />
</div>

Los datos se obtienen desde **Datos Abiertos Bogotá** y los canales oficiales de **TransMilenio**, siguiendo una metodología de tres etapas:

```mermaid
flowchart TD
    A[Recolección] --> B[Limpieza]
    B --> C[Análisis]
    C --> D[Propuestas]
```

<<div align="center">
<table>
<tr><th>Etapa</th><th>Acción</th><th>Resultado</th></tr>
<tr><td><b>1. Recolección</b></td><td>Fuentes existentes de Datos Abiertos Bogotá y TransMilenio</td><td>Datos por estación</td></tr>
<tr><td><b>2. Limpieza</b></td><td>Depuración de datos incompletos</td><td>Datos organizados</td></tr>
<tr><td><b>3. Agrupación</b></td><td>Clasificación por horas pico y horas valle</td><td>Patrones de demanda</td></tr>
<tr><td><b>4. Indicador</b></td><td>Validaciones vs frecuencia de la ruta FJ23</td><td>Brecha oferta-demanda</td></tr>
<tr><td><b>5. Diagnóstico</b></td><td>Identificación de franjas críticas</td><td>Momentos de congestión</td></tr>
</table>
</div>

> *La capacidad de transporte = frecuencia de buses × capacidad por bus. Si capacidad < validaciones → congestión identificada.*

---

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Montserrat&size=28&pause=1000&color=8B0000&center=true&vCenter=true&width=350&lines=Producto" />
</div>

El entregable final es un **tablero de visualización interactivo** que permite:

<div align="center">
<table>
<tr><th>Funcionalidad</th><th>Descripción</th></tr>
<tr><td>Validaciones por día</td><td>Patrones de uso semanal por estación</td></tr>
<tr><td>Filtro por hora</td><td>Demanda específica por franja horaria</td></tr>
<tr><td>Oferta vs Demanda</td><td>Comparació SI/NO de cobertura del sistema</td></tr>
<tr><td>Escenarios comparativos</td><td>Simulación de rutas nuevas o mayor frecuencia</td></tr>
</table>
</div>

```mermaid
flowchart LR
    A[Dashboard] --> B[Validaciones por dia]
    A --> C[Análisis por hora]
    A --> D[Brecha oferta-demanda]
    A --> E[Escenarios comparativos]
    E --> F[Mayor frecuencia FJ23]
    E --> G[Nueva ruta complementaria]
```

<div align="center">
<img src="https://img.shields.io/badge/Herramienta-Dashboard-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Enfoque-Optimización-darkred?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Impacto-Movilidad+Sostenible-orange?style=for-the-badge"/>
</div>

<br/>

> *El producto no solo muestra el problema — evalúa las soluciones.*

---
