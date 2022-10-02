# projectIoT2022 Maceta Inteligente

## Integrantes

- Juan Antonio Rincon Torres
- Duarte Vázquez José Carlos 

## Objetivo general
Nuestro proyecto tiene como plan ser un sistema enfocado a mantener con diversos parametros cuidar una planta sin supervisón de añguna persona
esto para que las plantas o semillas tengan una humedad y temeperatura así como detectar si la luz alrededor es optima para la planta.

## Objetivos especificos
- Cuidar una planta para poder hacerlas creer lo suficiente 
- No tener que recordar diariamente regar una planta
- El sistemma mantendra la panta en optimas condiciones


## Tabla de Software Utilizado

| Id | Software           | Versión | Tipo |
|----|--------------------|---------|------|
| 1  | Visual Studio Code | 17.2    | IDE  |
| 2  | Arduino            | 2.0.0   | IDE  |

## Tabla de Hardware utilizado

| Id | Componente                       | Descripción                                                                                                                                                                                                                                                                         | Imagen | Cantidad | Costo Total |
|----|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------|-------------|
| 1  | ESP32                            | El módulo ESP32 es una solución de  Wi-Fi/Bluetooth todo en uno, integrada  y certificada que proporciona no solo  la radio inalámbrica, sino también un  procesador integrado con interfaces para  conectarse con varios periféricos.                                              |    ![image](https://user-images.githubusercontent.com/84553507/193392556-f26cdec7-c08e-45cd-923f-abc6dedb2dd7.png)| 1        | $150.00     |
| 2  | Sensor de  temperatura y humedad | El DHT22 (AM2302) es un sensor digital de  temperatura y humedad relativa de buen  rendimiento y bajo costo. Integra un sensor  capacitivo de humedad y un termistor para  medir el aire circundante, y muestra los  datos mediante una señal digital en el pin de datos.           |     ![image](https://user-images.githubusercontent.com/84553507/193392583-740a1455-afde-43b2-942b-5948ac55d759.png)| 1        | $136.00     |
| 3  | LED                              | Un diodo LED es un dispositivo que permite el  paso de corriente en un solo sentido y que al  ser polarizado emite un haz de luz                                                                                                                                                    |    ![image](https://user-images.githubusercontent.com/84553507/193392617-b7587229-1575-40fc-8a9f-79402a560e38.png)| 3        | $18.00      |
| 4  | Buzzer                           | Un buzzer o zumbador es un dispositivo que es  capaz de enviar avisos a través del sonido. Puede  ser mecánico, electromecánico o piezoeléctrico.                                                                                                                                   |  ![image](https://user-images.githubusercontent.com/84553507/193392627-54c5c576-f5fc-44fc-b7b8-ecce85c0376c.png)| 1        | $71.00      |
| 5  | Cámara                           | El sensor de imagen OV7670 cuenta con una  cámara VGA de un solo chip y procesador de  imágenes para todas las funciones.                                                                                                                                                       |    ![image](https://user-images.githubusercontent.com/84553507/193392634-ca093ec2-b972-42df-b369-b77f009030c4.png)| 1        | $135.00     |

## Epicas del proyecto
- quiero que mis plantas se mantengan en optimas condiciones
- quiero que el programa avise en cuando debo llenar el tanque de Agua
- -necesito que la maceta see encuentre en optimas condiciones para que mis semilas germinen, o plantas puedan Crecer más.

## Tabla de historias de usuario

| Id | Historias de Usuario                                                                                                                    | Prioridad | Estimación    | Como probarlo                                                     | Responsable                  |
|----|-----------------------------------------------------------------------------------------------------------------------------------------|-----------|---------------|-------------------------------------------------------------------|------------------------------|
| 1  | Quiero asegurar que la Maceta tenga las optimas condiciones de humedad y temperartura  a lo largo del día                                          | Alta      | 3 semanas     | Manteniendo regada la tierra y que la planta este en un lugar con suficiente luz solar.                               | Rincon Torres Juan Antonio  |
| 2  | Quiero que el sistema me avise durante el día si el tanque de agua necesita rellenarse o si el ambiente es muy caliente durante el Día  | Alta      | 3 semanas     | Con un Led de Algun color y un buzzer que emita las alertas en tiempo Real, dependiendo de la situación este emite alertas distintas.            | Duarte Vázquez José Carlos  |

