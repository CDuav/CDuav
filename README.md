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

## Tabla de historias de usuario

| Id | Historias de Usuario                                                                                                                    | Prioridad | Estimación    | Como probarlo                                                     | Responsable                  |
|----|-----------------------------------------------------------------------------------------------------------------------------------------|-----------|---------------|-------------------------------------------------------------------|------------------------------|
| 1  | Quiero poder conocer el ambiente en el que se encuentra mi mascota  en caso de que se pierda.                                           | Alta      | 3 semanas     | Aumentando temperatura y humedad                                  | Erik Daniel Mendez Enriquez  |
| 2  | Quiero poder saber si mi mascota se encuentra en peligro de intoxicación o si  el ambiente que lo rodea hay peligro de una fuga de gas. | Alta      | 2 a 3 semanas | Usando un gas de manera controlada cerca del sensor               | Oscar Iván Pérez Mejía       |
| 3  | Quiero conocer si mi mascota corre el riesgo de sufrir algún daño por  quemadura mientras no me encuentro con él.                       | Alta      | 3 semanas     | Exponiendo el proyecto a una llama controlada                     | Alyne Elizabeth Rojas Gloria |
| 4  | En caso de perder a mi mascota quiero poder dar con el en tiempo  real para ir a buscarlo y alcanzarlo.                                 | Alta      | 3 semanas     | Desarrollando una aplicación que nos permita probar el sensor GPS | Andrea Trujillo Azpeitia     |
