##  ELECTRÓNICA DIGITAL 2 2021-1 UNIVERSIDAD NACIONAL DE COLOMBIA 
###  https://unal-edigital2.github.io/2021-1/

## Profesor:
	Ferney Alberto Beltrán Molina, Ing, MSc, PhD(c)
	fabeltranm@unal.edu.co.
	github: https://github.com/Fabeltranm/

## Años anteriores
* [2015-2017](https://sites.google.com/site/edigital2unal/)
* [2018](https://github.com/unal-edigital2/2020-2/blob/master/docs/proyectos2018.md)
* [2019](https://unal-edigital2.github.io/2019-2/)
* [2020-2](https://unal-edigital2.github.io/2020-2/)

## Horario 
	* Clases en zoom
	* Teoria: Martes y jueves 7-9am
	* Laboratorio
	
## entrega final del proyecto
 
* [Grupo 01](https://github.com/unal-edigital2/w07_entrega-_final-grupo11)
* [Grupo 02](https://github.com/unal-edigital2/w07_entrega-_final-grupo12)
* [Grupo 04](https://github.com/unal-edigital2/w07_entrega-_final-grupo14)
* [Grupo 05](https://github.com/unal-edigital2/w07_entrega-_final-grupo15)

## Metodología

El estudiante es responsable de adquirir el conocimiento, y tiene la responsabilidad de preparar los temas que se van a  tratar, se dejarán documentos que deben ser analizados por  el estudiante; las dudas se discutirán y aclararán en clase. 

Se diseñará e implementará un dispositivo digital de mediana complejidad, utilizando las herramientas  suministradas y los conocimientos adquiridos; las tareas hardware se implementarán en un un dispositivo lógico programable (FPGA) y las tareas software en un soft-core (SoC) implementado en el mismo.

Se conformarán grupos de trabajo de 3 personas, las cuales se encargarán de generar y publicar en un sitio público github la documentación necesaria para futuras mejoras o correcciones.


### Evaluación
* 15% AutoEvaluación
* 15% CoEvaluación
* 70% Proyecto (3 entregas)

## Material de Clase

Semana   | Tema   | Documentación | otros | Video
--       | --     | --            | -- | --   
Semana 1 | Introducción  | [link](./slides/week01/week1_digital2.pdf) | --| 
Semana 2  | Repaso  | [link](./slides/week02/week2_digital2.pdf) | -- | 
 ||  | [link](./slides/week02/week3_digital2.pdf) | -- | 
Semana 3-4  | intro Procesador caso J1|[link](./slides/week03/week4_digital2.pdf) |  -- | 
Semana 3-4  | |  |  | 
Semana 4-5  | |  |  | 
Semana 6-7 | pipeline   | [link](./slides/week5_digital2_.pdf)  | --| 
Semana 8 | proyecto  |  | --| 
Semana 9 | I/O  |  | --| 
Semana 10-11 | chache  |  | --|  

## videos 

[link](https://drive.google.com/drive/folders/1dBglkMceGa2hCZL5vTpy7_vCFYOZRpEu?usp=sharing)

## Estructura de los Laboratorios y Proyecto 


## Cronograma de laboratorios  (Prelabs) 


Semana   | Tema   | Guia de laboratorio | WP | deadline 
--       | --     | --            	| -- | --   
Semana 1 | instalación linux | [link] | |
Semana 2 | instalación Viviado/quartus | [link](./labs/lab00.md) | |
Semana 3 |  configuración Vivado -ALU | [link](./labs/lab01.md) | [wp01](https://classroom.github.com/g/00dJ40MG) |


## Cronograma de laboratorios  (Prelabs) 

El trabajo presentado a continuación  tiene como objetivo diseñar  un sistema autónmo capaz  de navegar  y trazar un laberinto al mismo tiempo que  procesar imagenes de objetos por color. 

En las próximas 5 semanas se estará trabajando en la adquisición, procesamiento y visualización de  imágenes. Para ello se hará uso de los siguientes componentes:

* Cámara OV7970 sin FIFO con las siguientes características:
* Tarjeta STM o Arduino, usado para la navegación del  robot autonomo
* Tarjeta de desarrollo FPGA, Nexys4, quacho-basic  para ka adquisición y  procesamiento de imagen
* Sistema de visualización.
* Sensores y actuadores según seleccione el grupo.

![Diagrama](./docs/figs/escenario.png)


## Metodología de trabajo 

Para cada paquete de trabajo se debe clonar la plantilla dada, y los resultados del trabajo de cada grupo deben ser subidos antes de la fecha estipulada. Se recomienda  leer la ayuda de github classroom en este [link](https://education.github.com/) y ver los videos de github de su canal de YouTube de este [link]( https://www.youtube.com/githubguides) o pueden descargar un libro de git del siguiente [link]( https://git-scm.com/book/en/v2)
Antes de empezar  si no ha tenido ningún acercamiento con los repositorios de git  debe realizar los siguientes pasos:
* Crear una cuenta de github. Ver este [video](https://www.youtube.com/watch?v=ezxRcdJ8glM&feature=youtu.be)
* Para crear repositorios  revise este [link](https://help.github.com/en/github/getting-started-with-github/create-a-repo)

Antes de comenzar con cada paquete de trabajo se debe leer las instrucciones  y tener todos los archivos. Para acceder a cada paquete de trabajo debe:
* Aceptar la asignación de cada link dado. 
* La aplicación les pregunta si desean crear un grupo nuevo o unirse a uno existente:
	* Para crear un grupo nuevo coloque "Grupo-xx", donde xx es el número del grupo.
	* Para unirse a un grupo existente, busque el nombre  y pulse el botón ´join´.
	
***Nota: Todos los estudiantes debes unirse al grupo correspondiente  y tener cuidado de no equivocarse de grupo***

Luego de unirse a cada grupo de trabajo debe clonar su  repositorio en su computador, para lo cual: 
* Si usted  no tiene ningún conocimiento de cómo hacer esto, recomiendo  usar ***github Desktop*** el cual se puede descargar de este [link]( https://desktop.github.com), y la documentación  de uso la encuentra en este [link](https://help.github.com/en/desktop/getting-started-with-github-desktop) ***Recuerde lo que debe hacer es clonar el repositorio creado de forma automática por git classroom y NO crear uno nuevo***
* Para los estudiantes que usen el sistema operativo Linux  les recomiendo usar la siguiente guía para clonar el repositorio e iniciar en  el mundo de  control de versiones [link]( https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

***RECUERDEN:*** Todos los integrantes del grupo deben  trabajar en el respectivo repositorio y participar en los respectivos commit y push, tanto de la documentación

## Documentación
Para todos los paquetes de trabajo se debe  realizar  la documentación respectiva, que evidencie el progreso del trabajo. Puede hacer uso de fotos, videos, comentar el código HDL, y todo lo que el grupo considere necesario  para explicar los avances que va teniendo. 
Recuerde el trabajo que ustedes documenten, será el que leerán sus compañeros de los próximos semestres. En este contexto, la evaluación de la documentación será  tenida en cuenta la minuciosidad y claridad de la misma.

La documentación se debe  diligenciar en el archivo README.md, que se encuentra en cada repositorio dentro de la carpeta docs, en el cual deben colocar el nombre3 de los integrantes  y el  número de identificación.
El archivo README.md, se debe escribir en formato Markdown. Para aprender cual es el formato de este documento se recomienda revisar el siguiente [link](https://guides.github.com/features/mastering-markdown/) que les da una visión rápida de formato usado para hacer la documentación. 
Las imágenes, fotos y soportes gráficos deben ser alojados en la carpeta ‘figs’ y deben ser vinculadas en documento README.md.

## Descripción de Hardware
El código HDL está alojado en la carpeta ***hw***. Allí  están los archivos fuentes dados en clase  y allí deben alojar todo los archivos  diseñados  y desarrollados por los integrantes de grupo y según sea solicitado en la  guía de cada paquete de trabajo.

## Descripción del firmware
El código del firmare debe se alojado en la carpeta ***sw***. Allí  están los archivos fuentes dados en clase  y allí deben alojar todo los archivos  diseñados  y desarrollados por los integrantes de grupo y según sea solicitado en la  guía de cada paquete de trabajo.

## Entrega
Recuerde tener presente el deadline  de cada paquete de trabajo, a las 8 de la noche del día indicado  se cierra  el sistema  y los grupos no podrán actualizar el repositorio.
Para actualizar el repositorio deben realizar  el respectivo commit y push, según sea la plataforma que estén utilizando y como se explicó en clase.
Recuerda también revisar que en la página de github se refleja las actualizaciones realizadas por el grupo de trabajo 
  

## Desarrollo 
A continuación se presenta cada actividad a realizar, el plan de trabajo del proyecto de cada semana se encuentra en el link de documentación y el link de trabajo se encuentra en la columna  repositorio.



WP  | semana | deadline  | Tema | Documentación| Repositorio 
--  | --     | --        | --   | --          | --  
01| semana 1 |  | Definición completa de  los periféricos  y mapa de memoria  | [link](./docs/WP01.md) | [WP01]().
02  | semana 2 |  | Construcción del bloque  Cámara  y modulo de procesamiento   | [link](./docs/WP02.md) |  [WP02](https://classroom.github.com/g/fskVZJhK) 
03| semana 3 |   | Construcción del bloque Driver Radar, Estructura  del software  | [link](./docs/WP03.md) |  [WP02]()
04  | semana 4 |  | Inicio SoC Litex.  | |  [WP04](https://classroom.github.com/g/qqeF36oA)
05  | semana 5 |  | SoC con interripciones .  | |  [WP05](https://classroom.github.com/g/llp2Y_dc)
06  | semana 6 |  | SoC con periféricos en verilog.  ||   [WP06](https://classroom.github.com/g/_wfeVTAZ)
07  | semana 7 |  | Integración driver con SoC, pruebas  funcionales de cada driver.  |   
08  | semana 8 |  | : Software  del hard procesador  y el procesador IP  | |  
09  | semana 9 |  | Integración del proyecto y pruebas funcionales  | |  
10  | semana 10 |  | Presentación  entrega del proyecto| [link](./docs/WP07.md) |  [WP07](https://classroom.github.com/g/hfWKBknQ) 

