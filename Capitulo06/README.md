# Práctica: Preparar, simular y documentar una negociación con Copilot

**Duración:** 105 min

## Descripción
Los participantes utilizarán Microsoft 365 Copilot para preparar, ensayar y documentar el proceso completo de negociación con un proveedor estratégico. Integrando la evidencia de las prácticas previas sobre Biometría Facial, IA Generativa y Contact Center, utilizarán Copilot en Word y Copilot Chat  para estructurar la estrategia de negociación, configurar a Copilot como contraparte en un juego de roles interactivo y redactar los acuerdos finales. Posteriormente, utilizarán Microsoft Clipchamp con Copilot para transformar la estrategia en una cápsula en video. Finalmente, resolverán un reto técnico en Clipchamp para diseñar un video ejecutivo de cierre de negociación dirigido a la Vicepresidencia.

## Pasos para ejecutar la práctica

1. **Estructuración del Plan Estratégico de Negociación en Microsoft Word:**
   * Abre **Microsoft Word** en un documento en blanco y actívalo en modo **Edición**.
   * Activa **Copilot en Word** y envía el siguiente prompt para estructurar la matriz de preparación táctica integrando las variables críticas de los 3 casos:
     ```text
     Actúa como un Lead Negotiator de Abastecimiento Estratégico Bancario.
     
     Estructura la Planilla de Estrategia de Negociación para la mesa de discusión final con el proveedor tecnológico considerando:
     - Biometría Facial: Exigencia de SLA 99.9999% frente a flexibilización de penalidades y esquemas de bolsa de transacciones para 40M de clientes.
     - IA Generativa: Incertidumbre del consumo de 70B a 100B tokens/año a 5 años, cláusulas de techo de costo (Price Cap) y portabilidad de modelos.
     - Contact Center: Absorción del ajuste de SMMLV (23%) e IPC (6%) para 300M de llamadas a cambio de compromisos de automatización de Nivel 1.
     
     Organiza el documento en:
     1. Objetivos ZOPA (Zone of Possible Agreement) y BATNA (Best Alternative to a Negotiated Agreement).
     2. Matriz de Variables Negociables, Puntos de Intercambio y Concesiones.
     3. Argumentario y Matriz de Objeciones Anticipadas.
     ```
   * Guarda el archivo con el nombre exacto: `Plan_Estrategico_Negociacion_Bancaria.docx`.

2. **Simulación Interactiva de Negociación (Roleplay) en Copilot Chat:**
   * Abre **Microsoft 365 Copilot Chat** y adjunta el documento `Plan_Estrategico_Negociacion_Bancaria.docx`.
   * Envía la siguiente instrucción para activar el simulador de negociación:
     ```text
     Actúa como el Vicepresidente Comercial del Proveedor Tecnológico. Tu objetivo es maximizar tu margen operativo y evitar asumir riesgos de SMMLV/IPC o penalidades por SLA en biometría.

     Reglas del juego de roles:
     1. Simula la reunión de negociación conmigo (Category Manager del Banco) paso a paso.
     2. Presenta objeciones firmes sobre la exigencia de SLA 99.9999% en biometría y rechaza absorber el 23% de incremento de SMMLV en Contact Center.
     3. Haz una objeción/intervención a la vez y espera mi respuesta antes de continuar.
     4. Evalúa mi contraargumentación basada en el archivo adjunto Plan_Estrategico_Negociacion_Bancaria.docx y ofrece concesiones progresivas solo si mi posición de abastecimiento es sólida.
     ```
   * Realiza al menos 3 intercambios de negociación interactiva en el chat respondiendo a las objeciones planteadas por Copilot.

3. **Documentación del Memorando de Acuerdos (MoU) en Microsoft Word:**
   * Regresa al documento `Plan_Estrategico_Negociacion_Bancaria.docx` en **Microsoft Word**.
   * Activa **Copilot en Word** (modo **Edición**), copia y pega la transcripción del cierre de la simulación efectuada en el Paso 2 y envía la siguiente orden:
     ```text
     Con base en el resultado de la simulación de negociación realizada, redacta e incorpora al final del documento la sección 'Memorando de Entendimiento (MoU) y Minuta de Cierre'.
     
     Detalla los acuerdos alcanzados, los compromisos de las partes, los puntos pendientes para revisión jurídica y las cláusulas de reajuste de IPC/SMMLV y consumo de tokens acordadas.
     ```
   * Guarda los cambios en `Plan_Estrategico_Negociacion_Bancaria.docx`.

