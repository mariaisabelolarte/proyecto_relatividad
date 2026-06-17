# Retroalimentación de proyecto computacional

- Nombre completo: OLARTE GARCIA MARIA ISABEL
- Cédula: 1034986320

## Archivos revisados

- Proyecto_DiscoAcrecion_RG2026_1.ipynb (versión final entregada)

## Historial de commits

- Repositorio original: https://github.com/mariaisabelolarte/proyecto_relatividad
- Fecha de creación del repositorio: 2026-04-14 (antes del 14 de abril: sí)
- Total de commits desde creación del repo: 9
- Primer commit: 2026-04-17
- Último commit: 2026-05-27
- Días activos con commits: 9
- Semanas activas con commits: 5
- Mayor pausa entre commits: 14 días (4-may → 18-may)

### Aplicación al repositorio

- Inicio oportuno: 5.0
- Constancia semanal: 4.0
- Regularidad: 4.0
- Iteración: 4.0
- Nota de ritmo de commits (promedio): 4.25 / 5.0

Interpretación breve: inicio en la fecha límite exacta, buen número de commits con trabajo distribuido en cinco semanas. La mayor pausa (14 días en la segunda quincena de mayo) indica una pequeña concentración de esfuerzo al final, pero en general el ritmo fue sostenido y constante.

## Retroalimentación

- Archivo revisado: Proyecto_DiscoAcrecion_RG2026_1.ipynb (versión final entregada)

### Aspectos positivos

- El notebook cubre cinco secciones bien diferenciadas — dinámica newtoniana (Rebound), beaming relativista, jets astrofísicos, geodésicas de Schwarzschild y Kerr, y trayectorias de fotones — demostrando una integración real del material del curso.
- Se incluye la **métrica de Kerr**, que va más allá de lo mínimo esperado. Los símbolos de Christoffel se calculan simbólicamente con SymPy, lo que refleja un manejo sólido del formalismo tensorial.
- La sección de **beaming relativista** es rigurosa: se define el factor de beaming δ(β, θ) y el desplazamiento espectral z, se exploran distintos valores de β e i, y se usa un colormap personalizado para visualizar el corrimiento espectral a lo largo del disco, que es exactamente el fenómeno central del proyecto.
- La narrativa general del notebook es fluida: la mayoría de los bloques de código están contextualizados con texto explicativo.

### Aspectos por mejorar

- El notebook no tiene **sección de conclusiones**. Se recomienda agregar una sección final que responda directamente al objetivo del proyecto: ¿qué se simuló en cada parte?, ¿qué se aprendió?, ¿qué limitaciones tienen los modelos usados? [Mejorado]
- El enunciado pide **producir una imagen del disco** que integre los efectos calculados. Las cinco secciones quedan desconectadas entre sí; el paso que falta es articularlas en una figura síntesis que muestre el disco con corrimiento espectral, las órbitas relativistas y las trayectorias de fotones en un mismo marco. [Mejorado]
- Algunas celdas de código —en particular las que construyen animaciones y figuras interactivas— mezclan lógica de cálculo con lógica de graficación. Conviene separar ambas responsabilidades: primero calcular y guardar los datos en variables, luego graficar en una celda aparte, cada una con su texto explicativo. [Mejorado]
- Hay algunas celdas de código sin celda de texto anterior. Aunque sean celdas de apoyo (parámetros, condiciones iniciales), vale la pena antecederlas con una línea que explique qué se está definiendo y por qué se eligieron esos valores. [Mejorado]

### Valoración global

- Trabajo ambicioso y técnicamente sólido, con buen nivel de apropiación de los temas del curso. Los dos puntos más importantes para completar el proyecto son la imagen síntesis del disco y la sección de conclusiones.
- Estado de recepción: se recibe como fue entregado, con recomendaciones de mejora orientadas a completar el objetivo central del proyecto (imagen del disco) y fortalecer la comunicación científica del informe.
- Muy buen trabajo, muy completo.

## Valoración final

- Mejoras implementadas: 5,00 (70%)
- Aplicación al repositorio: 4,25 (10%)
- Aspectos positivos: 4,80 (10%)
- Valoración global: 4,80 (10%)

**Nota final (redondeada)**: 4,9
