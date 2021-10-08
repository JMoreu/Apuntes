# TEORÍA DE LA POO

## BASES DE LA PROGRAMACIÓN ORIENTADA A OBJETOS

### POO: Fundamentos de la Programación Orientada a Objetos.

- Qué es el software

La información, de todo tipo que das al ordenador para manipular la entrada de datos de un usuaio.
**Es decir, el software es la información**

- La Crisis del Software

El software es información voluminosa y compleja que no podemos tratar de manera desordenada, pues esto marcará la diferencia entre que un proyecto salga adelante o fracase.

- La historia del software

Al principio los lebuajes de alto nivel eran orientados a procesos, esta forma de trabajar daba más importancia a los procesos que los datos.
entonces se dieron cuenta de que los datos requerian de mayor atención surgiendo asi los lenguajes orientados a datos, el problema era que cuando había que cambiar un dato era necesario revisar todas las estructuras anteriores.
De la unión entre estos dos tipos nace la Programación Orientada a Objetos, un equilibrio entre las 2 anteriores, que cuida tanto los datos como los procesos y evita los problemas de acoplamiento de los otros paradigmas.

- Bases de la Programación Orientada a objetos

Existen 4 conceptos fundamentales relacionados entre si:

- Abstracción: Proceso mental de extracción de las características esenciales de algo, ignorando los detalles superfluos.

- Encapsulación: Proceso por el que se ocultan los detalles del soporte de las caracteristicas esenciales de una abstracción.

- Modularización: Proceso de descomposición de un sistema en un conjunto de módulos o piezas independientes y cohesivos (con significado propio). Lo adecuado es conseguir los mínimos acoplamientos.

- Jerarquización: Proceso de estructuración por el que se produce una organización (jerarquía) de un conjunto de elementos en grados o niveles de responsabilidad, incumbencia o composición entre otros

video visto

### Beneficios de la Programación Orientada a Objetos.

- Abstracción.

**Es un proceso mental por el que se ignoran las caracteristicas de algo, quedandonos con lo que realmente nos importa.** La clave es "Proceso mental" asi que nos tenemos que poner a pensar, extrayendo aquello que realmente nos importa ignorando lo superfluo.

Es un proceso subjetivo. No sera el mismo proceso el de un pasajero que el de el mecanico del autobus.

- Encapsulación.

**Es el proceso por el cual se ocultan los detalles del soporte donde se almacenan las caracteristicas de una abstracción.** En este punto el detalle clave para entender esta en la palabre "Soporte". Cuando encapsulamos estamos guardando cómo se soprta algo, como se almacena, qué medio es, cual es su nombre, etc.

Ejemplo: Forma de almacenar la fecha, con 3 variables, con una string como en linux etc. si esta información de como esta definido esta forma se diría que esta encapsulado.

A tener en cuenta: si un programador da a conocer como guardaba esta fecha, y deja que los demás toquen esas variables libremente. Si queremos cambiar la "Abstracción" de la fecha por un timestamp por ejemplo afectaria a todos los que en su codigo hayan accedido a esa abstracción tendran que revisar ese codigo afectando asi a todos sus programas.

El primer momento donde apareció encapsulación en el mundo de la programación fue con las variables locales de las funciones. Estas variables son propias de una función y no pueden mencionarse fuera, luego estan encapsuladas.

Para aclarar: **No se oculta la información** el programador que programo la fecha te tiene que informar en todo momento sobre el dia mes y el año si se lo pides, lo que no te deja saber ni tocar son las variables o cualquier otro soporte mediante el cual está almacenando la fecha.

- Modularización.

**Es la descomposición de un sistema, creando una serie de piezas que colaboran entre si**Acoplados y cohesivos. Tener la capacidad de segmentarlo en diversas partes independientes, que tengan sentido.

Sistema: ejemplo, un ser vivo (una planta,el hombre...) o parte de un ser vivo(el sistema nervioso, circulatorio, etc) o cualquier tipo de producto(desde un coche, hasta una universidad, el sistema solar etc). En cualquiera de estos sistemas debemos reconocer diversas partes y podremos observar que todas colaboran entre si para llevar a cabo un objetivo o conjunto de tareas.

Acoplamiento: Los cambios de piezas y el grado de repercusión en otros elementos del sistema, si es un sistema poco acoplado quiere decir que ese cambio de pieza afectara poco a los demas elementos del sistema.

