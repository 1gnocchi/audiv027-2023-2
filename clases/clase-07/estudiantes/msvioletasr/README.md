# Primer Trabajo Grupo 8

Integrantes: Violeta Silva, Fae Ávila y Kamila Mansilla

Link a p5.js en Fullscreen: https://editor.p5js.org/msvioletasr/full/TyKuLwPm0

Link a p5.js embed: https://editor.p5js.org/msvioletasr/sketches/TyKuLwPm0

# Materiales: 

Para crear este modelo usamos el tutorial sobre SoundClassification de learn.ml5js.org. Duplicamos y editamos el ejemplo incluido en esa página. Además, usamos el modo de audio de Teachable Machine para entrenar nuestro modelo. 

-Computador o celular

-Micrófono

-Conexión a internet

-Voz

# Referentes: 

Respecto a los referentes se tomaron en cuenta en primer lugar Shazam, ya que queríamos simular la identificación de música que logra hacer esta aplicación, y para esto queríamos usar Sound Classification, pero teniendo en cuenta la complejidad para programar algo así, decidimos tomar como referente diversos reconocimientos de voz, grabando nuestras propias voces.

Biometría de voz: Sistema de identificación
Google usa inteligencia artificial para crear un modelo de voz

# Registro:

Para empezar leímos la página del tutorial de SoundClassification, luego de lo cual decidimos usar Teachable Machine para crear un modelo entrenado propio que reemplazara el que ya estaba. 

![código original](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/b5c8885d-226f-48e7-ac02-748e6e8d4f15)

Para esto grabamos el sonido de ambiente dentro de la sala, pero para lograr más claridad salimos a un lugar más callado para grabar nuestras voces.
A continuación se pueden ver videos de este proceso:

https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/efd87560-2db0-47c3-b332-2e2a7bdc9489

https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/045816b0-e979-47bd-bef4-f68a7d60dc35

https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/3753137c-ac2e-4484-a85a-9270849a16da

Aquí se puede ver el modelo ya entrenado:

![Teachable Machine 1](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/476e8124-73e3-444c-a864-92a9c3b86cbc)

Luego de esto exportamos el modelo entrenado a un sitio web:

![Teachable Machine Exportado](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/b0e1a5cd-8ae6-4a8e-b148-1e21cdc8ab58)

Después editamos el código para que usara nuestro modelo en vez del que estaba incluido por default:

![Códico p5 js](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/a3bae044-74e1-486c-a55d-9439dba11777)

En la siguiente foto se puede ver el código funcionando e identificando nuestras voces:

![Código funcionando](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/fa6b75f8-f323-427b-844f-ed9e706eb42b)

Finalmente, cambiamos el texto que originalmente estaba en inglés por uno en español:

![Cambiando texto](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/0d40c25d-0c85-442c-bb9f-7074ef2517ea)

# Conclusión 

En conclusión al usar Teachable Machine se logró reconocer y diferenciar 5 tipos de sonido, siendo estos: Sonido de fondo, voces de Violeta, Fae, Damian y Kamila. 

No tuvimos dificultad al usar Teachable Machine, que fue un programa muy intuitivo ya que este presentaba colores, formas y textos que son amigables para el usuario que recién se va incorporando; en sí la interfaz guía al usuario a través de un paso a paso muy visual y ordenado, y el flujo dentro del sitio es simple, directo y conciso, ya que no se necesita ir a otra pestaña para poder usar esta herramienta. Además, en ningún momento tuvimos que usar código para obtener el modelo entrenado, ya que venía integrado dentro del programa.

![ui](https://github.com/msvioletasr/audiv027-2023-2/assets/142625864/422cf0c8-639a-4917-af11-05c031b7b882)


Pero por otro lado, fue complicado poder incorporar nuestro modelo entrenado a p5.js ya que al principio intentamos descargar el modelo y ponerlo como archivo, pero necesitábamos ponerlo como sitio web (html), para lo cual no encontramos instrucciones claras o simples. Pero con la orientación del profesor pudimos solucionar este problema y crear un programa funcional.
