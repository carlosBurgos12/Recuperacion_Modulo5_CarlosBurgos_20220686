# Repositorio para aplicación movil ejemplo

## La aplicación móvil esta creada con React Native Expo y una Api en PHP, La misma Api del Coffeeshop

La api utilizada en el proyecto fue tomada del siguiente repositorio: https://github.com/dacasoft/coffeeshop

## Para ejecutar la aplicación sigue los siguientes pasos

* 1- Clona el repositorio
* 2- Instala las dependencias con el comando npm install
* 3- correr el programa con el comando npx expo start 
* 4- Agrega el siguiente codigo en el archivo cliente.php del API: 

![Codigo extra en el case del archivo cliente.php para el registro de un usuario](assets/code_movil.png)

## Dependencias del proyecto:
### Dependencias para el funcionamiento de la app, si creas un proyecto nuevo, deberas de instalar las siguientes dependencias en el proyecto.

* npm i @expo/vector-icons@^14.0.2
* npm i  @react-native-community/datetimepicker@8.0.1
* npm i @react-navigation/bottom-tabs@^6.5.20
* npm i @react-navigation/native@^6.1.17
* npm i @react-navigation/native-stack@^6.9.26
* npm i react-native-mask-text@^0.14.2
* npm i react-native-picker-select@^9.1.3
* npm i react-native-vector-icons@^10.1.0
* npm i react-native-screens
* npm i react-native-safe-area-context


## Si el proyecto no corre en los dispositivos ejecutar el siguiente comando:

* npx expo install expo@latest