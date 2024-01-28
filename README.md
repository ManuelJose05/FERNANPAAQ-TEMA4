# MANUAL DE USUARIO FERNANPAAQ
Practica Obligatoria Tema 3. Programa de una compañia de transportes realizado por Manuel José Liébana

## Índice
1. [Comenzando](#comenzando)
2. [Requisitos Mínimos](#requisitos)
3. [Instalación](#Instalación)
4. [Ejecucion](#ejecucion)
5. [Colaboradores](#colaboradores)


## 🔰​ Comenzando 🔰​

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

## ✔ Requisitos Mínimos ✔

_Debes tener instalado Windows 10 o Windows 11 (x64) y la siguiente versión de java
**Java SE Development Kit 19.0.2**, para descargarla acceda al siguiente enlace_

```
https://download.oracle.com/java/19/archive/jdk-19.0.2_windows-x64_bin.exe
```

Para comprobar la version de java que tenemos instalada en nuestro equipo, escribimos "cmd" en el buscador de Windows. Después de ejecutarlo, escribimos "java-version" en la terminal.

_A continuación, debes tener el siguiente path en tus variables de entorno del sistema, si no sabes mirarlo en el buscador de Windows "Editar las variables del entorno" y por último añadir la siguiente línea al path si no la tienes:_

```
C:\Program Files\Java\jdk-19.0.2\bin
```

## 🔧 Instalación 🔧

_Una vez cumplas los requisitos, debes descargarte nuestro repositorio, pulsando en el siguiente botón:_

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/22e5bcb4-96f0-4117-a4cd-fd84532fa13c)

_Ahora con el proyecto en tu equipo situandolo en el disco C: solo tendrás que descomprimirlo con permisos de administrador para pasar al siguiente apartado_

## ⚙️ Ejecución ⚙️
_Con el programa descomprimido, se va a encontrar una carpeta **POO3** y un ejecutable llamado **FERNANPAAQ**. Para acceder al programa primero debe cumplir los requisitos y después puede abrir la aplicación._

_Al abrir la aplicación se encontrará con la siguiente pantalla:_

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/076ab3cf-5ca6-463c-b9c6-0462d08bc8d9)

Encontrarás un menú con las siguientes opciones:
1. Iniciar sesión
2. Crear cuenta
3. Mostrar envío (sin iniciar sesión)
4. Salir

#### 1. Iniciar sesión
En este bloque nos vuelve a aparecer otro menú con las siguientes opciones:
  1. Administrador
  2. Conductor
  3. Usuario
  4. Salir

#### Iniciar sesión como Administrador
Te aparecerán las siguientes opciones:

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/36b9163c-0765-4ab6-a35b-c5d0c82f0492)

1. Podrás crear un envío en el que tendrás que introducir el nombre del destinatario y su dirección de destino formada por (calle / localidad / provinicia)
   
   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/c23d5c89-d32c-45fc-bb17-1dc4074e7685)

2. Te aparecerán los envíos que no tengan asignados conductores, eligirás el envío que desees y le asignarás el conductor que quieras en caso de que no este ocupado. En la nueva versión hemos añadido una función que envía un mensaje automático a Telegram indicando que se ha asignado un conductor al envío, indicando su nombre y número de teléfono
   
   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/65592973-ad79-4e69-8ae8-d33593e10cb0)

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/75814442-cd9f-4cd2-826f-217ad7b2e5f2)

3. Se mostrará en pantalla toda la información de los usuarios registrados en el programa
   
   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/279a17e0-b541-4e0b-9ff4-6b892ed606f6)

4. Se mostrará la información de todos los envíos registrados en el programa

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/44e2a1c0-340a-4290-a33e-960fe5f4b62a)

5. Se mostrará la información de todos los conductores registrados en el programa

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/71979516-c644-4047-abf4-1fa3f95ead29)

6. Podrás modificar el correo y clave del administrador

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/fa2c656f-005e-4c2f-b00f-683b01f9b131)

7. Esta opción te permite salir del menú

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/d128249e-4eb9-4307-ad7b-8c6afb424996)

#### Iniciar sesión como Transportista
Para poder iniciar sesión como Transportista, primero debes registrarte. Una vez te hayas registrado te aparecerá el siguiente menú:

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/67a71e99-207b-4e1d-aae1-745ebd5173f7)

1. Muestra al transportista la información de los envíos que tiene asignados

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/7559ea69-6fb7-48da-81ca-affdc571c709)

2. Permite al transportista cambiar el estado de un envío. Se ha añadido una función que al cambiar el estado de un envío se envía un correo al usuario indicandole el estado de su envío.

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/b3e1b439-41c1-4eb4-8506-9a2d838ca66c)

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/f7a5f466-0261-4bc4-a393-61972d3e9acc)

3. Muestra al transportista los paquetes que ha entregado
4. Permite al transportista modificar la información de su perfil
   
   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/f6e1e298-61b5-432e-936e-562db814e1e8)

5. Permite al transportista salir del menú

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/2a690cac-993c-47e9-9323-f7ce13544b10)

#### Iniciar sesión como Usuario
Para poder iniciar sesión como Usuario, primero debes registrarte. Una vez te hayas registrado te aparecerá el siguiente menú:

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/c240eb19-f5e0-47e7-8707-89fab6227ffa)

1. Muestrá la información de los envíos que van dirigidos a dicho usuario
2. Permite al usuario modificar los datos de entrega de un envío, es decir, permite modificar el lugar de destino del envío
3. Muestra toda la información del usuario
4. Permite modificar el perfil del usuario
5. Permite al usuario salir del menú

#### 2. Crear Cuenta
Al seleccionar esta opción, el progarma nos muestra el siguiente menú:

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/abbd4890-050c-4a59-8b20-4e409eee2189)

1. Nos permite registrarnos como conductor, el programa nos pedirá nuestro nombre y número de teléfono
   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/1d2c3aed-3816-44f8-abd5-39ba424fd610)

3. Nos permite registrarnos como usuarios o destinatarios, el programa nos pedíra nombre, correo, clave, dirección, localidad, provinica y número de teléfono. Ahora hemos implementado un token que enviará un correo al usuario con un código de confirmación para poder registrarse. Una vez introducido el código, el proceso de registro habrá finalizado. En caso contrario, no se registrará el usario al sistema

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/e645f10b-448c-46d1-b723-2d7c957ecae7)


![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/350bac74-22a7-4b54-b20a-fb1b344e2cd1)

5. Esta opción nos permite salir del menú

   ![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/c605b18c-c575-45b4-bbab-90b7a88c1d78)


#### 3. Mostrar envío
Este apartado nos muestra la información del envío sin la necesidad de iniciar sesión, solo necesitaremos el número de seguimiento del envío.

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/304e4aa6-81b6-4feb-b292-169b09facdba)

#### 4. Salir
La última opción es la que permite apagar el software por completo

![image](https://github.com/ManuelJose05/FERNANPAAQ-TEMA3/assets/150932456/109592f3-2187-4165-9068-e97676263695)

## 📝 Creador 📝

- Manuel José Liebana Vilches - https://github.com/ManuelJose05

