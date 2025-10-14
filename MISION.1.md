# MISION 1
### Construyendo un Modelo de Machine Learning
*Este es el módulo, su propósito es generar un momento de revelación ("¡aha!") donde el concepto abstracto de Machine Learning se convierte en un proceso tangible, controlable y sorprendentemente simple.*

### La Misión
*Nuestra misión es construir un sistema de IA que pueda distinguir automáticamente entre un 'Producto Correcto' y un 'Producto Defectuoso'. Y lo haremos sin escribir una sola línea de código.*

***

## Actividad Guiada Paso a Paso: Su primer clasificador de imágenes

### Paso 1: Configuración del Proyecto
1.  Vamos a ir a [https://teachablemachine.withgoogle.com/train](https://teachablemachine.withgoogle.com/train)
2.  Ahora vamos a seleccionar, **proyecto de imagen**.
3.  Finalmente, deben elegir la opción **"Modelo de imagen estándar"**.

### Paso 2: Recopilación de Datos
1.  Renombren "**Clase 1**" a "**Producto Correcto**" y "**Clase 2**" a "**Producto Defectuoso**".
2.  Ahora vamos a crear nuestro propio conjunto de datos usando nuestras webcams. Para la clase '**Producto Correcto**', vamos a usar un objeto común que tengamos a mano, como una taza de café, y la sostendremos correctamente frente a la cámara. Para la clase '**Producto Defectuoso**', usaremos la misma taza, pero la sostendremos al revés, de lado o tapándola parcialmente.

> **Consejo:** Para que el modelo sea más inteligente, debemos darle variedad. Muevan un poco el objeto, cambien ligeramente la iluminación, inclínenlo. Mantengan presionado el botón de '**Mantener pulsado para grabar**' para capturar unas 100-200 imágenes para cada clase. Cuantos más ejemplos diversos le demos, mejor aprenderá.

Es importante destacar que todo este proceso de entrenamiento ocurre localmente en sus computadores; ninguna imagen se envía a la nube, garantizando la privacidad de los datos.

### Paso 3: Entrenamiento del Modelo
1.  Una vez que tengan suficientes imágenes para ambas clases, hagan clic en el botón azul "**Entrenar modelo**".
2.  En este momento, el sistema está analizando todas las imágenes que le proporcionaron. Está aprendiendo los patrones visuales —los píxeles, las formas y los colores— que definen un '**Producto Correcto**' frente a un '**Producto Defectuoso**'. Es crucial que mantengan esta pestaña del navegador abierta mientras se entrena el modelo.
3.  Si sienten curiosidad, pueden hacer clic en la pestaña '**Avanzado**' para ver gráficos del proceso de aprendizaje, pero no es necesario entenderlos para usar la herramienta. *Esto simplemente muestra que no hay magia, solo matemáticas.*

### Paso 4: Prueba e Iteración
Cuando el entrenamiento finalice (generalmente en menos de un minuto), el panel de "**Vista previa**" a la derecha se activará.

> **Actividad Práctica:** "¡Es hora de probar su creación! Sostengan su objeto frente a la webcam y observen cómo el modelo lo clasifica en tiempo real, mostrando un porcentaje de confianza para cada clase".

Ahora, intenten engañarlo. ¿Qué pasa si le muestran el objeto en una posición que no le enseñaron? ¿Qué ocurre si presentan un objeto completamente nuevo? ¿La confianza del modelo baja? Esta es la forma en que se prueba la precisión de un modelo en el mundo real.
