# Tarea en equipo: GitHub
 
## Objetivo
El propósito de este repositorio es servir como base para la práctica colaborativa. El objetivo principal es preparar un entorno con múltiples ramas para aprender a gestionar flujos de trabajo profesionales y resolver conflictos de fusión (*merge conflicts*) de forma controlada.

---

## Estructura del Repositorio
Para este proyecto, se han configurado tres entornos distintos:

* **`main`**: Rama principal destinada exclusivamente a la documentación. Se mantiene limpia de código fuente.
* **`dev`**: Rama de desarrollo donde se integrarán las funciones experimentales y carpetas de trabajo.
* **`prod`**: Rama de producción que simula el estado final del proyecto listo para despliegue.

---

## PASOS realizados para la configuración
Siguiendo las instrucciones del análisis, se han ejecutado las siguientes tareas:

1.  **Inicialización**: Creación del repositorio en GitHub y vinculación con el entorno local en Visual Studio Code.
2.  **Gestión de Ramas**: 
    * Creación de la rama `dev` mediante `git checkout -b dev`.
    * Creación de la rama `prod` mediante `git checkout -b prod`.
3.  **Diferenciación de Contenido**: 
    * Se han subido archivos y carpetas específicos a `dev` que **no** existen en `prod`.
    * Se han configurado archivos únicos en `prod` para simular un entorno de producción estable.
4.  **Documentación**: Elaboración de este archivo `README.md` estructurado para guiar a los futuros colaboradores.

---

## Instrucciones para la práctica del lunes
* Cada integrante del equipo deberá clonar este repositorio.
* Se realizarán cambios simultáneos en las mismas líneas de archivos específicos para forzar la aparición de conflictos.
* Aprenderemos a usar la herramienta de resolución de conflictos de VS Code para elegir los cambios correctos.
