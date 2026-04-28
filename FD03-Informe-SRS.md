<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *“Dashboard de análisis electoral y evaluación de planes de gobierno - Perú 2021” ***

Curso: *Inteligencia de Negocios *

Docente: *Mag. Patrick Jose Cuadros Quiroga*

Integrantes:


***Chura Ticona, Mary Luz        (2019065163)***
***Diego Chara Apaza			 (2019065026)***

**Tacna – Perú**

***2026***

**  
**
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|












**Sistema *{Nombre del Sistema}***

**Documento de SRS**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>



---

## INTRODUCCIÓN

El presente documento describe la especificación de requerimientos del sistema *Dashboard de análisis electoral y evaluación de planes de gobierno – Perú 2021*. Este documento establece las funcionalidades, restricciones y características del sistema, con el propósito de servir como base para su diseño e implementación.

El sistema busca facilitar el análisis de información electoral mediante herramientas de visualización de datos, permitiendo a los usuarios interpretar resultados y comparar propuestas de manera clara y eficiente.

---

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## I. GENERALIDADES DE LA EMPRESA

### 1. Nombre de la Empresa
Proyecto académico desarrollado en la Universidad Privada de Tacna.

### 2. Visión
Desarrollar soluciones tecnológicas basadas en inteligencia de negocios que faciliten la toma de decisiones.

### 3. Misión
Diseñar e implementar un sistema de dashboard interactivo para el análisis electoral.

### 4. Organigrama

<p align="center">
  <img src="./img/organigrama.png" width="500"/>
</p>

<p align="center"><em>Figura 1. Organigrama del equipo del proyecto</em></p>



## II. VISIONAMIENTO DE LA EMPRESA

### 1. Descripción del Problema

La información electoral en el Perú se encuentra distribuida en múltiples fuentes, dificultando su análisis y comprensión. Los planes de gobierno son extensos y poco comparables, lo que limita la toma de decisiones informadas.



### 2. Objetivos de Negocios

- Facilitar el acceso a información electoral  
- Mejorar la toma de decisiones  
- Promover el análisis de datos  



### 3. Objetivos de Diseño

- Implementar dashboards interactivos  
- Diseñar una interfaz amigable  
- Permitir análisis dinámico de datos  



### 4. Alcance del Proyecto

El sistema permitirá visualizar resultados electorales, comparar candidatos y analizar propuestas mediante dashboards interactivos.


### 5. Viabilidad del Sistema

El sistema es viable debido al uso de herramientas como Power BI y datos públicos.



### 6. Información obtenida

- ONPE  
- Datos abiertos del Perú  



<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## III. ANÁLISIS DE PROCESOS

### a) Proceso Actual

El análisis electoral se realiza manualmente mediante documentos y reportes dispersos.

<p align="center">
  <img src="./img/proceso-actual.png" width="500"/>
</p>

<p align="center"><em>Figura 2. Proceso actual</em></p>

---

### b) Proceso Propuesto

El sistema automatiza el análisis mediante dashboards.

<p align="center">
  <img src="./img/proceso-propuesto.png" width="500"/>
</p>

<p align="center"><em>Figura 3. Proceso propuesto</em></p>

---

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## IV. ESPECIFICACIÓN DE REQUERIMIENTOS DE SOFTWARE

### a) Requerimientos Funcionales Inicial

| Código | Requerimiento | Descripción |
|------|-------------|------------|
| RF01 | Visualizar resultados | Mostrar resultados electorales |
| RF02 | Comparar candidatos | Comparación de candidatos |
| RF03 | Mostrar propuestas | Visualización de propuestas |
| RF04 | Filtrar información | Filtrado de datos |
| RF05 | Visualizar gráficos | Gráficos interactivos |

---

### b) Requerimientos No Funcionales

| Código | Requerimiento | Descripción |
|------|-------------|------------|
| RNF01 | Usabilidad | Interfaz amigable |
| RNF02 | Rendimiento | Carga rápida |
| RNF03 | Disponibilidad | 24/7 |
| RNF04 | Seguridad | Datos públicos |
| RNF05 | Compatibilidad | Navegadores |

---

### c) Requerimientos Funcionales Final

| Código | Requerimiento | Descripción |
|------|-------------|------------|
| RF01 | Dashboard general | Resumen electoral |
| RF02 | Comparación | Comparar candidatos |
| RF03 | Análisis sectorial | Propuestas por sector |
| RF04 | Filtros dinámicos | Interacción |
| RF05 | Reportes | Generación de reportes |

---

### d) Reglas de Negocio

- Uso de datos públicos  
- Cada candidato tiene múltiples propuestas  
- Cada propuesta pertenece a un sector  



<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## V. FASE DE DESARROLLO

### 1. Perfiles de Usuario

- Usuario general  
- Analista  
- Administrador  

---

### 2. Modelo Conceptual

<p align="center">
  <img src="./img/casos-uso.png" width="500"/>
</p>

<p align="center"><em>Figura 4. Diagrama de casos de uso</em></p>

---

### 3. Modelo Lógico

<p align="center">
  <img src="./img/clases.png" width="500"/>
</p>

<p align="center"><em>Figura 5. Diagrama de clases</em></p>

---

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## CONCLUSIONES

El sistema permite mejorar el análisis de información electoral mediante dashboards interactivos, facilitando la toma de decisiones.

---

## RECOMENDACIONES

Se recomienda continuar con el desarrollo del sistema y mejorar las visualizaciones.

---

## BIBLIOGRAFÍA

- ONPE  
- Datos abiertos Perú  

---

## WEBGRAFÍA

- https://www.onpe.gob.pe