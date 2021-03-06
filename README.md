# Foto 360 Low Cost

El proyecto tiene como objetivo generar un espacio para fotografiá 360º  y se conforma de:

    * Caja de luz
    * Luces
    * Base giratoria y controlador
    * Smartphone (Android) [Pendiente de actualizacion Cámara Reflex]
    * Complemento : uso de Scrcpy
   [Scrcpy (v1.15.1)](https://github.com/Genymobile/scrcpy)

Tutorial que he seguido para configurar el Scrcpy [ALSW](https://nocheprogramacion.com/Tutoriales/065_Como_ver_tu_celular_en_tu_PC.html)


### Esquema de iluminación y representación

![Caja de luz](/Fotos%20auxiliares/Captura%20de%20pantalla_2020-11-17_12-49-22.png) 


### Conexiones

![Diagrama](/Conexiones.png)

El control se conforma de:
    
    1 boton
    2 leds indicadores

Se requiere conectar el arduino al computador ya que se hace uso de comunicación serial, se configura el  Smartphone con  Scrcpy para funcionar en modo espejo y poder controlar el  Smartphone desde el computador, se ejecuta el archivo de python par que todo es listo.

EL led Amarillo funciona como indicador de estado.
    
    • Led parpadeando lento: modo espera
    • Led parpadeando rápido: modo finalizado de fotos
      
El led verde encenderá para indica cuándo la base gira y se tomara la foto.

Después de conectar lo necesario  (recuerda poner la alimentación externa para el motor) el led amarillo comenzara a parpadear lento para indica el modo espera, presiona el boto por asta que el led permanezca prendido y suelte y comenzara a girar la base  y tomar fotos de manera automática, recuerda configura el Smartphone para tomar la fotos, cuando termine de girar la base el led amarillo comenzara a parpadear de manera mas rápida para indicar que finaliso, presiona nuevamente el boto asta que pasa a parpadear de como al principio para dejar  en funcionamiento.    


### Imágen final de producto 
La idea es obtener este tipo de fotos

<img src="/Fotos%20auxiliares/DCW0018.gif" width="400" height="400" ALT="DCW0018"/>

### Contáctame
Si te gustaría saber más hacerca del proyecto o te intereso contactame:

[Ing.JuanZD](https://ingjuanzd.github.io/)

Este proyecto se desarrollo para apoyar a Decoration Croncrete and Wood y su página está en remodelación

[Decoration Concrete and Wood](https://www.instagram.com/decorationcw/)
