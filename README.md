# Nek Bolso inteligente

_Nek es un bolso para medir el pulso cardico y la temperatura de las personas mayores._

## Materia: Desarrollo para dispositivos inteligentes 
## Docente: Anastacio Rodríguez García
## Integrantes
### Sandoval Rodríguez Lendy Joanna
### Rosas Castillo Gabriela 

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
| Nombre |  Imagen | Descripción | Cantidad | 
| :---         |     :---:      |          ---: |       ---: |
| Visor LCD   | ![image](https://user-images.githubusercontent.com/80369054/173699668-76e4703f-cbea-4009-903c-d10d63ba1bb5.png)|Un LCD (liquid crystal display) una pantalla delgada y plana formada por un número de píxeles en color o monocromos colocados delante de una fuente de luz o reflectora.    |       1 |
| Sensor de pulso cardiaco   | ![image](https://user-images.githubusercontent.com/80369054/173700441-4970d2a4-3b3c-45f0-ac1f-100021e835c4.png)     | Sera utilizado para medir el pulso de las personas para obtener la frecuencia cardíaca, en tiempo real, en el proyecto.    |      1 |
| Placa de pruebas     | ![image](https://user-images.githubusercontent.com/80369054/173700581-fb88b3ca-80a7-4a99-91e2-e18a7c9db920.png)| Se usará para realizar el circuito.     |       1 |
| Cables jumper    | ![image](https://user-images.githubusercontent.com/80369054/173700664-17c86f8f-e01b-4c69-9a0e-3bbe1ef021c2.png)     |Son parte del circuito     |      1 |
| Sensor de temperatura y humedad     | ![image](https://user-images.githubusercontent.com/72764179/185485095-722e5099-6165-40c8-973a-73612d40daca.png)    | Dispositivo utilizado en espacios de interior a fin de monitorear la temperatura y humedad   |     1 |
| Bolso   | ![image](https://user-images.githubusercontent.com/72764179/185469042-34b9f094-117c-4fea-9a1a-f89334c70f25.png) | Prototipo inicial para el proyecto    |  1 |
| Placa ESP32   | ![image](https://user-images.githubusercontent.com/72764179/185485204-4a764b66-4d85-46f2-8cfc-02a8bf6624c4.png) | Chip con tecnología Wi-Fi y Bluetooth de modo dual integrada    |       1 |
| Cable de datos   | ![image](https://user-images.githubusercontent.com/72764179/185485764-8e547675-e2dd-4370-90e5-04d5838557b4.png) | Es un cable que permite la transmisión de datos de un punto a otro dentro entre ordenadores  |       1 |
| Tela   | ![image](https://user-images.githubusercontent.com/72764179/185485470-2e465117-dded-438c-b5eb-6d3bb1235292.png) | Tejido hecho con fibras textiles, que se utiliza para la confección de prendas, forros de diversos objetos    |       1 |

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
| Nombre |  Imagen | Descripción | Cantidad | 
| :---         |     :---:      |          ---: |       ---: |
| Display de LCD   | ![image](https://user-images.githubusercontent.com/72764179/185487602-a56f2c13-4814-444e-9f8f-9d501f8f8fb9.png) |Un LCD (liquid crystal display) una pantalla delgada y plana formada por un número de píxeles en color o monocromos colocados delante de una fuente de luz o reflectora.    |       1 |
| Sensor de pulso cardiaco   | ![image](https://user-images.githubusercontent.com/80369054/173700441-4970d2a4-3b3c-45f0-ac1f-100021e835c4.png)     | Sera utilizado para medir el pulso de las personas para obtener la frecuencia cardíaca, en tiempo real, en el proyecto.    |      1 |
| Placa de pruebas     | ![image](https://user-images.githubusercontent.com/80369054/173700581-fb88b3ca-80a7-4a99-91e2-e18a7c9db920.png)| Se usará para realizar el circuito.     |       1 |
| Cables jumper    | ![image](https://user-images.githubusercontent.com/80369054/173700664-17c86f8f-e01b-4c69-9a0e-3bbe1ef021c2.png)     |Son parte del circuito     |      1 |
| Sensor de temperatura y humedad     | ![image](https://user-images.githubusercontent.com/72764179/185485095-722e5099-6165-40c8-973a-73612d40daca.png)    | Dispositivo utilizado en espacios de interior a fin de monitorear la temperatura y humedad   |     1 |
| Bolso   | ![image](https://user-images.githubusercontent.com/72764179/185469042-34b9f094-117c-4fea-9a1a-f89334c70f25.png) | Prototipo inicial para el proyecto    |  1 |
| Placa ESP32   | ![image](https://user-images.githubusercontent.com/72764179/185485204-4a764b66-4d85-46f2-8cfc-02a8bf6624c4.png) | Chip con tecnología Wi-Fi y Bluetooth de modo dual integrada    |       1 |
| Cable de datos   | ![image](https://user-images.githubusercontent.com/72764179/185485764-8e547675-e2dd-4370-90e5-04d5838557b4.png) | Es un cable que permite la transmisión de datos de un punto a otro dentro entre ordenadores  |       1 |
| Tela   | ![image](https://user-images.githubusercontent.com/72764179/185485470-2e465117-dded-438c-b5eb-6d3bb1235292.png) | Tejido hecho con fibras textiles, que se utiliza para la confección de prendas, forros de diversos objetos    |       1 |
| Botón   | ![image](https://user-images.githubusercontent.com/72764179/185487057-2bc9e1fc-aec5-476a-a517-977dc439a9b3.png) | Un botón puede conectarse a cualquier pin (digital o analógico, este servirá para controlar la visualización de los datos del pulso cardíaco)  |       1 |
| ESP32-CAM   | ![image](https://user-images.githubusercontent.com/72764179/185487369-8f281d40-584e-40d5-9843-a08709e63e75.png) | Es una tarjeta de desarrollo que esta basada en microcontroladores como el ESP32, teniendo una tarjeta incorporada, una cámara y un led de flash, permite hacer streaming de video, tomar fotos    |       1 |

## Tareas⚙️
1.- Integrar la placa ESPCAM para tomar fotos en tiempo real y almacenar las fotografias en una SD

2.- Realizar pruebas finales de la funcionalidad del prototipo

## Tablero
![image](https://user-images.githubusercontent.com/80369054/184990114-f3fa7de2-5583-4775-98f3-ae6e5290f857.png)


## Esquema de sensor de temperatura y humedad
![image](https://user-images.githubusercontent.com/80369054/185491058-a52f0d3c-6b5a-4fc3-b1b6-b88996c42cf1.png)

## Esquema de sensor de Pulso Cardiaco
![image](https://user-images.githubusercontent.com/80369054/184967842-c929c87f-40c5-4fea-9880-eccaef6e3754.png)

## Dibujo del prototipo final
![WhatsApp Image 2022-08-17 at 3 10 23 PM](https://user-images.githubusercontent.com/72764179/185233863-0b5e3d03-698f-4f4d-ad80-2e1df4363d59.jpeg)

##Resultado final 
![image](https://user-images.githubusercontent.com/80369054/185492206-fa17c7dc-ace4-4b3e-a5cc-a96b06de3d6f.png)

##Video

---
⌨️ con ❤️ por Equipo 4 😊
