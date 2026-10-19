# Práctica: Preparar y analizar una RFP/RFQ con Copilot

**Duración:** 105 min

## Descripción
Los participantes utilizarán Microsoft 365 Copilot para apoyar el ciclo completo de elaboración y evaluación de una RFP/RFQ para los casos emblemáticos del banco (Biometría Facial, Contratación de IA y Contact Center) sin sustituir el criterio profesional de Abastecimiento. A partir de los requerimientos de la entidad, los participantes usarán Copilot Chat para transformar datos operativos en criterios evaluables y construir el pliego de condiciones. Posteriormente, trabajarán con propuestas de proveedores autogeneradas para extraer alcance, drivers de costo, condiciones comerciales, SLA, escalabilidad, supuestos y vacíos de información. Utilizarán Copilot en Word, Excel y PowerPoint (incluyendo la generación de imágenes conceptuales) para normalizar las ofertas, estructurar una matriz comparativa y preparar la presentación de la Mesa de Evaluación. Finalmente, resolverán un reto independiente para construir una presentación ejecutiva de recomendación en un archivo PowerPoint completamente nuevo.

## Pasos para ejecutar la práctica

1. **Transformación de requerimientos y construcción del pliego RFP en Microsoft Word:**
   * Abre Microsoft 365 Copilot Chat y envía el siguiente prompt para estructurar la base de la RFP integrando los 3 casos:
     ```text
     Actúa como un Especialista en Sourcing Estratégico Bancario.
     
     Transforma los siguientes datos operativos en una Estructura de Requerimientos y Criterios Evaluables para una RFP/RFQ de Abastecimiento:
     - Biometría Facial: 30M a 40M de clientes, 1 billón de transacciones, SLA 99.9999% y proyección a 10 compañías.
     - Contratación de IA: Consumo de 70 a 100 billones de tokens/año a 5 años con modelos de cobro flexibilizados.
     - Contact Center: 300M llamadas/año, ajuste por IPC del 6% y SMMLV del 23%.
     
     Genera la estructura formal de la RFP en las siguientes secciones:
     1. Objeto y Alcance Técnico.
     2. Acuerdos de Nivel de Servicio (SLA) y Penalizaciones.
     3. Esquema Comercial y Reglas de Escalabilidad Financiera.
     4. Matriz de Preguntas Obligatorias para la Propuesta del Proveedor.
     ```
   * Abre **Microsoft Word** en un documento en blanco, activa **Copilot en Word**, copia o genera este contenido y guarda el archivo con el nombre exacto: `Pliego_RFP_Abastecimiento_Bancario.docx`.

2. **Autogeneración y normalización de propuestas competitivas de proveedores:**
   * Abre Microsoft 365 Copilot Chat, adjunta el archivo `Pliego_RFP_Abastecimiento_Bancario.docx` y envía la siguiente instrucción para autogenerar las ofertas de dos proveedores competidores:
     ```text
     Con base en el pliego adjunto Pliego_RFP_Abastecimiento_Bancario.docx, autogenera la respuesta sintética de dos proveedores ficticios para la RFP:
     
     - Proveedor Alfa (TechGlobal): Alta capacidad técnica, cumple SLA de 99.9999% en biometría, pero propone cobro rígido por usuario y ajustes anuales fijos del 10%.
     - Proveedor Beta (CloudInnovate): Esquema de cobro por token/transacción altamente escalable, absorbe 50% del impacto de SMMLV/IPC en Contact Center, pero exige exclusividad a 5 años y SLA de biometría en 99.99%.
     
     Estructura la respuesta comparando para cada uno: Alcance, Drivers de Costo, Condiciones Comercial/SLA, Supuestos Tecnológicos y Exclusiones/Faltantes.
     ```

3. **Construcción de la Matriz Comparativa y Normalización de Ofertas en Excel:**
   * Abre **Microsoft Excel** y crea un libro nuevo guardado como `Matriz_Evaluacion_Comparativa_RFP.xlsx`.
   * En Copilot en Excel (modo **Edición**), envía la siguiente orden utilizando los datos normalizados de los proveedores Alfa y Beta:
     ```text
     Estructura una Matriz de Evaluación Homologada de Ofertas con las columnas: Criterio_Evaluacion, Peso_Pct, Proveedor_Alfa_Oferta, Proveedor_Beta_Oferta, Puntuacion_Alfa (1-5), Puntuacion_Beta (1-5), Brecha_Identificada y Pregunta_Aclaracion_Ronda2.
     
     Puebla la matriz con 8 filas cubriendo aspectos técnicos, SLA, modelo económico e impacto de IPC/SMMLV. Aplica formato condicional para resaltar la puntuación más alta en cada criterio.
     ```