Los mejores sistemas son poco acoplados, porque permiten hacer cambios en las piezas sin que estos repercutan en las demas partes del sistema. Aunque el acoplamiento siempre va a existir ya que si tenemos una pieza que no esta acoplada con ninguna otra del sistema esa pieza no forma parte de ese sistema si no que sera parte de otro con el que si que este acoplada. hay que reducir los acoplamientos no anularlos.

Cohesión en un sistema bien modularizado implica que sus módulos deben ser entendibles por si mismos. El término viene de coherencia y quiere decir que las parted de un sistema deben funcionar de una manera dada en todas las ocasiones y además ese funcionamiento debe entenderse bien, sin que para ello necesites explicar otra cantidad indeterminada de datos adicionales que quiza no forman parte de esa pieza.

En terminos de programación: Es cohesivo si consigues explicarlo atendiendo a su propio código, si tienes que hablar de codigo que esta disperso por otros lugares, otras estructuras guardadas en variables ajenas al modulo, entonces no es cohesivo. si te dan un codigo que entiendes sin recurrir a otras partes del proyecto entonces es cohesivo.

La modularización va de la mano de la abstracción y la encapsulación, puesto que estos conceptos representan las herramientas necesarias para hacer módulos cohesivos y poco acoplados. **Encapsular reduce los acplamientos**, porque los cambios en las cosas de dentro del modulo no afectan al resto de los modulos del sistema.

La modularidad va de la mano de la abstracción. Si yo entiendo una pieza por si misma normalmente es que es una buena abstracción. **La abstracción correcta permite entender las piezas ppor si mismas y por tanto disponer de módulos cohesivos.**

- Jerarquización.

**Es la estructuración por niveles de los módulos o elementos que forman parte de un sistema.** Es la forma de organizar los módulos, existiendo jerarquías de todo tipo y con diversos grados de dependencia, responsabilidad, incumbencia, composicion, entre otros.

Jerarquías típicas podria ser algo como los animales, en las que podemos clasificar vertebrados e invertebrados. los vertebrados a su vez se dividen en mamiferos, aves, resptiles ...

En POO las jerarquías las forman las clases, las cuales se apoyan en otras para llevar a cabo las tareas, ya sea mediante herencia o composición que veremos mas adelante.

- Conclusión.

Estos 4 conceptos vistos son fundamentales y estan relacionados porque la encapsulación oculta los detalles de la abstracción. Estan relacionados con la modularidad, porque para ser poco acoplados tienen que encapsular y para ser cohesivos deben ser buenas abstracciones. La jerarquia está relacionada con los módulos ya qye estos deben estar organizados por niveles, con algun tipo de jerarquía ya sea de composición, clasificación, o alguna otra.

### Qué es la programación Orientada a Objetos?

Se define como un **paradigma de la programación**, un manera de programar mas específica, donde se **organiza el código en unidades denominadas clases**, de las cuales se crean objetos que se relacionan entre sí para conseguir los objetivos de las aplicaciones.

Entendemos la POO como una forma especial de programar, mas cercana a como expresariamos las cosas en la vida real, permite asi diseñar mejor las aplicaciones llegando a mayores cotas de complejidad, sin que el código se vuelva inmanejable.

Ahora tendremos que pensar nuestros programas en términos de clases, objetos, propiedades, métodos y otras cosas que veremos rapidamente para aclarar conceptos y dar una base que nos permita soltarnos un poco con los conceptos de este tipo de programación.

- Motivación de la programación orientada a objetos.

Durante mucho tiempo los programadores resolvían una y otra vez los mismos problemas, para que estos esfuerzos puedan ser reutilizados se créo la posibilidad de utilizar módulos. El primer módulo existnte fue la función, que somos capaces de escribir una vez e invocar cualquier número de veces.

Sin embargo, la **función se centra mucho en aportar una funcionalidad dada**, pero no tanto interés con los datos. Es verdad que puede recibir datos como parametros y devolverlos, pero los trata de una forma volatil, centrada en operaciones. Simplemente hace su trabajo procesandolos y devolviendo la salida.

En las aplicaciones los datos están muy ligados a la funcionalidad por ejempli: imaginamos un punto que se mueve por la pantalla, el punto tiene coordenadas y podemos trasladarlo de una posición a otra, sumando o restando valores a sus coordenadas. Antes de la POO ocurria que cada coordenada del punto tenía que guardarse en una variable diferente (2 para ser exacto x,y) y las funciones de traslación estaban almacenadas por otra parte. Esta situacion no facilitaba la organización del código ni tampoco su reutilización.

