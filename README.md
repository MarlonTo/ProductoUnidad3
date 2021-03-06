# Producto_Unidad3
# Informe 
##  Implementación de  2 circuitos combinancionales  empleando Python y simulados en una Raspberry Pi.


## 1.PLANTEAMIENTO DEL PROBLEMA

Implementanar 2 circuitos combinancionales con la programacion orientada a objetos (POO) en la plataforma create.withcode.uk



## 2.OBJETIVOS

### General:

Diseñar 2  programas en la Raspberry pi por medio del leguaje de programacióm python

### Específicos:

> Explorar las bibliotecas que nos ofrece pyhon para poder controlar los puertos de la GPIO de la raspberry pi
 
> Comprender la sintaxis y la semántica de la programación orientada a objetos de Python.




## 3.ESTADO DEL ARTE

### Tema: Sistema de identificación y conteo de personas utilizando rambuesa pi

Investigadores: Tussanai Prthonratt, Natchaphon Brapanonte y Wisatute Gunjarueg

Año:  2016

El trabajo se enfoca en un implementación de OpenCV en un incrustado sistema me gusta Raspberry Pi para crear una mini estación independiente para contar La característica clave de AU-PiCC (Assumption University's Contador de clientes de frambuesa Pi) es contar un número de personas interesadas en el producto de destino en un área predefinida a lo largo con una simple identificación facial para evitar contar duplicados. Los resultados experimentales muestran que esta frambuesa basada en Pi sistema se puede utilizar como una simple estación de contador de personas. 

Lugar:Da Nang, Vietnam

### Tema: SMARISA: un anillo inteligente basado en Raspberry Pi para la seguridad de las mujeres con IoT

Investigadores: Navya R. Sogi, Priya Chatterjee, U. Nethra y V. Suma

Año:2018

Todos los días, todas las mujeres, niñas, madres y mujeres de todos los ámbitos de la vida luchan por estar a salvo y protegerse de la mirada errante de los hombres horriblemente insensibles que abusan, asaltan y violan la dignidad de las mujeres a diario. Las calles, el transporte público, los lugares públicos en particular se han convertido en dominio de los cazadores. Debido a estas atrocidades a las que están sometidas las mujeres en el escenario actual, se propone un wearable de seguridad inteligente para mujeres basado en Internet of Things. Se implementa en forma de anillo inteligente (SMARISA) y se compone de Raspberry Pi Zero, cámara Raspberry Pi, timbre y botón para activar los servicios. Este dispositivo es extremadamente portátil y puede ser activado por la víctima al ser asaltada con solo hacer clic en un botón que buscará su ubicación actual y también capturará la imagen del atacante a través de la cámara Raspberry Pi. La ubicación y el enlace de la imagen capturada se enviarán a los números de contacto de emergencia predefinidos o a la policía a través del teléfono inteligente de la víctima, lo que evitará el uso de dispositivos / módulos de hardware adicionales y hará que el dispositivo sea compacto.

Lugar: Coimbatore, India
 
## 4.MARCO TEÓRICO



 
### Python
 
Python fue creado a finales de los ochenta por Guido van Rossum en el Centro para las Matemáticas y la Informática (CWI, Centrum Wiskunde & Informatica), en los Países Bajos, como un sucesor del lenguaje de programación ABC, capaz de manejar excepciones e interactuar con el sistema operativo Amoeba. El nombre del lenguaje proviene de la afición de un grupo británico de comediantes conocidos como Monty Python. (Python, n.d.)
Python es un lenguaje de programación interpretado el cual hace hincapié en la legibilidad de su código. Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida, programación funcional.
Este lenguaje está administrado por la Python Software Foundation. es una organización sin fines de lucro creada el 6 de marzo de 2001 dedicada al lenguaje de programación Python. Es responsable de varios procesos dentro de la comunidad, como el desarrollo de Python, la administración de los derechos intelectuales y de obtener fondos.(Operadores Python ➞ Explicamos Todos Los Operadores + Ejemplos Reales, n.d.)
 
  ![](IMG/20151016121002_python.jpg)


 
Los pasos para comenzar con Python en la programación de una interfaz de usuario no son terriblemente complejos, pero requiere que el usuario empiece a tomar algunas decisiones. Por su naturaleza como un lenguaje de programación de propósito general con intérpretes disponibles en todos los sistemas operativos comunes, Python tiene que ser bastante agnóstico en cuanto a las opciones que presenta para crear interfaces gráficas de usuario.
Afortunadamente, hay muchas opciones disponibles para los programadores que buscan crear una manera fácil para que los usuarios interactúen con sus programas. Existen enlaces para varios frameworks de interfaz de usuario en una variedad de plataformas, incluidas las nativas Windows, Mac y Linux, y muchas que funcionan en las tres.
En este punto, tiene que evaluar bien el hecho de necesitar una interfaz gráfica. Al momento de desarrollar una aplicación, también debe considerar una interfaz web, especialmente si cree que los usuarios puedan querer alojar su aplicación de forma remota, y proyectos como Django, Flask o Pyramid hacen que esto sea sencillo. Incluso puede usar una librería como pywebview para colocar una capa delgada alrededor de una aplicación web en una ventana GUI más nativa.

### Programación orientada a objetos

La Programación Orientada a Objetos (POO u OOP según sus siglas en inglés) es un paradigma de programación que usa objetos y sus interacciones para diseñar aplicaciones y programas de computadora. Está basado en varias técnicas, incluyendo herencia, modularidad, polimorfismo, y encapsulamiento. Su uso se popularizó a principios de la década de 1990. Actualmente son muchos los lenguajes de programación que soportan la orientación a objetos.

#### Clase

Definiciones de las propiedades y comportamiento de un tipo de objeto concreto. La instanciación es la lectura de estas definiciones y la creación de un objeto a partir de ellas.

#### Objeto

Instancia de una clase. Entidad provista de un conjunto de propiedades o atributos (datos) y de comportamiento o funcionalidad (métodos), los mismos que consecuentemente reaccionan a eventos. Se corresponden con los objetos reales del mundo que nos rodea, o con objetos internos del sistema (del programa). Es una instancia a una clase.

#### Método

Algoritmo asociado a un objeto (o a una clase de objetos), cuya ejecución se desencadena tras la recepción de un “mensaje”. Desde el punto de vista del comportamiento, es lo que el objeto puede hacer. Un método puede producir un cambio en las propiedades del objeto, o la generación de un “evento” con un nuevo mensaje para otro objeto del sistema.

#### Atributos

Características que tiene la clase

#### Componentes de un objeto

Atributos, identidad, relaciones y métodos.
 
#### Identificación de un objeto

Un objeto se representa por medio de una tabla o entidad que esté compuesta por sus atributos y funciones correspondientes.


![](IMG/oop.png)
 
### RASPBERRY PI
 
Raspberry PI es una placa computadora (SBC) o Pc de placa única, de bajo precio, se podría expresar que es un ordenador de tamaño reducido, del orden de una tarjeta de crédito, desarrollado en el Reino Unido por la Fundación Raspberry PI (Universidad de Cambridge) en 2011, con el objetivo de estimular la enseñanza de la informática en las escuelas, aunque no empezó su comercialización hasta el año 2012. El concepto es el de un ordenador desnudo de todos los accesorios que se pueden eliminar sin que afecte al funcionamiento básico. Está formada por una placa que soporta varios componentes necesarios en un ordenador común y es capaz de comportarse como tal. A la Raspberry Pi la han definido como una maravilla en miniatura, que guarda en su interior un importante poder de cómputo en un tamaño muy reducido. Es capaz de realizar cosas extraordinarias(Yamanoor, Narasimha Saii,Yamanoor, 2013)
 
Los componentes de la Raspberry Pi son:
 
●	Un Chipset Broadcom BCM2835, que contiene un procesador central (CPU) ARM1176JZF-S a 700 MHz (el firmware incluye unos modos Turbo para que el usuario pueda hacerle overclock de hasta 1 GHz sin perder la garantía)
 
●	Un procesador gráfico (GPU) VideoCore IV
 
●	Un módulo de 512 MB de memoria RAM (aunque originalmente al ser lanzado eran 256 MB).
 
●	Un conector de RJ45 conectado a un integrado lan9512 -jzx de SMSC que nos proporciona conectividad a 10/100 Mbps
 
●	2 buses USB 2.0
 
●	Una salida analógica de audio estéreo por Jack de 3.5 mm.
 
●	Salida digital de video + audio HDMI
 
●	Salida analógica de video RCA
 
●	Pines de entrada y salida de propósito general
 
●	Conector de alimentación microUSB
 
●	Lector de tarjetas SD
 
(Yamanoor, Narasimha Saii,Yamanoor, 2013)

![](IMG/ras.jpg)
 
### Puerto GPIO de la  RASPBERRY PI
 
La placa Raspberry Pi puede comunicarse con dispositivos externos a través del conector GPIO incorporado. En este conector hay pines de alimentación integrados (+5 y +3.3 V), tierra y pines de entrada / salida capaces de implementar diferentes protocolos.
 
Dado que existen dos versiones diferentes de hardware Raspberry Pi (rev. 1 y 2), las asignaciones de puertos también pueden variar. Sin entrar, en este momento, en los detalles de los protocolos, las dos posibles versiones de nuestra Raspberry Pi nos llevan a dos posibles escenarios de hardware. Podemos ver aquí un pin de diagrama comparativo de numeración GPIO.
 
#### Los pines GPIO tienen funciones específicas:
 
El color amarillo (2): Alimentación a 3.3V.
 
El color  rojo (2): Alimentación a 5V.
 
El color naranja (26): Pueden configurarse como entradas o salidas se las conoce también como pines de Propósito General.
 
El color gris (2): Son pines reservados.
 
El color negro (8): Conexión a GND.
 
El color azul (2): Comunicación mediante el protocolo I2C (Circuito inter-integrado).
 
El color verde (2): Destinados a conexión para UART para puerto serie convencional.
 
El color morado (5): Comunicación mediante el protocolo SPI (Es un protocolo síncrono, el cual sincroniza y transmite datos  por medio de 4 señales).
 
 ![](IMG/gpio.jpg)
 
  ![](IMG/grande.png)


### Create.withcode.uk online
 
Create.withcode.uk es un editor de python en línea que le permite escribir, ejecutar, depurar y compartir código de python en su navegador web. Se lanzó en abril de 2016 para ayudar a los estudiantes a aprender a escribir código en cualquier dispositivo sin tener que instalar ningún software especializado.

Todos los recursos en este sitio se publican bajo la licencia Creative Commons de uso compartido, lo que significa que puede usar cualquier cosa aquí para cualquier propósito, siempre y cuando me haga referencia como autor original. Sin embargo, hasta ahora, aunque create.withcode.uk ha sido de uso gratuito, el código fuente que lo hace funcionar no ha estado disponible de forma abierta.

Create.withcode.uk ahora es de código abierto. Esto significa que si puede pensar en una forma de mejorar el editor de Python o detecta un error que necesita reparación, no tiene que esperar a que lo codifique: puede saltar y adaptarlo / ampliarlo / mejorarlo te gusta. Puedes usarlo libremente para tus propios proyectos.

 ![](IMG/cre.PNG)



## 5. DIAGRAMAS

 ![](IMG/dia1.jpg)


 ![](IMG/dia2.png)


## 6. LISTA DE COMPONENTES 

#### Diseño una calculadora científica en Python

- Interner
- Plataforma create.withcode.uk online
- Computador
- Python


 
## 7. MAPA DE VARIABLES

### Programa de la Alarma

 ![](IMG/IMG.JPG)

### Programa de  riego automático

 ![](IMG/variabes2.PNG)



## 8. APORTACIONES


Otra forma de resolver el ejercicio de El riego automático es por medio de compuertas lógicas o circuitos integrados para ello lo que primero se realizará son las tablas de verdad aplicando las condiciones que nos muestra el ejercicio obteniendo el siguiente resultado.

 ![](IMG/1.PNG)

Una vez seleccionado los apartados donde se cumple el problema se procederá a simplificar esto se le puede realizar utilizando un software online obteniendo el siguiente resultado

 ![](IMG/2.PNG)
 
  ![](IMG/3.PNG)


## 9. EXPLICACION DEL CODIGO FUENTE

  ![](IMG/aux2.PNG)


### Programa de la Alarma

Se quiere realizar un circuito para activar la alarma de incendios (A) para la evacuación de un edificio.
Para ello se tiene un sensor de gases (G), un sensor de humos (H), y dos señales procedentes de un
termómetro que indican si la temperatura es mayor de 45ºC (T45) y si la temperatura es mayor de 60ºC
(T60). Debido a que a veces los sensores detectan humos y gases que no siempre proceden de
incendios (por ejemplo, de los cigarrillos o las cocinas), para evitar falsas alarmas, la señal A se
activará cuando se cumplan las siguientes condiciones:

a. Si la temperatura es mayor de 60ºC siempre se activará la alarma

b. Si la temperatura está entre 45ºC y 60ºC se activará la alarma sólo si han detectado gases o
humos (o ambos).

c. Si la temperatura es menor de 45ºC se activará la alarma sólo si se detectan gases y humos

Resumiendo, las 4 señales binarias de entrada y la salida:

• G: vale '1' si se detecta GAS resultante de la combustión.

• H: vale '1' si se detecta HUMO.

• T45: vale '1' si la temperatura es superior a 45ºC

• T60: vale '1' si la temperatura es superior a 60ºC

La señal de salida A (alarma) se activará a nivel alto

REQUERIMIENTOS.

• Se debe implementar los 2 enunciados empleando Python y simulado en una Raspberry Pi.

• No se debe ingresar datos por consola.

• El programa debe presentar en pantalla información relacionada a lo que se está realizando.

• Se debe emplear conceptos de POO.

• Cada enunciado se implementará en una clase con sus funciones.

• Se debe emplear un programa de selección (clase) que permita seleccionar la ejecución de los
programas.

• El programa principal crear objetos de cada clase y llamar a las funciones que correspondan para que
opera la lógica de negocio del problema.


  ![](IMG/aux1.PNG)


### Programa de  riego automático

Este programa deseaba hacer un circuito que permitirá realizar un riego automático para ello primero se creó una clase dentro de esta clase se definió las funciones las funciones vienen hacer las entradas del enunciado del problema tenemos la señal de tierra seca la señal de restricciones la señal que indica si es de día o de noche la señal que indica si el depósito de agua está vacío o lleno una vez definidas las funciones c añadió que no una de ellas a un pin del arroz pero que viene a ser la entrada mientras que la salida viene a ser el funcionamiento de la bomba para las condiciones se utilizó funciones if-else y dependiendo la condición que nos arrojaba en el enunciado se la aplican estas condiciones serán :

i. Para evitar que la bomba se estropee por funcionar en vacío, nunca se accionará la
bomba cuando el depósito de agua esté vacío.

ii. Si hay restricciones en el riego (época de verano), sólo se podrá regar de noche.

iii. En el resto del año (si no hay restricciones) se podrá regar de día y de noche (si la
tierra está seca)

Una vez realizadas las condiciones se creará un apartado principal y se iniciará con un güey que permitirá hacer un bucle se colocará las funciones que muestren la condición y las variables.


## 10. CONCLUSIONES


- Python nos permite como programadores  formar un codigo simple y ordenado. Sus aplicaciones, tanto en la comunidad docente como
en la científica, le permitirán aumentar su popularidad y adopción a nivel internacional. Sin mencionar que gracias a sus librerias nos permiten la interaccion de muychos apratados, como lo fue en este proyecto con la raspberry pi.

- El futuro de la tecnología es muy prometedor pero necesitamos hacer un esfuerzo. Raspberry Pi está pensado para que todo el mundo pueda aprender a programar y sea capaz de introducirse en las ciencias de la computación.

- La página https://create.withcode.uk/ la cual puedes crea funciones para ingresar y sacar datos, tiene muchas limitaciones de varias librerías y una de esas es la de librería SYS. 





 
## 11.RECOMENDACIONES



- Para poder realizar un programa en esta plataforma online hay que saber primero saber lenguaje Python, luego de ya tener los conocimentos vas al siguiente nivel el cual es la programacion dirigido objetos con plus de cono cimiento en activar los pines del Raspberry y poder hacer que se pueda ingresar o sacar datos. Estos pasos a seguir nos facilitara para crear mas facil cualquier proyecto relaccionado al mismo. 


 
## 12. CRONOGRAMA

![](IMG/cronos.PNG)


 
 ## 13.BIBLIOGRAFÍA:

- Brand, I., Roy, J., Ray, A., Oberlin, J., & Oberlix, S. (2018, October). Pidrone: An autonomous educational drone using raspberry pi and python. In 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (pp. 1-7). IEEE.

- Otero, P. G. (2020). EQUIPO DE ADQUISICIÓN DE AUDIO MULTICANAL USANDO RASPBERRY PI Y PYTHON. Revista Telemática, 19(1), 48-60.

- Martín Montero, A. (2018). Programación y control de un reloj de tiempo real con Raspberry Pi.

- Tobajas García, A. (2016). Diseño e implementación de una estación meteorológica con Raspberry Pi.

- http://lab1electronicaanalogica.blogspot.com/2018/03/lab-2-de-electronica-digital.html
 
 
## 14. ANEXOS

![](IMG/222.jpg)

![](IMG/data.png)



 
## 15. MANUAL DE USUARIO

Abrimos La página https://create.withcode.uk/ en la cual podremos escribir nuestro codigo, una vez terminado nuestro codigo, tendremos que hacer un click en en la imagen de una triangulo "play" y el progrma automaticamente lo correra.

![](IMG/2.PNG)
