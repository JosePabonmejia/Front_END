# Curso de Sistemas de Diseño Efectivos 
¡Bienvenido al curso de Sistemas de Diseño! <br> 
En este curso aprenderás a crear sistemas de diseño desde cero así como todas las herramientas que tienes para dialogar y trabajar junto con otros equipos a la hora de crear o iterar productos de software.

## Partes del Design System

* Principios: marcan la pauta y las reglas de nuestro producto
* Sistema: Cual va a ser el flujo de creación (tiempos y forma)
* Foundations: Bases de todo lo visual
* Componentes: Partes que forman un todo

## Principios del sistema de siseño 

Los principios del diseño son la base fundamental de los paradigmas y metodologías que aplicaremos en nuestro sistema. Todas las decisiones que tomemos deben tener en cuenta y fundamentarse en estos principios, así evitamos cometer errores o generar conflictos, ya que todos los caminos serian correctos.<br>

Principios del sistema de diseño:<br>

* Accesibilidad: Nuestro producto debería ser usable para cualquier usuario, debemos construir productos perceptibles, operables, entendibles y robustos.
* Consistencia: Todo el equipo deben tener los mismos objetivos y deben hablarle de la misma forma a los usuarios, sea visualmente o por escrito.
* Reusabilidad: Cada hora que invirtamos trabajando en algún componente debe servir para construir otros componentes y evitar que tu o alguien más tenga que reconstruir nuestro trabajo.
* Shareable: Debemos construir y trabajar con herramientas que nos permitan compartir todo nuestro trabajo.

## Niveles de Sistematización

El Design System Workflow nos ayuda a entender mucho mejor cómo entra, por dónde sale y por cuáles puntos pasa nuestro trabajo cuando trabajamos con sistemas de diseño.<br>

En este workflow o flujo de trabajo comenzamos diseñando y documentando para después hacer deploy (un término de programación para los momentos en que pasamos nuestro trabajo a producción, una versión funcionando en vivo), en esta etapa de deploy debemos tener muy claro para cuál plataforma o entorno estamos trabajando, así tendremos mucho más claro todo lo que vamos a necesitar construir (por ejemplo, cuando construimos páginas web trabajamos en archivos .css con los estilos de nuestros productos).<br>

Pero el trabajo no termina aquí, después de hacer deploy entramos a la etapa de testing para evaluar la efectividad de estos estilos y seguirlos mejorando.<br>

También vamos a aprender sobre Building Design Systems, donde construimos herramientas para que todos puedan usar e implementar las guías y los estilos que estamos trabajando. Para organizarnos y sistematizar estos procesos podemos implementar el modelo solitario, dónde tú, el diseñador haces todo el trabajo para que alguien más lo consuma, pero existen otros modelos como el centralizado o el confederado donde trabajamos con otras personas o incluso otros equipos y pedimos feedback dependiendo de la organización de nuestras empresas.<br>

### Resumen 
        • Solitario: tú construyes, los demás consumen
        • Centralizado: tú consultas a los demás departamentos y construyes un SD
        • Confederado: varios equipos dentro de varios departamentos y todos construyen el sistema

## Paradigmas: Diseño atómico, diseño procedural y DRY

Existen varios paradigmas de diseño que pueden guiarte en la construcción de tu sistema de diseño.<br>

***El paradigma procedural*** es la construcción de objetos variados para posteriormente construir nuestros sistemas a partir de estos elementos, es la construcción de funciones que en el futuro se construirán a sí mismas. En vez de construir todos los objetos de nuestro sistema, vamos a trabajar los elementos y reglas que se resolverán después. Por ejemplo, construir las mangas, el cuello u otros elementos para al obtener el resultado de un abrigo.<br>

Otro paradigma que debemos entender es el ***diseño atómico*** para organizar los elementos de nuestros diseños y software. Los elementos independientes más sencillos de nuestro sistema (labels, inputs, botones, títulos, etc) los conocemos como átomos, pero cuando juntamos átomos construimos moléculas, elementos sencillos unidos entre sí (un buscador por ejemplo, el conjunto de label + input + botón), y formamos organismos cuando juntamos moléculas (por ejemplo, una barra de navegación con logos, enlaces y un buscador).<br>

Con la suma de estos organismos generamos ***templates***, la forma más básica de nuestras plataformas qué podemos utilizar en diferentes partes de nuestros diseños aplicando pequeños cambios en los átomos, y cuando aplicamos estos cambios para las partes especificas de nuestro sitio obtenemos páginas, el resultado final de toda la organización de elementos independientes hasta formas conjuntos de organismos complicados y armónicos entre sí.<br>

Por último, vamos a entender ***el paradigma dry (Don’t Repeat Yourself)*** para construir elementos reciclables y no gastar tiempo volviendo a construir los mismos objetos una y otra vez.<br>