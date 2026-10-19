# Práctica: Orquestar un workflow de Abastecimiento con Microsoft 365 Copilot

**Duración:** 105 min

## Descripción
Los participantes integrarán Microsoft 365 Copilot en un flujo de trabajo de Abastecimiento de principio a fin (*end-to-end*), conectando los entregables de las prácticas previas sobre los tres casos del banco (Biometría Facial, IA Generativa y Contact Center). Utilizarán Copilot Chat para consolidar la estrategia; Word para el informe formal de sourcing; Excel (en modo Edición) para el modelo financiero de TCO; PowerPoint para el comité ejecutivo; y Outlook para la comunicación y notificación formal a la alta dirección. Finalmente, resolverán un reto independiente para orquestar la transferencia completa del expediente a la mesa de Operaciones y Contratación.

## Pasos para ejecutar la práctica

1. **Consolidación de inteligencia y estrategia en Copilot Chat:**
   * Abre **Microsoft 365 Copilot Chat**.
   * Envía la siguiente instrucción para integrar en un único máster de conocimiento los hallazgos de las etapas previas (market scan, RFI/RFP, TCO, TPRM y negociación):
     ```text
     Actúa como un Director Global de Abastecimiento Estratégico Bancario.
     
     Sintetiza en un Cuadro de Mando de Orquestación de Sourcing la información clave de los 3 proyectos del Banco:
     - Biometría Facial: 40M clientes, 1B transacciones, SLA 99.9999% y modelo de bolsa de transacciones.
     - IA Generativa: Consumo de 70B a 100B tokens/año, techo de costo (Price Cap) a 5 años y cláusulas anti lock-in.
     - Contact Center: 300M llamadas/año, absorción del incremento del 23% en SMMLV e IPC del 6% condicionada a metas del 5% de automatización anual.
     
     Estructura la salida en las secciones:
     1. Trazabilidad del Proceso (Sourcing -> Negociación).
     2. Balance Económico y Ahorro Aportado al Banco (USD).
     3. Matriz Integrada de Riesgos y Mitigantes.
     ```

2. **Formalización del Informe Consolidado de Sourcing en Microsoft Word:**
   * Abre **Microsoft Word** en un documento en blanco y actívalo en modo **Edición**.
   * Activa **Copilot en Word**, copia y vincula la síntesis generada en el Paso 1 y envía la siguiente orden:
     ```text
     Redacta el 'Informe Ejecutivo de Orquestación de Abastecimiento Bancario' integrando las siguientes secciones formales:
     1. Resumen Ejecutivo y Decisión de Adjudicación.
     2. Matriz Comparativa del Proceso (Market Scan, RFP, TCO y Negociación).
     3. Modelo de Gobernanza, SLAs y Cláusulas Contractuales Definitivas.
     4. Matriz de Mitigación de Riesgos de Terceros (TPRM).
     ```
   * Guarda el archivo con el nombre exacto: `Informe_Orquestacion_Abastecimiento_Bancario.docx`.

3. **Auditoría del Modelo Financiero y Sensibilidad de TCO en Microsoft Excel (Modo Edición):**
   * Abre **Microsoft Excel** en un libro nuevo guardado como `Cuadro_Mando_Financiero_TCO.xlsx`.
   * Selecciona la **Hoja 1**, renómbrala como `TCO_Final` y activa **Copilot en Excel** (modo **Edición**).
   * Envía el siguiente prompt para estructurar la tabla consolidada de impacto financiero:
     ```text
     Diseña una tabla llamada Tabla_TCO_Final que consolide el TCO a 5 años de los 3 proyectos (Biometría, IA y Contact Center).
     
     Columnas requeridas: Proyecto, TCO_Inicial_Propuesto_USD, Ahorro_Logrado_Negociacion_USD, TCO_Final_Ajustado_USD, Pct_Ahorro y Estado_Aprobacion.
     
     Puebla 3 filas con los datos negociados, agrega una fila de TOTALES calculada automáticamente y aplica un formato condicional resaltando en verde las celdas donde Pct_Ahorro sea mayor al 8%.
     ```

