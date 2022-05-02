# Memoria Cache

La caché es la memoria temporal denominada oficialmente "memoria caché del CPU". Esta función de tu computadora, alojada en un chip, te permite acceder a cierta información más rápidamente que si lo hicieras desde el disco duro. Los datos de los programas y archivos que más usas se almacenan en esta memoria temporal, que también es la memoria más rápida de la computadora.

## ¿Cómo afecta la memoria caché al rendimiento? 
Ya sabemos que esta memoria puede acceder a datos de uso frecuente con máxima eficiencia. Sin embargo, decidir qué datos se almacenan es todo un arte.

La computadora espera a que utilices los datos, luego cataloga una copia de los datos a los que accedes una y otra vez en la biblioteca especial de memoria “caché”. Este proceso se denomina "almacenamiento en caché". Cuanto más uses algo, es más probable que una copia termine en tu caché.

## Caché vs. RAM

Cuando tu computadora necesita acceder a los datos rápidamente, pero no puede encontrarlos en la caché, los buscará dentro de la memoria de acceso aleatorio (RAM). La RAM es el tipo principal de almacenamiento de datos informáticos que guarda la información y los procesos de los programas. Está más lejos del CPU que la memoria caché y no es tan rápida; la caché es en realidad 100 veces más rápida que la RAM estándar.

Si la caché es tan rápida, ¿por qué no se almacenan allí todos los datos? El almacenamiento en la caché es limitado y muy costoso para su espacio, por lo que tiene sentido solo mantener allí los datos a los se accede con mayor frecuencia y dejar todo lo demás en la RAM.

## ¿Qué pasa si la caché se llena?

Aunque el almacenamiento en caché puede ayudar a acelerar una computadora, si esta memoria alcanza su límite de almacenamiento, puede ralentizarla. Es importante ejecutar tareas de mantenimiento porque algunas de estas funciones eliminarán de la memoria los archivos temporales que tu computadora probablemente ya no necesite. Lo mismo aplica para el navegador de Internet, que almacena incluso más datos en la caché y puede llegar a atascar tu PC. Si aún no has borrado el historial de tu navegador o los archivos temporales de Internet, ¡hazlo ya!

## Aspectos que influyen en el desempeño del caché

1. **Mayor caché** &rarr; mejor funcionamiento &rarr; Mayor precio
2. **Tamaño de la línea del caché** &rarr; un caché de 16 KB puede dividirse en:
   - 1k líneas de 16 bytes
   - 2k líneas de 8 bytes
3. **Organización del caché** &rarr; Como sabe que palabras de memoria tiene en distintos caches un momento dado
4. **Distintos caches**:
   - Caché unificado = un solo caché
   - Caches divididos = diseño Harvard &rarr; Mark III
5. **Número de caches**:
   - Primario &rarr; Chip CPU
   - Secundario &rarr; Fuera del chip
   - Terciario &rarr; alejado del chip

## Explicación de los niveles de caché


1. **Caché de nivel 1**

El nivel 1 (L1) es la caché integrada en tu CPU. Evalúa los datos a los que acaba de acceder tu CPU y determina a cuáles es probable que vuelvas a acceder pronto. Así que esos datos se van al caché L1 porque allí es el primer lugar donde tu computadora revisará la próxima vez que necesites esta información. Este es el más rápido de los niveles de caché.

2. **Caché de nivel 2**

Al nivel 2 (L2) también se le conoce como "caché secundaria". Es el lugar al que acude tu computadora cuando no puede encontrar los datos (o tiene un “fallo”) después de buscar en la caché L1. El nivel 2 suele estar en una tarjeta de memoria muy cerca del procesador.

3. **Caché de nivel 3**

También encontrarás memoria caché en el disco duro. Esto se denomina "caché de disco". Es el más lento de todos los niveles de caché, ya que toma los datos del disco duro para colocarlos en la RAM. La memoria RAM también puede almacenar información para los accesorios y periféricos de la computadora, como la unidad de DVD, en una “caché de periféricos”.

4. **Caché de GPU**

La obtención de los datos necesarios para renderizar gráficos debe suceder muy rápido, por lo que es lógico que se utilice un sistema de caché. Si los gráficos de tu computadora están integrados, serán manejados por una unidad de procesamiento gráfico (GPU) que se combina con la CPU en un chip. Ambas funciones trabajan con los mismos recursos, por lo que la caché de la GPU también es limitada.

Una tarjeta gráfica dedicada e independiente (también llamada "gráficos discretos") estará separada de la CPU y también vendrá con su propia memoria caché. Las computadoras gaming más rápidas tendrán una tarjeta gráfica dedicada con almacenes de caché adecuados integrados en la GPU para evitar retrasos o stuttering (tartamudeos) con juegos intensos.