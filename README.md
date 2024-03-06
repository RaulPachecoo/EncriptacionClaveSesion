# Proceso de Encriptación y Desencriptación Asimétrica de una Clave de Sesión

## Paso 1: Generación de la clave secreta de sesión
   Se genera una clave secreta de sesión utilizando el algoritmo de cifrado Blowfish con una longitud de 128 bits.

   ![Imagen de ejemplo](https://files.catbox.moe/uzvkky.png)


## Paso 2: Generación del par de claves RSA
   Se genera un par de claves RSA con una longitud de 1024 bits.

   ![Imagen de ejemplo](https://files.catbox.moe/ydfjqh.png)

## Paso 3: Encriptación de la clave secreta
   Se utiliza un cifrador RSA para encriptar la clave secreta de sesión generada anteriormente.

   ![Imagen de ejemplo](https://files.catbox.moe/h8sn0r.png)

## Paso 4: Desencriptación de la clave secreta
   Se utiliza el mismo cifrador RSA para desencriptar la clave secreta previamente encriptada.

   ![Imagen de ejemplo](https://files.catbox.moe/1eaw7e.png)

## Verificación
   Finalmente, se verifica si la clave secreta original y la clave secreta desencriptada son iguales.

   ![Imagen de ejemplo](https://files.catbox.moe/qfzhb8.png)

Este código demuestra un ejemplo básico de encriptación y desencriptación utilizando cifrado asimétrico (RSA) para encriptar una clave secreta de sesión y luego volver a desencriptarla.