Con la POO se buscaba resolver estas situaciones, creando unas mejores condiciones para poder **desarrollar aplilcaciones cada vez, mas complejas,** ademas pretendia dar unas pautas para realizar las cosas de manera que otras personas pudieran usarlas y adelantar su trabajo, lo que deriva en mayores facilidades para la reutilización del codigo.

la POO no es dificil, pero es a veces subjetiva de quien la programa, aunque se pueda resolver el mismo problema con diferentes formas no siempre es correcto, lo dificil no es usar POO si no programar bien, porque así podemos aprovechar todas las ventajas de la POO.

- Cómo se piensa en objetos.

Ejemplo coche, para modelizarlo en un esquema de POO.

Diriamos que el coche es el elemento principal que tiene una serie de caracteristicas, como podrian ser el color, el modelo o la marca. Además tiene una serie de funcionalidades asociadas, como pueden ser ponerse en marcha, parar o aparcar.

Por tanto, pensar en objetos requiere analizar qué elementos vas a manejar en tus programas, tratando de identificar sus características y funcionalidades. Una vez tengamos un ecosistema de objetos, éstos colaborarán entre sí para resolver los objetivos de las aplicaciones.

- Manejando el concepto de clase

En un esquema POO "el coche" sería lo que se conoce como "Clase". La **clase contiene la definición de las caracteristicas de un modelo** (el coche), como el color o la marca, **junto con la implantación de sus funcionalidades**, como arrancar o parar.

Las características definidas en la clase las llamamos **propiedades** y las funcionalidades asociadas las llamamos **métodos**.

Para entender este concepto tan importante dentro de la POO, podemos pensar que **la clase es como un libro** que describe omo son todos los objetos de un mismo tipo. La clase coche describe cómo son todos los coches del mundo, es decir, qué propiedades tienen y qué funcionalidades deben poder realizar y, por supuesto, cómo se realizan.

- Manejando el concepto de objetos.

**A partir de una clase podemos crear cualquier número de objetos de esa clase.** Por ejemplo, a partir de la clase "el coche" podemos crear un coche rojo que es de la marca Ford y modelo Fiesta, otro verde que es de la marca Seat y modelo ibiza.

- Otros ejemplos de clases y objetos

Como modelizaríamos en un esquema POO una fracción, es decir, esa estructura matemática que tiene un numerador y denominador que divide al numerador por ejemplo 3/2.

La fracción será la clase y tendrá 2 propiedades, numerador y el denominador. Luego podría tener varios metodos como simplificarse sumarse con otra fracción o número, restarse  con otra fracción, etc.

A parir de la definición de un fracción (la clase) podremos construir un número indeterminado de objetos de tipo fracción y construirá muchos objetos de tipo fracción para hacer cuentas diversas. Pero podrías usar esa misma clase fracción en un programa de contabilidad o facturación.

otro ejemplo podría ser la clase coordenada, que tiene 2 propiedades valor x e y. Podrías tener otra clase "Coordenada 3D" que necesitaría 3 propiedades x, y, z. Las coordenadas se podrían sumar a otra coordenada, mostrarse un gráfico, encontrar el camino mas corto entre 2 coordenadas, etc.

Estos son simles ejemplos de clases, que tambien nos sirven para destacar la reutilización que podemos conseguir con los objetos. La clase coordenada la podremos usar en infinidad de programas graficos, gestion de un parking. A partir de clase coche y crearan diver objetos de tipo coche para acer las operativas tanto en la aplicación del taller como en la del parking.

- Los objetos colaboran entre sí.

En los lenguajes puramente orientados a objetos, tendremos únicamente clases y objetos. Las clases permitirán definir un número indeterminado de objetos, que colaboran entre ellos para resolver los problemas.

Con muchos objetos de diferentes clases conseguiremos realizar las acciones que se desean implementar en la funcionalidad de la aplicación.

Además, las propias aplicaciones como un todo, tambiés serán definidas por medio de clases. Es decir, el taller de coches será una clase, de la que podremos crear el objeto taller de coches, que utilizara objetos coche, objetos de clase herramienta, objetos de clase mecánico, objetos de clase recambio, etc.

Para continuar vamos a definir de manera más formal los conceptos que acabamos de introducir anteriormente.

- Clases en POO.

Las clases son declaraciones de objetos, también se podrían definir como abstracciones de objetos. Esto quiere decir que la definición de un objeto sera la clase. Cuando programamos un objeto y definimos sus caracteristicas y funcionalidades en realidad lo que estamos haciendo es programar una clase. En los ejemplos anteriores hablábamos de las clases de coche o fracción porque sólo estuvimos definiendo, aunque por encima, sus formas.

