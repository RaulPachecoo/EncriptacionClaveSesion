# Proceso de Encriptación y Desencriptación Asimétrica

## Paso 1: Generación de la clave secreta de sesión
Se genera una clave secreta de sesión utilizando el algoritmo de cifrado Blowfish con una longitud de 128 bits.

## Paso 2: Generación del par de claves RSA
Se genera un par de claves RSA con una longitud de 1024 bits.

## Paso 3: Encriptación de la clave secreta
Se utiliza un cifrador RSA para encriptar la clave secreta de sesión generada anteriormente.

## Paso 4: Desencriptación de la clave secreta
Se utiliza el mismo cifrador RSA para desencriptar la clave secreta previamente encriptada.

## Verificación
Finalmente, se verifica si la clave secreta original y la clave secreta desencriptada son iguales.

Este código demuestra un ejemplo básico de encriptación y desencriptación utilizando cifrado asimétrico (RSA) para encriptar una clave secreta de sesión y luego volver a desencriptarla.
