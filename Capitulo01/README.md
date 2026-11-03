# Práctica: Mapear el proceso de Abastecimiento e identificar oportunidades de uso de Copilot

**Duración:** 90 min

## Descripción
Los participantes utilizarán Microsoft 365 Copilot para recorrer los tres casos reales del banco (Biometría Facial, Contratación de IA y Contact Center) y mapear, desde la perspectiva del flujo de Abastecimiento, qué actividades pueden apoyarse con IA. Proporcionarán a Copilot el contexto operativo para construir prompts estructurados que identifiquen variables, supuestos, información faltante, preguntas de aclaración y tareas clave en el ciclo de compras. Finalmente, resolverán un reto práctico donde, orientados por pistas estratégicas, utilizarán su criterio profesional y Copilot para balancear trade-offs financieros, contractuales y de riesgo de terceros, consolidando el informe ejecutivo en Word.

## Pasos para ejecutar la práctica

1. **Autogeneración del expediente base de los 3 casos:**
   * Abre Microsoft 365 Copilot Chat.
   * Copia, pega y envía el siguiente prompt para autogenerar la ficha técnica de los tres proyectos de la entidad:
     ```text
     Actúa como un Gerente de Abastecimiento Estratégico Bancario.
     
     Genera la Ficha Técnica de Contexto Operativo para Abastecimiento basada en los siguientes tres proyectos reales de la entidad:
     
     1. Proyecto Biometría Facial: 30 millones de clientes actuales, 40 millones proyectados, 1 billón de transacciones estimadas, disponibilidad SLA requerida de 99.9999% y un mercado de 10 compañías proveedoras.
     2. Proyecto Contratación de IA Generativa: Volumen de 70 a 100 billones de tokens/año con un horizonte de contratación de 5 años.
     3. Proyecto Contact Center: Volumen de 300 millones de llamadas/año, proyectado bajo variables de IPC del 6% y ajuste de SMMLV del 23%.
     
     Estructura la respuesta indicando para cada proyecto: Objetivo de Abastecimiento, Complejidad Operativa, Impacto Financiero y Nivel de Criterio Humano Requerido.
     ```

2. **Identificación de variables, supuestos y preguntas de aclaración:**
   * En el mismo chat, envía la siguiente instrucción para cuestionar el requerimiento del negocio y detectar vacíos de información:
     ```text
     Con base en la Ficha Técnica autogenerada, analiza cada proyecto e identifica:
     1. Variables críticas de abastecimiento e indicadores clave.
     2. Supuestos financieros y técnicos que deben validarse con la banca de inversión/tecnología.
     3. Información faltante y preguntas de aclaración urgentes que el equipo de Abastecimiento debe formular al área requirente antes de salir al mercado.
     ```

3. **Mapeo del ciclo de compras y matriz de oportunidades de IA:**
   * En el mismo chat, envía el siguiente prompt para estructurar el uso de Copilot a lo largo del flujo de compras (Sourcing, Evaluación Técnica, Análisis Económico/TCO, Riesgo TPRM, Negociación y Control Contratación):
     ```text
     Con base en la información analizada, mapea las oportunidades de uso de Copilot en las 6 etapas del flujo de Abastecimiento, considerando referentes públicos de transformación bancaria (como Deutsche Bank en TPRM y Hellenic Bank con GEP).
     
     Genera el resultado en una Matriz de Oportunidades de IA en Abastecimiento Financiero formateada en tabla Markdown (.md) con las columnas: Etapa_Flujo, Proyecto_Aplicable, Tarea_Clave, Riesgo_Asociado, Pregunta_Aclaracion_Negocio y Oportunidad_Copilot.
     ```

4. **Consolidación del expediente base y exportación a Word:**
   * En el mismo chat, solicita a Copilot consolidar el avance de la sesión:
     ```text
     Consolida la Ficha Técnica de los 3 casos, el cuestionamiento de requerimientos y la Matriz de Oportunidades de IA en un informe estructurado.
     ```
   * Al finalizar la respuesta de Copilot, selecciona **Exportar a Word** y guarda el archivo con el nombre exacto: `Mapa_Oportunidades_IA_Abastecimiento.docx`.

5. **EL RETO: Resolución de Trade-Offs Estratégicos y Negociación (Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas estratégicas proporcionadas a continuación.
   * Abre Microsoft Word, activa Copilot en el documento `Mapa_Oportunidades_IA_Abastecimiento.docx` (o utiliza Copilot Chat adjuntando el documento) y redacta tu propio prompt para resolver los 3 escenarios del reto, aplicando tu criterio especializado de Abastecimiento:

   > **DESAFÍO DEL RETO:**
   > Como Category Manager Senior, debes estructurar la posición de negociación y las cláusulas de protección para los 3 proyectos críticos antes de la reunión de aprobación con la Vicepresidencia.
   >
   > **Pistas para construir tu prompt en Copilot:**
   > - *Pista Biometría (SLA y Concentración):* Pide a Copilot que compare el costo de infraestructura/penalización entre un SLA de 99.9999% vs 99.99% para 1 billón de transacciones. Solicita opciones para negociar con un oligopolio de 10 proveedores (ej. contratos multiproveedor, esquemas de bolsa de horas o benchmarking de precios).
   > - *Pista IA Generativa (Consumo y Lock-in):* Pide a Copilot diseñar un modelo de precios por escalones de volumen (tiering) para 70-100 billones de tokens/año a 5 años, e incluir cláusulas de desacoplamiento de API y portabilidad de prompts para evitar depender de un solo LLM.
   > - *Pista Contact Center (Indexación e Impacto SMMLV):* Pide a Copilot formular una estructura de revisión tarifaria que absorba el IPC del 6% y el SMMLV del 23% para 300 millones de llamadas, condicionando el reajuste a metas de automatización del 5% anual en atención Nivel 1.

   * Genera las soluciones con Copilot, valida el resultado con tu criterio profesional e incorpóralo como la sección final del documento guardándolo como: `Informe_Estrategico_Abastecimiento_Bancario.docx`.

## Resultado esperado
Un documento ejecutivo guardado como `Informe_Estrategico_Abastecimiento_Bancario.docx` que contiene la ficha técnica de los 3 proyectos, el mapeo de oportunidades de IA en el ciclo de compras y la solución propia del estudiante para el reto estratégico de negociación y estructuración contractual.
