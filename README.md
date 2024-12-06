# Proyecto: Implementación de Filtro de Kalman para un Sistema Dinámico No Lineal

Este repositorio contiene el desarrollo de un proyecto sobre filtros de Kalman, incluyendo la simulación, implementación y análisis de diferentes variantes de este filtro para un sistema dinámico no lineal con entrada. 

## Contenido del Proyecto

El trabajo se divide en las siguientes partes principales:

1. **Toma de Datos Experimentales**
   - Simulación de un sistema dinámico no lineal en Simulink.
   - Generación de datos experimentales con ruido.

2. **Filtro Extendido de Kalman (EKF)**
   - Implementación del filtro extendido de Kalman para estimar los estados del sistema.
   - Análisis gráfico de los resultados:
     - Estados estimados e intervalos de confianza.
     - Traza de la matriz de covarianzas.
     - Norma de la ganancia de Kalman.
     - Prueba de blancura.

3. **Filtro de Kalman Conjunto (JKF)**
   - Implementación del filtro conjunto de Kalman para estimar estados y parámetros.
   - Análisis gráfico de los resultados:
     - Estados y parámetros estimados.
     - Número de condición de la matriz de observabilidad.
     - Norma de la ganancia de Kalman.

4. **Control de Realimentación del Estado**
   - Implementación de un controlador de realimentación del estado utilizando el EKF.
   - Simulación y análisis de los resultados:
     - Estados controlados.
     - Acción de control.
     - Robustez frente a perturbaciones.

## Estructura del Repositorio

Este repositorio incluye los siguientes archivos y carpetas:

- `Informe/`  
  Contiene el archivo Live Script en formato MATLAB (`.mlx`) con los resultados, cálculos y gráficos en formato IMRAD.

- `Simulaciones/`  
  Incluye los archivos de Simulink (`.slx`) para:
  1. Generación de datos experimentales con ruido.
  2. Control de realimentación del estado.

- `README.md`  
  Este archivo.

- `Referencias/`  
  Recursos bibliográficos utilizados para desarrollar el proyecto.

## Requisitos Previos

- **MATLAB** con soporte para Live Scripts y Simulink.
- Conocimientos básicos sobre:
  - Sistemas dinámicos no lineales.
  - Filtros de Kalman (EKF y JKF).
  - Control de sistemas.

## Cómo Ejecutar el Proyecto

1. **Simulación y Toma de Datos**
   - Abrir el archivo de Simulink en `Simulaciones/`.
   - Ejecutar la simulación para generar datos experimentales.

2. **Análisis del Filtro de Kalman**
   - Abrir el archivo Live Script en `Informe/`.
   - Ejecutar las celdas paso a paso para generar gráficos y análisis.

3. **Control de Realimentación**
   - Abrir el archivo de Simulink correspondiente en `Simulaciones/`.
   - Modificar las condiciones iniciales según sea necesario.
   - Ejecutar la simulación para observar el comportamiento controlado.

## Formato del Informe

El informe sigue el formato IMRAD (Introducción, Métodos, Resultados y Discusión). 

- **Introducción**: Breve descripción del problema y del modelo utilizado.
- **Métodos**: Descripción de la implementación y procedimientos realizados.
- **Resultados**: Gráficos y análisis de los filtros y control.
- **Discusión**: Interpretación y discusión de los resultados obtenidos.

## Contribuciones

Este proyecto fue desarrollado de manera **[individual/colaborativa]**.  
- [Nombre del/los autor/es]  

## Licencia

Este proyecto se encuentra bajo la licencia [Licencia MIT/GPL/Otra].

## Referencias

Se pueden encontrar referencias relevantes en la carpeta `Referencias/`.
