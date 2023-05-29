# Apuntes de Análisis de Algoritmos
Este repositorio contiene una aplicación web estática diseñada para proporcionar una guía de estudio estructurada para el curso de Análisis de Algoritmos. Cada tema del curso se encuentra en su propia página, que se puede acceder a través de la página principal.

## Estructura del Proyecto
El proyecto sigue una estructura de directorio basada en los temas principales del curso:

```bash
/
├─ index.html
├─ Notacion_Asintotica/
│   └─ index.html
├─ Dividir_Conquistar/
│   └─ index.html
├─ Programacion_Dinamica/
│   └─ index.html
├─ Algoritmos_Voraces/
│   └─ index.html
├─ Computabilidad_Tractabilidad/
│   └─ index.html
├─ Aprendizaje_Maquina/
│   └─ index.html
└─ Geometria_Computacional/
    └─ index.html
```

Cada archivo index.html dentro de las subcarpetas representa una página de contenido para ese tema específico.

## Despliegue en AWS S3
Esta aplicación web estática se aloja y se sirve a través de un bucket de Amazon S3. Las páginas se almacenan como objetos dentro del bucket y se sirven a través de la funcionalidad de alojamiento de sitios web estáticos de S3.

## Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o una pull request para sugerir cambios o mejoras.

