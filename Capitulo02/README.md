# Práctica: Investigar mercado, proveedores y modelos de contratación con Copilot

**Duración:** 105 min

## Descripción
Los participantes utilizarán Microsoft 365 Copilot para realizar un market scan y benchmark a partir de los casos de biometría facial y contratación de servicios de IA. Construirán prompts estructurados para investigar el mercado, identificar proveedores relevantes, recopilar información pública, comparar modelos operativos y de contratación, reconocer drivers de costo, tendencias y riesgos de terceros, organizando los hallazgos en una matriz con fuentes. Se utilizará Copilot para generar preguntas de profundización, resumir diferencias entre competidores y preparar entregables ejecutivos en Word, Excel y la infografía final. El ejercicio enfatiza el uso riguroso de fuentes, la trazabilidad, la separación entre hechos e inferencias y la validación profesional.

## Pasos para ejecutar la práctica

1. **Investigación de mercado y mapeo de proveedores (Market Scan):**
   * Abre Microsoft 365 Copilot Chat.
   * Envía el siguiente prompt para estructurar la investigación inicial de proveedores y modelos de servicio para Biometría Facial e IA Generativa:
     ```text
     Actúa como un Especialista en Intelligence & Market Research de Abastecimiento Bancario.
     
     Realiza un estudio de mercado (Market Scan) enfocado en dos categorías críticas para el sector financiero:
     1. Biometría Facial masiva (mínimo 5 proveedores globales/regionales representativos).
     2. Servicios y plataformas de IA Generativa empresarial (mínimo 4 modelos/proveedores Cloud/LLM).
     
     Para cada categoría detalla:
     - Principales jugadores del mercado y modelo operativo/arquitectura habitual.
     - Esquemas de contratación estándar (suscripción, licencias por volumen, consumo por token/transacción).
     - Drivers de costo invisibles o variables de escalamiento financiero.
     - Tendencias de adopción e innovaciones recientes.
     
     Exige separar explícitamente HECHOS DOCUMENTADOS de INFERENCIAS O ESTIMACIONES DEL MERCADO.
     ```

2. **Comparación de modelos operativos y esquemas de licenciamiento:**
   * En el mismo chat, profundiza en las estructuras contractuales enviando:
     ```text
     Con base en el Market Scan previo, realiza una comparación detallada entre los modelos operativos identificados:
     
     - En Biometría Facial: Compara modelos On-Premise vs Cloud/SaaS frente a latencia, almacenamiento de plantillas biométricas y soberanía de datos.
     - En IA Generativa: Compara consumo por Tokens (Pay-as-you-go) vs Capacidad Reservada (Provisioned Throughput) vs Licenciamiento por Usuario.
     
     Identifica para cada modelo los riesgos de dependencia tecnológica (lock-in), cláusulas de salida y el impacto en el Total Cost of Ownership (TCO) a 3 y 5 años.
     ```

3. **Matriz de benchmark y análisis de TCO/Riesgos en Microsoft Excel:**
   * Abre **Microsoft Excel** y crea un libro nuevo guardado como `Benchmark_Mercado_Proveedores.xlsx`.
   * En Copilot en Excel (modo **Edición**), envía la siguiente orden utilizando los hallazgos del paso previo:
     ```text
     Estructura una Matriz de Benchmark de Proveedores con las columnas: Categoria, Proveedor_Servicio, Modelo_Contratacion, Drivers_Costo, Nivel_Riesgo_Terceros (Alto/Medio/Bajo), Ventajas_Operativas, Desventajas_Contractuales y Fuentes_Referencia.
     
     Genera 8 filas con los datos de biometría e IA generativa analizados. Aplica formato condicional para resaltar las celdas donde el Nivel_Riesgo_Terceros sea "Alto".
     ```

4. **Cuestionamiento de proveedores y preguntas de profundización RFI:**
   * En Copilot Chat, adjunta o vincula el análisis del libro `Benchmark_Mercado_Proveedores.xlsx` y envía:
     ```text
     Con base en la matriz de benchmark, genera un cuestionario técnico y comercial de RFI (Request for Information) de 6 preguntas estratégicas por categoría (Biometría e IA).
     
     Las preguntas deben estar diseñadas para obligar al proveedor a revelar:
     1. Costos ocultos por latencia, soporte o consumo no planificado.
     2. Mecanismos de portabilidad, salida y mitigación de lock-in.
     3. Evidencia de certificaciones de seguridad (ISO 27001, SOC 2 Type II) y soberanía de datos.
     ```

5. **Consolidación del Brief Ejecutivo de Sourcing en Microsoft Word:**
   * Abre **Microsoft Word** y activa Copilot en el documento.
   * Solicita la integración del brief ejecutando el siguiente prompt:
     ```text
     Redacta un Brief Ejecutivo de Inteligencia de Mercado para la Mesa de Sourcing utilizando los resultados de la investigación, el análisis de modelos operativos y el cuestionario RFI.
     
     Estructura el documento en:
     1. Contexto y Dinámica del Mercado de Biometría e IA.
     2. Análisis Comparativo de Modelos Operativos y Drivers de Costo (TCO).
     3. Matriz de Preguntas de Profundización RFI.
     4. Recomendaciones de Abastecimiento y Criterios de Validación Humana.
     ```
   * Guarda el archivo con el nombre exacto: `Brief_Ejecutivo_Sourcing_Mercado.docx`.

6. **EL RETO: Generación de Infografía Ejecutiva de Sourcing (Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas estratégicas que se presentan a continuación.
   * Utiliza Copilot Chat (aprovechando sus capacidades de estructuración visual, artefactos y generación/sugerencia de imágenes) para crear una **Infografía Ejecutiva de Sourcing** basada en la evidencia compilada en `Brief_Ejecutivo_Sourcing_Mercado.docx`:

   > **DESAFÍO DEL RETO:**
   > Genera una Infografía Ejecutiva completa de Sourcing estructurada en 3 secciones visuales sintéticas para presentar al Comité Directivo de Compras, consolidando el panorama competitivo, la estructura de costos/TCO y la matriz de riesgos con sus preguntas RFI clave.
   >
   > **Pistas para construir tu prompt e infografía con Copilot:**
   > - *Pista Sección 1 (Panorama y Competencia):* Pide a Copilot organizar en la infografía una síntesis visual del Market Scan utilizando bloques, íconos conceptuales o esquemas para comparar la alta concentración de mercado en Biometría vs la fragmentación y dinamismo de IA. Solícita la generación de un elemento visual/imagen representativo del ecosistema de arquitectura cloud y biometría.
   > - *Pista Sección 2 (Estructura de Costos y TCO):* Solicita a Copilot diagramar los drivers de costo ocultos (tokens no planificados, latencia, soporte) y comparar gráficamente el TCO a 3 y 5 años (consumo por demanda vs capacidad reservada).
   > - *Pista Sección 3 (Matriz de Riesgos y RFI):* Pide a Copilot estructurar con códigos de color visuales (Verde/Amarillo/Rojo) los niveles de riesgo por dependencia tecnológica (lock-in) y destacar las 3 preguntas indispensables que cada proveedor debe responder en el RFI antes de avanzar a la licitación (RFP).

   * Exporta o guarda el resultado de la infografía generada.

## Resultado esperado
Un libro en Excel `Benchmark_Mercado_Proveedores.xlsx`, un documento en Word `Brief_Ejecutivo_Sourcing_Mercado.docx` con las preguntas de RFI y la resolución del reto: la **Infografía Ejecutiva de Sourcing** estructurada y generada con Copilot.
