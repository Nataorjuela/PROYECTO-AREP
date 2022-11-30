# PROYECTO-AREP

## Autores
* **Natalia Orjuela Hernandez** - *Autor*  - *Estudiante de ingeniería de sistemas*
* **David Otalora Bernal** - *Autor*  - *Estudiante de ingeniería de sistemas*
* **Juan Esteban Cortés** - *Autor*  - *Estudiante de ingeniería de sistemas*
* **Norbey Cardona Herrera** - *Autor*  - *Estudiante de ingeniería de sistemas*
* **30/11/2022** - *Fecha* 

## Tabla de contenido

- [Descripción](#descripci%C3%B3n).
- [Arquitectura](#arquitectura).
- [Paper](#paper).
- [Servicios-Implementados-AWS](#servicios-implementados-aws).
- [Licencia](#licencia)

## Descripción 
El concepto de ciudades inteligentes no es algo nuevo, pero ha tomado fuerza en los últimos años. Hoy en día se habla de ciudades inteligentes y sostenibles. Se ha visto como la tecnología avanza a pasos agigantados, pero la sostenibilidad no ha tenido grandes avances. Aunque el acceso a la información se ha facilitado en gran medida, las personas aún no son lo suficientemente concientes de los problemas ambientales actuales y qué deberían hacer para contrarrestarlos.

Por lo mencionado anteriormente, se ha ideado una arquitectura utilizando algunos servicios de AWS y sensores para ayudar a dar un mejor uso a los residuos reciclables, notificando a los aliados(recicladores) cuáles son los contenedores más llenos para que se haga una recolección prioritaria en estos. Se llevarán registros en la base de datos que serán analizados para tener una idea del impacto que ha tenido la arquitectura implementada con respecto a meses anteriores, además de establecer puntos críticos en la ayuda de servicios de ubicación.

## Arquitectura
Esta arquitectura tendrá una platafoma que conectará a los aliados(recicladores) con los usuarios que generan los residuos aprovechables, mostrado mediante un aplicativo la ubicación de las casas a las cuales el aliado deberá recolectar estos residuos y llevarlos hasta el contenedor inteligente el cual se mostrará en el mapa y en el  cual tendrá la distancia más corta de la casa a el contenedor,los aliados estarán ubicados por localidades, distribuidos de tal forma que estén cerca a los contenedores y a los usuarios, una vez el aliado recibe estos residuos, deberá realizar la separación de estos de manera adecuada en el contenedor e informará al usuario la cantidad y la calidad de estos residuos, tambien se mostrará en tiempo real la trazabilidad de estos residuos desde la entrega hasta el punto de descargue.

![](/img/diagrama_aws.png)

## Paper

[Paper](https://github.com/Nataorjuela/PROYECTO-AREP/blob/master/PaperProyectoArep.pdf "paper")


## Servicios Implementados AWS

[AWS KINESIS](https://www.youtube.com/watch?v=V-lditk9HaM "AWS KINESIS")

[AWS DYNAMO](https://www.youtube.com/watch?v=9SrmUXgk_Og "AWS DYNAMO")

[AWS COGNITO](https://www.youtube.com/watch?v=wfD-Hyr4Nxo "AWS COGNITO")

[AWS LOCATION SERVICE](https://www.youtube.com/watch?v=jpser559otI "AWS LOCATION SERVICE")

## Licencia
[Licencia](/LICENSE.txt)