4. **Elaboración de la Presentación Ejecutiva en Microsoft PowerPoint:**
   * Abre **Microsoft PowerPoint** en una presentación en blanco.
   * Activa **Copilot en PowerPoint**, adjunta el documento `Informe_Orquestacion_Abastecimiento_Bancario.docx` y envía el siguiente prompt:
     ```text
     Crea una presentación de 4 diapositivas para el Comité Directivo de Compras basada en el documento adjunto:
     - Diapositiva 1: Resumen de la Decisión de Adjudicación y Estrategia End-to-End.
     - Diapositiva 2: Resultados Financieros y Eficiencias de TCO (USD).
     - Diapositiva 3: Matriz de Gobernanza y Control de Riesgos TPRM.
     - Diapositiva 4: Hoja de Ruta de Implementación y Transición.
     ```
   * Guarda la presentación con el nombre exacto: `Presentacion_Ejecutiva_Orquestacion.pptx`.

5. **Notificación Estratégica y Seguimiento Ejecutivo en Microsoft Outlook:**
   * Abre **Microsoft Outlook** y crea un nuevo correo.
   * Activa **Copilot en Outlook** (Borrador con Copilot) y solicita:
     ```text
     Actúa como el Category Manager Lead de Abastecimiento.
     
     Redacta un correo ejecutivo dirigido a la Vicepresidencia Ejecutiva notificando la finalización exitosa del workflow de Abastecimiento de Biometría, IA y Contact Center.
     
     Cuerpo del mensaje:
     1. Resumen general de adjudicación e hitos del proceso.
     2. Inserción del cuadro con la tabla de ahorros negociados en TCO Final (USD).
     3. Destacar la mitigación de los riesgos macroeconómicos (SMMLV/IPC) y de ciberseguridad.
     4. Solicitud formal de aprobación de la resolución de adjudicación y próximos pasos para la firma del contrato.
     ```

6. **EL RETO: Orquestación del Paquete de Transferencia Operativa y Contratación (Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas operativas que se presentan a continuación.
   * Utiliza la evidencia construida a lo largo de todos los artefactos (`Informe_Orquestacion_Abastecimiento_Bancario.docx`, `Cuadro_Mando_Financiero_TCO.xlsx` y `Presentacion_Ejecutiva_Orquestacion.pptx`) para resolver el reto de orquestación final en **Copilot Chat**:

   > **DESAFÍO DEL RETO:**
   > Como Category Manager Lead, debes utilizar Copilot Chat para estructurar el **Handover Pack** (Dossier de Empalme Operativo) que se entregará al equipo de Gestión de Contratos y a las áreas usuarias para asegurar que los acuerdos de Biometría, IA y Contact Center se ejecuten sin desviaciones.
   >
   > **Pistas para construir tu prompt en Copilot Chat:**
   > - *Pista 1 (Ficha de Empalme Contratación):* Pide a Copilot Chat consolidar una matriz en tabla Markdown que vincule cada proyecto con: Nombre del Proveedor Adjudicado, Valor Total del Contrato (TCO Ajustado), SLA No Negociable y Cláusula de Salida/Penalización.
   > - *Pista 2 (Protocolo de Control Cambiario y Escalabilidad):* Solicita a Copilot Chat definir el procedimiento exacto para auditar trimestralmente el consumo de tokens en IA Generativa y las revisiones por IPC/SMMLV en Contact Center, indicando alertas tempranas de sobrecosto.
   > - *Pista 3 (Comunicación de Transición para Proveedores no Adjudicados):* Pide a Copilot Chat redactar una plantilla formal de carta de agradecimiento y retroalimentación (Debriefing Letter) para los proveedores que no resultaron seleccionados en la RFP, manteniendo la relación comercial transparente del Banco.

   * Guarda o exporta el dossier de transferencia consolidado.

## Resultado esperado
Un informe integral en Word `Informe_Orquestacion_Abastecimiento_Bancario.docx`, un cuadro de mando en Excel `Cuadro_Mando_Financiero_TCO.xlsx`, una presentación en PowerPoint `Presentacion_Ejecutiva_Orquestacion.pptx`, el borrador formal de notificación en Outlook, y la resolución del reto: el **Handover Pack** completo de transferencia operativa estructurado desde Copilot Chat.
