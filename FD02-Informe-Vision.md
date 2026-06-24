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


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Visión</u>**

1. <span id="_Toc52661346" class="anchor"></span>

## 1. INTRODUCCIÓN

En la actualidad, el acceso a la información política es fundamental para la toma de decisiones informadas por parte de los ciudadanos. Sin embargo, en el Perú, la información relacionada con los candidatos presidenciales y sus planes de gobierno suele encontrarse dispersa en múltiples fuentes, lo que dificulta su análisis, comparación y comprensión.
En este contexto, surge la necesidad de implementar soluciones tecnológicas que permitan organizar, visualizar y analizar esta información de manera clara y accesible. El presente documento propone el desarrollo de un dashboard interactivo orientado al análisis de candidatos presidenciales y la evaluación de sus planes de gobierno en el marco de las Elecciones Generales del Perú 2026.
A lo largo de este documento se describen los objetivos, alcance, usuarios, características y beneficios del sistema, con el fin de establecer una visión clara del proyecto y su impacto en el análisis de información política.


### 1.1 Propósito

El propósito de este documento es definir una visión clara y estructurada del sistema “Dashboard de análisis de candidatos presidenciales y evaluación de planes de gobierno-Perú 2026”, estableciendo sus objetivos, funcionalidades, alcance y beneficios esperados.
Asimismo, busca servir como guía para el desarrollo del sistema, permitiendo que todos los involucrados tengan una comprensión común del proyecto y sus alcances.

### 1.2 Alcance

El sistema contempla el desarrollo de un dashboard interactivo que permitirá a los usuarios analizar el perfil de los candidatos presidenciales y comparar sus planes de gobierno.
El sistema incluirá funcionalidades como:

	Visualización del perfil de candidatos (datos personales, características socioeconómicas y trayectoria)
- Clasificación de propuestas por dimensiones (social, económica, institucional y territorial-ambiental)
- 	Comparación de propuestas por temas como salud, educación, seguridad y economía
- 	Uso de filtros dinámicos para analizar información por candidato, partido o dimensión
- 	Visualización de indicadores que permitan identificar prioridades y enfoques de los planes de gobierno

No se contempla la integración con sistemas oficiales en tiempo real ni el uso de datos sensibles, ya que el proyecto se desarrolla en un entorno académico.


### 1.3 Definiciones, Siglas y Abreviaturas

- Dashboard: Herramienta visual que permite representar datos mediante gráficos e indicadores
- BI: Business Intelligence (Inteligencia de Negocios)
- ONPE: Oficina Nacional de Procesos Electorales
- Dataset: Conjunto de datos organizados para su análisis

### 1.4 Referencias

El presente documento se basa en el informe de factibilidad desarrollado previamente, así como en información proveniente de fuentes oficiales como la ONPE y portales de datos abiertos relacionados con las Elecciones Generales del Perú 2026.

### 1.5 Visión General

El sistema propuesto es una herramienta digital orientada a mejorar el acceso y comprensión de la información política en el Perú.
Su finalidad es proporcionar una plataforma que permita analizar el perfil de los candidatos presidenciales y comparar sus planes de gobierno de manera clara, estructurada y visual.
A través de esta solución, se busca transformar información compleja en conocimiento accesible, facilitando el análisis de propuestas políticas, promoviendo la transparencia y contribuyendo a una toma de decisiones informada.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>
## 2. POSICIONAMIENTO

### 2.1 Oportunidad de negocio

El crecimiento del uso de herramientas digitales y plataformas de análisis de datos representa una oportunidad significativa para el desarrollo de soluciones orientadas al análisis político. En el Perú, los planes de gobierno contienen información valiosa, pero no siempre se presentan de forma clara, integrada y fácil de comparar.
En este contexto, existe una oportunidad para desarrollar un dashboard que permita centralizar, organizar y visualizar las propuestas de los candidatos, facilitando su análisis comparativo.
Asimismo, el proyecto se alinea con la creciente demanda de herramientas de Business Intelligence (BI), que permiten transformar datos en información útil para la toma de decisiones. Esto no solo aporta valor académico, sino que también tiene potencial aplicación en ámbitos educativos, institucionales y de análisis político.


### 2.2 Definición del problema

Actualmente, la información relacionada con los candidatos presidenciales y sus planes de gobierno en el Perú se encuentra distribuida en diversas fuentes, lo que dificulta su acceso, análisis y comparación.

Los planes de gobierno suelen ser documentos extensos, técnicos y poco estandarizados, lo que limita su interpretación y la comparación directa entre candidatos. Además, no existe una herramienta que integre el perfil de los candidatos con el análisis estructurado de sus propuestas.

