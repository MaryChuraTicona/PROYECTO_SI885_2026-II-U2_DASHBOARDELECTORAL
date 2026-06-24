<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Dashboard de análisis electoral de candidatos presidenciales - Perú 2026***

Curso: *Inteligencia de Negocios*

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

Sistema *Dashboard de análisis electoral de candidatos presidenciales – Perú 2026*

Informe de Factibilidad

Versión *1.0*

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MCT, DCA|PCQ|PCQ|13/04/2026|Versión Original|

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# **INDICE GENERAL**

[1. Descripción del Proyecto](#_Toc52661346)

[2. Riesgos](#_Toc52661347)

[3. Análisis de la Situación actual](#_Toc52661348)

[4. Estudio de Factibilidad](#_Toc52661349)

[4.1 Factibilidad Técnica](#_Toc52661350)

[4.2 Factibilidad económica](#_Toc52661351)

[4.3 Factibilidad Operativa](#_Toc52661352)

[4.4 Factibilidad Legal](#_Toc52661353)

[4.5 Factibilidad Social](#_Toc52661354)

[4.6 Factibilidad Ambiental](#_Toc52661355)

[5. Análisis Financiero](#_Toc52661356)

[6. Conclusiones](#_Toc52661357)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Factibilidad</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Descripción del Proyecto**

### 1.1 Nombre del proyecto
Dashboard de análisis electoral de candidatos presidenciales – Perú 2026

### 1.2 Duración del proyecto

- Fecha de inicio: 13 de abril del 2026  
- Fecha de finalización: 13 de julio del 2026  
- Duración estimada: 3 meses  

### 1.3 Descripción

El presente proyecto consiste en el desarrollo de un dashboard interactivo para el análisis del perfil de los candidatos presidenciales en el contexto de las Elecciones Generales del Perú 2026. La solución integra información relevante de cada candidato, como datos personales, perfil socioeconómico, patrimonio declarado, antecedentes legales y presencia en redes sociales.

El sistema permite organizar y visualizar la información de manera dinámica, facilitando la exploración individual de cada candidato mediante filtros interactivos, así como la comparación entre candidatos según indicadores clave como ingresos, patrimonio, nivel de riesgo legal y actividad en campaña.

Las visualizaciones incluyen análisis demográfico (edad, género, nivel educativo), perfil económico (ingresos y bienes declarados ante la ONPE), clasificación de riesgo legal y penal, presencia en TikTok y cobertura de visitas de campaña por región.

El dashboard transforma información dispersa en múltiples fuentes oficiales en una herramienta visual clara, permitiendo analizar el perfil integral de cada candidato y favoreciendo una comprensión objetiva del panorama electoral.

El proyecto está orientado a estudiantes, ciudadanos y analistas interesados en el análisis electoral, proporcionando una plataforma que promueve la transparencia, el acceso a la información y la toma de decisiones informadas.

### 1.4 Objetivos

#### 1.4.1 Objetivo general

- Desarrollar un dashboard interactivo que permita analizar el perfil integral de los candidatos presidenciales del Perú para las Elecciones Generales 2026, mediante visualizaciones dinámicas e indicadores que faciliten la interpretación de su información socioeconómica, legal y de campaña.

#### 1.4.2 Objetivos Específicos

- Integrar información de los candidatos presidenciales incluyendo datos personales, perfil socioeconómico y trayectoria.
- Diseñar visualizaciones que permitan analizar individualmente a cada candidato mediante filtros dinámicos.
- Analizar los ingresos y patrimonio declarados por cada candidato ante la ONPE.
- Clasificar a los candidatos según su nivel de riesgo legal y penal mediante indicadores visuales.
- Evaluar la presencia digital de los candidatos en la red social TikTok.
- Analizar la cobertura geográfica de las visitas de campaña por candidato.
- Implementar herramientas de comparación entre candidatos según indicadores clave.
- Publicar el dashboard en un entorno accesible que permita su visualización e interacción.



<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Riesgos**

- Dificultad para encontrar información completa y ordenada sobre los candidatos presidenciales en fuentes oficiales.
- Posible inconsistencia entre las fuentes de información electoral consultadas (ONPE, JNE, medios digitales).
- Retrasos en la limpieza y estructuración de los datos en la base de datos Azure SQL.
- Errores en la clasificación del nivel de riesgo legal y penal de los candidatos.
- Limitaciones técnicas en el diseño e implementación del dashboard en Power BI.
- Falta de experiencia del equipo en herramientas de visualización de datos e inteligencia de negocios.
- Datos incompletos en tablas como historial de TikTok o visitas de campaña por candidato.
- Dificultad para establecer relaciones correctas entre tablas en el modelo de datos.
- Posibles problemas al publicar el dashboard en Power BI Service o repositorio público.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Análisis de la Situación actual**

    3.1. Planteamiento del problema

            En el Perú, la información relacionada con los candidatos presidenciales se encuentra distribuida en múltiples fuentes, como declaraciones juradas de la ONPE, portales institucionales y registros públicos. Esta dispersión dificulta el acceso, análisis y comprensión del perfil real de cada candidato por parte de los ciudadanos.

            En el contexto de las Elecciones Generales del Perú 2026, los datos sobre ingresos, patrimonio, antecedentes legales y actividad de campaña de los candidatos están disponibles de forma fragmentada y en formatos poco accesibles, lo que impide una evaluación comparativa clara entre los postulantes.

            Asimismo, no existe una herramienta integrada que permita visualizar de manera conjunta el perfil socioeconómico, legal y digital de los candidatos presidenciales, lo que limita la capacidad del ciudadano de evaluar objetivamente a quienes aspiran al cargo.

            Esta situación genera una brecha en la capacidad de los ciudadanos, estudiantes y analistas para interpretar de forma clara la información disponible sobre los candidatos, dificultando la toma de decisiones informadas.

            En este contexto, surge la necesidad de desarrollar un dashboard interactivo que permita integrar, organizar y visualizar el perfil de los candidatos presidenciales, facilitando su análisis comparativo mediante herramientas gráficas, filtros dinámicos e indicadores visuales basados en datos oficiales.

            De esta manera, el proyecto busca transformar información electoral compleja y dispersa en una plataforma accesible, clara y útil, contribuyendo a la transparencia informativa y al fortalecimiento de la cultura democrática en el Perú.




    3.2. Consideraciones de hardware y software

            Con respecto a los recursos tecnológicos requeridos para el desarrollo del proyecto de dashboard de análisis electoral, se consideran los siguientes componentes de hardware y software necesarios para la recopilación, procesamiento y visualización de datos.
                
<div align="center">
  <img src="./media/software.png" width="500"/>
</div>

<div align="center"><em>Figura: Herramientas de software utilizadas</em></div>
            


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**

    Describir los resultados que esperan alcanzar del estudio de factibilidad, las actividades que se realizaron para preparar la evaluación de factibilidad y por quien fue aprobado.

    4.1. <span id="_Toc52661350" class="anchor"></span>Factibilidad Técnica

        El proyecto de dashboard de análisis electoral es técnicamente viable, ya que se basa en el uso de herramientas ampliamente utilizadas en el análisis y visualización de datos, como Power BI, Microsoft Excel y lenguajes de programación como Python.

        Estas tecnologías permiten la recopilación, procesamiento y representación gráfica de grandes volúmenes de información electoral de manera eficiente, facilitando la construcción de dashboards interactivos que permiten comparar candidatos, resultados y propuestas de gobierno.

        Asimismo, el desarrollo del sistema se realizará de manera progresiva, iniciando con la recopilación y limpieza de datos provenientes de fuentes oficiales como la ONPE, seguido de la estructuración de la información y finalmente la implementación de dashboards interactivos. Este enfoque incremental permite reducir riesgos técnicos y asegurar la correcta construcción del sistema.

        Desde el punto de vista de infraestructura, el proyecto puede ser desplegado utilizando servicios en la nube como AWS o Azure, mediante el uso de herramientas de infraestructura como código como Terraform, lo que permite automatizar la configuración del entorno, optimizar recursos y reducir costos operativos.

        En cuanto al entorno tecnológico, el sistema es viable debido a que las herramientas utilizadas son accesibles, cuentan con documentación amplia y no requieren infraestructura compleja para su implementación. Además, los usuarios finales están familiarizados con el uso de dashboards y plataformas digitales, lo que facilita la adopción del sistema.

        Finalmente, el proyecto no requiere el desarrollo de aplicaciones móviles ni el uso de tecnologías complejas como geolocalización o notificaciones en tiempo real, lo que reduce significativamente la complejidad técnica y aumenta su viabilidad.


    4.2. <span id="_Toc52661351" class="anchor"></span>Factibilidad Económica

        El proyecto de dashboard de análisis electoral es técnicamente viable, ya que se basa en el uso de herramientas ampliamente utilizadas en el análisis y visualización de datos, como Power BI, Microsoft Excel y lenguajes de programación como Python.

    *

        Definir los siguientes costos:

        4.2.1. Costos Generales

    <div align="center">
    <img src="./media/Costos.png" width="500"/>
    </div>

    <div align="center"><em>Tabla 2: Costos generales</em></div>



        4.2.2. Costos operativos durante el desarrollo 
        
    <div align="center">
    <img src="./media/Operativos.png" width="500"/>
    </div>

    <div align="center"><em>Tabla 3: Costos operativos durante el desarrollo</em></div>

        4.2.3. Costos del ambiente

    <div align="center">
    <img src="./media/Ambiente.png" width="500"/>
    </div>

    <div align="center"><em>Tabla 4: Costos del ambiente</em></div>

        4.2.4. Costos de personal

      <div align="center">
    <img src="./media/Personal.png" width="500"/>
    </div>

    <div align="center"><em>Tabla 5: Costos de personal</em></div>


        4.2.5.  Costos totales del desarrollo del sistema
  <div align="center">
    <img src="./media/TOTATLES.png" width="500"/>
    </div>

    <div align="center"><em>Tabla 6: Costos totales del desarrollo del sistema</em></div>

    4.3. <span id="_Toc52661352" class="anchor"></span>Factibilidad Operativa

        La factibilidad operativa del proyecto de dashboard de análisis electoral es alta, debido a que los usuarios objetivo cuentan con conocimientos básicos en el uso de herramientas digitales, lo que facilita la adopción del sistema. Actualmente, la mayoría de personas está familiarizada con el uso de plataformas web, dashboards interactivos y visualización de datos, lo que permite que la implementación del sistema no requiera procesos complejos de adaptación.

        El sistema será diseñado considerando principios de usabilidad y accesibilidad, con el objetivo de que los usuarios puedan interactuar de manera sencilla e intuitiva con la información. A través de gráficos, indicadores y filtros dinámicos, el dashboard permitirá una navegación clara y eficiente, facilitando la comprensión de los resultados electorales y la comparación de propuestas de los candidatos.

        Asimismo, el proyecto presenta una alta adaptabilidad, ya que puede integrarse fácilmente con diferentes fuentes de datos, como información oficial de entidades públicas o datasets abiertos. Esta característica permite mantener el sistema actualizado y mejorar su funcionalidad a lo largo del tiempo sin necesidad de realizar cambios estructurales complejos.

        En cuanto al soporte y mantenimiento, el sistema requerirá actualizaciones periódicas para garantizar la calidad de la información, el correcto funcionamiento de los dashboards y la mejora continua de la experiencia del usuario. Estas actividades pueden ser gestionadas por el equipo de desarrollo sin requerir recursos adicionales significativos.

        Por otro lado, el proyecto contempla la posibilidad de incorporar mejoras continuas basadas en la retroalimentación de los usuarios, lo que permitirá optimizar el sistema y adaptarlo a nuevas necesidades. De esta manera, el dashboard no solo será funcional en su etapa inicial, sino que podrá evolucionar progresivamente.

        Finalmente, el desarrollo del sistema será realizado por un equipo de estudiantes con conocimientos en análisis de datos y desarrollo de software, quienes asumirán roles específicos en el diseño, implementación y documentación del proyecto. En conjunto, estos factores demuestran que el proyecto es operativamente viable, ya que puede ser implementado, utilizado y mantenido de manera eficiente en su entorno de aplicación.


    4.4. <span id="_Toc52661353" class="anchor"></span>Factibilidad Legal

        La factibilidad legal del proyecto de dashboard de análisis electoral es alta, ya que se basa en el uso de información pública proveniente de fuentes oficiales, como datos electorales y planes de gobierno publicados por entidades del Estado. Esto garantiza que la información utilizada no infringe derechos de propiedad privada ni normas de confidencialidad.

        Asimismo, el proyecto cumple con la normativa vigente en el Perú relacionada con la protección de datos personales, como la Ley N° 29733, Ley de Protección de Datos Personales. En este sentido, el sistema no recopila ni almacena datos sensibles de los usuarios, ya que su función principal es la visualización y análisis de información pública.

        En cuanto al desarrollo del software, se respetan las licencias de las herramientas utilizadas, tales como Power BI, Python, Visual Studio Code y otras tecnologías de uso libre o educativo. Esto asegura que el sistema sea desarrollado de manera legal y sostenible.

        Finalmente, el proyecto incluirá términos de uso y referencias a las fuentes de información empleadas, garantizando transparencia en el manejo de los datos y delimitando responsabilidades en el uso del sistema. Por lo tanto, el proyecto es legalmente viable.


    4.5. <span id="_Toc52661354" class="anchor"></span>Factibilidad Social 

        El proyecto presenta una alta viabilidad social, ya que responde a la necesidad de mejorar el acceso a la información electoral de manera clara, organizada y comprensible. En muchos casos, los ciudadanos no cuentan con herramientas que les permitan analizar y comparar de forma sencilla los planes de gobierno y propuestas de los candidatos presidenciales.

        La implementación de un dashboard de análisis electoral contribuye a fortalecer la transparencia informativa, permitiendo a los usuarios comprender mejor los resultados de las elecciones y las propuestas políticas. Esto favorece una toma de decisiones más informada y promueve una participación ciudadana más consciente.

        Asimismo, el proyecto tiene un impacto positivo en el ámbito educativo, ya que puede ser utilizado como herramienta de aprendizaje para estudiantes y personas interesadas en temas políticos, sociales y de análisis de datos.

        En este sentido, el sistema no solo beneficia a los usuarios individuales, sino que también aporta al desarrollo de una sociedad más informada y crítica, fortaleciendo los procesos democráticos. Por lo tanto, el proyecto es socialmente viable.*


    4.6. <span id="_Toc52661355" class="anchor"></span>Factibilidad Ambiental

        El proyecto es ambientalmente viable, ya que se basa en el uso de herramientas digitales que no requieren el uso de recursos físicos significativos. Al tratarse de un sistema de visualización de datos, se reduce el uso de papel y otros materiales tradicionales utilizados para la difusión de información, contribuyendo así a una gestión más sostenible.

        Asimismo, el sistema utiliza infraestructura tecnológica ya existente, como computadoras personales y servicios en la nube, lo que evita la necesidad de implementar nuevos recursos físicos que generen impacto ambiental adicional.

        En relación con el consumo energético, el proyecto se apoya en tecnologías eficientes y optimizadas, lo que minimiza el uso de energía en comparación con otros sistemas más complejos. Además, al centralizar la información en un solo entorno digital, se reduce la necesidad de desplazamientos físicos para acceder a información electoral.

        Por otro lado, el proyecto contribuye indirectamente a la educación digital y al uso responsable de la información, promoviendo prácticas sostenibles mediante el aprovechamiento de tecnologías modernas.

        En consecuencia, el proyecto no genera impactos negativos significativos en el medio ambiente y, por el contrario, contribuye a la reducción del uso de recursos físicos, por lo que es ambientalmente viable.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661356" class="anchor"></span>**Análisis Financiero**

    El proyecto de dashboard de análisis electoral se justifica económicamente debido a que permite optimizar el acceso, análisis y comprensión de la información electoral mediante el uso de herramientas tecnológicas de visualización de datos.

    Si bien el sistema no genera ingresos directos como un producto comercial, produce beneficios económicos indirectos, tales como la optimización del tiempo de análisis, la mejora en la toma de decisiones y el aprovechamiento eficiente de información pública. Además, puede ser utilizado como base para futuros desarrollos tecnológicos o aplicaciones de análisis de datos.

    La inversión inicial del proyecto corresponde al desarrollo del sistema, incluyendo recursos humanos, herramientas tecnológicas y costos operativos durante un periodo de tres meses. Posteriormente, el sistema entra en funcionamiento, generando beneficios mensuales estimados que permiten recuperar la inversión en el corto plazo.


    5.1. Justificación de la Inversión

        5.1.1. Beneficios del Proyecto

               - Beneficios tangibles: 
                    - Reducción del tiempo y costo en el análisis manual de información electoral
                    - Optimización en la organización y procesamiento de datos provenientes de fuentes oficiales
                    - Disminución de esfuerzos repetitivos en la elaboración de reportes
                    -  Mejora en la eficiencia del uso de recursos humanos mediante la automatización del análisis de datos
                    - Ahorro económico estimado de S/ 1,200 mensuales (S/ 14,400 anuales) basado en la reducción del 40% del tiempo de análisis, según estimaciones de productividad en automatización de datos
               - Beneficios intangibles:
                    - Mejora en el acceso a la información electoral de forma clara y estructurada
                    - Apoyo en la toma de decisiones informadas por parte de los usuarios
                    - Incremento en la transparencia y comprensión de los procesos electorales
                    -  Fortalecimiento del análisis académico y político mediante herramientas digitales
                    - Promoción del uso de tecnologías de visualización de datos en el análisis electoral. 

        
        5.1.2. Criterios de Inversión 

                Para evaluar la viabilidad económica del proyecto, se ha considerado un horizonte de evaluación de un año, tomando en cuenta la inversión inicial y los beneficios económicos generados durante la operación del sistema.   
 <div align="center">
    <img src="./media/TOTAL.png" width="500"/>
    
 </div>
    <div align="center"><em>Tabla 7: Viabilidad</em></div>


            5.1.2.1. Relación Beneficio/Costo (B/C)

                            B/C = 1.33
                
                La relación beneficio/costo obtenida es de 1.33, lo que indica que por cada sol invertido en el proyecto se obtiene un beneficio de S/ 1.33. Esto demuestra que los beneficios generados superan los costos de implementación y operación, haciendo el proyecto económicamente viable.

            5.1.2.2. Valor Actual Neto (VAN)
             
                          VAN = S/. 2,242.94
                El Valor Actual Neto del proyecto es de S/ 2,242.94, lo que indica que, considerando una tasa de descuento del 8%, el proyecto genera beneficios económicos adicionales después de recuperar la inversión inicial.

            5.1.2.3 Tasa Interna de Retorno (TIR)*

                            TIR = 0.046
                La Tasa Interna de Retorno obtenida es de 4.6%, la cual es menor a la tasa de descuento del 8%. Sin embargo, debido a que el proyecto presenta un VAN positivo y beneficios operativos, se considera viable en el contexto académico, ya que no tiene como objetivo principal la generación de rentabilidad financiera, sino el desarrollo de una solución tecnológica funcional.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661357" class="anchor"></span>**Conclusiones**

En conclusión, el proyecto de dashboard de análisis electoral de candidatos presidenciales – Perú 2026 es viable desde el punto de vista técnico, ya que se cuenta con herramientas accesibles y ampliamente utilizadas como Power BI, Excel y tecnologías de desarrollo que permiten implementar una solución eficiente, escalable y de fácil acceso para los usuarios.

Respecto a la factibilidad económica, el proyecto presenta resultados favorables, con un Valor Actual Neto (VAN) de S/ 2,242.94 y una relación beneficio/costo (B/C) de 1.33, lo que indica que la inversión es recuperable y que los beneficios generados superan los costos de implementación y operación. Si bien la Tasa Interna de Retorno (TIR) es de 4.6%, menor a la tasa de descuento del 8%, el proyecto sigue siendo viable en el contexto académico, ya que su objetivo principal no es la generación de rentabilidad financiera, sino el desarrollo de una solución tecnológica funcional y útil.
En cuanto a la factibilidad operativa, el sistema es viable debido a que los usuarios están familiarizados con el uso de herramientas digitales y dashboards, lo que facilita su implementación, uso y mantenimiento sin requerir procesos complejos de capacitación.
Desde el punto de vista legal, el proyecto cumple con la normativa vigente en el Perú, especialmente en lo relacionado con el uso de información pública y la protección de datos personales, garantizando un manejo adecuado y transparente de la información.
En relación con la factibilidad social, el sistema tiene un impacto positivo, ya que contribuye a mejorar el acceso a la información electoral, facilita la comparación de propuestas de los candidatos y promueve una toma de decisiones más informada por parte de los ciudadanos.
Finalmente, en cuanto a la factibilidad ambiental, el proyecto no genera impactos negativos significativos, ya que se basa en el uso de herramientas digitales que reducen el consumo de recursos físicos, promoviendo prácticas sostenibles mediante la gestión eficiente de la información.

En conjunto, los resultados obtenidos demuestran que el proyecto es viable desde un enfoque técnico, económico y social, siendo una propuesta recomendable para su desarrollo e implementación en el ámbito académico.