- Propiedades de las clases.

**Las propiedades o atributos son las caracteristicas de los objetos o ejemplares de una clase.** Cuando definimos una propiedad normalmente especificamos su nombre y su tipo.

Aunque no hay una manera muy correcta de hablar, nos podemos hacer a la idea de que las propiedades son algo así como variables donde almacenaremos los datos relacionados con los onjetos.

- Métodos en las clases.

**Son las funcionalidades asociadas a los objetos**, que son implantadas o programadas dentro de las clases. Es decir cuando estamos programando las clases, las funciones que creamos dentro asociadas a esas clases las llamamos métodos.

Aunque los métodos son como funciones, es importante que los llames métodos para que quede claro que son funciones que podremos invocar sobre todos los objetos creados a partir de una clase.

- Objetos en POO

Los objetos son **ejemplares de una clase**. A partir de una clase puedo crear ejemplares(objetos) de esa clase, que tendrán por tanto las caracteristicas y funcionalidades definidas en esa clase.

Cuando creamos un ejemplar tenemos que especificar la clase a partir de la cual se creará. Esta acción  de crear un objeto a partir de una clase se llama **instanciar** Por ejemplo, un objeto de la clase fracción sería por ejemplo 3/5. el concepto o definición de fracción sería la clase, pero cuando ya estamos hablando de una fracción en concreto seria lo que llamamos objeto.

Para crear un objeto se requiere una instrucción especial parecida a esta (varia dependiendo del lenguaje de programación)

`miCoche = new Coche()`

Con la palabra "new" especificamos que se tiene que crear una instancia de la clase que sigue a continuación.

En este caso "Coche" sería el nombre de la clase. Con la palaba "new" se crea una nueva instancia de coche, un objeto concreto de la clase coche y ese objeto se almacena en la variable "miCoche".

dentro de los paréntesis podriamos colocar parámetros con los que inicializar el objeto de la clase coche, como podría ser su color, o su marca.

- Estado en objetos.

Cuando tenemos un objeto sus propiedades toman valores. Por ejemplo, cuando tenemos un coche la propiedada colo tomará un valor en concreto, como por ejemplo rojo o gris metalizado. **El valor concreto de una propiedad de un objeto se llama estado.**

Para acceder a un estado de un objeto para ver su valor o cabiarlo se utiliza el operador punto.

`miCoche.color = "rojo"`

El objeto es miCoche, luego colocamos el operador punto y por ultimo el nombre de la propiedad que queremos acceder. En este ejemplo cambiamos la propiedad "color" del objeto al valor "rojo". Esto lo hacemos con una simple asignación.

- mensajes en objetos.

Un **mensaje en un objeto es la acción de efectuar una llamada a un método.** Por ejemplo, cuando le decimos a un objeto coche que se ponga en marcha estamos pasándole el mensaje "ponte en marcha".

Para mandar mensajes a los objetos utilizamos el operador punto, seguido del método que deseamos invocar y los parésntesis, como en las llamadas a las fucniones.

`miCoche.ponteEnMarcha()`

En este ejemplo pasamos el mensaje "ponteEnMarcha" al objeto "miCoche".

Después del nombre del metodo que queremos invocar hay que colocar parentesis igual que cuando invocamos una funcion dentro de los parentesis irían los parámetros, si es que el método los requiere.

### Métodos y atributos static en POO

- Qué es static

La definición normal de elementos estaticos (o miembros de clase) nos dice que son aquellos que pertenecen a la clase, en lugar de pertenecer a un objeto en particular.

**Clases:** Definiciones de elementos de un tipo homogéneo.
**Objetos:** Concreción de un ejemplar de una clase.

En las clases defines que tal objeto tendrá tales atributos y tales métodos, sin embargo, para acceder a ellos o darles valores necesitas construir objetos de esa clase. Una casa tendrá un número de puertas para entrar, en las que tendrás definida que una de las características de la casa es el numero de puertas, pero solo concretarás ese número cuando construyas objetos de la clase casaa. Un coche tiene un color y hasta que no construyas coches no les asignarás un color en concreto. En la clase cuadrado definiras el calculo del área es el lado elevado a 2 pero para calcular el área de un cuadrado necesitas tener un objeto de esa clase y pedirle que te devuelva su área.

