
# La Memoria Técnica 

## Elías Pérez Arroyo

## 1ºDesarrollo de Aplicaciones Multiplataforma

## 15/05/2026

[1\. Análisis de Necesidades	2](#1.-análisis-de-necesidades)

[1.1. Contexto y Problemática Actual	2](#1.1.-contexto-y-problemática-actual)

[1.2. Solución Propuesta: Infraestructura Híbrida Docker-Guacamole	2](#1.2.-solución-propuesta:-infraestructura-híbrida-docker-guacamole)

[1.3. Justificación Técnica y Beneficios	2](#1.3.-justificación-técnica-y-beneficios)


# 1\. Análisis de Necesidades {#1.-análisis-de-necesidades}

## 1.1. Contexto y Problemática Actual {#1.1.-contexto-y-problemática-actual}

Actualmente la empresa de este proyecto no dispone ni de monitores ni teclados para manejar sus servidores que se encuentran en Dublín fuera del alcance de los trabajadores debido a medidas de seguridad que se han implantado.

## 1.2. Solución Propuesta: Infraestructura Híbrida Docker-Guacamole {#1.2.-solución-propuesta:-infraestructura-híbrida-docker-guacamole}

Una vez hecho un planteamiento de las necesidades y requerimientos, se ha propuesto el uso de **Apache Guacamole** a través de **Docker Compose.** Esta aplicación web HTML5 ofrece estas ventajas:

* Acceder a los servidores desde cualquier dispositivo.\[1\]  
* Mantener todos los servicios en la nube.\[1\]  
* Facilita el acceso y manejo de varios servidores a la vez con varios usuarios.\[1\]  
* El acceso es siempre desde un navegador web basado en HTML5.\[1\]

### 1.3. Justificación Técnica y Beneficios  {#1.3.-justificación-técnica-y-beneficios}

Con la implementación de esta infraestructura híbrida de Docker-Guacamole se consigue portabilidad, seguridad y flexibilidad ya que permite la fácil recuperación del sistema en caso de fallos, permite acceder a los equipos sin la necesidad de instalar clientes esppeciales y  sin violar firewalls que pueda haber previamente junto a todos los beneficios antes nombrados. Así mismo Guacamole se encuentra bajo el umbral de la licencia Apache 2.0 que permite el libre uso y modificación bajo su protección.

\[1\] “Introduction — Apache guacamole manual v1.6.0”, *Apache.org*. \[En línea\]. Disponible en: https://guacamole.apache.org/doc/gug/introduction.html. \[Consultado: 15-may-2026\].


