# Nek Bolso inteligente

_Nek es un bolso para medir el pulso cardico y la temperatura de las personas mayores._

## Objetivo 🚀

_Lograr optener un buen producto que realice las acciones que nos propusimos para las personas mayores._

Mira **Deployment** para conocer como desplegar el proyecto.


## Visión 📋

_Este proyecto tiene como finalidad medir el pulso de las personas mayores por medio de un bolso inteligente mostrandolo en un display de LCD, medir la temperatura y ambiente en el que la persona se encuentra, también el bolso podrá tomar fotografias y video en tiempo real para saber donde se encuentra la persona que esta usando el bolso._

## Sprint 1


## Epicas 
| ID |  Actividad | Prioridad | 
| :---         |     :---:      |          ---: |
| 1.0     |  Integrar el sensor de pulso cardiaco al bolso     |         Debería|
| 1.1     |  Integrar el display de LCD para mostrar el pulso de las personas    |         Debería|


## Material utilizado 🔧

| Nombre |  Imagen | Descripción | Cantidad | 
| :---         |     :---:      |          ---: |       ---: |
| Visor LCD   | ![image](https://user-images.githubusercontent.com/80369054/173699668-76e4703f-cbea-4009-903c-d10d63ba1bb5.png)|Un LCD (liquid crystal display) una pantalla delgada y plana formada por un número de píxeles en color o monocromos colocados delante de una fuente de luz o reflectora.    |       1 |
| Sensor de pulso cardiaco   | ![image](https://user-images.githubusercontent.com/80369054/173700441-4970d2a4-3b3c-45f0-ac1f-100021e835c4.png)     | Sera utilizado para medir el pulso de las personas para obtener la frecuencia cardíaca, en tiempo real, en el proyecto.    |      1 |
| Placa de pruebas     | ![image](https://user-images.githubusercontent.com/80369054/173700581-fb88b3ca-80a7-4a99-91e2-e18a7c9db920.png)| Se usará para realizar el circuito.     |       1 |
| Cables jumper    | ![image](https://user-images.githubusercontent.com/80369054/173700664-17c86f8f-e01b-4c69-9a0e-3bbe1ef021c2.png)     |Son parte del circuito     |      1 |
| Arduino Uno    | ![image](https://user-images.githubusercontent.com/80369054/173700791-49503c38-92bf-4e2d-a558-9062e92ce779.png)     |Son parte del circuito   |     1 |
| Cable     | ![image](https://user-images.githubusercontent.com/80369054/173700866-c17b8071-de85-4803-a0e1-17754eaf6605.png)     | Es parye del circuito    |       1 |
| Bolso   | ![image](https://user-images.githubusercontent.com/72764179/185469042-34b9f094-117c-4fea-9a1a-f89334c70f25.png) | Prototipo inicial para el proyecto    |  1 |
| LED   | ![image](https://user-images.githubusercontent.com/80369054/173701052-c63d6cc8-c752-4067-a071-b3914c7f7969.png)      | Sera parte del circuito para mostrar las pulsaciones    |       1 |

## Tareas⚙️

1.- Sensor de pulso: El bolso inteligente medirá el pulso de las personas, mostrando en el programa de arduino las pulsaciones por medio de una gráfica.

2.- Display LCD: Mostrará los datos del pulso en pantalla.

## Tablero

![image](https://user-images.githubusercontent.com/80369054/184989623-42c3470e-7b0e-45d0-a085-074c7a5bd66b.png)

## Diagrama inicial⌨️

![image](https://user-images.githubusercontent.com/72764179/185483262-bff0ac7d-d159-4132-831f-b462a063c43e.png)

## Prototipo 📦

![image](https://user-images.githubusercontent.com/72764179/185483914-26e1b2cf-6f4a-4cef-89c2-ee906fcf65c6.png)


## Sprint 2

## Epicas 
| ID |  Actividad | Prioridad | 
| :---         |     :---:      |          ---: |
| 2.0     |  Integrar el sensor de temperatura y humedad   |         Debería|
| 2.1     |  Estructura de base de datos   |         Debería|
| 2.2     |  Estructura y visualizacion de datos en la aplicacion |         Debería|
| 2.3    | Mejora del prototipo|         Debería|

## Material
![image](https://user-images.githubusercontent.com/80369054/184964036-1c231fb5-4c4f-42a3-ae6c-e9d9dacc022e.png)

## Tareas⚙️
1.- Sensor de temperatura y humedad: El usuario podra medir la temperatura del ambiente en el que se encuentra junto con la humedad y podra visualizarla en su telefono desde la aplicación.

2.- Crear la estructura de la BD para almacenamiento de datos.

## Tablero

![image](https://user-images.githubusercontent.com/80369054/184989975-e065a626-755b-47bb-8006-f198432564e7.png)


## Sprint 3

## Epicas 
| ID |  Actividad | Prioridad | 
| :---         |     :---:      |          ---: |
| 3.0     |  Integrar la ESP-CAM para grabar videos y tomar fotos en tiempo real |         Debería|
| 3.1     |  Implementar la pantalla EW162B0YMY   |         Debería|
| 3.2     | Almacenamiento de datos en la SD |         Debería|
| 3.3   | Pruebas para la funcionalidad del sensor de pulso|         Debería|

## Material
![image](https://user-images.githubusercontent.com/80369054/184966722-a605ce39-3a29-4ebb-abb6-dbec981accaf.png)

## Tareas⚙️
1.- Integrar la placa ESPCAM para tomar fotos en tiempo real y almacenar las fotografias en una SD

2.- Realizar pruebas finales de la funcionalidad del prototipo

## Tablero
![image](https://user-images.githubusercontent.com/80369054/184990114-f3fa7de2-5583-4775-98f3-ae6e5290f857.png)


## Esquema
![image](https://user-images.githubusercontent.com/80369054/184967842-c929c87f-40c5-4fea-9880-eccaef6e3754.png)

## Dibujo del prototipo final
![WhatsApp Image 2022-08-17 at 3 10 23 PM](https://user-images.githubusercontent.com/72764179/185233863-0b5e3d03-698f-4f4d-ad80-2e1df4363d59.jpeg)

##Estructura de base de datos para el sensor de pulso
![image](https://user-images.githubusercontent.com/80369054/184977379-2ccf2105-8c30-4788-ae5e-eb6fbb03e5eb.png)

---
⌨️ con ❤️ por Equipo 4 😊
