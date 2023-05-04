# DOJO-I (Parte 3)
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
 
  button = digitalRead(BUTTON);
  delay(1500);
  if(button == 1)
  {
    Serial.println("Extendiendo");
    semaforo(PINLEDTRES, duracion);
    duracion = duracion *2;
  }else
  {
    Serial.println("Tiempo Normal");
    duracion = 5000;
  }

  //ROJO
  semaforo(PINLEDTRES, duracion);

  //AMARILLO
  semaforo(PINLEDDOS, 3000);

  //VERDE
  semaforo(PINLEDUNO, 5000);
 
 }

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/3zi9R65tnj8-copy-of-segunda-entrega-matias-skenen-02-dojo-i/editel?sharecode=JKjHienjvPec6KL6ZyZD8ggS9sHiFMRXm5TPB4-hd_c)
## :tv: Link al video del proceso
- [video](https://www.youtube.com/watch?v=VyGjE8kx-O0)


---