Esta situación genera una brecha en la capacidad de los ciudadanos, estudiantes y analistas para comprender de manera integral las prioridades, enfoques y estrategias de los partidos políticos.

Por ello, se propone el desarrollo de un dashboard interactivo que permita centralizar la información, organizar las propuestas y facilitar su análisis comparativo mediante visualizaciones claras y herramientas dinámicas de exploración.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>
## 3. DESCRIPCIÓN DE LOS INTERESADOS Y USUARIOS

### 3.1 Resumen de los interesados

Los principales interesados en el sistema de dashboard de análisis electoral incluyen a estudiantes, docentes, analistas de datos y ciudadanos interesados en comprender los procesos electorales.

Asimismo, el equipo desarrollador constituye un interesado clave, ya que es responsable de la implementación, mantenimiento y mejora del sistema. Las instituciones educativas también se consideran interesadas, debido a que pueden utilizar el sistema como herramienta de aprendizaje en cursos relacionados con análisis de datos y ciencias sociales.

### 3.2 Resumen de los usuarios

Los usuarios del sistema están conformados principalmente por estudiantes, ciudadanos y analistas que desean visualizar información electoral de manera clara y estructurada.

Asimismo, se consideran usuarios técnicos como los desarrolladores y analistas de datos, quienes interactúan con el sistema para actualizar información, mejorar visualizaciones y asegurar el correcto funcionamiento del dashboard.

### 3.3 Entorno de usuario

El sistema será utilizado en un entorno web, accesible desde computadoras personales o dispositivos móviles con conexión a internet.

El dashboard contará con una interfaz amigable e intuitiva, permitiendo a los usuarios interactuar con gráficos, filtros y reportes sin necesidad de conocimientos técnicos avanzados. Esto facilita su uso tanto en contextos académicos como personales.

### 3.4 Perfiles de los interesados

Los interesados del sistema incluyen principalmente al equipo desarrollador, encargado del diseño e implementación del dashboard, y a las instituciones educativas, que pueden utilizar el sistema como herramienta de apoyo académico.

Asimismo, se consideran interesados los analistas de datos y docentes, quienes buscan herramientas que faciliten la interpretación de información electoral y la enseñanza de conceptos relacionados con análisis de datos.

### 3.5 Perfiles de los usuarios

Los usuarios del sistema se dividen en dos grupos principales:

- Usuarios generales: ciudadanos y estudiantes interesados en analizar resultados electorales y comparar propuestas de candidatos.
- Usuarios técnicos: desarrolladores y analistas de datos que gestionan la información, actualizan el sistema y mejoran las visualizaciones.

Cada grupo tiene diferentes niveles de conocimiento técnico, por lo que el sistema debe ser accesible y fácil de usar.

### 3.6 Necesidades de los interesados y usuarios

Las principales necesidades identificadas son:

- Acceso a información electoral organizada y confiable  
- Visualización clara de resultados y propuestas  
- Comparación de candidatos por sectores (salud, educación, economía, etc.)  
- Herramientas interactivas para análisis de datos  
- Facilidad de uso sin requerir conocimientos técnicos avanzados  
- Acceso desde cualquier dispositivo con conexión a internet  

Estas necesidades justifican el desarrollo del dashboard como una solución que facilita el análisis y comprensión de la información electoral.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>
## 4. VISTA GENERAL DEL PRODUCTO

### 4.1 Perspectiva del producto

El sistema Dashboard de análisis electoral se presenta como una solución tecnológica orientada a la visualización y análisis de datos electorales del Perú.

El producto no reemplaza sistemas existentes, sino que complementa la información disponible en fuentes oficiales, integrándola en un entorno visual interactivo que facilita su comprensión.

El sistema permitirá centralizar datos electorales y planes de gobierno, transformándolos en gráficos, indicadores y reportes que apoyan el análisis y la toma de decisiones.

### 4.2 Resumen de capacidades

El sistema contará con las siguientes capacidades principales:

- Visualización de resultados electorales mediante gráficos dinámicos  
- Comparación de candidatos y sus propuestas de gobierno  
- Clasificación de propuestas por sectores (educación, salud, economía, etc.)  
- Análisis de impacto y viabilidad de propuestas  
- Generación de reportes visuales  
- Interacción mediante filtros y segmentación de datos  

Estas capacidades permitirán transformar datos complejos en información clara y útil para el usuario.

### 4.3 Suposiciones y dependencias

El sistema asume que los usuarios cuentan con acceso a internet y dispositivos capaces de visualizar dashboards.

Asimismo, depende de la disponibilidad de información electoral proveniente de fuentes oficiales o datasets previamente recopilados.

El correcto funcionamiento del sistema también depende del uso adecuado de herramientas de análisis de datos y de la calidad de la información utilizada.

### 4.4 Costos y precios

