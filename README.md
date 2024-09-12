# Generador de Contraseñas Aleatorias

## Descripción

Este script en Python genera contraseñas seguras y aleatorias de acuerdo con un tamaño especificado por el usuario. El tamaño de la contraseña puede variar entre 6 y 16 caracteres. La contraseña generada incluye letras (mayúsculas y minúsculas), números y caracteres especiales para asegurar su robustez. 

El código utiliza la librería `random` para seleccionar de manera aleatoria letras, números y caracteres especiales, garantizando que al menos uno de cada tipo esté presente en la contraseña generada.

## Funcionamiento

1. **Entrada de usuario**: El usuario debe introducir un tamaño para la contraseña. Este valor debe estar entre 6 y 16 caracteres.
2. **Validación**: Si el tamaño introducido no está en este rango, se muestra un mensaje de error.
3. **Generación de contraseña**: Si el tamaño es válido:
   - Se selecciona al menos una letra, un número y un carácter especial para garantizar la diversidad.
   - El resto de la contraseña se completa con caracteres aleatorios (letras, números y especiales).
   - Finalmente, la contraseña se desordena para asegurar la aleatoriedad total.
4. **Salida**: La contraseña generada se muestra al usuario.

## Ejemplo de uso

Si el usuario introduce un tamaño de `10`, el programa generará una contraseña como la siguiente:

```
Xg5!aBq#9R
```

En este ejemplo, la contraseña incluye letras mayúsculas y minúsculas, números y caracteres especiales, cumpliendo con los requisitos de seguridad.

## Consideraciones

- El tamaño de la contraseña debe estar entre 6 y 16 caracteres. 
- Es importante contar con caracteres especiales para aumentar la complejidad y seguridad de la contraseña.
- Este script es ideal para generar contraseñas seguras que combinen diversos tipos de caracteres.

## Utilidad en Ingeniería de Datos

***En el campo de la ingeniería de datos, la generación de contraseñas seguras es esencial cuando se trabaja con bases de datos, sistemas de autenticación y acceso a plataformas sensibles. Este código puede ser fácilmente adaptado para automatizar la creación de contraseñas en sistemas de manejo de usuarios, evitando errores manuales y asegurando un nivel adecuado de seguridad.***