- Ejemplos de situaciones de la vida real donde tendríamos miembros estáticos.

 Pensemos en los autobuses de la ciudad. todos los buses por ejemplo tienen la misma tarifa. En condiciones normales, para acceder al precio de un autobús necesitaria instanciar un objeto autobús y luego consultar su precío **¿Es esto practico?** quizás solo quiero saber su precio para salir de casa con dinero suficiente para pagarlo, pero en el caso de un atributo normal necesariamente deberia tener instanciado un autobus para preguntar su precio.

 Pensemos en el numero "Pi". Sabemos que necesitamos ese número para realizar cálculos con circuferencias. Podría tener ls clase Circunferencia y definir como atributo el número Pi. Sin embargo, igual necesito ese número para otra cosa, como pasar ángulos de valores de grados a radianes. En ese caso, en condiciones normales sin atributos de clase, necesitaría instanciar cualquier circulo para luego preguntarle por el valor de "Pi". De nuevo, no parece muy práctico.

 > **Nota:** Ojo, porque en el caso de Pi su valor sera siempre constante. Podriamos usar constantes en el caso de que el lenguaje las tuviese, pero los atributos estáticos no tienen por qué ser siempre un valor invariable, como es el caso del precio de los Autobuses que sube cada año.

 En cuanto a métodos, pensemos por ejemplo en la clase Fecha. Puedo intentar construir fechas con un dia, un mes y un año, pero puede que no necesite una fecha en un momento dado y solo quiera saber si una fecha podría ser válida. En situaciones normales deberia intentar construir esa fecha y esperar a ver si el constructor me arroja un error o si la fecha que construye es válida. Quiza sería mas cómodo tener un método vinculado a la clase, en el que podría pasarle un mes, un día  y un año y que me diga si son válidos o no.

 - Cómo definir y usar miembros estáticos.

  Esto ya depende del lenguaje de programación, generalmente se usa el modificador "static" para definir los miembros clase, pero podrian existir otros metodos segun el lenguaje


  ```java
  Class AutobusMetropolitano {
  	public static precio = 1.20;
  	}
  ```

podras ver que en la definición de la clase hemos asignado un valor al precio a la hora de declarar ese atributo de clase. esto es una condición indispensable en muchos lenguajes, puesto que si existe este atributo debería tener un valor antes de instanciar el primer objeto. Osea, no es como los atributos normales, que les podemos asignar valores a traves del constructor.

Luego podríamos acceder a esos elementos a traves del nombre de la clase:

```java
if(1.5 >= AutobusMetropolitano.precio){
	//todo bien
	}`

Ese codigo seria en el caso de que estés accediendo al atributo estático desde fuera de la clase, pero en muchos lenguajes puedes acceder a esos atributos (o métodos) desde la vista privada de tus clases(código de implantación de la clase) a traves de la palabra "self".

```java
class AutobusMetropolitano {
	static precio = 1.20;
	// ...

	public function aceptarPago(dinero){
		if (dinero < self.precio){
			return false;
		}
	// ...
	}
}
```

En caso de los metodos estáticos la forma de crearlos o usarlos no varía mucho, utilizando el mismo modificador "static" al declarar el método

```java
class Fecha{
	// ...
	public static functon valida(ano,mes,dia){
		if (dia > 31){
			return false;
			//...
		}
	}
}
```

Ahora para saber si un conjunto de año mes y dia es válido podrias invocar al método estático a través del nombre de la clase.

```java
if(Fecha.valida(2014, 2, 29)){
	//es valida
}else{
	//no es valida
}
```

Como en el caso de los atributos de clase, también podrías acceder a métodos de clase con la palabra "self" si estas dentro del códifo de tu clase.

- Miembros estáticos son susceptibles de hacer "marranadas".

En ocasiones se tiende a usar los métodos estáticos para agregar datos a modo de variables globales, que estén presentes en cualquier lugar de la aplicación a partir del nombre de una clase. Esto nos puede acarrear exactamente los mismos problemas que conocemos por el uso de variables globales en general.

### Herencia en POO

- Jerarquización

Es un proceso poe el cual se crean organizaciones de elementos en distintos niveles. No es exclusivo de la POO, pueden haber diversos tipos de jerarquías, como clasificación o composición.

**Composición:** Es cuando unos elementos podemos decir que están compuestos de otros, o que unos elementos están presentes en otros. Por ejemplo, el sistema respiratorio y los pulmones, la nariz etc. Podemos decir que los pulmones encontramos bronquios y alvéolos. En esta jerarquía  de elementos podemos decir que puede haber una jerarquía de composición. La factura tiene un cliente, varios conceptos facturables, un impuesto, etc.

