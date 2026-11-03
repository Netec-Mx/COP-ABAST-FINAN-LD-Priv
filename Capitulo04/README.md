# Práctica: Construir y analizar un TCO y business case con Copilot en Excel

**Duración:** 105 min

## Descripción
Los participantes utilizarán Microsoft 365 Copilot en Excel para estructurar un análisis avanzado de Spend, Total Cost of Ownership (TCO) y Business Case a partir de los datos operativos de los tres proyectos del banco (Biometría Facial, Contratación de IA y Contact Center). Organizarán tablas de datos autogeneradas, solicitarán a Copilot la creación de fórmulas avanzadas y columnas calculadas siempre en modo Edición, normalizarán alternativas económicas, compararán escenarios, realizarán análisis de sensibilidad y generarán gráficos dinámicos de soporte. Finalmente, resolverán un reto técnico en Copilot Chat utilizando el archivo de Excel como fuente de datos para evaluar escenarios de estrés financiero y sensibilidad de costos.

## Pasos para ejecutar la práctica

1. **Autogeneración y estructuración del modelo de Spend en Microsoft Excel (Modo Edición):**
   * Abre **Microsoft Excel** en un libro en blanco y guárdalo inmediatamente con el nombre exacto: `Modelo_TCO_BusinessCase_Abastecimiento.xlsx`.
   * Selecciona la **Hoja 1**, renómbrala como `Spend_Base` y activa **Copilot en Excel** (modo **Edición**).
   * Envía el siguiente prompt para poblar la tabla base con las variables operativas y de mercado de los 3 proyectos:
     ```text
     Actúa como un Analista Financiero de Abastecimiento Bancario.
     
     Crea una tabla formateada de Excel llamada Tabla_SpendBase con las siguientes columnas y datos ficticios simulados para 5 años (Año 1 a Año 5):
     - Proyecto: Biometría Facial, IA Generativa, Contact Center.
     - Anio: 1, 2, 3, 4, 5.
     - Volumen_Base: Biometría (30M a 40M clientes, escalando a 1 billón de transacciones), IA (70B a 100B tokens/año), Contact Center (300M llamadas/año).
     - Tarifa_Unitaria_USD: Valores base de mercado (ej. $0.00015/transacción biométrica, $0.000002/token IA, $0.85/llamada).
     - Factor_Macro_IPC: 6% anual para Contact Center.
     - Factor_Macro_SMMLV: 23% de incremento inicial para Contact Center.
     ```

2. **Formulación y creación de columnas calculadas (Modo Edición):**
   * En la misma hoja `Spend_Base` de `Modelo_TCO_BusinessCase_Abastecimiento.xlsx`, utiliza **Copilot en Excel** (modo **Edición**) para agregar los cálculos de costos proyectados mediante fórmulas:
     ```text
     Agrega dos columnas calculadas a la Tabla_SpendBase utilizando fórmulas de Excel:
     1. Columna 'Costo_Directo_Anual': Que multiplique Volumen_Base por Tarifa_Unitaria_USD.
     2. Columna 'Costo_Ajustado_Macro': Para Contact Center, aplica el impacto acumulado del IPC (6%) y SMMLV (23%); para Biometría e IA, mantén el Costo_Directo_Anual.
     
     Explica paso a paso las fórmulas creadas.
     ```

3. **Construcción del modelo TCO consolidado a 5 años (Modo Edición):**
   * Crea una nueva hoja en el libro llamada `TCO_Consolidado`.
   * En **Copilot en Excel** (modo **Edición**), envía la siguiente instrucción para consolidar la estructura del TCO agregando costos indirectos de implementación y soporte:
     ```text
     Diseña una tabla llamada Tabla_TCO_5Anios en la hoja TCO_Consolidado que organice el TCO total por proyecto a 5 años.
     
     Columnas requeridas: Proyecto, CapEx_Inicial_USD, OpEx_Acumulado_5Anios, Costo_Soporte_Mantenimiento, Costo_Riesgo_Terceros, TCO_Total_USD y Pct_Sobre_Total.
     
     Puebla la tabla con los datos resumidos de la hoja Spend_Base y agrega una fila de TOTALES al final calculada automáticamente.
     ```