El sistema no contempla costos para los usuarios finales, ya que se desarrolla en un entorno académico con fines educativos.

Los costos asociados corresponden al desarrollo, implementación y mantenimiento del sistema, los cuales han sido detallados en el informe de factibilidad.

El acceso al dashboard será gratuito, permitiendo su uso por parte de estudiantes, docentes y ciudadanos interesados.

### 4.5 Licenciamiento e instalación

El sistema será implementado como una plataforma digital accesible mediante navegador web, sin necesidad de instalación por parte del usuario final.

El acceso se realizará a través de un enlace público, permitiendo visualizar el dashboard desde cualquier dispositivo con conexión a internet.

Las herramientas utilizadas para su desarrollo serán de uso libre o educativo, garantizando la viabilidad del sistema en el entorno académico.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661350" class="anchor"></span>
## 5. CARACTERÍSTICAS DEL PRODUCTO
El sistema Dashboard de análisis electoral contará con las siguientes características principales:

- Visualización de resultados electorales mediante gráficos interactivos  
- Comparación de candidatos presidenciales  
- Análisis de propuestas de gobierno por sectores (educación, salud, economía, etc.)  
- Uso de filtros y segmentación de datos para personalizar el análisis  
- Generación de reportes visuales  
- Interfaz intuitiva y fácil de usar  

Estas características permiten transformar la información electoral en una herramienta accesible para el análisis y la toma de decisiones.
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661351" class="anchor"></span>
## 6. RESTRICCIONES
El sistema presenta las siguientes restricciones:

- Dependencia de conexión a internet para su uso  
- Uso de datos previamente recopilados (no en tiempo real)  
- Limitación a herramientas gratuitas o académicas  
- Acceso mediante navegador web (no aplicación móvil)  
- Dependencia de la calidad de los datos utilizados  

Estas restricciones se deben principalmente al enfoque académico del proyecto.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

7. <span id="_Toc52661352" class="anchor"></span>
## 7. RANGOS DE CALIDAD
El sistema debe cumplir con los siguientes criterios de calidad:

- Usabilidad: interfaz intuitiva y fácil de navegar  
- Rendimiento: carga rápida de dashboards  
- Disponibilidad: acceso continuo mediante web  
- Confiabilidad: datos consistentes y bien estructurados  
- Seguridad: uso de datos públicos sin comprometer información sensible  

Estos criterios aseguran una experiencia adecuada para el usuario.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

8. <span id="_Toc52661353" class="anchor"></span>
## 8. PRECEDENCIA Y PRIORIDAD
Las funcionalidades del sistema se priorizan de la siguiente manera:

Prioridad alta:
- Visualización de resultados electorales  
- Comparación de candidatos  

Prioridad media:
- Análisis de propuestas por sector  
- Filtros interactivos  

Prioridad baja:
- Generación de reportes avanzados  
- Mejoras visuales adicionales  

Esta priorización permite asegurar una implementación progresiva del sistema.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

9. <span id="_Toc52661354" class="anchor"></span>
## 9. OTROS REQUERIMIENTOS DEL PRODUCTO
El sistema deberá cumplir con los siguientes requerimientos adicionales:

- Compatibilidad con navegadores web modernos  
- Diseño responsivo para diferentes dispositivos  
- Uso de buenas prácticas de desarrollo  
- Escalabilidad para futuras mejoras  
- Facilidad de mantenimiento  

Asimismo, se deberán considerar los siguientes estándares:

a) Estándares legales: uso de datos públicos y cumplimiento de normativas  
b) Estándares de comunicación: claridad en la presentación de la información  
c) Estándares de plataforma: compatibilidad con herramientas de BI  
d) Estándares de calidad y seguridad: integridad y confiabilidad de los datos  
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

10. <span id="_Toc52661355" class="anchor"></span>
## 10. CONCLUSIONES
El sistema Dashboard de análisis electoral es una solución viable que permite mejorar el acceso y análisis de la información electoral.

El proyecto cumple con los requerimientos técnicos y funcionales necesarios para su implementación en un entorno académico, proporcionando una herramienta útil para estudiantes, analistas y ciudadanos.

Asimismo, el sistema contribuye a la transparencia informativa y facilita la toma de decisiones mediante el uso de visualizaciones de datos.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

11. <span id="_Toc52661356" class="anchor"></span>
## 11. RECOMENDACIONES
Se recomienda continuar con el desarrollo del sistema priorizando las funcionalidades principales del dashboard.

Asimismo, se sugiere mejorar progresivamente las visualizaciones e incorporar nuevas fuentes de datos para enriquecer el análisis.

También se recomienda validar el sistema mediante pruebas con usuarios para optimizar la experiencia de uso.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

12. <span id="_Toc52661357" class="anchor"></span>

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>