4. **Redacción de la Minuta de Cierre y Correo de Seguimiento:**
   * En **Copilot Chat**, adjunta el archivo actualizado `Plan_Estrategico_Negociacion_Bancaria.docx` y envía:
     ```text
     Con base en el MoU del archivo adjunto, redacta una comunicación ejecutiva de seguimiento para enviar por correo/Teams al Comité de Compras y al Proveedor.
     
     Incluye: Resumen de concesiones logradas por el Banco, ahorro estimado en USD frente a la propuesta inicial y próximos pasos para la firma del contrato.
     ```

5. **Creación de Video Resumen del Plan de Negociación con Copilot en Microsoft Clipchamp:**
   * Accede a Microsoft 365 y abre **Microsoft Clipchamp** (desde la web de Microsoft 365 o la aplicación de escritorio).
   * Haz clic en **Crear un video con IA** (o la opción asistida por Copilot dentro de Clipchamp).
   * En el cuadro de texto del asistente de IA de Clipchamp, escribe la siguiente descripción del guión basándote en el documento `Plan_Estrategico_Negociacion_Bancaria.docx`:
     ```text
     Crea un video corporativo de 45 segundos sobre la Estrategia de Negociación y Cierre con el Proveedor.
     Estilo: Profesional, dinámico y financiero.
     Mensaje clave: Acuerdos en Biometría (SLA), IA (Techo de costo en tokens) y Contact Center (Productividad por SMMLV).
     ```
   * Revisa la línea de tiempo autogenerada por Clipchamp, los estilos visuales, la música de fondo corporativa y exporta el video en resolución 1080p con el nombre: `Resumen_Estrategia_Negociacion.mp4`.

6. **EL RETO: Creación de Video Ejecutivo de Cierre en Clipchamp (Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas operativas que se presentan a continuación.
   * Utiliza la evidencia del documento `Plan_Estrategico_Negociacion_Bancaria.docx` para construir de forma independiente tu propio video ejecutivo utilizando **Clipchamp Copilot**:

   > **DESAFÍO DEL RETO:**
   > Como Category Manager Lead, debes crear un video ejecutivo sintetizado de 60 segundos en Microsoft Clipchamp utilizando las funciones asistidas por IA para presentarlo a la Vicepresidencia de Operaciones como resumen visual del éxito de la negociación.
   >
   > **Pasos y Pistas para construir tu video en Clipchamp con Copilot:**
   > - *Pista 1 (Acceso e Ingreso):* Ingresa a Microsoft 365, abre **Clipchamp**, selecciona la opción **Crear un video con IA** e ingresa el título del proyecto: `Cierre_Ejecutivo_Mesa_Negociacion`.
   > - *Pista 2 (Prompt del Guión y Narrativa):* Ingresa una instrucción clara a la IA de Clipchamp solicitando: *"Genera un video ejecutivo sobre los resultados de la negociación del Banco. Muestra el balance entre el ahorro logrado en la tarifa de Contact Center (mitigando el 23% de SMMLV), el esquema de flexibilidad en tokens de IA a 5 años y la garantía de SLA del 99.9999% en Biometría Facial."*
   > - *Pista 3 (Estilo, Voz en Off y Exportación):* Selecciona un ritmo de edición corporativo, añade voz sintética en español (IA Text-to-Speech) que narre los 3 hitos clave, edita los subtítulos automáticos para asegurar que los números sean exactos y exporta el archivo final como `Video_Ejecutivo_Cierre_Negociacion.mp4`.

   * Guarda y exporta el video entregable del reto.

## Resultado esperado
Un documento en Word `Plan_Estrategico_Negociacion_Bancaria.docx` con el plan ZOPA/BATNA y el MoU firmado, el registro de la simulación interactiva en Copilot Chat, el video explicativo `Resumen_Estrategia_Negociacion.mp4` y la resolución del reto: el video ejecutivo completo `Video_Ejecutivo_Cierre_Negociacion.mp4` generado en Microsoft Clipchamp.
