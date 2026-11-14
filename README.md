## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Ing. Balthazar Martín
* Título corto del trabajo: Réplica: Fuente Buck 15V/1A
* Descripción: Módulo regulador conmutado step-down (Buck) de 15V y 1A (15W) operando a 200 kHz. Está basado en el controlador PWM TL494 y un transistor de paso Darlington PNP TIP127. El objetivo de este circuito es refactorizar un proyecto universitario original (THT/1 Capa) hacia un diseño mixto (SMD/THT) en 2 capas, implementando componentes pasivos de control SMD (>= 0805) y el IC TL494 en encapsulado SOIC-16 para facilitar el ensamblaje y retrabajo manual. El circuito incluye lazo de realimentación de tensión y protección contra cortocircuitos (limitación a 1A) mediante sensado low-side.
* Cursada: OCT-NOV-DIC 2026

## Licencia de este trabajo ##
Este proyecto de hardware y su documentación asociada se distribuyen bajo la licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**. 
Para ver una copia de esta licencia, visita http://creativecommons.org/licenses/by/4.0/ o revisa el archivo `LICENSE.txt` adjunto en este repositorio.

## Estructura del TP FINAL ##

Se propone y se pide utilizar la siguiente estructura.

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Estudios previos, estado del arte, resumen de las investigaciones.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos (placa original en 1 capa y ensayada).
  * Presupuestos, cotizaciones.
* info: Toda la iformación recolectada, principalmente de terceros, como por ejemplo:
  * Hojas de datos (Datasheets del TL494, TIP127, 1N5822, etc.).
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.

Dependiendo la magnitud del proyecto, tendremos más o menos información en estos directorios. 
Revisar los README.md en cada directorio para conocer las pautas de cada uno para este TP.

## Obligatorios para el TP Final ##
* doc/propuesta/README.md (con textos y links, formato markdown, a imágenes que deben estar en el mismo repo. Las imágenes son las que se piden en las pautas de TP).
* info/*.pdf (Se piden solo las hojas de datos de los componentes relevantes como circuitos integrados, conectores particulares, módulos, etc. No es necesario poner hojas de pasivos, discretos comunes, conectores estándar.)
* pcb/* (Acá va el proyecto KiCad, modelos 3D, bibliotecas particulares y archivos generados como BOM, gerbers, etc.). EVITE subir al git archivos temporales de KiCad. Se recomienda usar un .gitignore adecuado.
* El alumnos es libre de agregar otras cosas, pero siempre tenga en cuenta que el repositorio es público. Evitar colocar información personal o documentación confidencial.