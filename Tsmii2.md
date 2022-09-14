
# TSR-2023-1-T1

Entrega de la tarea 1 de la asignatura.

Practica de documentación en Markdown

## Contenido

- [TSR-2023-1-T1](#tsr-2023-1-t1)
  - [Contenido](#contenido)
  - [Introducción](#introducción)
  - [Desarrollo](#desarrollo)
    - [Clasificación de los robots móviles por configuración](#clasificación-de-los-robots-móviles-por-configuración)
    - [Restricciones cinemáticas](#restricciones-cinemáticas)
    - [Conceptos de localización, ruta, odometría y planeación de ruta](#conceptos-de-localización-ruta-odometría-y-planeación-de-ruta)
    - [Diferencias entre sistemas holonómicos y no-honolomicos](#diferencias-entre-sistemas-holonómicos-y-no-honolomicos)
    - [Caracterización de la plataforma móvil TurtleBot3](#caracterización-de-la-plataforma-móvil-turtlebot3)
  - [Conclusiones](#conclusiones)
  - [Autor](#autor)
  - [Referencias](#referencias)

## Introducción

Texto sobre robots móviles

## Desarrollo

### Clasificación de los robots móviles por configuración

Existen 4 ptincipales configuraciones para la moviliodad de un robot y son las siguientes:

- Diferencial:
   Es el sistema utilizado por tanques militares, se tienen dos motores para el robot, mediante el giro de estos se obtiene el movimiento del robot.
- Automóvil:

  Análoga a la utilizada por automóviles, emplea un motor de tracción y otro de dirección.
- Triciclo:
  
  Utiliza dos motores para tracción y dirección, la estabilidad del motor se logra con ruedas locas.
- Omnidireccional:
  Sistema de movimiento complejo, en el que las llantas pueden generar movimientos en cualquier dirección del robot.

### Restricciones cinemáticas

>se define el concepto de restricción cinemática entre dos cuerpos, como las
condiciones impuestas sobre el movimiento relativo de ambos. Se indica que cuando esas
condiciones están expresadas mediante ecuaciones algebraicas en términos de las
coordenadas generalizadas, reciben el nombre de ecuaciones de restricción cinemáticas
holonómicas, y se indica la forma de representarlas[^1].

Las coordenadas dependientes son coordenadas que se utilizan para representar el sistema de manera unequívoca, se relacionan con las coordenadas independientes mediante las restricciones cinemáticas.

### Conceptos de localización, ruta, odometría y planeación de ruta

Localización:
se entiende como localización a la detección de la posición de un robot respecto a su medio ambiente, utilizando la información sobre el entorno recogida por el robot.

Ruta:
En robótica, el problema de planeación de rutas se define así:
>Dado un robot, un espacio de trabajo, una configuración inical y una configuración final, se desea encontrar una ruta libre de colisión para el robot, de la configuración inicial a la configuración final, si ésta existe. En caso contrario, determinar que dicha ruta no existe.[^2]

### Diferencias entre sistemas holonómicos y no-honolomicos

Se define como sistema holonomico a los robots que pueden cambiar su dirección de movimiento instantáneamente, sin necesidad de girar antes del cambio de dirección, además de esto, un robot holonómico tierne el mismo número de grados de libertad controlables y totales, mientras que un no holonómico tiene menos grados de libertad controlables que totales.
La maniobrabilidad de un sistema.

### Caracterización de la plataforma móvil TurtleBot3

- #### Modelo cinemático

![Modelo cinematico](modelo_cinematico.png)

- #### Sensores y actuadores que lo integran

  - Batería LiPo 11.1v 1800 mAh
  - OpenCR para ROS embebido
  - Motores Dynamixel-X series (XL430 o XM430)
  - sensor de distancia láser LDS-01
  - SBC

- #### Nodos y Tópicos de ROS utilizados por la plataforma Turtlebot3 y sus sensores

  - Topicos
    - clicked_point
    - cmd_vel
    - initialpose
    - joint_states
    - move_base_simple/goal
    - odom
    - rosout
    - rosout_agg
    - tf
    - tf_static
  
  - Nodos
  
    - robot_state_publisher
    - rosout
    - rviz
    - turtlebot3_fake_node

## Conclusiones

Conclusiones o cierre al trabajo realizado.

## Autor  

Sanchez Espinosa Miguel Angel [GitHub profile](https://github.com/MigSE)

## Referencias

https://core.ac.uk/download/pdf/229164924.pdf
http://www.upv.es/vltmodels/v2019/C07/07-07-DEFINICION-RESTRICCIONES.pdf
https://ocw.unican.es/pluginfile.php/2949/course/section/2799/Tema%207%20-%20Ana%CC%81lisis%20Cinema%CC%81tico%20III.pdf
http://www.kramirez.net/Robotica/Material/Presentaciones/Localizacion.pdf
http://catarina.udlap.mx/u_dl_a/tales/documentos/lis/munoz_r_o/capitulo4.pdf
http://blog.electricbricks.com/2010/07/sistemas-holonomicos/

[^1]: I.A. Glover and P.M. Grant, Digital Communications, 3rd ed. Harlow: Prentice Hall, 2009.
