![Tutorial Recursión imagen 1](https://raw.githubusercontent.com/sergiecode/tutorial-recursividad-js/master/tutorial-recursividad1.jpg)
![Tutorial Recursión imagen 2](https://raw.githubusercontent.com/sergiecode/tutorial-recursividad-js/master/tutorial-recursividad2.jpg)
![Tutorial Recursión imagen 3](https://raw.githubusercontent.com/sergiecode/tutorial-recursividad-js/master/tutorial-recursividad3.jpg)
![Tutorial Recursión imagen 4](https://raw.githubusercontent.com/sergiecode/tutorial-recursividad-js/master/tutorial-recursividad4.jpg)

# Tutorial de recursividad en JavaScript

Este es un tutorial sobre cómo utilizar la recursividad en JavaScript. En este tutorial, explicaremos el concepto de recursividad y cómo funciona en JavaScript.

## ¿Qué es la recursividad?

La recursividad es una técnica de programación en la que una función se llama a sí misma dentro de su propio cuerpo. En otras palabras, una función recursiva es una función que se llama a sí misma para resolver un problema.

## Ejemplo de recursividad en JavaScript

Para ilustrar cómo funciona la recursividad en JavaScript, aquí hay un ejemplo de una función que cuenta desde un número dado hasta 1 utilizando recursividad:

    function contador(cuenta){
        console.log(cuenta)
        if (cuenta > 1) contador(cuenta - 1)
    }
    
    contador(10)

En este ejemplo, la función `contador` se llama a sí misma con un argumento modificado (`cuenta - 1`) hasta que la condición `cuenta > 1` ya no se cumple.

## Conclusión

La recursividad es una técnica poderosa en la programación que se utiliza para resolver problemas complejos de manera más sencilla y elegante. En JavaScript, la recursividad puede ser una herramienta muy útil en la resolución de problemas complejos y la optimización de código.

Esperamos que este tutorial te haya sido útil para comprender cómo utilizar la recursividad en JavaScript. ¡Gracias por leer!
