---
title: "Málaga CitySense: el ciudadano como sensor"
related : true
categories:
  - Proyectos
tags: 
  - app
  - citysense
  - ciudadano como sensor
  - dato abierto
  - málaga
  - medioambiente
  - open data
  - sensores
  - smart city
---

![Málaga City Sense](/assets/images/2014/02/malaga-city-sense.png){:
.align-left} Hace ya dos años, desde
el
[Área de Innovación y nuevas Tecnologías](http://www.malaga.eu/ayto/m_ayto/portal/menu/seccion_0003/secciones/subSeccion_0006?id=454) reflexionábamos
sobre nuestro futuro como ciudad
([Málaga](http://es.wikipedia.org/wiki/M%C3%A1laga)) en el marco de las Smart
Cities y, en concreto, del Internet de las Cosas. Nos encontrábamos tratando la
problemática inherente a la sensorización de la ciudad: la introducción de miles
de sensores en el espacio urbano comporta más de un quebradero de cabeza en la
gestión de su ciclo de vida. Como ejemplo no hay más que pensar en la cantidad
de dispositivos que, ya al día de hoy, al final de su corto ciclo de vida se
quedan "colgados" en farolas, semáforos y otros soportes en forma de basura
electrónica, cuya recogida, de llevarla a cabo, tiene un coste considerable. Sin
duda, las ciudades se tendrán que plantear formas de evitar esta situación y
otras relacionadas, incluyendo el desarrollo de normativas aseguren la gestión
de la Internet de las Cosas y nuevos modelos de negocio que descarguen a la
ciudadanía de asumir los costes directos e indirectos que planteará esta nueva
revolución, aunque esto será motivo de otra entrada en este blog.

Pues bien, este tipo de reflexión dio lugar a una solución obvia consistente en
controlar el crecimiento del número de dispositivos sensoriales (lo cual no deja
de ser contrario al concepto en sí mismo del Internet de las Cosas). Entre otras
cosas analizamos los diferentes tipos de sensores potencialmente aplicables en
la ciudad comenzando con los más habituales: los dedicados al medioambiente.
Coincidiendo en el tiempo, algunos fabricantes de smartphones comenzaron a
incluir sensores de ese tipo en sus terminales. En concreto los galaxy de
Samsung y los nexus de Google disponían de un número de sensores
medioambientales por encima de lo habitual en otros fabricantes (temperatura,
humedad, presión, altitud, ...). Esto nos llevo a considerar la posibilidad de
que los ciudadanos que tuvieran terminales smartphones con esta diversidad de
sensores pudieran transmitir esa información, convirtiéndose en sensores
móviles. Al concepto lo denominamos "Ciudadano como sensor".

En otro orden de cosas y por la misma época, estábamos, y aun hoy lo estamos,
inmersos en el desarrollo y promoción del proyecto [FI-WARE](http://www.fi-ware.org/) que está financiado
por el VII Programa Marco de I+D de la UE dentro de su proyecto de colaboración
público-privada para el desarrollo del Internet del Futuro (Future Internet
Public Private Partnership o FI-PPP).

FI-WARE tiene como objetivo desarrollar una plataforma de middleware abierta
sobre la que desarrollar nuevas aplicaciones y servicios de Internet del Futuro.
Con este proyecto los desarrolladores de aplicaciones podrán crear nuevos
servicios basados en datos de redes de sensores, como las puestas en marcha para
proyectos de ciudades inteligentes.

El [Ayuntamiento de Málaga](http://www.malaga.eu/) participa activamente en el
proyecto en diferentes aspectos. El proyecto FI-WARE, en cuanto a
infraestructura se refiere, se basa en un modelo de nube. En Málaga albergamos y
soportamos parte de esa infraestructura que se encuentra en el Centro de Proceso
de Datos
del
[Centro Municipal de Informática](http://www.malaga.eu/ayto/m_ayto/portal/menu/seccion_0003/secciones/subSeccion_0002?id=161) (CEMI).
Además, la red de datos de nuestro Ayuntamiento se ha enlazado con la Red Iris
que es la responsable de desplegar la infraestructura europea FIWAT en la cual
se están probando y evaluando la mayoría de los componentes de FI-WARE.

Desde nuestro Ayuntamiento también colaboramos en la promoción de uso de la
plataforma FI-WARE en el ecosistema empresarial de la ciudad y es justo ahí
retomo el concepto de "Ciudadano como sensor".

Parecía natural y así lo hemos hecho, que para desarrollo del concepto
"Ciudadano como sensor" utilizáramos la plataforma FI-WARE. Para ello nos
plateamos el desarrollo de una aplicación que se basara en esta plataforma, cuyo
objetivo fuera el de recoger la información de los sensores de los móviles de
los ciudadanos y la enviara a un repositorio central para un análisis posterior
incluyendo su puesta a disposición del público
como [dato abierto](http://datosabiertos.malaga.eu/).

Además del reto técnico de desarrollo sobre la plataforma FI-WARE, esta
aplicación planteaba otro reto, si cabe, más grande: el de implicar al ciudadano
malagueño y que se prestara a facilitar la información. Para tal fin pensamos en
incorporar en la aplicación un canal de comunicación bidireccional por el cual
el ciudadano recibiera información de su ciudad y que. al mismo tiempo, el
ciudadano pudiera comunicarse con su administración local. Por otro lado se
usarían técnicas
de [gamificación](http://es.wikipedia.org/wiki/Ludificaci%C3%B3n) para animar y
recompensar a los ciudadanos que prestaran su colaboración.

Pues bien, esta aplicación es ya una realidad bajo la denominación de Málaga
Citysense.

## Málaga Citysense

![App City Sense](/assets/images/2014/02/app-city-sense-small.png){:
.align-right}Málaga Citysense se define como un proyecto de participación ciudadana en la
ciudad de Málaga que tiene como objetivo generar nuevas experiencias
colaborativas de los usuarios con la ciudad. Permite al usuario actuar como
sensor, colaborando activamente con la ciudad en la generación de datos abiertos
a través de la lectura de los sensores de los smartphones en los que sea
instalada la aplicación, enviándolos a la ciudad de forma anónima y segura.
También Málaga Citysense informa en tiempo real de los datos pertenecientes la
plataforma de datos abiertos de la ciudad de Málaga, permitiendo disponer de
información de interés de la ciudad.

Además del intercambio de información del cidadano con su ciudad, Málaga
Citiysense podrá interactuar con la nueva red de sensores y radio balizas que
pronto estará disponible en Málaga siendo pionera en el uso de esta tecnología
en entornos urbanos. Las radiobalizas bluetooth estarán instaladas por toda la
ciudad para ayudar a identificar y conocer puntos de interés cuando se esté
cercano a ellos. Antes de final de año la ciudad
de
[Málaga dispondrá de más de 50 radio balizas](http://www.urbanlabmalaga.es/proyecto/18/markdirect-malaga-citysense) emisoras
en los principales museos, monumentos y puntos de interés de la ciudad. No todos
los smartphones serán compatibles con esta nueva tecnología, pero el contenido
es accesible desde la aplicación Málaga Citysense con información de interés de
todos los puntos que forman parte del proyecto.

![App City Sense Land Page](/assets/images/2014/02/screen1-malaga-city-sense.png){:
.align-left}Para participar en el proyecto Málaga Citysense solo
hay
[instalar la app desde Google Play](https://play.google.com/store/apps/details?id=com.topdigital.malagacitysense).
Unicamente está disponible para dispositivos con Android a partir de la versión
4.1, debido a la interacción de la aplicación con los sensores del smartphone.
No requiere datos de carácter personal y no es necesario facilitar ningún dato
de contacto, permitiendo así la colaboración de forma anónima con la ciudad. La
aplicación se ejecuta en segunda plano haciendo envíos automatizados de la
información de los sensores. La frecuencia de envío de datos se configura en la
propia aplicación y va desde cada pocos minutos hasta una sóla vez cada hora que
es la opción por defecto. De esta forma el consumo de batería y datos del
smartphone es mínimo.

![App City Sense](/assets/images/2014/02/screen2-malaga-city-sense.png){:
.align-right} Todos los datos generados por la aplicación son anónimos, y no son accesibles
directamente por otros usuarios. El sistema Málaga Citysense analiza la
información generada por todos los usuarios que participan y genera informes de
todos los parámetros disponibles, haciéndolos visibles en la[ plataforma de dato
abierto de la ciudad](http://datosabiertos.malaga.eu/). La información estará disponible a partir de diciembre de
2014.

El ciudadano además obtiene información a través de la aplicación que proviene
de la información abierta que el Ayuntamiento de Málaga pone a disposición del
ciudadano y del público en general, Actualmente la aplicación presenta
información muy interesante para el usuario de este tipo de dispositivos,
agrupada en temáticas como accesibilidad y movilidad, cultura y turismo, empleo
y promoción empresarial, presidencia,

Por otro lado el usuario puede enviar la información que crea que pueda ser de
interés general a través de la opción qué está pasando. Los demás usuarios
podrán consultar esa información y hacerla útil en función de sus intereses.

Puedes ver un vídeo de demostración del sistema Málaga Citysense:

{% include video id="2kkJb7VpwB8" provider="youtube" %}

La aplicación Málaga Citysense ha sido desarrollada gracias a la colaboración
entre el [Área de Innovación y Nuevas Tecnologías](http://www.malaga.eu/ayto/m_ayto/portal/menu/seccion_0003/secciones/subSeccion_0006?id=454) del Ayuntamiento de Málaga,
[TopDigital](http://www.topdigital.es/) y [Telefónica I+D](http://www.tid.es/).

Finalmente, para disponer de información actualizada, el proyecto ha publicado
el portal [www.citysense.es](http://www.citysense.es/).

![www.citysense.es](/assets/images/2014/02/city-sense.png){: .align-left}
