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

**Documento de Visión**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# **ÍNDICE GENERAL**

1. [INTRODUCCIÓN](#1-introducción)  
   1.1 [Propósito (Diagrama 4+1)](#11-propósito-diagrama-41)  
   1.2 [Alcance](#12-alcance)  
   1.3 [Definición, siglas y abreviaturas](#13-definición-siglas-y-abreviaturas)  
   1.4 [Organización del documento](#14-organización-del-documento)  

2. [OBJETIVOS Y RESTRICCIONES ARQUITECTÓNICAS](#2-objetivos-y-restricciones-arquitectónicas)  
   2.1 [Priorización de requerimientos](#21-priorización-de-requerimientos)  
   2.1.1 [Requerimientos Funcionales](#211-requerimientos-funcionales)  
   2.1.2 [Requerimientos No Funcionales – Atributos de Calidad](#212-requerimientos-no-funcionales--atributos-de-calidad)  

3. [REPRESENTACIÓN DE LA ARQUITECTURA DEL SISTEMA](#3-representación-de-la-arquitectura-del-sistema)  
   3.1 [Vista de Caso de Uso](#31-vista-de-caso-de-uso)  
   3.1.1 [Diagramas de Casos de Uso](#311-diagramas-de-casos-de-uso)  

   3.2 [Vista Lógica](#32-vista-lógica)  
   3.2.1 [Diagrama de Subsistemas (Paquetes)](#321-diagrama-de-subsistemas-paquetes)  
   3.2.2 [Diagrama de Secuencia](#322-diagrama-de-secuencia)  
   3.2.3 [Diagrama de Colaboración](#323-diagrama-de-colaboración)  
   3.2.4 [Diagrama de Objetos](#324-diagrama-de-objetos)  
   3.2.5 [Diagrama de Clases](#325-diagrama-de-clases)  
   3.2.6 [Diagrama de Base de Datos](#326-diagrama-de-base-de-datos)  

   3.3 [Vista de Implementación](#33-vista-de-implementación)  
   3.3.1 [Diagrama de Arquitectura Software](#331-diagrama-de-arquitectura-software)  
   3.3.2 [Diagrama de Componentes](#332-diagrama-de-componentes)  

   3.4 [Vista de Procesos](#34-vista-de-procesos)  
   3.4.1 [Diagrama de Procesos del Sistema](#341-diagrama-de-procesos-del-sistema)  

   3.5 [Vista de Despliegue](#35-vista-de-despliegue)  
   3.5.1 [Diagrama de Despliegue](#351-diagrama-de-despliegue)  

4. [ATRIBUTOS DE CALIDAD DEL SOFTWARE](#4-atributos-de-calidad-del-software)  
   4.1 [Escenario de Funcionalidad](#41-escenario-de-funcionalidad)  
   4.2 [Escenario de Usabilidad](#42-escenario-de-usabilidad)  
   4.3 [Escenario de Confiabilidad](#43-escenario-de-confiabilidad)  
   4.4 [Escenario de Rendimiento](#44-escenario-de-rendimiento)  
   4.5 [Escenario de Mantenibilidad](#45-escenario-de-mantenibilidad)  
   4.6 [Otros Escenarios](#46-otros-escenarios)  

   <div style="page-break-after: always; visibility: hidden">\pagebreak</div>
# **ÍNDICE GENERAL**

1. INTRODUCCIÓN  
2. OBJETIVOS Y RESTRICCIONES ARQUITECTÓNICAS  
3. REPRESENTACIÓN DE LA ARQUITECTURA DEL SISTEMA  
4. ATRIBUTOS DE CALIDAD DEL SOFTWARE  

---

# **1. INTRODUCCIÓN**

## **1.1 Propósito (Modelo 4+1)**

El propósito del presente documento es describir la arquitectura del sistema Dashboard de análisis electoral y evaluación de planes de gobierno – Perú 2021, utilizando el modelo de vistas arquitectónicas 4+1. Este enfoque permite representar el sistema desde diferentes perspectivas, considerando la vista de casos de uso, vista lógica, vista de implementación, vista de procesos y vista de despliegue.
La arquitectura propuesta tiene como finalidad organizar los componentes principales del sistema, definir la relación entre sus módulos y establecer una base técnica que permita su desarrollo e implementación mediante herramientas de inteligencia de negocios como Power BI. El sistema está orientado a centralizar información electoral, visualizar resultados, comparar candidatos, analizar propuestas de gobierno y generar reportes visuales.


---

## **1.2 Alcance**

El documento de arquitectura comprende la representación estructural y funcional del sistema Dashboard de análisis electoral. Se incluyen las principales vistas arquitectónicas necesarias para comprender cómo se organiza el sistema, cómo interactúan sus componentes y cómo se despliega para su uso.
El alcance considera los siguientes elementos:
- Vista de casos de uso del sistema.
- 	Vista lógica mediante paquetes, clases, objetos y secuencia.
- 	Vista de implementación mediante arquitectura de software y componentes.
- 	Vista de procesos mediante diagramas de actividad.
- 	Vista de despliegue físico del sistema.
Atributos de calidad como funcionalidad, usabilidad, confiabilidad, rendimiento y mantenibilidad.
El sistema será desarrollado con fines académicos y estará orientado al análisis de datos electorales de las Elecciones Generales Perú 2021, sin integración en tiempo real con sistemas oficiales ni manejo de datos sensibles. 


---

## **1.3 Definiciones**

- **Dashboard**  : Herramienta visual que permite presentar datos mediante gráficos, indicadores y filtros interactivos.                            
- **BI**              : Business Intelligence o Inteligencia de Negocios, conjunto de procesos y herramientas para analizar datos.                       
- **Power BI**       : Herramienta de visualización de datos utilizada para construir dashboards interactivos.                                          
- **ONPE**           : Oficina Nacional de Procesos Electorales, fuente oficial de información electoral en el Perú.                                   
- **RF**             : Requerimiento funcional del sistema.                                                                                             
- **RNF**            : Requerimiento no funcional del sistema.                                                                                          
- **UML**            : Lenguaje Unificado de Modelado utilizado para representar diagramas de software.                                             
- **Vista 4+1**      : Modelo arquitectónico que organiza el sistema en diferentes vistas: lógica, procesos, implementación, despliegue y casos de uso. 
- **Indicador**      : Métrica utilizada para representar resultados electorales o evaluación de propuestas.                                            
- **Reporte visual** :  Salida gráfica generada a partir de la información analizada en el dashboard.
 

---

## **1.4 Organización**

El presente documento se encuentra organizado de la siguiente manera:
- En el Capítulo 1, se presenta la introducción del documento, el propósito de la arquitectura, el alcance, las definiciones y la organización general.
- 	En el Capítulo 2, se describen los objetivos y restricciones arquitectónicas, considerando los requerimientos funcionales y no funcionales del sistema.
- 	En el Capítulo 3, se desarrolla la representación de la arquitectura del sistema mediante las vistas del modelo 4+1, incluyendo vista de casos de uso, vista lógica, vista de implementación, vista de procesos y vista de despliegue.

- 	En el Capítulo 4, se describen los atributos de calidad del software, considerando funcionalidad, usabilidad, confiabilidad, rendimiento y mantenibilidad.


---

# **2. OBJETIVOS Y RESTRICCIONES ARQUITECTÓNICAS**

## **2.1 Requerimientos Funcionales**

| Código | Descripción | Prioridad |
|------|------------|----------|
| RF01 | Visualizar resultados | Alta |
| RF02 | Filtrar datos | Alta |
| RF03 | Consultar planes | Alta |
| RF04 | Clasificar propuestas | Alta |
| RF05 | Comparar candidatos | Alta |
| RF06 | Generar indicadores | Alta |
| RF07 | Interacción dashboard | Alta |
| RF08 | Evaluar propuestas | Media |
| RF09 | Generar reportes | Media |

---

## **2.2 Requerimientos No Funcionales**

| Código | Descripción | Prioridad |
|------|------------|----------|
| RNF01 | Usabilidad | Alta |
| RNF02 | Rendimiento | Alta |
| RNF03 | Disponibilidad | Alta |
| RNF04 | Compatibilidad | Media |
| RNF05 | Seguridad | Alta |
| RNF06 | Escalabilidad | Media |
| RNF07 | Mantenibilidad | Media |

---

# **3. ARQUITECTURA DEL SISTEMA**

## **3.1 Vista de Casos de Uso**

<p align="center">
  <img src="./media/casos de usos.png" width="500"/>
</p>

<p align="center"><em>Figura 1. Diagrama de casos de uso</em></p>

---

## **3.2 Vista Lógica**

3.2.	Vista Lógica
La vista lógica representa la estructura interna del sistema, enfocándose en los elementos que permiten cumplir con los requerimientos funcionales. Esta vista incluye la organización en paquetes, clases, objetos y la interacción entre ellos.
El sistema se organiza en módulos principales como:
- Gestión de datos (resultados electorales y planes de gobierno)
- 	Análisis electoral
- 	Evaluación de propuestas
- 	Visualización (dashboard)
-	Generación de reportes
Estos módulos permiten estructurar el sistema de manera clara, facilitando su desarrollo, mantenimiento y escalabilidad.
### **3.2.1 Diagrama de subsistemas**

<p align="center">
  <img src="./media/diagrama.png" width="500"/>
</p>

<p align="center"><em>Figura 2. Diagrama de subsistemas</em></p>

### **3.2.2 Diagrama de secuencia**

<p align="center">
  <img src="./media/secuencia.png" width="500"/>
</p>

<p align="center"><em>Figura 3. Diagrama de secuencia</em></p>

### **3.2.3 Diagrama de clases**

<p align="center">
  <img src="./media/Clases.png" width="500"/>
</p>

<p align="center"><em>Figura 4. Diagrama de Clases</em></p>

### **3.2.4 Diagrama de Base de datos**

<p align="center">
  <img src="./media/Bases.png" width="500"/>
</p>

<p align="center"><em>Figura 5. Diagrama de Base de datos</em></p>

---

## **3.3 Vista de Implementación**

La vista de implementación describe cómo se organiza el sistema a nivel de componentes de software, módulos y herramientas tecnológicas utilizadas para construir el dashboard. En este proyecto, la arquitectura se basa en un flujo de datos donde la información electoral y los planes de gobierno son recopilados, limpiados, estructurados y posteriormente visualizados mediante Power BI.
El sistema no contempla una aplicación web compleja con backend transaccional, sino una arquitectura orientada a inteligencia de negocios, donde los datos son procesados y transformados para alimentar visualizaciones interactivas.

### **3.3.1 Diagrama de  arquitectira  software (paquetes)** 

El diagrama de arquitectura software organiza el sistema en cuatro capas principales. La capa de datos contiene los datasets electorales, planes de gobierno y fuentes oficiales. La capa de procesamiento se encarga de limpiar, transformar y clasificar la información. La capa de análisis genera indicadores electorales, métricas de comparación y evaluación de propuestas. Finalmente, la capa de visualización presenta la información mediante dashboards interactivos, gráficos y reportes visuales en Power BI.

<p align="center">
  <img src="./media/paquetessoft.png" width="500"/>
</p>

<p align="center"><em>Figura 6. Diagrama de paquetes</em></p>

### **3.3.1 Diagrama de  arquitectira  software (componenetes)**
El diagrama de componentes representa la arquitectura del sistema a nivel de implementación, mostrando los elementos principales que intervienen en el funcionamiento del dashboard. El usuario interactúa directamente con el componente Power BI Dashboard, el cual permite visualizar la información mediante gráficos interactivos y reportes.
El dashboard se conecta con el Modelo de Datos, donde se estructuran los datos previamente procesados. Este modelo es alimentado por el componente Procesamiento ETL, encargado de la extracción, transformación y carga de datos provenientes de diferentes fuentes.
Las principales fuentes de datos incluyen información electoral de la ONPE, planes de gobierno de los candidatos y archivos estructurados como Excel o CSV. Esta arquitectura permite integrar múltiples fuentes, procesarlas y presentarlas de forma clara y organizada en el dashboard.

<p align="center">
  <img src="./media/componenetes.png" width="500"/>
</p>

<p align="center"><em>Figura 7. Diagrama de componentes</em></p>


---

## **3.4 Vista de Procesos**

La vista de procesos describe cómo el sistema se comporta dinámicamente, mostrando el flujo de actividades y la interacción entre los distintos procesos que permiten el funcionamiento del dashboard. En este sistema, los procesos están orientados principalmente al análisis de datos, desde la carga de información hasta su visualización y generación de reportes.

El sistema no maneja procesos concurrentes complejos, sino un flujo secuencial de procesamiento de datos y visualización, propio de una arquitectura de inteligencia de negocios. Sin embargo, sí existe interacción entre procesos como la carga de datos, el análisis, la aplicación de filtros y la generación de reportes.

## **3.4.1.	Diagrama de Procesos del sistema (diagrama de actividad)**

El diagrama de procesos del sistema representa el flujo general de funcionamiento del dashboard de análisis electoral. El proceso inicia con la obtención de datos desde fuentes oficiales, seguido del procesamiento de la información mediante técnicas de limpieza y transformación (ETL).
Posteriormente, el sistema permite realizar dos tipos principales de análisis: el análisis electoral, donde se cargan resultados y se generan indicadores, y el análisis de propuestas, donde se clasifican las propuestas y se evalúa su impacto y viabilidad. Una vez procesada la información, el sistema presenta los datos mediante un dashboard interactivo.
El usuario puede aplicar filtros para segmentar la información, lo que genera una actualización dinámica de las visualizaciones. Finalmente, el sistema permite generar reportes visuales que pueden ser exportados para su uso posterior.

<p align="center">
  <img src="./media/diagramaact.png" width="500"/>
</p>

<p align="center"><em>Figura 8. Diagrama de actividades</em></p>
---

## **3.5 Vista de Despliegue**

La vista de despliegue representa la distribución física del sistema y muestra los nodos donde se ejecutan sus componentes. En el caso del Dashboard de análisis electoral y evaluación de planes de gobierno – Perú 2021, el sistema se despliega en un entorno web, permitiendo que el usuario acceda al dashboard desde un navegador mediante conexión a internet.
El sistema utiliza fuentes de datos estructuradas, procesamiento de información y visualización mediante Power BI, por lo que su despliegue se apoya en equipos de desarrollo, almacenamiento de datos y un servicio web o cloud para publicación del dashboard.

### **3.5.1.	Diagrama de despliegue**

El diagrama de despliegue muestra la distribución física del sistema. El equipo de desarrollo utiliza Power BI Desktop, archivos Excel/CSV y herramientas de limpieza de datos como Python o Excel para preparar la información electoral y los planes de gobierno. Estos datos son organizados en un repositorio de datos compuesto por el dataset electoral y la información de planes de gobierno.
Posteriormente, el dashboard es construido en Power BI Desktop y publicado en un servicio web o entorno cloud, como Power BI Service. Finalmente, el usuario final accede al dashboard publicado desde un navegador web con conexión a internet, visualizando reportes e indicadores interactivos.

<p align="center">
  <img src="./media/despliegue.png" width="500"/>
</p>

<p align="center"><em>Figura 9. Diagrama de despliegue</em></p>

---

# **4. ATRIBUTOS DE CALIDAD**

##  **4.1.	Escenario de Funcionalidad**

La funcionalidad del sistema se evalúa en base a las capacidades que ofrece el dashboard para cumplir con los requerimientos definidos. El sistema permite visualizar resultados electorales, filtrar información, consultar planes de gobierno, comparar candidatos, generar indicadores y elaborar reportes visuales. Estas funciones garantizan que el sistema cumpla con su propósito principal de facilitar el análisis de información electoral.
Desde el punto de vista de calidad, la funcionalidad está relacionada con la correcta ejecución de las operaciones del sistema, asegurando que los datos sean procesados y representados adecuadamente. Asimismo, se garantiza la integridad de la información, ya que los datos provienen de fuentes oficiales y no son modificados por el usuario final.
---
## **4.2.	Escenario de Usabilidad (RNF01)**

La usabilidad del sistema se refiere a la facilidad con la que los usuarios pueden aprender a utilizar el dashboard y comprender la información presentada. En este caso, el sistema está diseñado con una interfaz intuitiva basada en gráficos interactivos, filtros dinámicos y visualizaciones claras.
El usuario puede navegar fácilmente entre las diferentes secciones del dashboard, aplicar filtros y analizar los resultados sin necesidad de conocimientos técnicos avanzados. Además, el sistema minimiza errores mediante una interacción guiada y presenta la información de manera comprensible, lo que mejora la experiencia del usuario, generando confianza y satisfacción.
---
## **4.3.	Escenario de Confiabilidad (RNF05, RNF03)**

La confiabilidad del sistema se basa en la capacidad de proporcionar información precisa, consistente y disponible en todo momento. El sistema utiliza datos provenientes de fuentes oficiales, lo que garantiza la integridad de la información.

Asimismo, el sistema está disponible a través de un entorno web, permitiendo su acceso continuo por parte de los usuarios. Al no manejar datos sensibles, se reduce el riesgo de fallas relacionadas con la seguridad. La confiabilidad también implica que el sistema responda correctamente ante errores, mostrando mensajes adecuados en caso de datos incompletos o no disponibles.
---
## **4.4.	 Escenario de Rendimiento (RNF02)**

El rendimiento del sistema se evalúa en función del tiempo de respuesta y la eficiencia en el procesamiento de datos. El dashboard debe ser capaz de cargar información, aplicar filtros y actualizar visualizaciones en un tiempo menor a 5 segundos.
El uso de herramientas de inteligencia de negocios como Power BI permite optimizar el procesamiento de grandes volúmenes de datos, garantizando una respuesta rápida y eficiente. Esto asegura una experiencia fluida para el usuario, evitando retrasos en la interacción con el sistema.

--- 
## **4.5.	Escenario de Mantenibilidad (RNF07)**

La mantenibilidad del sistema se refiere a la facilidad con la que puede ser modificado, actualizado o mejorado sin afectar su funcionamiento. El sistema permite la actualización de datasets, la modificación de indicadores y la incorporación de nuevas visualizaciones sin necesidad de rediseñar toda la estructura.
Esto facilita su evolución en el tiempo, permitiendo adaptar el dashboard a nuevos procesos electorales, cambios en la información o mejoras en el análisis de datos. La arquitectura modular del sistema contribuye a que estas modificaciones sean realizadas de manera eficiente.
---
## **4.6.	Otros Escenarios (RNF06 – Escalabilidad, RNF04 – Compatibilidad)**

El sistema presenta atributos adicionales como escalabilidad y compatibilidad. La escalabilidad permite incorporar nuevos datos electorales, nuevos candidatos o nuevas variables de análisis sin afectar el rendimiento del sistema.
Por otro lado, la compatibilidad garantiza que el sistema funcione correctamente en navegadores modernos como Chrome, Edge y Firefox, permitiendo el acceso desde diferentes dispositivos con conexión a internet.
En conjunto, estos atributos aseguran que el sistema sea adaptable, accesible y capaz de evolucionar según nuevas necesidades.
