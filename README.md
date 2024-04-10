# Term-metro-
Practica back end! 

Aquí tienes el desglose del código en formato :

```markdown
# Conversor de Temperatura

Este es un simple programa en Java que convierte una temperatura de grados Celsius a grados Fahrenheit y muestra ambos valores en la consola.

## Desglose del Código

1. **Definición de la Temperatura en Grados Celsius:**
   ```java
   double temperaturaEnCelsius = 30.4;
   ```

2. **Conversión de la Temperatura a Grados Fahrenheit:**
   ```java
   double temperaturaEnFahrenheit = (temperaturaEnCelsius * 1.8) + 32;
   ```

3. **Creación del Mensaje con `String.format()`:**
   ```java
   String mensaje = String.format("La temperatura de %f Celsius es equivalente a %f Fahrenheit", temperaturaEnCelsius, temperaturaEnFahrenheit);
   ```

4. **Impresión del Mensaje en la Consola:**
   ```java
   System.out.println(mensaje);
   ```

5. **Conversión de la Temperatura en Grados Fahrenheit a un Número Entero:**
   ```java
   int temperaturaEnFahrenheitEntero = (int) temperaturaEnFahrenheit;
   ```

6. **Impresión de la Temperatura en Grados Fahrenheit como un Número Entero en la Consola:**
   ```java
   System.out.println("La temperatura en Fahrenheit entera es: " + temperaturaEnFahrenheitEntero);
   ```

## Ejemplo de Uso

1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en tu entorno de desarrollo Java preferido.
3. Ejecuta el programa `Main.java`.
4. Sigue las instrucciones en la consola para ingresar la temperatura en grados Celsius.

## Contribución

Si encuentras algún error o tienes alguna sugerencia de mejora, ¡no dudes en abrir un issue o enviar un pull request!

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).
```

Este formato Markdown proporciona una explicación clara y estructurada del código, así como instrucciones para el uso del programa y detalles sobre la contribución y la licencia del proyecto.