**Clasificación:** Este tipo de jerarquización indica que unos elementos son una especialización de otros. Por ejemplo, los animales, donde tenemos vertebrados e invertebrados. Luego, dentro de los vertebrados encontramos aves, reptiles, mamíferos, etc. En los mamíferos encontramos perros, vacas, conejos...

Los lenguajes de programación orientados a objetos son capaces de crear jerarquizaciones basadas en composición con lo que ya sabemos de clases y objetos. Eso es porque podemos tener como propiedades de objetos, otros objetos. Por ejemplo, en el caso de la factura, podríamos tener como propiedades el cliente, el impuesto, la lista de conceptos facturables, etc. Sin embargo, para hacer jerarquías de clasificación nos hace falta conocer la herencia.

- Reutilización del código

Por otra parte, otro de los mecanismos que cualquier lenguaje de programación debe proveer es la posibilidad de reutilizar el código. En la programación estructurada tenemos las funciones, así que ya hemos podido reutilizar el código de alguna manera. Así pues, el equivalente a las funciones, los métodos, ya nos da un grado de reutilización, pero no llegan al nivel de potencia de las que encontraremos en la herencia.

No necesitamos decirte mucho más para entender las bondades de la reutilización: en inglés lo resume el término "DRY" Don't Repeat Yourself y es uno de los enunciados que debes tener mas presente cuando programas. "No es mejor quien mas lineas de código hace, sino quien mejor las reutiliza".

- Herencia de la POO

La herencia es la transmisión del código entre unas clases y otras. Para soportar un mecanismo de herencia tenemos 2 clases: la clase padre y la/s clase/s hija/s. La clase padre es la que transmite su código a las clases hijas. En muchos lenguajes de programación se declara con la palabra "extends".

`class Hija extends Padre{}`

Eso quiere decir que todo el código de la clase padre se transmite, tal cual, a la clase hija. Si lo quieres ver asi es como si tuvieres escrito, linea a linea, todo el codigo de la class "Padre" dentro de las llaves de la class "Hija". Por eso la herencia es fundamental para reutilizar código, porque no necesitas volver a incorporar el código de Padre a Hija, sino que realmente al hacer el "extends" es como si ya estuviera ahí.

- Ejemplo de herencia

Volvamos a los animales, pensemos en los mamíferos. Todos tienen una serie de características, como meses de gestación en la barriga de la madre, pechos en las hembras para amamantar y luego funcionalidades como dar a luz, mamar, etc. Eso quiere decir que cuando realices la clase perro vas a tener que implementar esos atributos y métodos, igual que la clase vaca, cerdo, humano, etc.

 en este esquema tendríamos una clase mamífero que nos define atributos como numero_mamas, meses_gestacion y métodos como dar_a_luz(), mamar(). Luego tendrías la clase perro que extiende (hereda) el código del mamífero, así como las vacas, que también heredan de mamífero y cualquiera de los otros animales de esta clasificación.

 Otro ejemplo, tenemos alumnos universitarios. Algunos son alumnos normales, otros Erasmus y otros becarios. Probablemente tendremos una clase Alumno con una serie de métodos como asistir_a_clase(), hacer_examen() etc., que son comunes a todos los alumnos, pero hay operaciones que son diferentes en cada tipo de alumno como pagar_mensualidad() (los becarios no pagan) o matricularse() (los Erasmus que son estudiantes de intercambio, se matriculan en su universidad de origen).

 Lo que debes observar es que con la herencia siempre consigues clases hijas que son una especialización de la clase padre. Para saber si está correcto emplear herencia entre unas clases y otras, plantéate la pregunta ¿CLASE HIJA es un CLASE PADRE? (por ejemplo, ¿un perro es un mamífero? ¿Un becario es un alumno de universidad?)

 > **Nota:** Existen otros modos de decir clases hija, como clase heredada, clase derivada, etc.

 - Otras cosas a saber sobre la herencia

 En este artículo nos hemos limitado a hablar sobre el concepto de herencia, pero no sobre una serie de mecanismos asociados que resultan clave para entender todavía mejor las posibilidades de esta capacidad de la POO. Nos referimos a la visibilidad de propiedades y métodos entre clases padre e hija, la posibilidad de hacer clases abstractas, que son las que contienen métodos abstractos o incluso propiedades abstractas. Hemos dejado de lado asuntos como la herencia múltiple, que te proporciona la posibilidad de heredar de varias clases a la vez (los ejemplos mencionados son de herencia simple).

### Polimorfismo en POO

