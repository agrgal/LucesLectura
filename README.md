# LucesLectura
Luces de lectura construidas con ESP8266

## Contenido

### 1W_Power_Version7_tiempo_apagado

En esta carpeta almaceno la versión definitiva del dispositivo: programa .ino para el IDE Arduino, carpeta **data** con la página web (el ESP8266 actúa como servidor) e instrucciones básicas.
El servidor puede encontrarse en la dirección **192.168.1.20** (puede cambiarse) o en la dirección local **milampara** (no funciona con móviles). 

En la programación hay que introducir el **SSID** de la red y la **contraseña** para que funcione. 

En el modo manual, una vez encendido las luces parpadean un instante. El sistema se inicia, tardando unos segundos en activarse. Tras ese tiempo, pueden pulsarse los botones que actuarán, indistintamente, en el lado izquierdo o derecho. 
Una pulsación aumentará la intensidad del nivel 0 al 10. Posteriores pulsaciones disminuirán del 10 al 0 y así, sucesivamente. Mejor apagar el dispositivo con el interruptor manual. 

En el modo IoT, puede usarse la página alojada en el servidor **192.168.1.20** con un navegador. Seguir las instrucciones. Apagar definitivamente con el interruptor, para ahorrar batería. 

El dispositivo carga la pila 18650 con un módulo TP4056. Mejor con el interruptor apagado. 

### Bibliotecas_tools_para_Arduino1.8.9

Bibliotecas necesarias para poder usar el dispositivo ESP8266 como servidor web asíncrono y su memoria Flash.

### Gallery

Fotografías del dispositivo acabado e instalado.

### PCB

Información sobre el esquemático y el diseño de la placa PCB (easyEDA). Puede mejorarse en el futuro usando quizás otro tipo de conectores. 

### Piezas_3D

El dispositivo se forma con tres piezas que se han impreso en PLA. Conviene que no le den a las piezas la luz directa del sol durante mucho tiempo, ya que pueden perder su forma. 
Una pieza es la base, que se monta sobre la pared con dos tacos y dos tornillos, donde encaja la carcasa, deslizándola hacia la parte inferior. El hueco rectangular que dejan permite 
la colocación del módulo TP4056 para permitir la carga. Por último, cubrimos con la tapa. 

[Ver trabajo en ONSHAPE] (https://cad.onshape.com/documents/27e3b7ccac053051369a8975/w/175055362edb9ac8fa9f8f1a/e/0181f3b4124862bc1465c52c?renderMode=0&uiState=645d2dc07caf9401d7ae401f)

### Versiones_previas

Versiones y desarrollo anterior, paso a paso. 

### Pintura

Las piezas 3D se han pintado usando una imprimación para plásticos en spray, y una pintura acrílica imitando a la madera y aplicada con paletina de unos 4cm. Una sola capa. Dejar secar un día completo. 
