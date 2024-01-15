# TCP-SERVER
Implementación simple de un servidor y un cliente TCP escritos en C++. Estos programas demuestran una comunicación básica entre un servidor y un cliente usando sockets en C++.

## Estructura del Proyecto

El proyecto consiste en dos archivos principales:

1. servidor.cpp: Este archivo contiene el código para el servidor TCP. Establece un socket de servidor, espera conexiones entrantes y envía un mensaje al cliente una vez establecida la conexión.
2. cliente.cpp: Este archivo contiene el código para el cliente TCP. Conecta con el servidor y recibe el mensaje enviado por el servidor.

## Requisitos

Para ejecutar estos programas, necesitarás un sistema que soporte compilación de código C++, como puede ser un entorno Linux o Windows con MinGW o similar.
Compilación y Ejecución

Primero, clona este repositorio en tu máquina local usando:

```bash git clone [URL del repositorio]```

## Compilando el Servidor

Para compilar el servidor, navega al directorio del proyecto y ejecuta el siguiente comando en la terminal:

```bash g++ -o servidor servidor.cpp```

Esto creará un archivo ejecutable llamado servidor.
Compilando el Cliente

De manera similar, para compilar el cliente, ejecuta:

```bash g++ -o cliente cliente.cpp```

Esto creará un archivo ejecutable llamado cliente.
Ejecutando los Programas

Primero, ejecuta el servidor:

```bash ./servidor```

Luego, en una terminal diferente, ejecuta el cliente:

```bash ./cliente```
