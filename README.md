# Datos deportivos



## Especificación del sistema:
Se desea construir un sistema que permita la carga y explotación de datos deportivos. Se espera que el software desarrollado pueda estar accesible a través de múltiples dispositivos y plataformas. 


Se permitirá la importación/obtención de datos externos que se podrá realizar a través de ficheros de texto plano que se puedan obtener a través de diferentes páginas de resultados deportivos (ej football.data.co.uk) o directamente a través de casas de apuestas.


El sistema deberá almacenar datos de eventos deportivos. Estos eventos deportivos podrán tener cualquier número de participantes, aunque en su mayoría son eventos deportivos de dos contrincantes. Estos eventos se realizarán en una fecha y hora concretas y tendrán un resultado. Los participantes en estos eventos deberán ser identificados de manera univoca, aunque las distintas fuentes de datos los identifiquen de formas distintas. Dependiendo del tipo de deporte podrán tener unos datos u otros, pero todos tendrán al menos un nombre.

Se llevará un control de los sucesos que ocurran durante el evento como goles, tarjetas, expulsiones, descalificaciones, retiradas, averiás, lesiones, etc.

El almacenamiento de los datos se realizará en diversos formatos como ficheros de texto plano y bases de datos relacionales.

Los usuarios desean poder exportar cualquiera de los datos recogidos en el sistema (eventos, participantes, sucesos, etc.) a diferentes formatos comunes como CSV, JSON, XML, etc.

Se espera que el sistema facilite la gestión y el tratamiento de los datos para distintos fines.

Los usuarios podrán en cualquier momento realizar consultas sobre los datos tales como: ver los resultados de un determinado evento o filtrar resultados para un determinado participante. Los datos siempre podrán ordenarse acorde con distintos criterios establecidos por el usuario. El sistema ofrecerá un conjunto de consultas predefinidas, aunque los usuarios podrán opcionalmente configurar sus propias consultas seleccionando datos concretos de entre los almacenados en el sistema.

Los usuarios esperan obtener estadísticas sobre aspectos concretos de los eventos, los cuales podrán estar agrupados de una forma concreta (Ej., una jornada de liga, una competición completa, medias anuales, etc.).

Se podrá también obtener estadísticas sobre sucesos y participantes concretos (ej., número de tarjetas rojas y amarillas ha obtenido un determinado participante, número de partidos ganados de un participante en una competición, etc.)

Se espera contar con un interfaz fácil e intuitiva para los usuarios. 

* * *

Se pide:

1. Leer la especificación del sistema provista.
2. Identificar los requisitos funcionales y especificar cada requisito con la estructura propuesta en el estándar IEEE 830: entradas, procesamiento y salidas.
3. Identificar dos requisitos no funcionales que describan restricciones que considera necesarias para el sistema a construir

