# Tecnologías de memoria : SRAM y DRAM

![](https://http2.mlstatic.com/D_NQ_NP_824324-CBT46029925553_052021-O.jpg)

## RAM estática (SRAM)

SRAM son las siglas de la voz inglesa Static Random Access Memory, que significa memoria estática de acceso aleatorio (o RAM estática), para denominar a un tipo de tecnología de memoria RAM basada en semiconductores, capaz de mantener los datos, mientras siga alimentada, sin necesidad de circuito de refresco. Este concepto surge en oposición al de memoria DRAM (RAM dinámica), con la que se denomina al tipo de tecnología RAM basada en condensadores, que sí necesita refresco dinámico de sus cargas.

Existen dos tipos: volátiles y no volátiles, cuya diferencia estriba en si los datos permanecen o se volatilizan en ausencia de alimentación eléctrica.

Se construye internamente empleando circuitos tipo **LATCH S-R** (FLIP-FLOP-D básicos).

Estas memorias tienen la propiedad de que su contenido se conserva en tanto se sigue alimentando de corriente al circuito, ya sea segundos, minutos, horas y hasta días.

Las RAM estáticas son muy rápidas con un tiempo de acceso de unos cuantos nanosegundos y por esta razón son populares como memoria cache de segundo nivel.

### Diseño

Estas memorias son de acceso aleatorio, lo que significa que las posiciones en la memoria pueden ser escritas o leídas en cualquier orden, independientemente de cual fuera la última posición de memoria accedida. Cada bit en una SRAM se almacena en cuatro transistores, que forman un biestable. Este circuito biestable tiene dos estados estables, utilizados para almacenar (representar) un 0 o un 1. Se utilizan otros dos transistores adicionales para controlar el acceso al biestable durante las operaciones de lectura y escritura. Una SRAM típica utilizará seis MOSFET para almacenar cada bit. Adicionalmente, se puede encontrar otros tipos de SRAM, que utilizan ocho, diez, o más transistores por bit.2​3​4​ Esto es utilizado para implementar más de un puerto de lectura o escritura en determinados tipos de memoria de video.

Un menor número de transistores por celda, hará posible reducir el tamaño de esta, reduciendo el coste por bit en la fabricación, al poder implementar más celdas en una misma oblea de silicio.

Es posible fabricar celdas que utilicen menos de seis transistores, pero en los casos de tres transistores5​6​ o uno solo se estaría hablando de memoria DRAM, no SRAM.

El acceso a la celda es controlado por un bus de control (WL en la figura), que controla los dos transistores de acceso M5 y M6, quienes controlan si la celda debe ser conectada a los buses BL y BL. Ambos son utilizados para transmitir datos tanto para las operaciones de lectura como las de escritura, y aunque no es estrictamente necesario disponer de ambos buses, se suelen implementar para mejorar los márgenes de ruido.

A diferencia de la DRAM, en la cual la señal de la línea de salida se conecta a un capacitador, y este es el que hace oscilar la señal durante las operaciones de lectura, en las celdas SRAM son los propios biestables los que hacen oscilar dicha señal, mientras que la estructura simétrica permite detectar pequeñas variaciones de voltaje con mayor precisión. Otra ventaja de las memorias SRAM frente a DRAM, es que aceptan recibir todos los bits de dirección al mismo tiempo.

## RAM dinámicas (DRAM)

La memoria dinámica de acceso aleatorio o DRAM (del inglés dynamic random-access memory) es un tipo de tecnología de memoria de acceso aleatorio (RAM) basada en condensadores, los cuales pierden su carga progresivamente, necesitando de un circuito dinámico de refresco que, cada cierto período, revisa dicha carga y la repone en un ciclo de refresco. En oposición a este concepto surge el de SRAM (RAM estática), con la que se denomina al tipo de tecnología RAM basada en semiconductores que, mientras siga alimentada, no necesita refresco.

Se usa principalmente como módulos de memoria principal de ordenadores y otros dispositivos. Su principal ventaja es la posibilidad de construir memorias con una gran densidad de posiciones y que todavía funcionen a una velocidad alta: en la actualidad se fabrican integrados con millones de posiciones y velocidades de acceso medidos en millones de bit por segundo.

Como el resto de tipos de RAM, es volátil por lo que si se interrumpe la alimentación eléctrica la información almacenada se pierde. Fue inventada a finales de los sesenta y es una de las memorias más usadas en la actualidad.

## Tipos de chips de RAM

### DRAMFPM (modo de página rápida)

(Fast Page Mode).
Es el tipo mas antiguo y menos complejo de RAM. Todavía se usa en muchas PC de hoy en día

### DRAM EDO (Salida de datos extendida)

(Extended data output)
Es más rápida que la DRAM FPM ya que se permite utilizar una segunda referencia a la memoria antes de que la anterior se haya completado.

### SDRAM (DRAM Sincrónica)

Es un híbrido de RAM estática y dinámica controlado por un solo reloj sincrónico libera ráfagas de datos a velocidades muy altas (hasta 133 MHZ) lo que proporciona mas datos a la CPU.
