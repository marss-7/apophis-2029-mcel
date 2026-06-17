# Retroalimentación de proyecto computacional

- Nombre completo: GRANADA RESTREPO MARHIA JOSE
- Cédula: 1094890344

## Archivos revisados

- Apophis.ipynb (versión final entregada)

## Historial de commits

- Repositorio original: https://github.com/marss-7/apophis-2029-mcel
- Fecha de creación del repositorio: 2026-03-22 (antes del 14 de abril: si)
- Total de commits desde creación del repo: 9
- Primer commit: 2026-03-21
- Último commit: 2026-05-30
- Días activos con commits: 7
- Semanas activas con commits: 4
- Mayor pausa entre commits: 30 días

### Aplicación al repositorio

- Inicio oportuno: 5.0
- Constancia semanal: 3.0
- Regularidad: 3.0
- Iteración: 4.0
- Nota de ritmo de commits (promedio): 3.75 / 5.0

Interpretación breve: Ritmo aceptable con evidencia de trabajo distribuido.

## Retroalimentación

- Archivo revisado: Apophis.ipynb (versión final entregada)

### Aspectos positivos

- Se evidencia el objetivo central del proyecto (trayectoria de Apophis, contexto de 2029 y estimación de acercamiento a la Tierra).
- Se aplican varias estrategias de modelado/validación y no un único experimento.
- Hay secciones de metodología/resultados con interpretación de hallazgos.
- El tamaño de las celdas de código es razonable para lectura y mantenimiento.
- Muy buenos los experimentos finales con la teoría de los 3 cuerpos.

### Aspectos por mejorar

- La narrativa del notebook debe mejorar: muchas celdas de código no están antecedidas por explicación. [Mejorado]
- Evitar repeticiones de patrones de cálculo como "pos_vel_saturno = pos_vel_saturno / np.array([AU, AU, AU, V_canon, V_canon, V_canon])" para eso se puede definir una variable factor_conversion = 1 / np.array([AU, AU, AU, V_canon, V_canon, V_canon]). [Mejorado]
- El modelo de 3 cuerpos no concluye con ningún resultado de valor para el proyecto ¿qué se quería obtener? [Mejorado]
- Indicar las fuentes de las que obtuvo las masas de los cuerpos.  [Mejorado]
- No hay aplicación de la solución analítica al problema de los dos cuerpos (solución a la ecuación de Kepler) [Mejorado]
- No hay aplicación de la teoría del CRTBP, al menos en la representación de la solución en el sistema rotante. [Mejorado]
- Se recomienda cerrar con una sección unica de conclusiones (3-5 puntos) que sintetice hallazgos físicos y computacionales y responda directamente al objetivo del proyecto. [Mejorado]

### Valoración global

- Trabajo técnicamente sólido en términos generales, con oportunidades claras de mejora en presentación y calidad de reporte.
- Estado de recepción: se recibe como fue entregado, con recomendaciones de mejora.
- El proyecto final no tiene ningún gráfico, tuve que correrlo instalando los paquetes que hacían falta, debes intentar siempre verificar el producto entregado
- El trabajo entregado cumple el objetivo perseguido.

## Valoración final

- Mejoras implementadas: 5.00 (70%)
- Aplicación al repositorio: 3.75 (10%)
- Aspectos positivos: 3.50 (10%)
- Valoración global: 3.50 (10%)

**Nota final (redondeada)**: 0.7×5.00 + 0.1×3.75 + 0.1×3.50 + 0.1×3.50 = (redondeado) 4.6
