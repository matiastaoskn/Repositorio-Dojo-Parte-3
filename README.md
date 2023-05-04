# DOJO-I (Parte 2)
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Matias Skenen


## Proyecto: Semaforo
[Proyecto 1](https://user-images.githubusercontent.com/93952537/236280630-a084f336-75c3-4943-be82-ab6381e8bf13.PNG)



## Descripción
En este parrafo deberan describir que funcion cumple su proyecto. Que solucion esta ofreciendo.

## Función principal
Esta funcion se encarga de encender y apagar los leds.

2, 3, 4, son #define que utilizamos para agregar los leds, asociandolo a pines de la placa arduino.

(Breve explicación de la función)

void loop()

{
  //ROJO
  semaforo(PINLEDTRES, 5000, 0, 0, 0, 0);
  
  titilo(PINLEDTRES,1000, 3);
  
  //AMARILLO
  semaforo(PINLEDDOS, 0, 200, 300, 1000, 3);
  titilo(PINLEDDOS,1000, 3);
  
  //VERDE
  semaforo(PINLEDUNO, 5000, 0, 0, 0, 0);

  titilo(PINLEDUNO,1000, 3);

  //AMARILLO
  semaforo(PINLEDDOS, 0, 200, 300, 1000, 3);

  titilo(PINLEDDOS,1000, 3);
}

## :robot: Link al proyecto
- [proyecto]([https://www.tinkercad.com/things/iGZplXy7dOf-primera-entrega-matias-skenen-01-dojo-i/editel?sharecode=xUV1EZMR_iX3sahqaI9wbTSUNm4nuyn2QpeAgWrUPLg](https://www.tinkercad.com/things/8wluitiqOAZ-copy-of-primera-entrega-matias-skenen-01-dojo-i/editel?sharecode=mtc3Vndk-CvX9adMNDXIhhC3Ek4rtVqth4sa7LxDHnQ))
## :tv: Link al video del proceso
- [video](https://www.youtube.com/watch?v=VyGjE8kx-O0)


---