4. **Elaboración de la Presentación de Avance con Apoyo Visual en PowerPoint:**
   * Abre **Microsoft PowerPoint** y crea una presentación en blanco.
   * Activa **Copilot en PowerPoint**, adjunta el documento `Pliego_RFP_Abastecimiento_Bancario.docx` y envía el siguiente prompt:
     ```text
     Crea una presentación de 3 diapositivas para la Mesa de Evaluación de Abastecimiento basada en el pliego adjunto:
     - Diapositiva 1: Resumen de Requerimientos Críticos y Parámetros RFP.
     - Diapositiva 2: Comparativa de Ofertas (Proveedor Alfa vs Proveedor Beta).
     - Diapositiva 3: Preguntas de Aclaración para la Segunda Ronda de Negociación.
     ```
   * En la Diapositiva 1, utiliza Copilot en PowerPoint o Copilot Chat para generar o insertar una imagen conceptual solicitando:
     ```text
     Genera una imagen conceptual de estilo corporativo que represente la evaluación de infraestructura tecnológica bancaria, ciberseguridad biométrica y procesamiento masivo de datos.
     ```
   * Guarda esta presentación inicial con el nombre exacto: `Avance_Mesa_Evaluacion_RFP.pptx`.

5. **Consolidación del Informe Técnico en Word:**
   * Abre el archivo `Pliego_RFP_Abastecimiento_Bancario.docx` en **Microsoft Word**, activa **Copilot en Word** y adjunta el libro `Matriz_Evaluacion_Comparativa_RFP.xlsx`.
   * Envía la siguiente instrucción para integrar el dictamen técnico:
     ```text
     Con base en la matriz de evaluación del archivo adjunto Matriz_Evaluacion_Comparativa_RFP.xlsx, redacta e incorpora al final del documento la sección "Dictamen de Homologación de Ofertas y Hallazgos de RFP", detallando los riesgos comerciales, las exclusiones detectadas y las condiciones no negociables para la siguiente ronda.
     ```
   * Guarda los cambios en el archivo `Pliego_RFP_Abastecimiento_Bancario.docx`.

6. **EL RETO: Presentación Ejecutiva Final de Recomendación en PowerPoint (Nuevo Archivo - Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas estratégicas que se presentan a continuación.
   * Abre un **NUEVO archivo en blanco de Microsoft PowerPoint** (diferente al utilizado en el Paso 4) y guárdalo desde el inicio con el nombre exacto: `Dictamen_Final_Adjudicacion_RFP.pptx`.
   * Utiliza **Copilot en PowerPoint** (o apóyate en Copilot Chat) adjuntando el documento de Word actualizado `Pliego_RFP_Abastecimiento_Bancario.docx` y el libro `Matriz_Evaluacion_Comparativa_RFP.xlsx` para diseñar la presentación final de recomendación para la Vicepresidencia:

   > **DESAFÍO DEL RETO:**
   > Diseña una presentación ejecutiva totalmente nueva de 4 diapositivas orientada a la toma de decisiones del Comité de Compras, que justifique la selección del proveedor recomendado o la estrategia de negociación para la Ronda 2, balanceando los riesgos técnicos de Biometría, IA y Contact Center.
   >
   > **Pistas para construir tu prompt e infografía visual en el nuevo PowerPoint con Copilot:**
   > - *Pista Diapositiva 1 (Diagnóstico y Cuadro de Mando):* Solicita a Copilot generar una diapositiva ejecutiva con el resumen de la RFP y la puntuación ponderada global de los proveedores Alfa y Beta. Pide generar una imagen ilustrativa sobre analítica financiera y toma de decisiones en abastecimiento bancario.
   > - *Pista Diapositiva 2 (Análisis de Trade-Offs Financieros y SLAs):* Pide a Copilot estructurar una comparación visual de los impactos en costos: el riesgo de rígidez de tarifa por usuario de Alfa frente al riesgo de exclusividad y SLA de 99.99% en biometría de Beta.
   > - *Pista Diapositiva 3 (Absorción de Variables Macroeconómicas):* Solicita a Copilot diagramar cómo cada propuesta responde al ajuste de SMMLV (23%) e IPC (6%) en Contact Center y la escalabilidad por consumo de tokens en IA Generativa.
   > - *Pista Diapositiva 4 (Estrategia de Ronda 2 y Recomendación):* Pide a Copilot organizar en bloques visuales (Líneas Rojas, Concesiones Posibles y Preguntas de Cierre) la postura que el Banco debe asumir antes de la adjudicación final.

   * Guarda la presentación final en el nuevo archivo: `Dictamen_Final_Adjudicacion_RFP.pptx`.

## Resultado esperado
Un pliego complementado en Word `Pliego_RFP_Abastecimiento_Bancario.docx`, un libro en Excel `Matriz_Evaluacion_Comparativa_RFP.xlsx`, una presentación de avance `Avance_Mesa_Evaluacion_RFP.pptx` con imagen conceptual, y la resolución del reto: la presentación ejecutiva completamente nueva en PowerPoint `Dictamen_Final_Adjudicacion_RFP.pptx`.
