# MikroPrintr-3D.


MikroPrintr-3D es una placa controladora para impresora 3d, de bajo coste basada en el microcontrolador Arduino Mega 2560 Pro-Micro, una versión compacta del Arduino Mega 2560, manteniendo sus mismas prestaciones que la versión estándar. 

## Origen del Concepto.
La inspiración de este proyecto proviene de proyectos similares de placas controladoras de impresión 3d de bajo coste, como Sinaptec AT328, o Morpheus Board.
Sin embargo la desventaja principal de estos proyectos radica en el uso de microcontroladores, aunque de bajo coste, requieren modificaciones específicas en el firmware de Marlin, y aunque están soportadas de manera oficial, no elimina las maniobras de manipulación y tampoco significa que todas las funcionalidades estén soportadas de manera nativa o el uso de una versión limitada de otros firmwares.

Esta necesidad llevo a la creación de una solución más completa así como estándar que permita aprovechar las funcionalidades de Marlin sin requerir mayores modificaciones.

## Características de MikroPrintr-3D.

- MCU: Arduino Mega 2560 Pro-Micro. es una versión compacta del Arduino Mega 2560 y posee las mismas capacidades del Arduino Mega estándar, con la ventaja de un tamaño sumamente reducido. El Soporte de Marlin es totalmente nativo y funcional, por lo que no se requieren modificaciones especiales del Firmware.

- Soporte Estándar de Marlin, sin necesidad de modificaciones especiales para el soporte de Hardware. 
solo se requiere las modificaciones básicas de los archivos de configuración.
La placa está diseñada bajo el estándar de ramps shield.

- Fabricación de bajo coste. Tanto para la elaboración de la PCB, como la adquisición de los componentes activos y pasivos que integran la placa. 

- Tamaño Reducido. cumple con no sobrepasar los 1000 mm2 lo que es igual a un tamaño de fabricación de 100x100 mm. 

- Integración en una sola placa. El diseño sigue el estándar de Ramps 1.4 para las conexiones, de manera que no solamente existe soporte nativo, sino que además la PCB es de fácil fabricación al ser mayormente de una sola capa. 


- Soporte Estándar para pantallas LCD. La placa permite el uso de la smart reprap controller (lcd 2004) o la smart reprap full graphic controller (lcd 12864).