4. **Análisis de sensibilidad y formato condicional (Modo Edición):**
   * Crea una nueva hoja llamada `Analisis_Sensibilidad`.
   * En **Copilot en Excel** (modo **Edición**), envía la siguiente orden para estructurar un cuadro comparativo de escenarios:
     ```text
     Crea una tabla llamada Tabla_Sensibilidad en la hoja Analisis_Sensibilidad que compare 3 escenarios financieros para el TCO global a 5 años:
     1. Escenario Base: IPC 6%, SMMLV 23%, IA 70B tokens/año, Biometría 30M clientes.
     2. Escenario Estresado: IPC 9%, SMMLV 28%, IA 100B tokens/año, Biometría 40M clientes y 1 billón de transacciones.
     3. Escenario Optimizado (IA / Automatización): Reducción del 15% en volumen de llamadas por autogestión de Nivel 1 y descuento por volumen de tokens del 10%.
     
     Calcula la variación porcentual de cada escenario frente al Escenario Base y aplica un formato condicional resaltando en rojo las variaciones superiores al 15% y en verde los ahorros superiores al 5%.
     ```

5. **Generación de gráficos dinámicos de TCO en Excel (Modo Edición):**
   * Manteniéndote en la hoja `Analisis_Sensibilidad`, utiliza **Copilot en Excel** (modo **Edición**) para insertar visualizaciones del modelo financiero:
     ```text
     Crea un gráfico de barras agrupadas que compare el TCO Total USD de los 3 proyectos a lo largo de los 3 escenarios (Base, Estresado, Optimizado).
     
     Añade además un gráfico de pastel o anillos que muestre la distribución porcentual del TCO acumulado por proyecto dentro de la hoja TCO_Consolidado.
     ```
   * Guarda todos los cambios en el libro `Modelo_TCO_BusinessCase_Abastecimiento.xlsx`.

6. **EL RETO: Evaluación de Estrés Financiero y Sensibilidad de Costos en Copilot Chat (Guiado por Pistas):**
   * Lee atentamente el desafío y las pistas financieras que se presentan a continuación.
   * Abre **Microsoft 365 Copilot Chat** y adjunta explícitamente el libro de Excel `Modelo_TCO_BusinessCase_Abastecimiento.xlsx` generado previamente:

   > **DESAFÍO DEL RETO:**
   > Como Category Manager, debes utilizar Copilot Chat para procesar los datos de `Modelo_TCO_BusinessCase_Abastecimiento.xlsx` y presentar al Comité de Finanzas la defensa estratégica del Business Case definitivo, demostrando bajo qué condiciones de negociación el proyecto de Contact Center y la Contratación de IA se mantienen viables financieramente frente al choque del IPC (6%) y SMMLV (23%).
   >
   > **Pistas para construir tu prompt en Copilot Chat:**
   > - *Pista 1 (Punto de Equilibrio en Contact Center):* Pide a Copilot Chat analizar los datos de la hoja `Spend_Base` y calcular cuántas llamadas del total de 300M deben migrar a bots de Nivel 1 (costo de IA por token) para neutralizar por completo el sobrecosto del 23% en SMMLV.
   > - *Pista 2 (Tiering de Tokens en IA Generativa):* Solicita a Copilot Chat evaluar la hoja `TCO_Consolidado` y modelar una estructura de precios por tramos de consumo (descuento del 5% al superar 80B tokens y 12% al superar 95B tokens), indicando el ahorro neto en USD logrado a 5 años.
   > - *Pista 3 (Cuadro Mando Business Case y Valor Presente Neto):* Solicita a Copilot Chat sintetizar en un resumen ejecutivo en tabla Markdown el TCO Ajustado con las mitigaciones aplicadas, calculando el Net Present Value (NPV / VPN) proyectado usando una tasa de descuento bancaria del 12%.

   * Exporta o guarda el análisis del reto para la mesa directiva.

## Resultado esperado
Un libro en Excel completo y automatizado `Modelo_TCO_BusinessCase_Abastecimiento.xlsx` elaborado siempre en modo Edición (con las hojas `Spend_Base`, `TCO_Consolidado`, `Analisis_Sensibilidad` con formato condicional y gráficos dinámicos), junto con la resolución del reto técnico procesado en Copilot Chat con fórmulas de punto de equilibrio, tiering y VPN.
