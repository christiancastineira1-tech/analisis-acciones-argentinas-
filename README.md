# Análisis Financiero — Acciones Argentinas

## Descripción
Análisis exploratorio del comportamiento histórico de cuatro acciones 
argentinas (GGAL, YPF, TGS, PAM) durante el período 2020-2024, 
utilizando Python y datos reales obtenidos de Yahoo Finance.

## Herramientas
- Python
- Jupyter Notebook
- yfinance
- Pandas
- Matplotlib

## Análisis realizados
1. Evolución histórica de precios
2. Rendimiento comparado base 100
3. Rendimiento acumulado total por acción
4. Volatilidad anualizada
5. Matriz de correlación entre activos
6. Retorno anual por año
7. Ratio de Sharpe

## Principales hallazgos
- PAM fue la acción con mayor rendimiento acumulado (454%) 
  y menor volatilidad (48.8%), resultando en el mejor ratio 
  de Sharpe del grupo (0.86)
- GGAL lideró en 2024 con un retorno anual de 292%, 
  impulsado por la normalización económica del gobierno Milei
- La alta correlación entre PAM y TGS (0.75) se explica por 
  pertenecer al mismo grupo económico (Grupo Pampa)
- YPF presentó el peor ratio riesgo/retorno del grupo

## Contexto macroeconómico
El período analizado refleja la volatilidad del mercado argentino:
estancamiento durante 2020-2022, recuperación anticipatoria en 2023 
pre-electoral, y un rally pronunciado en 2024 asociado al cambio de 
régimen económico y la desregulación del sector financiero y energético.

## Dataset
Datos históricos obtenidos mediante la librería yfinance desde Yahoo Finance.
