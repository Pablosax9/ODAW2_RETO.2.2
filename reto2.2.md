
# Reto 2.2
Nombre y Apellidos: Pablo Rodríguez Crespo
URL del repositorio de gitlab:

## Preguntas:
Sigue los siguientes pasos para completar el ejercicio:

1. Utiliza la clase `.caja` para definir distintos estilos de borde: aplica un borde sólido al lado superior, un borde punteado al lado derecho, un borde discontinuo al lado inferior, y un borde doble al lado izquierdo. Además, aplica un color diferente a cada lado del `div`, asegurándote de que los colores sean claramente distinguibles entre sí. Luego, ajusta el grosor de cada lado del borde para que sean diferentes (por ejemplo, 2px para el borde superior, 4px para el derecho, 6px para el inferior y 8px para el izquierdo).
2. Utiliza la clase `.caja-atajo` para definir en una sola línea el grosor, estilo y color del borde del `div`. El borde debe ser de 4 píxeles de grosor, de color púrpura, y de estilo sólido.
3. Utiliza la clase `.caja-bordes-especificos` para aplicar bordes solamente en dos lados del `div`: en el borde superior e inferior. Define el grosor, color y estilo de manera clara (por ejemplo, borde superior de 3 píxeles sólido y color turquesa).
4. Utiliza la clase `.caja-irregular` para hacer todas las esquinas del `div` irregulares utilizando valores distintos para cada esquina: esquina superior izquierda de 40 píxeles, superior derecha de 10 píxeles, inferior derecha de 30 píxeles e inferior izquierda de 5 píxeles.
5. Utiliza la clase `.caja-esquina-especifica` para definir una esquina específica redondeada: aplica `border-radius` solo a la esquina superior izquierda con un valor de 25 píxeles.

```html
  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio de Bordes en CSS</title>
    <style>
        .caja {
            width: 300px;
            height: 200px;
            margin: 20px auto;
            padding: 20px;
        }
        .caja-atajo {
            width: 300px;
            height: 200px;
            margin: 20px auto;
            padding: 20px;
        }
        .caja-bordes-especificos {
            width: 300px;
            height: 200px;
            margin: 20px auto;
            padding: 20px;
        }
        .caja-irregular {
            width: 300px;
            height: 200px;
            margin: 20px auto;
            padding: 20px;
        }
        .caja-esquina-especifica {
            width: 300px;
            height: 200px;
            margin: 20px auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="caja">
        <p>Este es el div caja.</p>
    </div>    
    <div class="caja-atajo">
        <p>Este es el div caja-atajo.</p>
    </div>
    <div class="caja-bordes-especificos">
        <p>Este es el div caja-bordes-especificos.</p>
    </div>
    <div class="caja-irregular">
        <p>Este es el div caja-irregular.</p>
    </div>
    <div class="caja-esquina-especifica">
        <p>Este es el div caja-esquina-especifica.</p>
    </div>
</body>
</html>
```

