**Arduino**
desarrollo de hardware

processing (software de arte y diseño)

- arduino nano 33 ble sense: 9 axis inertial sensor, sensor de humeldad, temperatura, microfoono, gestualidad, proximidad, luz, intensidad de luz

**TensorFlow Lite**
machine learning movil

**iniciar arduino**

- abrir arduino
- buscar sense
- elegir placa arduino nano 33 ble
- subir codigo con boton -> (subir)
- adentro del tab en linea 3, abajo de void setup, escribir "Serial." (debe ponerse Serial.begin)
- en begin poner velocidad "9600" (comun de arduino)
- adentro de void loop escribir "Serial.println" y escribir lo que queremos que diga


se ve:

void setup() {

Serial.begin(9600) ;

}

void loop() {

Serial.println("XXX") ;

}


**agregar librerias(bibliotecas) a arduino**
- en el tercer icono
- apds (sensor)
- tensowflow, se desarga en google

carpeta src: tiene el cosigo fuente

#include: lee el arvhico y lo usa
