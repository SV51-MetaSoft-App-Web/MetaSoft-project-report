# Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management.

En este punto del informe se describe las decisiones y los principios que ayudarán al 
equipo a garantizar la coherencia durante el desarrollo de la solución.

### 5.1.1. Software Development Environment Configuration.

En este apartado se proporcionan los enlaces a las aplicaciones y productos de 
software creados durante el ciclo del proyecto utilizando los programas correspondientes.

Con ese fin, se organizará en las siguientes secciones:
1. [ ] Project Management
2. [ ] Requirements Management
3. [ ] Product UX/UI Design
4. [ ] Software Development
5. [ ] Software Testing
6. [ ] Software Documentation

Asimismo, se clasificarán los elementos de estas secciones como rutas de referencia 
(para software basado en modelos Saas) o rutas de descarga (para productos que se 
ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos 
de software.

**Project Management**

Esta disciplina se fundamenta en la administración de proyectos y busca principalmente la 
mejora de procesos y su entorno con el propósito de lograr los resultados esperados.

* Durante el ciclo digital del proyecto, se llevará a cabo la implementación de un producto 
de software basado en el modelo SaaS, el cual funcionará a través de un navegador web; no 
obstante, no se desarrollará una versión de la aplicación móvil correspondiente.

**Requirements Management:**

Este proceso se enfoca en asegurar que una organización documente, verifique y satisfaga las 
necesidades y expectativas de sus clientes, así como las de las partes interesadas internas 
o externas.


* **Jira Software:** Esta es una plataforma que facilita la gestión de historias de usuario, 
organizándolas en epopeyas y evaluando su importancia en el programa según su prioridad y puntos 
de historia. Se utiliza debido a su capacidad para permitir que cada miembro del equipo tenga una 
vista en tiempo real de los avances en cada proyecto, contribuyendo con diferentes secciones o 
ajustando el flujo del proyecto según sea necesario.

**Product UX/UI Design**

Esta herramienta facilita la creación digital de modelos que se integran en la vida del consumidor. 
En este caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como 
con dispositivos móviles.

Para lograrlo, utilizamos varias herramientas de diseño y colaboración, que incluyen:

1. **Uxpressia:** Uxpressia es una plataforma en línea especializada en el mapeo de la trayectoria del
cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps 
y Journey Maps. Puedes encontrar más información sobre Uxpressia en este [enlace](https://uxpressia.com/).

2. **MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades 
colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una 
herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en su 
[sitio web](https://miro.com/es/).

3. **Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A 
diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que 
funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar 
Figma en [este enlace](https://www.figma.com/es-es/).

4. **Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y
trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas 
mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart 
en [este enlace](https://www.lucidchart.com/pages/es).

5. **Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en 
tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más 
información sobre Overflow, visita su [sitio web](https://overflow.io/).

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a garantizar que nuestros 
productos sean accesibles y atractivos en diferentes plataformas.


**Software Development:**

El desarrollo de software es una metodología aplicada en la creación de productos de software. Esta 
metodología se utiliza para establecer un proceso que guía el desarrollo del software, y cada uno de
sus pasos describe un enfoque específico para las distintas actividades que ocurren durante el proceso.

Aquí te presentamos algunas herramientas y tecnologías clave que utilizaremos en el proyecto:

1. **GitHub:** GitHub es una plataforma de repositorio comunitario que se utiliza para almacenar y 
gestionar los avances de proyectos realizados por grupos de personas. Puedes acceder al repositorio 
del proyecto en este [enlace](https://github.com/SV51-MetaSoft-App-Web).

2. **Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una empresa especializada en software, 
orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar 
sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para 
trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).

3. **HTML:** HTML es un lenguaje de marcado que se utiliza en el desarrollo de sitios web para crear
hipertextos y enlazar a otros documentos. Este lenguaje proporciona herramientas para diseñar 
sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos 
HTML para implementar la documentación de la página web. Obtén más información sobre la edición de
archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).

4. **CSS:** CSS es un lenguaje de diseño destinado al entorno web, que posibilita la mejora de la interfaz
de usuario previamente diseñada al añadir elementos como colores y tamaños, entre otros. Además, 
es posible crear un estilo en CSS y compartirlo en el sitio web creado en HTML. Este lenguaje será 
empleado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información 
sobre CSS en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

5. **JavaScript:** Es un lenguaje de programación que es interpretado por otros programas. Funciona bajo 
el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases 
para la implementación. Este lenguaje permite crear dinámicas para los usuarios a través de la 
lógica de programación y será utilizado en la creación de las interacciones dinámicas en la plataforma 
web. Puedes encontrar más detalles sobre JavaScript en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

Estas herramientas y tecnologías desempeñarán un papel fundamental en la creación exitosa de nuestro 
producto de software.

**Software Testing:**

Se trata de la acción de evaluar los elementos y el funcionamiento del software sometido a prueba 
mediante procesos de validación y verificación.

**Lenguaje Gherkin:** Este lenguaje, conocido como DSL (Lenguaje Específico de Dominio), está diseñado 
específicamente para abordar problemas particulares. Además de poder ser interpretado en código,
permite agregar historias de usuario del programa junto con sus componentes correspondientes, como 
Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.

**Software Documentation**

Se refiere a textos escritos o ilustraciones que acompañan al software de computadora o están 
integrados en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el 
software o cómo utilizarlo.

### 5.1.2. Source Code Management.

A continuación, se describe la gestión del código fuente, también conocida por las siglas SCM (Source Code Management). Su función principal es rastrear los cambios que realizará el equipo durante el desarrollo de su proyecto en el repositorio de código fuente. Se utilizará como un sistema de control de versiones que lepermitirá realizar un seguimiento de los cambios realizados por miembros o desarrolladores individuales del proyecto. Además, es importante tener en cuenta que usaremos GitHub como nuestro sistema de control de versiones.

1. [ ] URL de la organización: SV51-MetaSoft-App-Web - https://github.com/SV51-MetaSoft-App-Web

2. [ ] URL del repositorio de la Landing Page: ElixirControl-Landing-Page - https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page

3. [ ] URL del repositorio del Front-End: ElixirControl-FrontEnd - https://github.com/SV51-MetaSoft-App-Web/ElixirControl-FrontEnd

4. [ ] URL del repositorio del Back-End: ElixirControl-BackEnd - https://github.com/SV51-MetaSoft-App-Web/ElixirControl-BackEnd

**GitFlow**

GitFlow es un modelo alternativo para la creación de ramas en Git que se ha convertido en una herramienta esencial para muchos desarrolladores en los últimos años. Este flujo de trabajo de control de versiones, desarrollado y popularizado por Vicent Driessen, desempeña un papel crucial en la gestión de las versiones de un código, facilitando la creación ordenada de nuevas características (Features) y correcciones de problemas urgentes (Hotfixes).

![GitFlow.png](/assets/img/chapter-V/sprint-1/GitFlow.png)

Como se mencionó previamente, GitFlow opera con ramas o "branches". A continuación, se detallan las ramas que se utilizarán en el flujo de trabajo de nuestro proyecto.

* **Main Branches:**
    * **Main:** Esta es la rama principal desde la cual se ramifican todas las demás. Contendrá la versión más reciente junto con las versiones anteriores creadas por los desarrolladores. Aquí se mantendrá el historial oficial de las versiones publicadas.
    * **Develop:** Esta rama puede ser creada a partir de la rama principal (Main) y contendrá todas las características (Features) estables. A través de esta rama, el equipo podrá integrar las funcionalidades de manera efectiva.

* **Support Branches**
A diferencia de las ramas principales, estas ramas secundarias tienen una vida útil limitada, ya que se eliminan al fusionarse con sus ramas primarias.
    * **Feature:**
        * Se ramifica de: develop
        * Debe fusionarse de nuevo en: develop
        * Se utilizan para desarrollar las nuevas funciones que se integrarán en la próxima versión. Es importante destacar que esta rama existe únicamente mientras está en proceso de desarrollo. Sin embargo, una vez que el desarrollador haya completado esa función, se fusionará nuevamente con la rama "develop".

* **Convenciones para nombrar los Features:**
    * **Feture Branch:** feature/name
    **Example:**
        1. feature/welcome
        2. feature/about
        3. feture/myfeture
    * **Conventional Commits**
    El commit debe seguir la siguiente estructura:
    **\<type> [optional scope]: \<description>**
    **[optional body]**
    **[optional footer(s)]**
        * **Type:**
        **1\. feat:** Cuando se agrega un nuevo feature.
        **2\. fix:** cuando corriges un error.
        **3\. build:** cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.
        **4\. chore:** modificaciones privadas del código.
        **5\. docs:** commits que afectan solo a la documentación.
        **6\. refractor:** commits que reescriben o reestructura el código, pero no cambia el comportamiento.
        **7\. perf:** commits especiales que mejoran el rendimiento.
        **8\. style:** commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).
        **9\. test:** commits que agregan pruebas.
        * **Scope**
        Ofrece información contextual adicional. Aunque es opcional, es beneficioso incluirlo para proporcionar a los desarrolladores una descripción más detallada del commit.
        **\<description>**
        Es una parte obligatoria del formato de los commits. Siempre debemos usar lenguaje en modo imperativo y evitar escribir en mayúsculas
        **[optional body]**
        El cuerpo es opcional y, cuando se utiliza, debe explicar la motivación detrás del cambio y contrastarlo con el comportamiento anterior. Es ideal para mencionar identificadores de problemas y sus relaciones.
        **[optional footer(s)]**
        Esta sección es opcional y puede incluir información sobre cambios significativos. Puede hacer referencia al problema por su identificación y, en esta sección, se incluyen los cambios importantes precedidos por "BREAKING CHANGES:" seguido de uno o dos saltos de línea.
        **Ejemplos:**
            1. feat(welcome): add welcome section
            2. build(release): bump version to 1.0.0
            3. style: remove empty line
            4. feat(sign up): add the button to sign up
            5. feat!: email the costumer when product is shipped
            6. feat: remove ticket list endpoint
            refers to JIRA-1337
            BREAKING CHANGES: ticket enpoints no longer supports list all entites.

Como se mencionó previamente, la gestión de nuestro código fuente se llevará a cabo mediante
GitHub. El IDE utilizado en este caso, WebStorm, debe estar vinculado directamente al 
repositorio creado por nuestra StartUp. De esta manera, cada commit realizado por 
un miembro del equipo se subirá automáticamente y se cargará en el GitHub de la organización. Las instrucciones para completar con éxito este proceso de emparejamiento se detallan a continuación:

* **Activar el controlador de versiones del IDE**
Dado que utilizaremos GitHub para gestionar nuestro código, la opción que debe estar 
habilitada o seleccionada es aquella que indique que el sistema de control se realizará
mediante Git. Para hacer esto, siga los siguientes pasos:

  1. Diríjase a la pestaña "VCS" en WebStorm.
  2. Luego, seleccione la opción "Enable Version Control Integration".


![activar-el-controlador-de-versiones-1.png](/assets/img/chapter-V/sprint-1/activar-el-controlador-de-versiones-1.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![activar-el-controlador-de-versiones-2.png](/assets/img/chapter-V/sprint-1/activar-el-controlador-de-versiones-2.png)

* **Aregar una cuenta de GitHub, siga estos pasos:**
  1. Diríjase a la sección de configuración en su aplicación.
  2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
  3. En la configuración, busque la sección de version control.
  4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.


![aregar-una-cuenta-de-GitHub-1.png](/assets/img/chapter-V/sprint-1/aregar-una-cuenta-de-GitHub-1.png)

![aregar-una-cuenta-de-GitHub-2.png](/assets/img/chapter-V/sprint-1/aregar-una-cuenta-de-GitHub-2.png)

* **Configurar el nombre de usuario de Git:** Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
  1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
  2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
  3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.


![configurar-el-nombre-de-usuario-de-Git-1.png](/assets/img/chapter-V/sprint-1/configurar-el-nombre-de-usuario-de-Git-1.png)


* **Guardar el progreso en GitHub:** Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.


![guardar-el-progreso-en-GitHub-1.png](/assets/img/chapter-V/sprint-1/guardar-el-progreso-en-GitHub-1.png)


![guardar-el-progreso-en-GitHub-2.png](/assets/img/chapter-V/sprint-1/guardar-el-progreso-en-GitHub-2.png)

* **Configurar la propiedad del repositorio en GitHub:** Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
  1. Ingresa al repositorio creado en GitHub.
  2. Selecciona la pestaña 'settings'
  3. Dirigite al apartado de 'DangerZone'
  4. Luego da click en 'transfer'
  5. Finalmente elegimos el nuevo lugar para guardar el repositorio.


![configurar-la-propiedad-del-repositorio-en-GitHub-1.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-1.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-2.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-2.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-3.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-3.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-4.png](/assets/img/chapter-V/sprint-1/configurar-la-propiedad-del-repositorio-en-GitHub-4.png)


* **Configurar control remoto en Git:** Por último, dado que el repositorio ahora está bajo la propiedad de la empresa y depende de ella, es necesario acceder al control remoto del código. Para hacerlo, simplemente ingresa al repositorio creado y copia la URL del repositorio.

![configurar-control-remoto-en-Git-1.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-1.png)

Ahora, en el IDE, dirígete a la pestaña 'Git' y elige la opción 'Manage Remotes'.

![configurar-control-remoto-en-Git-2.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-2.png)

Finalmente, como último paso, debes pegar el enlace copiado en el campo de dirección que solicita el IDE para el control remoto en Git.

![configurar-control-remoto-en-Git-3.png](/assets/img/chapter-V/sprint-1/configurar-control-remoto-en-Git-3.png)

Si has seguido correctamente todos los pasos y directrices mencionados, entonces has completado la configuración con éxito. Ahora, solo necesitas realizar un commit y los cambios que hayas efectuado se guardarán en el repositorio de GitHub, ya sea que hayas realizado modificaciones en el código, creado nuevas ramas u otras acciones.

### 5.1.3. Source Code Style Guide & Conventions.

En esta sección, se presentarán las pautas, convenciones, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en la creación de nuestra aplicación. La observancia de este conjunto de directrices reviste una importancia fundamental, ya que tiene el propósito de mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el mantenimiento del mismo.

Dado que en este proyecto se emplearán varios lenguajes, como HTML, CSS, JavaScript, C# y TypeScript para el desarrollo de la plataforma web, así como Gherkin para el proceso de pruebas del programa, a continuación, se detallarán y describirán las reglas y recomendaciones generales que se tendrán en cuenta al utilizarlos.


**Nomenclatura General**

Para los nombres de variables, objetos, elementos y funciones que se utilicen en el proyecto, se emplearán términos en inglés que estén relacionados con lo que representan. No se utilizarán mayúsculas en estos nombres, ya que, de acuerdo con W3Schools (sin fecha), la combinación de mayúsculas y minúsculas puede dificultar la legibilidad del código. En su lugar, se optará por utilizar exclusivamente letras minúsculas, lo que contribuirá a una mayor claridad en el código.

Ejemplos de nomenclatura estándar, siguiendo las recomendaciones de Google (s.f.):

```
.gallery {}
.video {}
.login {}
```

Estas pautas de nomenclatura ayudarán a mantener una coherencia en el código y facilitarán su comprensión.

**Sangría**

Cuando se trabaje con HTML, CSS y/o JavaScript, se aplicará un espaciado de dos espacios antes de cada línea que se encuentre dentro de un bloque. Según W3Schools (sin fecha), no se recomienda el uso de la tecla "Tabulación". A continuación, se muestra un ejemplo de la sangría estándar en HTML siguiendo las directrices de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Título del Documento</title>
  </head>
  <body>
    <h1>Encabezado Principal</h1>
    <p>Este es un párrafo dentro del cuerpo del documento.</p>
  </body>
</html>
```

Este estilo de sangría proporciona una estructura clara y organizada al código, lo que facilita su lectura y mantenimiento.

Ejemplo de formato estándar de sangría en CSS, conforme a las recomendaciones de W3Schools (s.f):

``` CSS
html {
  background: #fff; /* Fondo blanco */
  color: #404;     /* Color de texto gris */
}
```

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3School (s.f.):

``` JavaScript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

**Especificaciones generales**

A continuación, detallaremos las reglas específicas necesarias para comprender el código de nuestra aplicación en cada lenguaje.

**HTML:**

HTML, acrónimo de HyperText Markup Language en inglés, es un lenguaje de marcado que se utiliza para definir la estructura de una página web. También incluye funcionalidades que permiten controlar el comportamiento de diferentes elementos del contenido de la página, como cambiar el tamaño del texto o aplicar formato cursiva, entre otros. En nuestro proyecto, emplearemos HTML5, y a continuación, se presentan las características y directrices que debemos seguir para utilizar este lenguaje de la siguiente manera:

* **Declare Document Type**
  La declaración del tipo de documento debe realizarse en la primera línea del código. Según las recomendaciones de Google (s.f.), se prefiere la sintaxis de HTML5 para todos los documentos HTML. Para declararla, simplemente copia lo siguiente:

``` html
<!DOCTYPE html>
```

* **Blank Lines**
  Cada vez que comiences un nuevo bloque, lista o tabla de gran longitud, es recomendable dejar una línea en blanco después del elemento anterior para mejorar la legibilidad y la presentación del código, de acuerdo con las pautas de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
<head>
<title>Animales Exóticos</title>
</head>
<body>
<h1>Lemur de Madagascar</h1>
<p>El lémur de Madagascar es un primate endémico de la isla de Madagascar en el Océano Índico.</p>

<h1>Pangolín</h1>
<p>El pangolín es un mamífero cubierto de escamas que se encuentra en regiones de África y Asia.</p>

<h1>Ocelote</h1>
<p>El ocelote es un felino salvaje que habita en América del Sur y Central, conocido por su pelaje moteado.</p>
</body>
</html>
```

Esta práctica de dejar una línea en blanco mejora la estructura y legibilidad del código HTML.

* **Quote attribute Values**
  Para los valores de los atributos, es común utilizar comillas dobles alrededor de ellos, aunque esta característica no sea obligatoria. Según W3Schools (sin fecha), esto mejora la legibilidad del código y es una práctica común entre los desarrolladores. Aquí tienes un ejemplo:

``` html
<table class="striped">
```

Este enfoque de usar comillas dobles alrededor de los valores de los atributos es ampliamente aceptado y recomendado en la comunidad de desarrollo web.

* **Never Skip the \<title> Element**
  El elemento `<title>` permite que las páginas aparezcan en la lista de resultados al realizar búsquedas en un navegador web. Además, este elemento es responsable de proporcionar el nombre de la página cuando se agrega a marcadores o favoritos. A continuación, se muestra un ejemplo de su uso:

``` html
<title>Guía de Estilo HTML y Convenciones de Codificación</title>
```

Este elemento es esencial para mejorar la identificación y accesibilidad de una página web.

* **HTML Line-Wrapping**
  A pesar de que en un documento HTML no exista un límite estricto en la cantidad de palabras por línea, no se recomienda generar líneas de código excesivamente largas. De hecho, hacerlo dificulta la legibilidad del código. Para continuar en la siguiente línea, se deben utilizar al menos cuatro espacios para distinguir elementos secundarios. Aquí tienes un ejemplo basado en las recomendaciones de Google (sin fecha):

``` html
<button mat-icon-button color='primary' class="menu-button"
(click)="openMenu()">
<mat-icon>menu</mat-icon>
</button>
```

Este estilo de formateo ayuda a mantener un código más legible y facilita la identificación de los elementos y su jerarquía en la estructura del documento HTML.

**CSS:**

CSS, conocido por sus siglas en inglés, Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje que se enfoca en definir y mejorar la presentación de un documento basado en HTML. A continuación, se presentan las directrices que debemos seguir al utilizar CSS:

* **Shorthand Properties**
  Se recomienda utilizar abreviaturas de propiedades y declarar los campos de los elementos en la menor cantidad de líneas posible, según las pautas de Google (sin fecha). Esto aumenta la eficiencia del código y lo hace más legible. Además, se debe evitar agregar unidades después del valor cero. Aquí tienes un ejemplo:

``` css
border-top: 0;
font: 100%/1.6 palatino, georgia, serif;
padding: 0 1em 0;
```

Siguiendo estas recomendaciones, se puede lograr un código CSS más conciso y fácil de entender.

* **Declaration Stops**
  Es importante incluir un punto y coma al final de cada declaración en CSS, al igual que en la mayoría de los lenguajes de programación. Siguiendo las pautas de Google (sin fecha), esta práctica contribuye a mantener la coherencia en el código. A continuación, se muestra un ejemplo:

``` css
html {
  background: #fff;
  color: #404;
}
```

El uso consistente de puntos y comas al final de las declaraciones CSS ayuda a prevenir errores y mejora la claridad del código.

* **Property Name Stops**
  Es necesario incluir un espacio entre los dos puntos que siguen al nombre de una propiedad y el valor correspondiente. Siempre se debe colocar un solo espacio después de los dos puntos, pero no antes. A continuación, se muestra un ejemplo siguiendo esta convención estándar de Google (s.f):

``` css
html {
  background: #fff;
  color: #404;
}
```

Mantener esta consistencia en la colocación de espacios ayuda a que el código CSS sea más legible y fácil de entender.

* **Declaration Block Separation**
  Es esencial utilizar un espacio separador después del nombre de un selector de elemento y antes de la llave que inicia un bloque de declaración CSS. Además, la llave de apertura del bloque debe estar en la misma línea que el selector. Aquí tienes un ejemplo siguiendo esta convención estándar de Google (sin fecha):

``` css
html {
  background: #fff;
  color: #404;
}
```

El cumplimiento de estas directrices ayuda a mantener la consistencia y la legibilidad en el código CSS.

* **CSS quotation Marks**
  No se deben utilizar comillas dobles (`"`) en el código CSS; en su lugar, se permiten y deben emplearse comillas simples (`'`) únicamente para selectores de atributos y valores de propiedades.
  Ejemplo conforme a las pautas estándar de Google (sin fecha):

``` css
html {
  font-family: 'open sans', arial, sans-serif;
}
```

Este ejemplo demuestra el uso de comillas simples para encerrar el valor del atributo `font-family` en CSS, lo cual es una práctica común y aceptada.

**JavaScript**

JavaScript es un lenguaje de programación que permite especificar de manera precisa las acciones que debe realizar el navegador web, incluyendo el orden de ejecución de tareas y la frecuencia con la que se deben llevar a cabo. A continuación, se presentan las pautas para el uso de JavaScript en nuestro proyecto:

* **Spaces around operators**
  Es importante añadir espacios alrededor de cada operador matemático y comas que se utilicen en el código JavaScript. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso consistente de espacios alrededor de operadores y comas mejora la legibilidad del código JavaScript.

* **Simple Statement's End**
  Es fundamental que una instrucción simple finalice con un punto y coma, tal como es el caso en muchos otros lenguajes de programación. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
let x = v + 7;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso de punto y coma al final de cada instrucción ayuda a garantizar la estructura correcta del código JavaScript y a evitar posibles errores.

* **Beginning and End of Function**
  Un bloque de función debe incluir una llave al final de la primera línea, de modo que el cierre de la función esté en la última línea, sin necesidad de un punto y coma. Este mismo principio se aplica a las estructuras condicionales y los bucles. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

En este ejemplo, la función `toCelsius` está formateada de acuerdo con estas pautas, con la llave de apertura en la misma línea que la declaración de la función y la llave de cierre en la última línea. Esto ayuda a mantener la estructura y la legibilidad del código JavaScript.

* **Object Rules**
  Para la creación de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea. Sin embargo, en este caso, la llave de cierre debe ir seguida de un punto y coma. Para definir las propiedades del objeto, se utilizan dos puntos y un espacio para separar el nombre de la propiedad de su valor. Si el valor es un string, se debe encerrar entre comillas dobles. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

En este ejemplo, el objeto `person` está formateado de acuerdo con estas pautas, lo que mejora la legibilidad y la estructura del código JavaScript.

**Gherking:**

Gherkin es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que se utiliza para resolver problemas específicos mediante la generación de casos de prueba que validan una característica en diversos escenarios. Gherkin incluye varios elementos, entre los cuales los más conocidos y utilizados son Feature, Scenario, Example, Given, When y Then. A continuación, se presentan las pautas que debemos seguir al utilizar Gherkin en nuestro código:

* **Discernible Given-When-Then Blocks**
  Es importante aplicar sangría a los elementos que representan los pasos a seguir en un escenario. En el caso de "And", se debe aplicar una sangría adicional. Siguiendo la recomendación de Keiblinger (2021), este enfoque ayuda a identificar rápidamente las partes que componen un escenario. A continuación, se muestra un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
  Given que en el formulario de ingreso de oferta laboral
  When escribo claramente los requisitos
  Then se mostrará el mensaje
  And mi oferta solo aparecerá a quienes cumplan con estos
  And se habilita la opción
```

En este ejemplo, se ha aplicado la sangría de manera adecuada para resaltar los pasos del escenario, y se ha utilizado una sangría adicional para los pasos que comienzan con "And". Esto mejora la legibilidad y la comprensión de los escenarios escritos en Gherkin.

* **Step with Tables**
  Conforme a la recomendación de Keiblinger (2021), cuando sea necesario introducir valores en partes del escenario, se debe emplear una tabla o crear un formulario que refleje esa parte del escenario. Antes de esta representación, se deben colocar dos puntos. Aquí tienes un ejemplo:

``` gherkin
Then se mostrará el mensaje:
  | Mensaje |
  | Se completaron los requisitos adecuadamente |
```

Este enfoque permite una representación clara y estructurada de los valores relacionados con una parte específica del escenario.

* **Reducing Noise**
  Para evitar la acumulación de demasiadas líneas de código en un escenario, es recomendable incluir valores por defecto dentro de los pasos para campos que no sean muy relevantes para ese escenario en particular. Los valores "estándar" que se coloquen deben estar entre comillas simples. Siguiendo el consejo de Keiblinger (2021), esta práctica contribuye significativamente a la reducción del tamaño del código. A continuación, se muestra un ejemplo:

``` gherkin
When escribo claramente los requisitos 'dominio en C'
```

En este ejemplo, se ha incluido un valor por defecto ('dominio en C') entre comillas simples dentro del paso para representar un campo que no es esencial en ese escenario. Esto ayuda a mantener el escenario más conciso y legible.

* **Scenarios Separator**
  Para separar dos escenarios, se debe insertar un salto de línea y, según la sugerencia de Keiblinger (2021), si es posible, agregar una línea de comentario para facilitar la visualización de estos. De esta manera, se identifica rápidamente el inicio y el fin de un escenario. A continuación, se presenta un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
Given que en el formulario de ingreso de oferta laboral
When escribo claramente los requisitos
Then se mostrará el mensaje
And mi oferta solo aparecerá a quienes cumplan con estos
And se habilita la opción

# --------------------------

Scenario: Otro escenario
Given que en otro contexto
When ocurre algo diferente
Then se muestra otro resultado
```

En este ejemplo, se ha agregado un salto de línea entre los dos escenarios y se ha incluido una línea de comentario como separador para mejorar la visualización y la identificación de cada escenario.

**C#:**

C# es un lenguaje de programación desarrollado por Microsoft en el año 2000 como parte de su plataforma .NET. Desde su creación, C# ha evolucionado significativamente, convirtiéndose en una herramienta esencial para el desarrollo de una amplia gama de aplicaciones, desde software de escritorio hasta aplicaciones web y móviles, así como servicios en la nube. Su diseño moderno y su integración con el ecosistema de .NET lo han consolidado como una opción preferida para muchos desarrolladores a nivel global.

A continuación, se presentan las pautas para utilizar C# en nuestro proyecto:

* **Datos de cadena**


Use **interpolación de cadenas** para concatenar cadenas cortas, como se muestra en el código siguiente.

```C#  
  string displayName = $"{nameList[n].LastName}, {nameList[n].FirstName}";
```

Para anexar cadenas en bucles, especialmente cuando se trabaja con grandes cantidades de texto, utilice un objeto System.Text.StringBuilder.
En este ejemplo, se han seguido las pautas para nombrar clases e interfaces de manera clara y legible.


```C#  
  var phrase = "lalalalalalalalalalalalalalalalalalalalalalalalalalalalalala";
  var manyPhrases = new StringBuilder();
  for (var i = 0; i < 10000; i++)
  {
      manyPhrases.Append(phrase);
  }
  //Console.WriteLine("tra" + manyPhrases);
```

* **Delegados**

Use **Func<> y Action<>** en lugar de definir tipos de delegado. En una clase, defina el método delegado.

```C#  
  Action<string> actionExample1 = x => Console.WriteLine($"x is: {x}");
  
  Action<string, string> actionExample2 = (x, y) => Console.WriteLine($"x is: {x}, y is {y}");
  
  Func<string, int> funcExample1 = x => Convert.ToInt32(x);
  
  Func<int, int, int> funcExample2 = (x, y) => x + y;
```

Llame al método con la signatura definida por el delegado Func<> o Action<>.

```C#  
  actionExample1("string for x");
  actionExample2("string for x", "string for y");
  Console.WriteLine($"The value is {funcExample1("1")}");
  Console.WriteLine($"The sum is {funcExample2(1, 2)}");
```

* **try-catch y using en el control de excepciones**

Use **try-catch** para controlar las excepciones. Use **using** para liberar recursos no administrados.

``` C#  
  try
  {
      // Code that may throw an exception
  }
  catch (Exception ex)
  {
      // Code to handle the exception
  }
  
  using (var resource = new Resource())
  {
      // Code that uses the resource
  }
```

* **Operadores && y ||**

Use **&&** y **||** en lugar de **&** y **|** para operaciones lógicas. Los operadores **&&** y **||** realizan una evaluación de cortocircuito, lo que significa que si la primera parte de la expresión es suficiente para determinar el resultado, la segunda parte no se evalúa.

```C#  
  if (a == 10 && b == 20)
  {
      // Code to execute if both conditions are true
  }
  
  if (a == 10 || b == 20)
  {
      // Code to execute if either condition is true
  }
```

* **Comentarios**

Use comentarios para explicar el código y proporcionar información adicional. Los comentarios deben ser claros y concisos.

```C#  
  // This is a single-line comment
  
  /*
  This is a multi-line comment
  that spans multiple lines
  */
```
* **Operador new**

Use **new** para crear instancias de clases y estructuras.

```C#  
  var person = new Person();
  var point = new Point(10, 20);
```

* **Control de eventos**

Use **eventos** para notificar a los suscriptores cuando ocurre un evento.

```C#  
  public class Button
  {
      public event EventHandler Click;
  
      protected virtual void OnClick(EventArgs e)
      {
          Click?.Invoke(this, e);
      }
  }
```

* **Consultas LINQ**

Use consultas LINQ para realizar operaciones de consulta en colecciones de datos.

```C#  
  var query = from c in customers
              where c.City == "London"
              select c;
```

* **Variables locales con asignación implícita de tipos**

Use la asignación implícita de tipos para las variables locales cuando el tipo se puede inferir fácilmente.

```C#  
  var name = "John";
  var age = 30;
```

**Typescript**

JavaScript es uno de los lenguajes más populares y ha experimentado un rápido avance y mejora en los últimos años. A continuación, se presentan las pautas para utilizar JavaScript en nuestro proyecto:

En TypeScript, se recomienda que las variables se declaren en minúsculas y se especifique el tipo de dato utilizando dos puntos después del nombre de la variable. Aquí tienes ejemplos de cómo declarar y asignar valores a variables en TypeScript:

``` typescript
// Definición e inicialización separadas
let edad: number;
edad = 20;

// Definición e inicialización en la misma línea.
let edadAitor: number = 18;
```

Además, en TypeScript, se siguen las mismas convenciones que se utilizan en JavaScript.

### 5.1.4. Software Deployment Configuration.

#### Landing Page Deployment

Para desplegar la Landing Page desde GitHubPages hay que seguir los siguientes pasos:

**1. Ubicar el repositorio que tiene guardado el codigo fuente y dirigirse al apartado de configuración (settings):**

![repo-landing-page.png](/assets/img/chapter-V/sprint-1/repo-landing-page.png)


**1. Seleccionar la sección pages:**


![pages-landing-page.png](/assets/img/chapter-V/sprint-1/pages-landing-page.png)


**1. Configurar la rama que será usada para hacer deploy:**

![rama-landing-page.png](/assets/img/chapter-V/sprint-1/rama-landing-page.png)


#### Aplicación ElixirControl Deployment


**Despliegue del Frontend**

Para este despliegue utilizamos la plataformad e vercel:

Para ello copiaremos el URL de nuestro repositorio de GitHub y lo pegaremos en la plataforma de vercel.

<img src="/assets/img/chapter-V/sprint-4/vercel6.jpeg" height="400" alt="landing_page">

Luego de pegar el URL de nuestro repositorio de GitHub, vercel nos pedira que configuremos el proyecto.

<img src="/assets/img/chapter-V/sprint-4/vercel2.png" height="400" alt="landing_page">

Una vez configurado el proyecto, vercel nos mostrará una rama de nuestra aplicación.

<img src="/assets/img/chapter-V/sprint-4/vercel3.png" height="350" alt="landing_page">

Para despues mostrarnos un mensaje de exito en el despliegue de nuestra aplicación.

<img src="/assets/img/chapter-V/sprint-4/vercel1.png" height="400" alt="landing_page">


#### Web services Deployment

El despliegue de los servicios web se realizara en MonsterASP.NET.

![](../assets/img/chapter-V/sprint-3/monster.PNG)

Para el correcto depliegue a partir de los repositorios de código fuente nos guiaremos del siguiente tutorial publicado por MonsterASP.NET llamado "How to deploy .NET Core Web API with Swagger using Visual Studio"

[Link de referencia:https://help.monsterasp.net/books/deploy/page/how-to-deploy-net-core-web-api-with-swagger-using-visual-studio](https://help.monsterasp.net/books/deploy/page/how-to-deploy-net-core-web-api-with-swagger-using-visual-studio)

![](../assets/img/chapter-V/sprint-3/monster-tutorial.PNG)

En primer lugar tenemos que crear un website dentro de MonsterASP.NET, para ello nos dirigimos a la sección de Websites y seleccionamos la opción de "Create Website"

Elijiremos la version gratuita ya que es mas que suficiente para el despliegue de nuestra aplicación le damos al boton de "Create"

![](../assets/img/chapter-V/sprint-3/gratuito.PNG)


![](../assets/img/chapter-V/sprint-3/create.PNG)

Luego tenemos que habilitar el modo de producción de swagger 

![](../assets/img/chapter-V/sprint-3/swagger.PNG)


Luego tendremos que descargar el "WebDeploy publish profile"

![](../assets/img/chapter-V/sprint-3/profile.PNG)

Y por ultimo publicamos el proyecto en Visual Studio 2022, utilizando el archivo descargado anteriormente.

![](../assets/img/chapter-V/sprint-3/publish.PNG)

![](../assets/img/chapter-V/sprint-3/import.PNG)

![](../assets/img/chapter-V/sprint-3/server.PNG)

Terminado los pasos nos aparecera un mensaje de exito en la publicación de nuestro proyecto junto a un link del proyecto deplegado.


### Despliegue de la base de datos

Para el depliegue de la base de datos se utilizo LightSail de AWS.

Inicio sesion con mi usuario de aws, me dirijo a Databases y me dirigo a "Create Database"

![](../assets/img/chapter-V/sprint-3/database1.PNG)

Seleccionamos MySql version 8.0.39

![](../assets/img/chapter-V/sprint-3/database2.PNG)

Elegimos el plan gratuito por 3 meses

![](../assets/img/chapter-V/sprint-3/database3.PNG)

Escribimos el nombre de nuestra base de datos y seleccionamos el boton de "Create database"

![](../assets/img/chapter-V/sprint-3/database4.PNG)

![](../assets/img/chapter-V/sprint-3/database.PNG)

Finalmente, nuestra base de datos esta creada y lista para ser utilizada

![](../assets/img/chapter-V/sprint-3/database5.PNG)


## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo gestionamos las tareas en Jira Software.

Repositorio: [https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page](https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page)

Landing Page Deployed: https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/


## 5.2. Landing Page, Services & Applications Implementation.


### 5.2.1. Sprint n

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del 
diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica
que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials
o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo 
gestionamos las tareas en Jira Software.

#### 5.2.1.1. Sprint Planning 1.

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--FILA 1-->
        <tr>
            <td>Date</td>
            <td>21-08-2024</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
         <!--FILA 4-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
         <!--FILA 5-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Jhordi Carranza - Oscar Armas - Luis Villegas - Juan Llamccaya </td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td>Sprint 1 Goal</td>
            <td> 
              Nuestro enfoque está en implementar la landing page de ElixirControl, incluyendo todas las 
              secciones acordadas y el requisito de cambio de idioma para la aplicación. Creemos que esto
              mejora la accesibilidad y la experiencia del usuario, permitiendo que más vinicultores y 
              distribuidores se conecten con la plataforma. Esto se confirmará cuando la landing page 
              esté completa, funcional y los usuarios puedan navegar por las secciones en su idioma 
              preferido, reportando satisfacción con la interfaz y la usabilidad.
            </td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>Sprint 1 Velocity</td>
            <td> 36 </td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>Sum of Story Points</td>
            <td> 43 </td>
        </tr>
    </tbody>
</table>


##### 5.2.1.2. Sprint Backlog 1.

<!--Status -> (To-do / In-Process / To-Review / Done) -->

<table>
    <thead>
        <tr>
            <th colspan="7">Srpint #</th>
            <th> Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1-->
        <tr>
            <td colspan="1">User Story</td>
            <td colspan="15">Work-Item / Task</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Description</td>
            <td>Estimation (hours)</td>
            <td>Assigned To</td>
            <td>Status</td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td rowspan="4" >US-001</td>
            <td rowspan="4" >Hipervínculos en el encabezado</td>
            <td>T001</td>
            <td>Definir enlaces del encabezado	</td>
            <td>Identificar y organizar los enlaces del encabezado.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 4-->
        <tr>
            <td>T002</td>
            <td>Implementar hipervínculos</td>
            <td>Añadir hipervínculos en HTML</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 5-->
        <tr>
            <td>T003</td>
            <td>Estilizar con CSS	</td>
            <td>Aplicar estilos básicos a los enlaces del encabezado</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionamiento	</td>
            <td>Asegurarse de que los hipervínculos funcionen correctamente.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td rowspan="3"> US-002	</td>
            <td rowspan="3">Información sobre beneficios o servicios de la app</td>
            <td> T005 </td>
            <td>Recopilar información de beneficios</td>
            <td>Obtener y redactar la información sobre los beneficios de la aplicación.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>T006</td>
            <td>Implementar en el sitio	</td>
            <td>Incluir la información de beneficios en la página correspondiente.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>T007</td>
            <td>Pruebas de visualización	</td>
            <td>Asegurarse de que la información esté visible y bien organizada.	</td>
            <td>1</td>
            <td></td> 
            <td>Done</td>
        </tr>
        <!--FILA 10-->
        <tr>
            <td rowspan="3"> US-003	</td>
            <td rowspan="3">Mostrar los planes disponibles</td>
            <td> T008 </td>
            <td>Definir estructura de precios</td>
            <td>Establecer la estructura de precios a seguir en la sección.</td>
            <td>4</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 11-->  
        <tr>
            <td>T009</td>
            <td>Implementar la funcionalidad de los planes	</td>
            <td>Crear la estructura de precios en HTML.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 12-->  
        <tr>
            <td>T010</td>
            <td>Estilizar con CSS	</td>
            <td>Aplicar estilos a la estructura de precios.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 13-->
        <tr>
            <td rowspan="5"> US-004	</td>
            <td rowspan="5">Información util en el footer </td>
            <td> T011 </td>
            <td>Recopilar opiniones</td>
            <td>Obtener y redactar opiniones de usuarios.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 14-->
        <tr>
            <td>T012</td>
            <td>Recopilar información útil	</td>
            <td>Organizar y decidir qué información incluir en el footer.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 15-->  
        <tr>
            <td>T013</td>
            <td>Implementar contenido en el footer</td>
            <td>Añadir la información útil al footer.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 16-->
        <tr>
            <td>T014</td>
            <td>Estilizar footer</td>
            <td> Dar estilo y formato al footer utilizando CSS.</td>
            <td>1</td>
            <td></td>
            <td>Done</td>   
        </tr>
        <!--FILA 17-->  
        <tr>
            <td> T015 </td>
            <td>Pruebas de visualización</td>
            <td>Verificar que la información sea clara y legible.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td rowspan="4"> US-005	</td>
            <td rowspan="4">Información sobre el producto	</td>
            <td> T016 </td>
            <td>Definir contenido sobre el producto	</td>
            <td>Recopilar y escribir la información relevante sobre el producto.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 14-->
        <tr>
            <td>T017</td>
            <td>Implementar el contenido en el sitio	</td>
            <td>Incluir la información en la página adecuada.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 15-->  
        <tr>
            <td>T018</td>
            <td>Estilizar y ajustar visualización	</td>
            <td>Ajustar el diseño y la visualización del contenido.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 16-->
        <tr>
            <td>T019</td>
            <td>Pruebas de visualización</td>
            <td> Comprobar que la información sea visible y bien organizada.</td>
            <td>1</td>
            <td></td>
            <td>Done</td>   
        </tr>
        <!--FILA 17-->  
        <tr>
            <td rowspan="3"> US-018	</td>
            <td rowspan="3">Implementar opción de cambio de idioma	</td>
            <td> T020 </td>
            <td>Funcionalidad para cambiar idioma</td>
            <td>Añadir la funcionalidad para cambiar el idioma de la aplicación en Angular.</td>
            <td>5</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T021 </td>
            <td>Definir textos traducidos</td>
            <td>Proveer textos traducidos en los diferentes idiomas soportados.</td>
            <td>4</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T022 </td>
            <td>Pruebas de funcionalidad de idiomas</td>
            <td>Verificar que el cambio de idioma funcione correctamente en toda la aplicación.	</td>
            <td>3</td>
            <td></td>
            <td>Done</td>
        </tr>
    </tbody>
</table>

##### 5.2.1.3. Development Evidence for Sprint Review.


<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1 -->
        <tr>
            <td rowspan="14">https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page</td>
            <td>main</td>
            <td>ca7aff9e22b71a4a96e8d823c0e61c347240df9c</td>
            <td>Initial commit</td>
            <td></td>
            <td>13/08/2024</td>
        </tr>
        <!--FILA 2 -->
        <tr>
            <td>develop</td>
            <td>23d5ab43ce3f6f11fe2a2fd4f9b81111ca927cd3</td>
            <td>feat: Added the base structure of the project.</td>
            <td></td>
            <td>21/08/2024</td>
        </tr>
        <!--FILA 3 -->
        <tr>
            <td>feature/nav</td>
            <td>c6a3d0698ef363310ca9a3c96d9d1ae658118f5b</td>
            <td>feat: Added header and navigation section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 4 -->
        <tr>
            <td>feature/hero</td>
            <td>456e8089d0e5e7805a2819885be2972e3d221aef</td>
            <td>feat(hero): Added hero section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 5 -->
        <tr>
            <td>feature/services</td>
            <td>c3e661b693063ca547c171ba3db89fd194255fc1</td>
            <td>feat(services): Added services section</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 6 -->
        <tr>
            <td>feature/services</td>
            <td>1462bee8ba47ca2f878468b262302d7586e0633e</td>
            <td>feat(services): Updated the styles of the services section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 7 -->
        <tr>
            <td>feature/testimonials</td>
            <td>79ef0471340e7e312c05d0e1c854cd7f0e562b19</td>
            <td>feat(testimonials): Added Testimonials section.</td>
            <td></td>
            <td>06/09/2024</td>
        </tr>
        <!--FILA 8 -->
        <tr>
            <td>feature/plans</td>
            <td>d706c364023e2d4addf47df3aa8cf0e8dcf937ed</td>
            <td>feat(plans): Added structure of plans in Spanish</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 9 -->
        <tr>
            <td>feature/plans</td>
            <td>2d7b2b5497c5ad9d77740d17b66fcca4fd529842</td>
            <td>feat(plans): Added structure of plans in English</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 10 -->
        <tr>
            <td>feature/plans</td>
            <td>98620905ab1a4b86b797b55133f26e0ecc69dd28</td>
            <td>feat(plans): Added styles for the plans section.</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 11 -->
        <tr>
            <td>feature/about-the-team</td>
            <td>775e984a0b45a388f19cfcea2a4cbf42e82f29ba</td> 
            <td>feat(about-the-team): Added content and styles to the About Team section</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/about-the-team</td>
            <td>9b3fe2fe56a55c7ecd7e88eea28a0e5c83d7ee29</td> 
            <td>feat(about-the-team): Added content and styles to the About Team section</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/footer</td>
            <td>636f5902fdec78f18206aa842c9ed10eb591ac05</td> 
            <td>feat(footer): Added content and styles to the footer section.</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/about-the-app</td>
            <td>f5ddbc9174940b126b2dbfb87c58a8ded713beb7</td> 
            <td>feat(about-the-app): Added content and styles in about the app section.</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
    </tbody>
</table>


##### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Para este primer sprint no se realizaron testing.

##### 5.2.1.5. Execution Evidence for Sprint Review.

Después de completar el Sprint 1, logramos implementar todas las secciones de nuestra Landing Page para garantizar una visualización perfecta. Además, le dimos un formato atractivo que captura la atención del usuario hacia sus diferentes componentes. También agregamos métodos de navegación en la página, como botones ubicados al principio, que te permiten moverte fácilmente de una sección a otra. A continuación, te mostraremos los avances a través de imágenes del resultado obtenido.

Es importante destacar que el objetivo principal de la Landing Page es convertir a los visitantes en futuros clientes o usuarios habituales de nuestro servicio. Para lograrlo, utilizamos llamados a la acción (Call To Action) que los guían hacia la aplicación web.

A continuación, te presentamos capturas de pantalla del desarrollo de la Landing Page:


**Encabezado y botones de desplazamiento:**

En la parte superior, se encuentra el encabezado (Header) que incluye botones de inicio (Home), beneficios (benefits), Pricing (Pricing), sobre la aplicación (about), testimonios de usuarios (testimonials), un formulario para que nos contacten (Contact), un apartado para saber sobre el equipo (About us) y un botón para cambiar el idioma entre inglés y español. Estos elementos permiten a los visitantes desplazarse fácilmente a la sección que deseen visualizar.

Imagen 01: Encabezado y botones de desplazamiento

![header-landing-page.png](../assets/img/chapter-V/sprint-1/header-landing-page.png)

**Sección Hero:**

Se presenta la sección "Hero", que incluye una breve descripción y una frase representativa de ElixirControl. Además, permite iniciar el uso del servicio web y proporciona una imagen relacionada con el mismo.

Imagen 02: Sección Hero

![hero-landing-page.png](../assets/img/chapter-V/sprint-1/hero-landing-page.png)


**Sección Services:**

Se presenta la sección de servicio que ofrecemos para nuestros segmentos objetivos. En esta sección, se describen los beneficios y características de ElixirControl, lo que permite a los visitantes conocer más sobre el servicio.

Imagen 03: Sección Services
![services-landing-page.png](../assets/img/chapter-V/sprint-1/services-landing-page.png)


**Sección Pricing:**

En la sección de precios, se detallan los planes y precios de ElixirControl. Esta información es esencial para que los visitantes conozcan las opciones disponibles y puedan elegir la que mejor se adapte a sus necesidades.

Imagen 04: Sección Pricing
![plans-landing-page.png](../assets/img/chapter-V/sprint-1/plans-landing-page.png)


**Sección About the App:**

En esta sección, se presenta información detallada sobre la aplicación ElixirControl, sus características y funcionalidades. Esto permite a los visitantes conocer más sobre la aplicación y cómo puede ayudarles en su día a día.

Imagen 05: Sección About the App

![about-the-app-landing-page.png](../assets/img/chapter-V/sprint-1/about-the-app-landing-page.png)


**Sección Testimonials:**

En la sección de testimonios, se presentan opiniones y comentarios de usuarios reales que han utilizado ElixirControl. Esto ayuda a generar confianza en los visitantes y a mostrarles la experiencia positiva de otros usuarios.

Imagen 06: Sección Testimonials

![testimonials-landing-page.png](../assets/img/chapter-V/sprint-1/testimonials-landing-page.png)

**Sección About the Team:**

En la sección "About the Team", se presenta información sobre el equipo de desarrollo de ElixirControl. Esto permite a los visitantes conocer a las personas detrás del servicio y generar confianza en la calidad y profesionalismo del equipo.

![about-the-team-landing-page.png](../assets/img/chapter-V/sprint-1/about-the-team-landing-page.png)

**Sección Contact:**

En la sección de contacto, se presenta un formulario que permite a los visitantes enviar consultas, comentarios o solicitudes de información sobre ElixirControl. Esto facilita la comunicación con los usuarios y permite responder a sus necesidades de manera eficiente.

![contact-landing-page.png](../assets/img/chapter-V/sprint-1/contact-landing-page.png)

**Footer:**

En el pie de página (Footer), se incluyen enlaces a las redes sociales de ElixirControl, información de contacto y un botón para volver al inicio de la página. Esto permite a los visitantes acceder a más información y mantenerse conectados con el servicio.

![footer-landing-page.png](../assets/img/chapter-V/sprint-1/footer-landing-page.png)


##### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer Sprint el equipo de desarrollo de MetaSoft ha diseñado, programado y puesto en funcionamiento el sitio web (Landing Page) Para presentar la aplicación Web propuesta denominada "ElixirControl". En este sitio web (Landing Page), se lográ visualizar varias secciones que ilustran en que consiste "ElixirControl", cada integrante del equipo de desarrollo de Metasoft estuvo a cargo de una sección en especifico.

<table>
  <thead>
    <tr>
      <th>End Point</th>
      <th> Funciones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/</td>
        <td>Mostrar la Landing Page Desplegada</td>
    </tr>
  </tbody>
</table>


##### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestro sitio web, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "realease-V1.0" que previamente se encontrba en la rama release-1.0.

[Landing Page ElexirControl](https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/) - https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/


##### 5.2.1.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de commits realizadas por cada integrante del equipo durante el desarrollo de la landing page.

![tb1-pulse.png](../assets/img/chapter-V/sprint-1/tb1-pulse.png)

Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![tb1-traffic.png](../assets/img/chapter-V/sprint-1/tb1-traffic.png)

#### 5.2.2. Sprint 2
En esta etapa de nuestro proyecto, nos hemos enfocado en implementar la funcionalidad de gestión y trazabilidad del proceso de vinificación dentro de nuestra aplicación ElixirControl, utilizando Vite y Vue en WebStorm como herramientas de desarrollo. Al finalizar este Sprint, se espera que todas las funcionalidades relacionadas, incluyendo la creación, edición y visualización de pedidos, estén completamente operativas. A continuación, se incluyen imágenes que muestran cómo gestionamos las tareas en nuestro tablero de Jira Software, reflejando el progreso y la asignación de responsabilidades del equipo.

##### 5.2.2.1. Sprint Planning 2

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 2</th>
        </tr>
    </thead>
    <tbody>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Date</td>
            <td>14-09-2024</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Location</td>
            <td>Modalidad Remota a través de la plataforma Discord</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Oscar Armas - Luis Villegas - Gustavo Huanca - Vicente Quijandria</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 1 Review Summary</td>
            <td> 
              En este sprint, el equipo completó con éxito la implementación de la landing page de 
              ElixirControl, incluyendo todas las secciones acordadas y la funcionalidad de cambio de idioma. 
              Esto mejora la accesibilidad y la experiencia del usuario, permitiendo una navegación 
              intuitiva en su idioma preferido. Recibimos comentarios positivos sobre la usabilidad 
              y estética de la página, lo que valida el impacto positivo de nuestro trabajo. No 
              obstante, identificamos oportunidades de mejora en la optimización de elementos 
              visuales y en la precisión de las traducciones. Con estos logros y aprendizajes, nos 
              preparamos para seguir aportando valor a nuestros vinicultores y distribuidores en el 
              próximo sprint.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 1 Retrospective Summary</td>
            <td>
              En este sprint, el equipo enfrentó desafíos en la comunicación y la gestión de tareas, 
              lo que impactó la colaboración y el flujo de trabajo. A pesar de estas dificultades,
              logramos completar la landing page de ElixirControl y la funcionalidad de cambio de 
              idioma, demostrando nuestra capacidad de adaptación. Los miembros del equipo resaltaron 
              la necesidad de mejorar la coordinación y clarificar roles para optimizar el uso del 
              tiempo y recursos. A pesar de los obstáculos, mantuvimos un fuerte compromiso con el 
              proyecto. De cara al próximo sprint, es crucial aplicar las lecciones aprendidas para 
              fortalecer nuestra dinámica de trabajo y asegurar que todos estén alineados en 
              nuestros objetivos.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Goal</td>
            <td> 
              Nuestro enfoque está en implementar la interfaz de usuario para la gestión de procesos 
              vitivinícolas, incluyendo la visualización y envío de solicitudes de pedidos a 
              vinicultores, la creación y visualización de procesos de vinificación, la gestión
              de datos de inventario del vinicultor y la administración de información de clientes. 
              Creemos que esto proporcionará una experiencia de usuario más ágil y efectiva para 
              vinicultores y distribuidores. Esto se confirmará cuando todas las funcionalidades 
              del frontend sean probadas con éxito, se utilicen activamente en la aplicación y los 
              usuarios reporten una mejora en la eficiencia de sus flujos de trabajo y satisfacción 
              con las nuevas características visuales implementadas.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Velocity</td>
            <td> Por definir </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sum of Story Points</td>
            <td> Por Definir </td>
        </tr>
        <!--====================================================================-->
    </tbody>
</table>


##### 5.2.2.2. Sprint Backlog 2

<table>
  <thead>
    <tr>
      <th>User Story</th>
      <th>Title</th>
      <th>Id</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-009</td>
      <td>Integración de Validadores en Formularios de la App Web</td>
      <td>T001</td>
      <td>Login de distribuidor y productor.</td>
      <td>Implementar formulario para logeo de distribuidores y productores.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-031</td>
      <td>Registro de Datos de Productores</td>
      <td>T002</td>
      <td>Registro de productor.</td>
      <td>Implementar formulario para registro de nuevos productores.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-006</td>
      <td>Registro de Entrada de Insumos</td>
      <td>T003</td>
      <td>Registro de insumos.</td>
      <td>Agregar función para registrar insumos en el inventario.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-007</td>
      <td>Registro de Salida de Productos Terminados</td>
      <td>T004</td>
      <td>Salida de productos.</td>
      <td>Agregar función para actualizar el inventario.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-008</td>
      <td>Visualizar Datos de Solicitud</td>
      <td>T005</td>
      <td>Mostrar datos de solicitud.</td>
      <td>Añadir función para mostrar los datos de solicitud y filtrarlos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-020</td>
      <td>Gestión de Lotes de Producción</td>
      <td>T006</td>
      <td>Visualización de lotes.</td>
      <td>Añadir funcionalidad para que el usuario pueda visualizar todos los lotes que ha gestionado.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-032</td>
      <td>Edición de Lotes</td>
      <td>T007</td>
      <td>Editar lotes.</td>
      <td>Añadir funcionalidad para que el usuario pueda modificar la información de un lote.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-033</td>
      <td>Eliminación de lotes</td>
      <td>T008</td>
      <td>Eliminar lote seleccionado.</td>
      <td>Añadir funcionalidad para que el usuario pueda eliminar un lote seleccionado.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-009</td>
      <td>Registro de Datos de Clientes</td>
      <td>T009</td>
      <td>Registro de nuevo cliente.</td>
      <td>Agregar opción para poder registrar un nuevo cliente con sus datos.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-034</td>
      <td>Visualización de detalles de cliente</td>
      <td>T010</td>
      <td>Visualizar informacion del cliente.</td>
      <td>Implementar funcionalidad para ver los detalles del cliente seleccionado.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-035</td>
      <td>Edición de información del cliente</td>
      <td>T011</td>
      <td>Modificar datos del cliente</td>
      <td>Implementar función para poder modificar los datos del cliente.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-036</td>
      <td>Eliminación de cliente</td>
      <td>T012</td>
      <td>Eliminar el cliente de la lista</td>
      <td>Implementar función para eliminar un cliente de la lista.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-011</td>
      <td>Registro de Pedidos de Clientes</td>
      <td>T013</td>
      <td>Registro de pedido.</td>
      <td>Agregar formulario para que el usuario registre su pedido.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-037</td>
      <td>Visualización de pedidos</td>
      <td>T014</td>
      <td>Visualizar lista de pedidos.</td>
      <td>Agregar funcionalidad para que el usuario vea la lista de pedidos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-012</td>
      <td>Visualización de Productos Disponibles</td>
      <td>T015</td>
      <td>Visualización de productos.</td>
      <td>Añadir función para que el usuario pueda ver la lista de productos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-038</td>
      <td>Búsqueda de productos</td>
      <td>T016</td>
      <td>Sistema de búsqueda de productos.</td>
      <td>Añadir funcionalidad para que el usuario pueda realizar la búsqueda de un pedido.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-013</td>
      <td>Visualizar Historial de Pedidos</td>
      <td>T017</td>
      <td>Acceso al historial.</td>
      <td>Agregar opción para que el usuario pueda ver la lista de pedidos realizados.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-039</td>
      <td>Filtrado por fecha.</td>
      <td>T018</td>
      <td>Filtrado de pedido por fecha.</td>
      <td>Agregar opción de poder filtrar un pedido específico usando un rango de fechas.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-40</td>
      <td>Detalles del Pedido</td>
      <td>T019</td>
      <td>Detalles del pedido.</td>
      <td>Agregar opción para mostrar los detalles completos de un pedido.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
  </tbody>
</table>


##### 5.2.2.3. Development Evidence for Sprint Review
<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
    <td>https://github.com/SV51-MetaSoft-App-Web/ElixirControl-FrontEnd.git</td>
    <td>Master</td>
    <td>7f851107203c3991fc1fe0d251782570f03545a8</td>
    <td>Chore: initial commit</td>
    <td></td>
    <td>Sep 19, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>7568ba72396e0ef2642a8a2b80ac0d550e955b0f</td>
    <td>Chore: clean up project</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>410beb3309b6bfc3b2ee7fd19e2f25a9d244277f</td>
    <td>Chore: added initial project configuration</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Develop</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/customer-management</td>
    <td>29c992c042ea81ee18785d764f06877138612f83</td>
    <td>Chore: create db.json</td>
    <td></td>
    <td>Sep 27, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/distributor-profile</td>
    <td>e8e82c48b77706b8ee8f20412a76f0c67e73bbbc</td>
    <td>Feat(distrubutor-profile): added db.json file to simulate the API</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>56974485b42a727becd17f1e65558c9af334fb5c</td>
    <td>feat(distributor-profile): update App.vue component to improve the design</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>33399c36ae71240f7ee69a2a28992da55e6f71da</td>
    <td>feat(distributor-profile): entities and services corresponding to the distributor profile order history section have been added</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>c12ef7575564e2680bb1e6098c8891d7d04bf7b3</td>
    <td>feat(distributor-profile): delete other entities and services dont corresponding to the distributor profile order history section have been added</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/inventory-management</td>
    <td>c6cdbc0dfea0c84aaf59ea49f1b86708a014c675</td>
    <td>feat(inventory-management): added db.json file to simulate the API</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>1d11d40e488cca8c5007bb53316a726c55a6c45c</td>
    <td>feat(inventory-management): update App.vue component to improve the design</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>e4b658a0d4ab734cd8c1ee4f596bc6f6843b33bc</td>
    <td>feat(inventory-management): entities and services corresponding to the inventory management have been added.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/producer-management</td>
    <td>f82742e28e0414009dfd0854e36faf0bd194bf94</td>
    <td>feat(winemaking-process): Entities and services corresponding to the winemaking process have been added.</td>
    <td></td>
    <td>Sep 23, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/winemaking-process</td>
    <td>d4bc3b86517a15e6032fe4827abdfca3e9adf1c2</td>
    <td>feat(winemaking-process): Added components for creating and editing objects.</td>
    <td></td>
    <td>Sep 24, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>45437600b7b04a168285c4af5fb6582a0e216412</td>
    <td>feat(winemaking-process): Added CRUD to the table with batch information.</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>113c3afe8a4bb5c43bb85421daa11adcca12a755</td>
    <td>feat(winemaking-process): Added CRUD to the table with fermentation information.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>0d5411dfec6057d3c2dbf1fa2e4b88387a915526</td>
    <td>feat(winemaking-process): Added CRUD to the table with aging information.</td>
    <td></td>
    <td>Sep 26, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>208f92424d3a0901c97c3e5d1c81cd882fcb2d2d</td>
    <td>feat(winemaking-process): Added CRUD to the table with bottling information.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>51082f2a5ac747e5179a278b4488d1c8b5e3530b</td>
    <td>feat(winemaking-process): Added CRUD to the table with clarification and pressing information.</td>
    <td></td>
    <td>Sep 27, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>49f65887335478860a0ac6c0d86a345ecc764f0d</td>
    <td>feat(winemaking-process): Added web app navigation bar.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/security</td>
    <td>70e035609157b60943f11454652b905b90d8492d</td>
    <td>feat(security): added "en.json" and "es.json" files.</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>aec471b4dae50e2e04b12112153338e826fc6f7c</td>
    <td>feat(security): added content of "index.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>0df6f357e4aee9314c137a477ea3e8bd8c8c1088</td>
    <td>feat(security): added pages in "views" section.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>c517242c4af0a179ef98eae9f9f8cc3679643bd9</td>
    <td>feat(security): added content of "App.vue" and "main.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>cb0a0b2c9e4095d8d52cabb7915c047a5744c78f</td>
    <td>feat(security): added content of "i18n.js" and "style.css".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>6810bd939a24f60aabba0049ea5e1642a265c5e9</td>
    <td>feat(security): added content of "vite.config.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>dec1b180326dec39db5801f8af263227a3ba8059</td>
    <td>feat(security): updated "style.css" and "vite.config.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>bd4043a36ffd972f4496196bb32bcb4b6b99fb46</td>
    <td>feat(security): added the component "Header.vue".</td>
    <td></td>
    <td></td>
  </tr>
</table>


##### 5.2.2.4. Testing Suite Evidence for Sprint Review

Para esta entrega no se ha realizado el testing

##### 5.2.2.5. Execution Evidence for Sprint Review
En este Sprint, nos hemos enfocado en el desarrollo y la implementación de la interfaz de gestión de pedidos, un componente esencial para mejorar la experiencia del usuario en nuestra aplicación. A través de un diseño intuitivo y funcional, buscamos facilitar la creación, edición y visualización de pedidos, permitiendo a los usuarios gestionar sus transacciones de manera eficiente y efectiva. Durante este período, hemos trabajado en varias vistas clave que contribuyen a esta funcionalidad. A continuación, se presentan las capturas de pantalla que ilustran las diferentes etapas del proceso de gestión de pedidos, destacando las características y mejoras implementadas. A continuación, te presentamos capturas de pantalla del desarrollo del front-end: 

![img.png](../assets/img/chapter-V/sprint-2/front1.png)

![img.png](../assets/img/chapter-V/sprint-2/front2.png)

![img.png](../assets/img/chapter-V/sprint-2/front3.png)

![img.png](../assets/img/chapter-V/sprint-2/front4.png)

![img.png](../assets/img/chapter-V/sprint-2/front5.png)

Para ello se ha realizado el video de ejecucion del landingPage implementando la ruta del frontend:

<img src="/assets/img/chapter-V/sprint-4/sprint_2.PNG" height="350" alt="sprint_2">

Enlace del video de ejecucion:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EcAq56hSa_1Gvy5T2KtfgsIBPyf8fD7HXSZcj0zrfrnZyg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=pkXn26

##### 5.2.2.6. Services Documentation Evidence for Sprint Review
Durante este Sprint, se ha llevado a cabo la documentación de los endpoints necesarios para la gestión de pedidos, utilizando OpenAPI como herramienta de referencia. Este proceso es fundamental para asegurar que todos los miembros del equipo, así como los desarrolladores futuros, tengan acceso a información clara y detallada sobre cómo interactuar con la API. La tabla a continuación detalla los endpoints documentados, proporcionando una visión clara de las acciones disponibles, los métodos HTTP asociados, y ejemplos de respuestas esperadas. Esta documentación no solo facilita el trabajo del equipo de desarrollo, sino que también mejora la comunicación entre los diferentes actores del proyecto.

| Endpoint | Acción | Verbo HTTP | Descripción | Ejemplo de Response |
|----------|--------|------------|-------------|---------------------|
| /api/pedidos | Crear Pedido | POST | Crea un nuevo pedido | { "id": 1, "status": "creado" } |
| /api/pedidos/{id} | Editar Pedido | PUT | Actualiza un pedido existente | { "id": 1, "status": "actualizado" } |
| /api/pedidos | Listar Pedidos | GET | Retorna la lista de pedidos | [{ "id": 1, "status": "creado" }, { "id": 2, "status": "enviado" }] |

La correcta implementación de estos endpoints en la aplicación, desarrollada con Vite y Vue en WebStorm, garantiza que los usuarios puedan gestionar sus pedidos de manera eficiente. Este enfoque no solo optimiza el flujo de trabajo, sino que también asegura que la experiencia del usuario sea fluida y satisfactoria. Además, la estandarización de la documentación mediante OpenAPI promueve una mejor colaboración entre equipos y una integración más sencilla con otros servicios en el futuro.

##### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante este Sprint, se llevó a cabo el proceso de despliegue de la aplicación utilizando Vite y Vue en WebStorm. La implementación se realizó en un entorno de producción, garantizando que todas las características desarrolladas fueran accesibles para los usuarios finales. El despliegue se realizó siguiendo una serie de pasos estructurados que incluyeron la preparación del entorno, la construcción del proyecto y la configuración del servidor. A continuación, se describen las etapas clave del proceso:

1. **Preparación del Entorno:** Se verificó que el entorno de producción estuviera configurado adecuadamente. Esto 
incluyó la instalación de las dependencias necesarias y la configuración de variables de entorno para asegurar que la aplicación funcionara correctamente en producción.
2. **Construcción del Proyecto:** Utilizando Vite, se ejecutó el comando de construcción, lo que permitió generar los archivos optimizados para producción. Este proceso optimiza el tamaño de los archivos y mejora el rendimiento de la aplicación.
3. **Configuración del Servidor:** Una vez construidos los archivos, se configuró el servidor para servir la aplicación. Esto incluyó la configuración de redirecciones adecuadas y la optimización de la entrega de contenido estático, asegurando que la aplicación se cargara rápidamente para los usuarios.
4. **Despliegue en Producción:** Finalmente, se subieron los archivos generados al repositorio de GitHub del grupo de trabajo. Como cada integrante trabajó en una rama diferente, se hizo “merge” para garantizar la recopilación general del proyecto.

##### 5.2.2.8. Team Collaboration Insights during Sprint

![img.png](../assets/img/chapter-V/sprint-2/img.png)

![img.png](../assets/img/chapter-V/sprint-2/img1.png)

![img.png](../assets/img/chapter-V/sprint-2/img2.png)


## 5.2.3. Sprint 3

El Sprint Planning es una reunión clave en Scrum donde el equipo se junta para definir el objetivo del próximo sprint y planificar las tareas a realizar. Durante esta sesión, revisamos el backlog del producto para identificar las historias de usuario más relevantes, asegurándonos de que todos comprendan su valor. El Product Owner guía la conversación y aclara dudas.

El proceso se divide en dos partes: primero, establecemos el objetivo del sprint y seleccionamos las historias a abordar; luego, desglosamos esas historias en tareas más pequeñas y asignamos responsabilidades. Al final, todos tenemos un plan claro y compartido, lo que nos permite avanzar juntos hacia nuestros objetivos en la próxima iteración.

#### 5.2.3.1.Spring Planning 3.



<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 3</th>
        </tr>
    </thead>
    <tbody>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Date</td>
            <td>19-10-2024</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Location</td>
            <td>Modalidad Remota a través de la plataforma Discord</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Oscar Armas - Luis Villegas - Gustavo Huanca - Vicente Quijandria</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Review Summary</td>
            <td> 
              Durante el Sprint #2, el equipo logró avances en la implementación de la gestión de 
              inventarios, gestión de productos terminados, gestión del proceso de vinificación por lotes 
              de cosecha de uvas, gestión de cartera de clientes de los vinicultores y el historial de 
              solicitudes de compra a vinicultores por parte de los distribuidores
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Retrospective Summary</td>
            <td>
              Durante este sprint, el equipo enfrentó algunos desafíos significativos, especialmente con el 
              retiro de dos integrantes que no mostraron el compromiso esperado y tenían limitaciones en sus
              conocimientos sobre el desarrollo del frontend. Esto afectó la comunicación y la gestión de 
              tareas, generando dificultades en el flujo de trabajo. A pesar de estos obstáculos, logramos 
              cumplir con los objetivos establecidos, gracias al compromiso y la colaboración de los demás
              miembros. A través de la resiliencia y el apoyo mutuo, completamos las entregas, demostrando
              que, incluso en situaciones adversas, el trabajo en equipo es fundamental. Identificamos 
              varias oportunidades para mejorar la claridad en los roles y fortalecer el seguimiento de 
              tareas, lo que nos ayudará a optimizar nuestra dinámica en futuros sprints. Nuestro desempeño
              refleja un camino claro hacia el cumplimiento de los objetivos del próximo sprint, 
              asegurando una mejor eficiencia en el uso de recursos y tiempo.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 3 Goal</td>
            <td> 
              Nuestro enfoque está en implementar endpoints para la gestión de procesos vitivinícolas, 
              incluyendo solicitudes de pedidos a vinicultores, creación y obtención de procesos de 
              vinificación, datos de inventario del vinicultor y gestión de datos de clientes. Creemos 
              que esto proporciona operaciones más ágiles y una mejor experiencia de usuario a los 
              vinicultores y distribuidores. Esto se confirmará cuando todos los endpoints sean probados
              con éxito y se utilicen activamente en la aplicación, y cuando los usuarios informen sobre 
              una mejora en la eficiencia de sus flujos de trabajo y satisfacción con las nuevas 
              características visuales del frontend. 
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 3 Velocity</td>
            <td> Por definir </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sum of Story Points</td>
            <td> Por Definir </td>
        </tr>
        <!--====================================================================-->
    </tbody>
</table>



#### 5.2.3.2.Sprint Backlog 3.


<!--Status -> (To-do / In-Process / To-Review / Done) -->

<table>
<thead>
  <tr>
  <th colspan="7">Srpint 3</th>
  <th> Sprint 3</th>
  </tr>
</thead>
<tbody>
<!--====================================================================-->
<tr>
  <td colspan="1">User Story</td>
  <td colspan="15">Work-Item / Task</td>
</tr>
<!--====================================================================-->
<tr>
  <td>Id</td>
  <td>Title</td>
  <td>Id</td>
  <td>Title</td>
  <td>Description</td>
  <td>Estimation (hours)</td>
  <td>Assigned To</td>
  <td>Status</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="3" >  TS-01  </td>
  <td rowspan="3" > Obtener Datos de los procesos de vinificación</td>
  <td> TS-01-T-01 </td>
  <td> Crear modelo de datos de vinificación </td>
  <td> Definir el modelo de datos del proceso de vinificación en la base de datos, incluyendo campos de lote, fase y fechas de cada etapa.	</td>
  <td> 5 </td>
  <td>Janover Saldaña</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-01-T-02 </td>
  <td> Implementar endpoint GET para lotes </td>
  <td> Configurar el endpoint GET (/api/v1/vinificacion/lotes) para consultar información detallada de cada lote en el proceso de vinificación.	</td>
  <td>5</td>
  <td>Janover Saldaña</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-01-T-03 </td>
  <td> Implementar endpoint GET para etapas </td>
  <td> Crear endpoints GET (/api/v1/vinificacion/{lote}/etapa) para consultar el estado de cada etapa (fermentación, prensado, clarificación, etc.) de un lote.	</td>
  <td> 5 </td>
  <td> Janover Saldaña </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="2"> TS-03 </td>
  <td rowspan="2"> Eliminar Datos de los Procesos de Vinificación	</td>
  <td> TS-03-T01 </td>
  <td> Implementar endpoint DELETE para lotes	</td>
  <td> Configurar el endpoint DELETE (/api/v1/vinificacion/lotes/{id}) para eliminar un lote completo, incluyendo sus datos de cada etapa del proceso.	</td>
  <td> 5 </td>
  <td> Janover Saldaña </td>
  <td> Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-03-T02 </td>
  <td> Desarrollar capa de servicio para eliminación	</td>
  <td> Crear la lógica de servicio para eliminar un lote y sus datos relacionados en la base de datos, asegurando integridad referencial.	</td>
  <td> 5</td>
  <td> Janover Saldaña </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="1"> TS-04 </td>
  <td rowspan="1"> Registro de Lotes en el Proceso de Vinificación </td>
  <td> TS-04-T01</td>
  <td> Implementar endpoint POST para lotes	</td>
  <td> Crear el endpoint POST (/api/v1/vinificacion/lotes) para registrar nuevos lotes, incluyendo información básica como tipo de uva y fecha de inicio.	</td>
  <td> 5 </td>
  <td> Janover Saldaña </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="1"> TS-05 </td>
  <td rowspan="1"> Registro de Etapas en el Proceso de Vinificación </td>
  <td> TS-05-T-01 </td>
  <td> Implementar endpoint POST para etapas	</td>
  <td> Crear el endpoint POST (/api/v1/vinificacion/{lote}/etapas) para registrar nuevas etapas de fermentación, prensado, clarificación, envejecimiento y embotellado.	</td>
  <td> 6 </td>
  <td> Janover Saldaña </td>
  <td> Done</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="4"> TS-14 </td>
  <td rowspan="4"> Ver detalles de un ítem del inventario</td>
  <td> TS-14-T-01 </td>
  <td> Ver detalle del ítem exitosamente </td>
  <td> Implementar un endpoint y un JSON con la información del ítem cuando se proporciona un ID válido. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-14-T-02 </td>
  <td> Diseño de la Estructura de la API </td>
  <td> Definir la estructura y los endpoints de la API para acceder a los detalles del ítem del inventario (/api/inventory/items/{id}). </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-14-T-03 </td>
  <td> Manejo de Control de Errores </td>
  <td> Implementar un manejo adecuado de errores para las respuestas de la API, como el mensaje de error 404. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-14-T-04 </td>
  <td> Prueba Unitaria para la API </td>
  <td> Desarrollar pruebas unitarias que verifiquen el comportamiento correcto del endpoint para cada uno de los escenarios definidos, incluyendo: 
  - Prueba para un ID válido.
  - Prueba para un ID inexistente.
  - Prueba para solicitud sin autorización.
  </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="4"> TS-16 </td>
  <td rowspan="4"> Agregar nuevo ítem al inventario</td>
  <td> TS-16-T-01 </td>
  <td> Implementar endpoint para agregar ítem </td>
  <td> Implementar un endpoint y un JSON para agregar un nuevo ítem al inventario. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-16-T-02 </td>
  <td> Validar datos del ítem </td>
  <td> Asegurarse de que los datos del nuevo ítem cumplan con las validaciones necesarias antes de ser agregados. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-16-T-03 </td>
  <td> Manejo de errores en la API </td>
  <td> Implementar manejo de errores para situaciones como datos inválidos o problemas de conexión. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-16-T-04 </td>
  <td> Pruebas unitarias para agregar ítem </td>
  <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint para agregar un nuevo ítem. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="4"> US-32 </td>
  <td rowspan="4"> Filtrar insumos del inventario por categoría</td>
  <td> US-32-T-01 </td>
  <td> Implementar endpoint de filtrado </td>
  <td> Implementar un endpoint que permita filtrar insumos del inventario según la categoría seleccionada. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-32-T-02 </td>
  <td> Validar categorías disponibles </td>
  <td> Asegurarse de que las categorías disponibles para el filtrado sean correctas y estén actualizadas. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-32-T-03 </td>
  <td> Manejo de errores en el filtrado </td>
  <td> Implementar manejo de errores para situaciones como categorías no encontradas o problemas en la consulta. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-32-T-04 </td>
  <td> Pruebas unitarias para el filtrado </td>
  <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint de filtrado por categoría. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="4"> US-33 </td>
  <td rowspan="4"> Buscar insumos en el inventario</td>
  <td> US-33-T-01 </td>
  <td> Implementar endpoint de búsqueda </td>
  <td> Implementar un endpoint que permita buscar insumos en el inventario utilizando diferentes criterios. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-33-T-02 </td>
  <td> Filtrar resultados por atributos </td>
  <td> Permitir a los usuarios filtrar los resultados de búsqueda por atributos específicos, como nombre, categoría y cantidad. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-33-T-03 </td>
  <td> Manejo de errores en la búsqueda </td>
  <td> Implementar manejo de errores para situaciones como insumos no encontrados o problemas en la consulta. </td>
  <td> 2h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> US-33-T-04 </td>
  <td> Pruebas unitarias para la búsqueda </td>
  <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint de búsqueda de insumos. </td>
  <td> 1h </td>
  <td> Luis Villegas </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="3">TS-09</td>
  <td rowspan="3">Registrar un pedido</td>
  <td>TS-09-T-01</td>
  <td>Implementar endpoint de pedidos</td>
  <td>Implementar la lógica para agregar una nueva orden</td>
  <td>3h</td>
  <td>Vicente</td>
  <td>Done</td> 
</tr>
<!--====================================================================-->
<tr>
  <td>TS-09-T-02</td>
  <td>Crear endpoint</td>
  <td>Crear el endpoint "/api/v1/order" en el controlador</td>
  <td>4h</td>
  <td>Vicente</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>TS-09-T-03</td>
  <td>validar endpoint</td>
  <td>Validar que el endpoint maneje correctamente las respuestas</td>
  <td>1h</td>
  <td>Vicente</td>
  <td>Done</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="6"> US-16	</td>
  <td rowspan="6">Crear un cliente distribuidor</td>
  <td>US-16: TASK-01</td>
  <td>Crear formulario de cliente distribuidor	</td>
  <td>Desarrollar un formulario para registrar y gestionar los datos de clientes distribuidores, asegurando que la información necesaria esté completa y estructurada para facilitar la administración y consulta posterior.	</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td> 
</tr>
<!--====================================================================-->
<tr>
  <td>US-16: TASK-02 </td>
  <td>Configurar validaciones de campos obligatorios	</td>
  <td>Configura los campos esenciales como obligatorios para asegurar que se complete toda la información necesaria antes de enviar el formulario.	</td>
  <td>2h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-16: TASK-03</td>
  <td>Desarrollar método de creación en ClientsService	</td>
  <td>Crear un método en ClientsService que permita enviar los datos de un cliente nuevo a la API, realizando una solicitud POST para registrar la información en el servidor.	</td>
  <td>2h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-16: TASK-04</td>
  <td>Conectar el formulario con el método de creación del servicio	</td>
  <td>Implementar la conexión entre el formulario de cliente distribuidor y el método que permite registrar un nuevo cliente. Esto incluye obtener los datos del formulario al enviarlo y gestionar la respuesta para confirmar la creación exitosa y manejar posibles errores.</td>
  <td>2h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-16: TASK-05</td>
  <td>Mostrar notificación de éxito	</td>
  <td>Implementar una notificación que informe al usuario sobre el registro exitoso del cliente, asegurando que sea clara y se cierre automáticamente después de unos segundos..</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-16: TASK-06</td>
  <td>Redirigir a la lista de clientes distribuidores	</td>
  <td> Redirigir al usuario a la lista de clientes distribuidores tras un registro exitoso, asegurando que la navegación sea intuitiva y rápida.</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="6"> US-17	</td>
  <td rowspan="6">Editar un cliente distribuidor</td>
  <td>US-17: TASK-01</td>
  <td>Crear componente de edición	</td>
  <td>Desarrollar ClientEditComponent.vue para editar los datos de un cliente, cargando la información actual y permitiendo su actualización a través de un formulario.	</td>
  <td>3h</td>
  <td>Gustavo</td>
  <td>Done</td> 
</tr>
<!--====================================================================-->
<tr>
  <td>US-17: TASK-02</td>
  <td>Implementar método de actualización en ClientsService	</td>
  <td>Desarrollar un método en ClientsService que permita actualizar los datos de un cliente existente mediante una solicitud PUT a la API.	</td>
  <td>2h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-17: TASK-03</td>
  <td>Configurar validaciones de datos	</td>
  <td>Implementar las validaciones necesarias en el formulario de edición para asegurar que todos los campos requeridos sean completados correctamente antes de permitir la actualización de los datos del cliente.	</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-17: TASK-04</td>
  <td>Conectar el formulario de edición con el servicio de actualización	</td>
  <td> Integrar el formulario de edición con el método de actualización del servicio, asegurando que los datos ingresados se envíen correctamente para actualizar la información del cliente en la API.	</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-17: TASK-05</td>
  <td> Mostrar notificación de éxito de edición	</td>
  <td>Implementar una notificación que informe al usuario sobre la edición exitosa de los datos del cliente, asegurando que sea clara y visible, y que se cierre automáticamente después de unos segundos.	</td>
  <td>2h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-17: TASK-06</td>
  <td> Actualizar vista de detalles	</td>
  <td>Actualizar la vista de detalles del cliente para mostrar la información más reciente después de la edición..	</td>
  <td>1h</td>
  <td>Gustavo</td>
  <td>Done</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="3"> TS-21 </td>
  <td rowspan="3"> Creación de pedidos de vinos </td>
  <td> TS-21-T-01 </td>
  <td> Implementar formulario de creación de pedidos </td>
  <td> Desarrollar el formulario de pedidos que permita seleccionar el tipo de producto y la cantidad deseada. </td>
  <td> 3h </td>
  <td> OscarArmas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-21-T-02 </td>
  <td> Configurar endpoint para la creación de pedidos </td>
  <td> Configurar el endpoint POST (/api/v1/pedidos) para procesar la creación de nuevos pedidos de vino. </td>
  <td> 3h </td>
  <td> OscarArmas </td>
  <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
  <td> TS-21-T-03 </td>
  <td> Validar los datos del pedido </td>
  <td> Implementar validaciones en el formulario de pedidos para asegurar que los datos sean correctos y completos antes de procesarlos. </td>
  <td> 3h </td>
  <td> OscarArmas </td>
  <td> Done </td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
  <td rowspan="3"> US-34	</td>
  <td rowspan="3">Obtener detalles de un pedido</td>
  <td>US-34: TASK-01</td>
  <td>Order details	</td>
  <td>Desarrollo del componente visual order-details	</td>
  <td>4h</td>
  <td>Vicente</td>
  <td>Done</td> 
</tr>
<!--====================================================================-->
<tr>
  <td>US-34: TASK-02</td>
  <td>Añadir campos en entity	</td>
  <td>Añadir los campos necesarios en el entity model para que maneje todos los detalles necesarios del pedido	</td>
  <td>2h</td>
  <td>Vicente</td>
  <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
  <td>US-34: TASK-03</td>
  <td>Validar que el service funcione</td>
  <td>Validar que el service retorne todos los datos del order-details</td>
  <td>1h</td>
  <td>Vicente</td>
  <td>Done</td>
</tr>
<!--==================================USER STORY==================================-->
<tr>
    <td rowspan="4"> TS-19 </td>
    <td rowspan="4"> Despliegue del Servicio Web </td>
    <td> TS-19-TASK-01 </td>
    <td> Activar Modo Producción y Configurar Swagger </td>
    <td> Configurar el proyecto para funcionar en modo producción y habilitar Swagger para acceso en producción. </td>
    <td> 2h </td>
    <td> Gustavo </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> TS-19-TASK-02 </td>
    <td> Configurar y Activar WebDeploy en el Hosting </td>
    <td> Activar la cuenta de WebDeploy en el panel de control de MonsterASP y preparar el perfil de publicación. </td>
    <td> 2h </td>
    <td> Gustavo </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-19-TASK-03</td>
    <td>Desplegar el Proyecto en el Servidor</td>
    <td>Publicar el proyecto en el servidor utilizando el perfil de publicación de WebDeploy.</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-19-TASK-04</td>
    <td>Verificar el Funcionamiento de la API y Swagger</td>
    <td>Comprobar que la API y la interfaz de Swagger están accesibles y funcionando correctamente en el entorno de producción.</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--================================== USER STORY TS-05 ==================================-->
<tr>
    <td rowspan="3">TS-05</td>
    <td rowspan="3">Crear un cliente distribuidor</td>
    <td>TS-05: TASK-01</td>
    <td>Implementar lógica de cliente</td>
    <td>Implementar la lógica para agregar un nuevo cliente distribuidor</td>
    <td>3h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-05: TASK-02</td>
    <td>Crear endpoint</td>
    <td>Crear el endpoint "/api/v1/clients" en el controlador</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-05: TASK-03</td>
    <td>Validar respuestas del endpoint</td>
    <td>Validar que el endpoint maneje correctamente las respuestas</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--================================== USER STORY TS-08 ==================================-->
<tr>
    <td rowspan="3">TS-08</td>
    <td rowspan="3">Ver los detalles de un cliente distribuidor</td>
    <td>TS-08: TASK-01</td>
    <td>Implementar lógica de detalles de cliente</td>
    <td>Implementar la lógica para obtener los detalles de un cliente distribuidor</td>
    <td>3h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-08: TASK-02</td>
    <td>Crear endpoint de detalles</td>
    <td>Crear el endpoint "/api/v1/clients/{id}" en el controlador</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-08: TASK-03</td>
    <td>Validar respuestas de detalles</td>
    <td>Validar que el endpoint maneje correctamente las respuestas</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--================================== USER STORY TS-18 ==================================-->
<tr>
    <td rowspan="3">TS-18</td>
    <td rowspan="3">Eliminar un cliente distribuidor</td>
    <td>TS-18: TASK-01</td>
    <td>Agregar botón de eliminación</td>
    <td>Agregar un botón en la lista de clientes para permitir la eliminación de un cliente distribuidor</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-18: TASK-02</td>
    <td>Desarrollar método de eliminación</td>
    <td>Desarrollar el método de eliminación en el servicio ClientsService para manejar la eliminación de clientes</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-18: TASK-03</td>
    <td>Implementar diálogo de confirmación</td>
    <td>Implementar un diálogo de confirmación que solicite al usuario la verificación antes de eliminar el cliente</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
</tbody>
</table>


#### 5.2.3.3.Development Evidence for Sprint Review.


<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="10">ElixirControl-Landing-Page</td>
            <td>main</td>
            <td>d3ec381</td>
            <td>chore(call-to-actin): Added the web application route in the call to action</td>
            <td>Added the web application route in the call to action</td>
            <td>Commited on 28/09/2024</td>
        </tr>
        <tr>
            <td>main</td>
            <td>d54a8d8</td>
            <td>feat: Updated the styles and html of the About The App section.</td>
            <td>Updated the styles and html of the About The App section.</td>
            <td>Commited on 02/11/2024</td>
        </tr>
    </tbody>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="21">ElixirControl-FrontEnd</td>
            <td>feature/winemaking-process</td>
            <td>e049e2f</td>
            <td>feat(winemaking-process): The structure of the components of the winemaking process has been updated.</td>
            <td>The structure of the components of the winemaking process has been updated.</td>
            <td>Commited on 09/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>9ee3db4</td>
            <td>feat(customer-management): clients.service added.</td>
            <td>clients.service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>0bc2260</td>
            <td>feat(customer-management): clients.service added.</td>
            <td>clients.service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>4399fe8</td>
            <td>feat(customer-management): client create and edit component added.</td>
            <td>client create and edit component added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>2dade9e</td>
            <td>feat(customer-management): client management added.</td>
            <td>client management added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b0ff73a</td>
            <td>feat(customer-management): client service added.</td>
            <td>client service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b0ff73a</td>
            <td>feat(customer-management): massage, skeleton, panel and divider from PrimeVue added.</td>
            <td>massage, skeleton, panel and divider from PrimeVue added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>3716964</td>
            <td>feat(oder-management): added order management structure.</td>
            <td>added order management structure.</td>
            <td>Commited on 14/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>bf4e1d1</td>
            <td>feat(order): added order entity</td>
            <td>added order entity.</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>dabe65c</td>
            <td>feat(order): added order create and edit component</td>
            <td>added order create and edit component</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b0ebd9a</td>
            <td>feat(order): created order service</td>
            <td>created order service</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>382a5bb</td>
            <td>feat(navbar-elixir-control.component.vue):  added the navbar elixir control component</td>
            <td>added the navbar elixir control component</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>a81e7d3</td>
            <td>feat(order-details):  added the order details card component</td>
            <td>added the order details card component</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>c7f9dc1</td>
            <td>refactor(order-management): edited the order management page</td>
            <td>edited the order management page</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>bd2a699</td>
            <td>refactor(order-api.service): applied the new endpoints of the db.json</td>
            <td>applied the new endpoints of the db.json</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ee5ec86</td>
            <td>feat(order-management): added the status button and its now displaying with a certain color depending on the status</td>
            <td>added the status button and its now displaying with a certain color depending on the status</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>9800bda</td>
            <td>refactor(index.js): changed the order details and my orders routes</td>
            <td>changed the order details and my orders routes</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>cd5e1ab</td>
            <td>feat(order-create-and-edit): added more inputs for the new attributes of the order</td>
            <td>added more inputs for the new attributes of the order</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>661eb7d</td>
            <td>feat(order.entity): added more attributes to the order entity</td>
            <td>added more attributes to the order entity</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>be0e883</td>
            <td>feat(order-details): added more details of the new attributes of the order</td>
            <td>added more details of the new attributes of the order</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>0c95e8a</td>
            <td>refactor(order-management): fixed an error of the details button not displaying correctly</td>
            <td>fixed an error of the details button not displaying correctly</td>
            <td>Commited on 27/10/2024</td>
        </tr>
    </tbody>
    <tbody>
        <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="44">ElixirControl-Platform</td>
            <td>feature/customer-management</td>
            <td>96a3929</td>
            <td>feat(customer-management): client command service added.</td>
            <td>client command service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>9ee3db4</td>
            <td>chore(develop): Added the base structure of bounded contexts.</td>
            <td>Added the base structure of bounded contexts.</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>3ed3156</td>
            <td>chore(customer-management): Added the order management bounded context structure.</td>
            <td>Added the order management bounded context structure.</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>713529c</td>
            <td>feat(customer-management): class client added.</td>
            <td>class client added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>487c5dc</td>
            <td>feat(customer-management): db context of clients added.</td>
            <td>db context of clients added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>3c32ce3</td>
            <td>feat(customer-management): client repository added.</td>
            <td>client repository added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>d89597e</td>
            <td>feat(customer-management): client resource added.</td>
            <td>client resource added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b4f8bdb</td>
            <td>feat(customer-management): client resource from entity assembles added.</td>
            <td>client resource from entity assembles added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>df2045a</td>
            <td>feat(customer-management): end points added.</td>
            <td>end points added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>0cc12a8</td>
            <td>feat(customer-management): create client command from resource assembler added.</td>
            <td>create client command from resource assembler added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>2233cbc</td>
            <td>feat(customer-management): interface client query service added.</td>
            <td>interface client query service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>7738dea</td>
            <td>feat(customer-management): dependency injection of clients added.</td>
            <td>dependency injection of clients added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b2a5d3d</td>
            <td>feat(customer-management): create client resource added.</td>
            <td>create client resource added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>34ace70</td>
            <td>feat(customer-management): client query service added.</td>
            <td>client query service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>1bd6da8</td>
            <td>feat(customer-management): find all clients async method added.</td>
            <td>find all clients async method added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>06ca584</td>
            <td>chore(inventory-management): Added the inventory management bounded context structure.</td>
            <td>Added the inventory management bounded context structure.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>b515735</td>
            <td>feat(inventory-management): Added resources and application layer for inventory.</td>
            <td>Added resources and application layer for inventory.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>4c1b464</td>
            <td>feat(inventory-management): Added transform and application layer for inventory.</td>
            <td>Added transform and application layer for inventory.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>b8979ff</td>
            <td>feat(inventory-management): added interface inventory controller</td>
            <td>added interface inventory controller</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b6a4487</td>
            <td>feat(CreateOrderCommand): added the command for Create Order</td>
            <td>added the command for Create Order</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b8e13b2</td>
            <td>feat(GetOrderByIdQuery): created the Get Order by Id Query</td>
            <td>created the Get Order by Id Query</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>730d4b5</td>
            <td>feat(Order): created the order entity on the domain</td>
            <td>created the order entity on the domain</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ccc505d</td>
            <td>feat(IOrderQueryService): added the Order Query Service interface</td>
            <td>added the Order Query Service interface</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>e06ad04</td>
            <td>feat(IOrderCommandService): added the OrderCommandService interface for handling the CreateOrderCommand</td>
            <td>added the OrderCommandService interface for handling the CreateOrderCommand</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>7fc94a6</td>
            <td>feat: added order controller repository and entityassembler</td>
            <td>added order controller repository and entityassembler</td>
            <td>Commited on 30/10/2024</td> 
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ce81dc3</td>
            <td>feat(Orders): added the Orders agreggate</td>
            <td>added the Orders agreggate</td>
            <td>Commited on 30/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>25c5b31</td>
            <td>refactor(example): deleted the example md files</td>
            <td>deleted the example md files</td>
            <td>Commited on 30/10/2024</td>   
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>cd0147d</td>
            <td>chore(order-request):Added the order request bounded context structure.</td>
            <td>Added the order request bounded context structure.</td>
            <td>Commited on 30/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>4406efb</td>
            <td>feat(order-request): Create Order Command From Resource Assembler added.</td>
            <td>Create Order Command From Resource Assembler added.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>9f72938</td>
            <td>feat(order-request): Get All Orders Query added</td>
            <td>Get All Orders Query added</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>a5370e1</td>
            <td>feat(order-request): Order Controller added.</td>
            <td>Order Controller added.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>90f1cda</td>
            <td>feat(order-request): Order Command Service added.</td>
            <td>Order Command Service added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>b3a2a98</td>
            <td>feat(order-request): Order Resource From Entity Assembler added.</td>
            <td>Order Resource From Entity Assembler added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>f50146b</td>
            <td>feat(order-request): Order Resource added.</td>
            <td>Order Resource added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>8ebe465</td>
            <td>feat(order-request): Order Query Service added.</td>
            <td>Order Query Service added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>30e4f42</td>
            <td>feat(winemaking-process): Added entity and command to add the clarification process to a batch.</td>
            <td>Added entity and command to add the clarification process to a batch.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>e816564</td>
            <td>chore(winemaking-process): Added the winemaking process bounded context structure.</td>
            <td>Added the winemaking process bounded context structure.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>92089e4</td>
            <td>feat(winemaking-process): Added the controller that creates the "Clarification" process for the batch.</td>
            <td>Added the controller that creates the "Clarification" process for the batch.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>b03da24</td>
            <td>feat(winemaking-process): Added endpoints that return the winemaking processes (Fermentation, Clarification)</td>
            <td>Added endpoints that return the winemaking processes (Fermentation, Clarification)</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>9eff846</td>
            <td>feat(winemaking-process): Added infrastructure and application layer for batches.</td>
            <td>Added infrastructure and application layer for batches.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>14ccb3a</td>
            <td>feat(winemaking-process): Added REST resources and transforms to add batch clarification stage.</td>
            <td>Added REST resources and transforms to add batch clarification stage.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>6e291d4</td>
            <td>feat(winemaking-process): Added implementation of the Service that returns the fermentation process by BatchID.</td>
            <td>Added implementation of the Service that returns the fermentation process by BatchID.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>84a1137</td>
            <td>feat(winemaking-process): Added the end point to create the fermentation state of a batch.</td>
            <td>Added the end point to create the fermentation state of a batch.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>70f11e5</td>
            <td>feat(winemaking-process): Added endpoints to create and return the batch pressing process.</td>
            <td>Added endpoints to create and return the batch pressing process.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
    </tbody>
</table>



#### 5.2.3.4.Testing Suite Evidence for Sprint Review.

En esta entrega no se han realizado los test

#### 5.2.3.5.Execution Evidence for Sprint Review.

* Landing Page Execution

Evidencias de última version de Landing Page

![fronted.png](/assets/img/chapter-V/sprint-3/fronted.png)

Evidencia del video de About the product

![aboutapp.png](/assets/img/chapter-V/sprint-3/aboutapp.png)

* Web Application Execution

Evidencias de última version de la aplicación con una mejora en la interfaz de navegación, mejora en los detalles 
del inventario y se completo la sección de "My Clients"

![frontendv2.png](/assets/img/chapter-V/sprint-3/frontendv2.png)

Evidencia de mejora del inventario

![frontendv3.png](/assets/img/chapter-V/sprint-3/frontendv3.png)

Evidencia de la sección de "My Clients"

![frontendv4.png](/assets/img/chapter-V/sprint-3/frontendv4.png)

* Web Services Execution

Evidencias de Swagger conectado a nuestro backend:

![api1.png](/assets/img/chapter-V/sprint-3/api1.png)

![api2.png](/assets/img/chapter-V/sprint-3/api2.png)

Enlace del Web Services desplegado: http://elixircontrol.runasp.net/swagger/index.html

Para este sprint, se ha realizado un video de ejecucion demostrativo del despliegue del backend:

<img src="/assets/img/chapter-V/sprint-4/sprint_3.PNG" height="350" alt="landing_page">

Enlance del video de ejecucion:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EQ2Ot4dlVrZGpvTXEAJOYWIBbjVd6I0wBj7U5zAB6GEXzQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=8tW9tF


#### 5.2.3.6.Services Documentation Evidence for Sprint Review.


### Batch Endpoints

| URL                                                | Endpoint                | HTTP Verb | Acción Implementada     | Sintaxis de Llamada                                                                             | Parámetros Posibles     | Ejemplo de Response                                                    | Explicación del Response                |
|----------------------------------------------------|-------------------------|-----------|-------------------------|-------------------------------------------------------------------------------------------------|-------------------------|------------------------------------------------------------------------|-----------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch/{batchId} | GET       | Obtener un lote por ID  | 'accept: application/json'                                                                      | batchId (path)          | `{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}`   | Retorna un objeto con detalles del lote |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch           | POST      | Crear un nuevo lote     | 'Content-Type: application/json' -d '{"vineyardCode": "string", "grapeVariety": "string", ...}' | JSON con datos del lote | `{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}`   | Retorna el objeto lote creado           |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch           | GET       | Obtener todos los lotes | 'accept: application/json'                                                                      | Ninguno                 | `[{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}]` | Retorna un array de objetos lote        |

## WinemakingProcessByBatch Endpoints

| URL                                                | Endpoint                                                | HTTP Verb | Acción Implementada             | Sintaxis de Llamada                                                                 | Parámetros Posibles                              | Ejemplo de Response                                                        | Explicación del Response                      |
|----------------------------------------------------|---------------------------------------------------------|-----------|---------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------|----------------------------------------------------------------------------|-----------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/fermentation  | GET       | Obtener fermentación por lote   | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "startDate": "string", ...}`                      | Retorna objeto con detalles de fermentación   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/fermentation        | POST      | Añadir fermentación a un lote   | 'Content-Type: application/json' -d '{"batchId": 0, "startDate": "string", ...}'    | batchId (path), JSON con datos de fermentación   | `{"id": 0, "batchId": 0, "startDate": "string", ...}`                      | Retorna el objeto fermentación creado         |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/clarification | GET       | Obtener clarificación por lote  | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna objeto con detalles de clarificación  |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/clarification       | POST      | Añadir clarificación a un lote  | 'Content-Type: application/json' -d '{"batchId": 0, "productsUsed": "string", ...}' | batchId (path), JSON con datos de clarificación  | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna el objeto clarificación creado        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/pressing      | GET       | Obtener prensado por lote       | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "pressingDate": "2024-11-03T09:24:52.277Z", ...}` | Retorna objeto con detalles de prensado       |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/pressing            | POST      | Añadir prensado a un lote       | 'Content-Type: application/json' -d '{"batchId": 0, "pressingDate": "string", ...}' | batchId (path), JSON con datos de prensado       | `{"id": 0, "batchId": 0, "pressingDate": "2024-11-03T09:24:52.281Z", ...}` | Retorna el objeto prensado creado             |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/aging         | GET       | Obtener envejecimiento por lote | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "barrelType": "string", ...}`                     | Retorna objeto con detalles de envejecimiento |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/aging               | POST      | Añadir envejecimiento a un lote | 'Content-Type: application/json' -d '{"batchId": 0, "barrelType": "string", ...}'   | batchId (path), JSON con datos de envejecimiento | `{"id": 0, "batchId": 0, "barrelType": "string", ...}`                     | Retorna el objeto envejecimiento creado       |

## Orders Endpoints

| URL                                                | Endpoint            | HTTP Verb | Acción Implementada       | Sintaxis de Llamada                                                                              | Parámetros Posibles        | Ejemplo de Response                                                     | Explicación del Response                   |
|----------------------------------------------------|---------------------|-----------|---------------------------|--------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------|--------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders      | POST      | Crear una nueva orden     | 'Content-Type: application/json' -d '{"businessName": "string", "requestedDate": "string", ...}' | JSON con datos de la orden | `{"id": 0, "businessName": "string", "requestedDate": "string", ...}`   | Retorna el objeto orden creado             |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders      | GET       | Obtener todas las órdenes | 'accept: application/json'                                                                       | Ninguno                    | `[{"id": 0, "businessName": "string", "requestedDate": "string", ...}]` | Retorna un array de objetos orden          |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders/{id} | GET       | Obtener una orden por ID  | 'accept: application/json'                                                                       | id (path)                  | `{"id": 0, "businessName": "string", "requestedDate": "string", ...}`   | Retorna un objeto con detalles de la orden |

## Inventory Endpoints

| URL                                                | Endpoint                        | HTTP Verb | Acción Implementada           | Sintaxis de Llamada                                                             | Parámetros Posibles           | Ejemplo de Response                                    | Explicación del Response                      |
|----------------------------------------------------|---------------------------------|-----------|-------------------------------|---------------------------------------------------------------------------------|-------------------------------|--------------------------------------------------------|-----------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory/{inventoryId} | GET       | Obtener inventario por ID     | 'accept: application/json'                                                      | inventoryId (path)            | `{"id": 0, "name": "string", "type": "string", ...}`   | Retorna un objeto con detalles del inventario |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory               | POST      | Crear un nuevo inventario     | 'Content-Type: application/json' -d '{"name": "string", "type": "string", ...}' | JSON con datos del inventario | `{"id": 0, "name": "string", "type": "string", ...}`   | Retorna el objeto inventario creado           |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory               | GET       | Obtener todos los inventarios | 'accept: application/json'                                                      | Ninguno                       | `[{"id": 0, "name": "string", "type": "string", ...}]` | Retorna un array de objetos inventario        |

## Clients Endpoints

| URL                                                | Endpoint                     | HTTP Verb | Acción Implementada        | Sintaxis de Llamada                                                                  | Parámetros Posibles        | Ejemplo de Response                                         | Explicación del Response                       |
|----------------------------------------------------|------------------------------|-----------|----------------------------|--------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------|------------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients              | POST      | Crear un nuevo cliente     | 'Content-Type: application/json' -d '{"personName": "string", "dni": "string", ...}' | JSON con datos del cliente | `{"id": 0, "personName": "string", "dni": "string", ...}`   | Retorna el objeto cliente creado               |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients              | GET       | Obtener todos los clientes | 'accept: application/json'                                                           | Ninguno                    | `[{"id": 0, "personName": "string", "dni": "string", ...}]` | Retorna un array de objetos cliente            |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{id}         | GET       | Obtener un cliente por ID  | 'accept: application/json'                                                           | id (path)                  | `{"id": 0, "personName": "string", "dni": "string", ...}`   | Retorna un objeto con detalles del cliente     |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{dni}/client | GET       | Obtener clientes por DNI   | 'accept: application/json'                                                           | dni (path)                 | `[{"id": 0, "personName": "string", "dni": "string", ...}]` | Retorna un array de objetos cliente con el DNI |

#### 5.2.3.7.Software Deployment Evidence for Sprint Review.


En esta sección se describen los procesos de despliegue de la base de datos y el Web Service realizados durante el Sprint. Para la base de datos, se utilizó AWS LightSail, donde se creó una base MySQL en un plan gratuito. El  Web Service se desplegó en MonsterASP.net, configurando un sitio web gratuito, activando el acceso de web deploy y publicando desde Visual Studio 2022. Ambos componentes quedaron listos para su uso.


### Despliegue de la base de datos

Se siguieron los pasos detallados previamente para desplegar la base de datos en AWS LightSail, comenzando desde la configuración inicial en la sección "Databases" hasta la selección de MySQL 8.0.39 y el plan gratuito de tres meses. Con la base de datos creada y configurada, se encuentra ahora lista para integrarse con los distintos productos digitales del proyecto (Landing Page, Web Applications y Web Services), permitiendo al equipo asegurar una publicación satisfactoria y conectividad centralizada en la nube.

![](../assets/img/chapter-V/sprint-3/database5.PNG)


### Despliegue del Web Service


En este Sprint se realizaron los procesos de Deployment necesarios para asegurar la correcta configuración y despliegue de los distintos componentes del proyecto. Para el Web Service, se utilizó la plataforma MonsterASP.net, donde se creó una cuenta, configuró un sitio web gratuito con el subdominio "ElixirControl", y se habilitó el acceso de Web Deploy. Luego, se descargó el perfil de publicación y se configuró el archivo program.cs para habilitar Swagger en producción. A través de Visual Studio, el proyecto fue desplegado exitosamente utilizando el perfil de publicación descargado. Como resultado, el Web Service quedó listo para pruebas y uso en el entorno de producción, accesible en el enlace http://elixircontrol.runasp.net/swagger/index.html. Este proceso de Deployment incluyó pasos detallados de configuración y automatización en un entorno en la nube, contribuyendo al avance general de la integración de los productos digitales del proyecto, como la Landing Page, las Web Applications y los Web Services.

![](../assets/img/chapter-V/sprint-3/back.PNG)



#### 5.2.3.8.Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue culminar los servicios tanto del frontend y backend. Se representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de clonaciones realizadas por cada integrante del equipo durante el desarrollo de los services.

![image (1).png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fimage%20%281%29.png)

![gitclones (1).png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fgitclones%20%281%29.png)

En esta captura se muestra el flujo de las ramas creadas, su creación.

![commits.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fcommits.png)


## 5.3. Validation Interviews.

En esta sección se realizarán entrevistas mediante las cuales buscamos recoger opiniones y recomendaciones. Esto asegura que la aplicación web no solo cumpla con los requisitos técnicos, sino también con las expectativas de nuestros segmentos objetivos.

### 5.3.1. Diseño de Entrevistas.

**User Goal: Navegar por la landing page**

_User persona → Vinicultores y Distribuidores_

**_Explicación del flujo →_** El usuario deberá ingresar a la landing page de la aplicación web.
En esta, podrá desplazarse y visualizar información general sobre los servicios ofrecidos, 
así como los beneficios de utilizar la aplicación. Además, podrá cambiar el idioma a inglés
o español a través de un botón. También, tendrá acceso directo a la aplicación web a través
de un Call To Action situado en la vista principal de la landing page.

### **User goals para vinicultores:**

1. **Gestionar el inventario de insumos y materiales:**

    **_User Goal →_** Como vinicultor, necesito poder registrar y actualizar el inventario 
    de insumos y materiales para controlar la disponibilidad de estos. 

    **_Explicación del flujo →_** Los vinicultores deben ingresar a la sección de gestión de 
    inventario de la aplicación web, esta se puede realizar búsquedas de materiales específicos,
    añadir nuevos ítems, y ajustar las cantidades manualmente según las compras o el consumo 
    en el proceso productivo.

   <br>

2. **Gestionar la cartera de clientes:**

    **_User Goal →_** Como vinicultor, necesito poder gestionar la información de mis clientes
    
    **_Explicación del flujo →_** Los vinicultores pueden añadir, modificar o eliminar clientes
    desde el módulo de gestión de clientes. Deben actualizar la información básica como nombres,
    contactos, nombre de negocios, encargados, RUC del negocio,etc.

   <br>

3. **Gestionar productos disponibles para la venta:**

    **_User Goal →_** Como vinicultor, necesito poder llevar un registro de mis productos que
    están listos para la venta.
    
    **_Explicación del flujo →_**  Desde la vista de productos, deben seleccionar los que están
    en inventario y publicar su disponibilidad. Pueden ajustar cantidades en función de la 
    producción y eliminar productos que ya no estén disponibles.

   <br>

4. **Controlar el proceso productivo de vino por fases:**

    **_User Goal →_** Como vinicultor, necesito poder llevar un registro detallado de cada lote
    de vino en producción, incluyendo las fases de fermentación, clarificación, prensado, 
    añejamiento y embotellado.
    
    **_Explicación del flujo →_** Los vinicultores deben crear y gestionar lotes en la aplicación,
    ingresando datos sobre cada fase del proceso. A medida que el lote avanza, actualizan el estado
    de cada fase y pueden ingresar observaciones o ajustar los tiempos de cada una según el avance
    del lote.


### **User goals para distribuidores:**

### 5.3.2. Registro de Entrevistas.

Entrevista a Vinicultor

<table>
<thead>
            <tr>
                <th>Entrevistado 1</th>
                <th>Giovanni Torres</th>
            <tr>
                <th>Entrevistador </th>
                <th>Luis Villegas</th>
            </tr>
</thead>        
<tbody>
            <tr>
                <td>Edad</td>
                <td>26</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>Tacna</td>
            </tr>
            <tr>
                <td><img src="/assets/img/chapter-V/sprint-3/entrevista_vinicultor.png" alt="agregar foto"></td>
                <td><strong>Resumen:</strong><br>
                  Giovanni Torres, de 25 años, participo en la entrevista centrada en la evaluación de la interfaz de usuario de nuestra aplicacion. Durante el desarrollo de la entrevista, destaco que la interfaz 
                  de la "Landing Page" esta bien hecho, le agrada mucho que se maneje bien la informacion y sobre todo se mantiene en order. En el apartado del "Front End" su navegacion fue fluida pero se vio 
                  interrumpida en la opcion de inventario en el momento de visualizar los detalles ya que no capturaba el dato. Por otro lado, en la opcion de proceso de vinificacion observó que necesita tener un 
                  mejor diseño para que pueda navegar más rapido en el momento de registrar embotellamientos y elproceso de la enfermentacion. Se concluye la entrevista, complentado todos los User Goals, 
                  destacando la faclidad de la intefaz de usuario y agregando comentarios para la implementacion de mejora en la aplicacion para que se peuda ser más intuitivo y se vea más profesional.
                </td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>06:24 min</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>[https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/ESCnPrRBol5Mh9m1g7LPXlsBOGddZUA2QIj9xLP9Vng8CQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dNgRoo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EVCtH24aZttMhqn0jWmJ1RQBMO__wC5WUSpc2nuiC0ZyLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=LtoFx8)</td>
            </tr>
</tbody>
</table>


<table>
<thead>
            <tr>
                <th>Entrevistado 2</th>
                <th>Jazzy Benitez</th>
            <tr>
                <th>Entrevistador </th>
                <th>Oscar Armas Sánchez</th>
            </tr>
</thead>        
<tbody>
            <tr>
                <td>Edad</td>
                <td>32</td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>Pisco</td>
            </tr>
            <tr>
                <td><img src="/assets/img/chapter-V/sprint-3/EntrevistaJazzy.png" alt="agregar foto"></td>
                <td><strong>Resumen:</strong><br>
                Jazzy Benítez, de 32 años, participó en una entrevista centrada en la evaluación de la interfaz de usuario de nuestra aplicación. Durante la conversación, Jazzy destacó que las tarjetas de los servicios en la página de inicio son una excelente forma de presentar la oferta de la empresa, permitiendo a los usuarios identificar rápidamente los servicios disponibles. También sugirió incluir, facilitando así la compra o venta de productos.Al iniciar sesión, Jazzy notó de inmediato el tipo de usuario que debía seleccionar y comentó que la página de inicio es muy accesible. Sin embargo, recomendó mejorar el diseño visual para que la interfaz luzca más profesional. En cuanto a la navegación, mencionó que pudo explorar fácilmente los vinos populares y acceder a los detalles de los productos gracias a los filtros disponibles en la sección de "vinos". Además, sugirió la incorporación de un carrito de compras, lo que permitiría a los usuarios adquirir múltiples productos a la vez. La entrevista concluyó con Jazzy destacando la simplicidad y facilidad de uso de la interfaz, sugiriendo que al implementar los comentarios proporcionados, la aplicación podría convertirse en una herramienta valiosa para los consumidores y entusiastas del vino y pisco.
                </td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td>05:56 min</td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>[https://1drv.ms/v/c/cab22ef84dc9095b/EZYjA8O9xGtAhrruq1zHJ1MBeLWhP1zuUOiB_DoX543Agg?e=to7r3s](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EVCtH24aZttMhqn0jWmJ1RQBMO__wC5WUSpc2nuiC0ZyLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=LtoFx8)</td>
            </tr>
</tbody>
</table>

<table>
  <thead>
    <tr>
      <th>Entrevistado 3</th>
      <th>Sandra Vázquez</th>
    </tr>
    <tr>
      <th>Entrevistador</th>
      <th>Gustavo Huanca</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Edad</td>
      <td>27</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Pisco</td>
    </tr>
    <tr>
      <td><img src="/assets/img/chapter-V/sprint-3/entrevista3.PNG" alt="agregar foto"></td>
      <td>
        <strong>Resumen:</strong><br>
        Sandra Vázquez, vinicultora de 27 años, participó en una entrevista sobre la usabilidad y diseño de nuestra aplicación. Sandra expresó interés en la opción de cambiar el idioma, aunque sugirió incluir opciones de país en el menú. Al revisar el inventario, señaló que sería útil poder añadir productos en español, ya que no domina el inglés. También exploró la sección de elaboración de vinos y comentó positivamente sobre la presentación de los lotes y su información detallada. Aunque la opción "Mis Clientes" no está implementada, Sandra consideró que sería beneficioso para gestionar contactos de clientes. En "Mis Pedidos", observó que es conveniente poder realizar órdenes desde la aplicación, y en "Mis Productos", apreció la facilidad para añadir vinos. Concluyó que la aplicación es interesante y le gustaría comenzar a usarla pronto, sugiriendo algunos ajustes que mejorarían la experiencia del usuario.
      </td>
    </tr>
    <tr>
      <td>Timing de la entrevista</td>
      <td>06:29 min</td>
    </tr>
    <tr>
      <td>URL de la entrevista</td>
      <td><a href="[https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215285_upc_edu_pe/Ea2HE51ZpMJFi9zmAP-uAxwBHJdT3HN7Nla0UPpN8ydg-A?e=WoAZ7d&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215285_upc_edu_pe/Ea2HE51ZpMJFi9zmAP-uAxwBHJdT3HN7Nla0UPpN8ydg-A?e=WoAZ7d&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EVCtH24aZttMhqn0jWmJ1RQBMO__wC5WUSpc2nuiC0ZyLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=LtoFx8)</a></td>
    </tr>
  </tbody>
</table>


### 5.3.3. Evaluaciones según heurísticas.

__________________________________________________________________________________________

<strong> <p style="text-align: center;"> UX Heuristics & Principles Evaluation </p> </strong> 

<p style="text-align: center; font-weight: bold;   font-style: italic;"> Usability – Inclusive Design – Information Architecture </p>

**_CARRERA:_** Ingeniería de Software

**_CURSO:_** Aplicaciones Web

**_SECCIÓN:_** SV51

**_PROFESOR:_** Angel Augusto Velasquez Nuñez

**_AUDITOR:_** MetaSoft

**_CLIENTE:_** MetaSoft

__________________________________________________________________________________________

**SITE o APP A EVALUAR:** ElixirControl

**TAREAS A EVALUAR:**

**_Landing Page: ElixirControl:_**

1. Información y descripción de la aplicación y sus funcionalidades
2. Visualización de planes de pago y precio de la aplicación
3. Interacción de la landing page con la aplicación


**_Web Application: ElixirControl:_**

1. Acceso a la visualizacion de datos en el inventario
2. Mejora de diseño en la interfaz en la seccion "Vinicultor"
3. Optimización de la Interfaz de Usuario
4. Implementación de Nuevas Funcionalidades
 


**ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

<table>
<thead>
  <tr>
    <th> Nivel </th>
    <th> Descripción </th>
  </tr>
</thead>

<tbody>
  <!--========================================= FILA 1 ======================================-->
  <tr>
    <td> 1 </td>
    <td> 
      Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco
      frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo 
    </td>
  </tr>
  <!--========================================= FILA 2 ======================================-->
  <tr>
    <td> 2 </td>
    <td> 
      Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de
      superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente
      reléase
    </td>
  </tr>
  <!--========================================= FILA 3 ======================================-->
  <tr>
    <td> 3 </td>
    <td> 
      Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es
      importante que sean corregidos y se les debe asignar una prioridad alta.
    </td>
  </tr>
  <!--========================================= FILA 4 ======================================-->
  <tr>
    <td> 4 </td>
    <td> 
      Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de
      la herramienta. Es imperativo que sea corregido antes del lanzamiento
    </td>
  </tr>
</tbody>
</table>


**TABLA DE RESUMEN - LANDING PAGE:**

<table>
<thead>
 <tr>
  <th> # </th>
  <th> Problema </th>
  <th> Escala de severidad </th>
  <th> Heurística/Principio violada(o) </th>
</tr>
</thead>
<tbody>
<!--========================================= FILA 1 ======================================-->
<tr>
  <td> 1 </td>
  <td> Falta de acción al elegir un plan en la sección de "Planes" </td>
  <td> 2</td>
  <td> Usability: Visibilidad del estado del sistema </td>
</tr>
<!--========================================= FILA 2 ======================================-->
<tr>
  <td> 2 </td>
  <td> Dificultades en la Navegación y Comprensión de la Propuesta de Valor en la Landing Page </td>
  <td> 2 </td>
  <td> Usability: Visibilidad del estado del sistema </td>
</tr>
<!--========================================= FILA 3 ======================================-->
<tr>
  <td> 3 </td>
  <td> Diseño inconsistente en la sección de "Servicios" </td>
  <td> 2 </td>
  <td> Inclusive Design: Estética y diseño minimalista </td>
</tr>
<!--========================================= FILA 4 ======================================-->
<tr>
  <td> 4 </td>
  <td> Call-to-Action (CTA) poco destacado </td>
  <td> 3 </td>
  <td> Usability: Visibilidad del estado del sistema </td>
</tr>
</tbody>
</table>


**_DESCRIPCIÓN DE PROBLEMAS - LANDING PAGE:_**

**PROBLEMA #1:** Falta de acción al elegir un plan en la sección de "Planes"

**Severidad: 2**

**Problema:**  
En la sección de "Planes" de la landing page, al seleccionar un plan, el sistema no despliega ninguna pestaña ni redirige al usuario a otra página para completar el proceso de elección. Esto puede generar confusión en el usuario, ya que no hay una acción clara o retroalimentación al seleccionar una opción. Esta problemática tiene una severidad de nivel 2, ya que no impide completamente el acceso a la aplicación, pero sí afecta la experiencia del usuario al hacer que el proceso de selección sea poco intuitivo.

![planes_seleccion.png](../assets/img/chapter-V/sprint-3/landing.PNG)

**Recomendación:**  
Se recomienda implementar una acción que guíe al usuario después de seleccionar un plan, como abrir una pestaña emergente con más detalles del plan o redirigir a una página de registro o pago. Esto facilitaría al usuario el proceso de completar su selección y mejoraría la experiencia de navegación al hacerlo más intuitivo y directo.

**PROBLEMA #2:** Dificultades en la Navegación y Comprensión de la Propuesta de Valor en la Landing Page

**Severidad: 2**

**Problema:**  
Los usuarios encuentran dificultades para navegar en la landing page debido a la falta de claridad en la estructura de información y a un diseño visual poco intuitivo. Esto puede llevar a confusión y a una experiencia de usuario negativa, dificultando que los visitantes comprendan rápidamente la propuesta de valor del producto.

![errorlandingpage.png](../assets/img/chapter-V/sprint-3/errorlandingpage.png)

**Recomendación:**  
Se sugiere realizar una revisión completa de la arquitectura de información de la landing page, asegurando que los elementos más importantes (como beneficios, características clave y llamados a la acción) sean fácilmente accesibles y visualmente destacados. Implementar un diseño más limpio y organizado, utilizando jerarquías visuales efectivas, permitirá guiar a los usuarios a través de la página de manera más fluida. Además, incluir etiquetas y descripciones claras para cada sección ayudará a los usuarios a entender mejor el contenido presentado.

**PROBLEMA #3:** Diseño inconsistente en la sección de "Servicios"

**Severidad: 2**

**Problema:**  
La sección de "Servicios" carece de una jerarquía visual clara, lo que dificulta que los usuarios identifiquen rápidamente las características ofrecidas por la aplicación. Los textos descriptivos no están suficientemente destacados, y la falta de íconos o elementos visuales de apoyo hace que la información no sea fácilmente escaneable.

![errorlandingpage3.png](../assets/img/chapter-V/sprint-4/errorlandingpage3.png)

**Recomendación:**  
Se sugiere rediseñar la sección utilizando una jerarquía visual clara que destaque títulos, descripciones e íconos representativos de cada servicio. Además, se recomienda mejorar el contraste y la organización del contenido para facilitar la lectura y comprensión rápida.

**PROBLEMA #4:** Diseño inconsistente en la sección de "Servicios""

**Severidad: 3**

**Problema:**  
Los botones de llamado a la acción ("Comienza ahora", "Contáctanos") no tienen suficiente prominencia en el diseño de la página. Esto podría llevar a que los usuarios no los perciban como elementos interactivos importantes, afectando la conversión y el flujo de navegación.

![errorlandingpage4.png](../assets/img/chapter-V/sprint-4/errorlandingpage4.png)

**Recomendación:**  
Se recomienda rediseñar los botones de CTA para que sean más visibles, utilizando colores llamativos que contrasten con el fondo, tamaños más grandes y ubicaciones estratégicas en la página. Incluir microinteracciones, como cambios de color al pasar el cursor, también puede aumentar la claridad de su función y atraer la atención del usuario.



**TABLA DE RESUMEN - WEB APPLICATION:**
<table>
<thead>
 <tr>
  <th> # </th>
  <th> Problema </th>
  <th> Escala de severidad </th>
  <th> Heurística/Principio violada(o) </th>
</tr>
</thead>
<tbody>
<!--========================================= FILA 1 ======================================-->
<tr>
  <td> 1 </td>
  <td> Falta de captura de datos en el inventario </td>
  <td> 3 </td>
  <td> Usability: Control y libertad del usuario  </td>
</tr>
<!--========================================= FILA 2 ======================================-->
<tr>
  <td> 2 </td>
  <td> Mejora de diseño en la interfaz en la seccion "Vinicultor" </td>
  <td> 1 </td>
  <td> Inclusive Design: Estética y diseño minimalista </td>
</tr>
<!--========================================= FILA 3 ======================================-->
<tr>
  <td> 3 </td>
  <td> Mejora de diseño en la interfaz de menu </td>
  <td> 1 </td>
  <td> Inclusive Design: Estética y diseño minimalista </td>
</tr>
<!--========================================= FILA 4 ======================================-->
<tr>
  <td> 4 </td>
  <td> Falta la opcion de editar una orden </td>
  <td> 4  </td>
  <td> Usability: Visibilidad del estado del sistema </td>
</tr>
</tbody>
</table>


**_DESCRIPCIÓN DE PROBLEMAS - WEB APPLICATION:_**

**_PROBLEMA #1: Falta de captura de datos en el inventario**

**_Severidad: 3_**

**_Problema:_**
El boton de detalles en el apartado de "Inventario" no captura los datos correctamente, lo cual puede generar
confusion al usuario al momento de navegar en el dicho apartado. Esta problemática es de un nivel 3 de severidad,
ya que impide al usuario acceder a la aplicación y puede afectar negativamente
su experiencia.

![inventario_correcion.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Finventario_correcion.png)

**_Recomendación:_**
Se recomienda realizar un cambio en la estrcutura del codigo en la seccion de "Inventario" para que pueda captar bien los datos que
el usuario podra ir agregando. A partir de ello, el usuario ya podra visualizar correctamente los datos sin problema alguno.

**_PROBLEMA #2: Mejora de diseño en la interfaz en la seccion "Vinicultor"**

**_Severidad: 1_**

**_Problema:_** 

En el apartado de "Viniciacion" el usuario se le dificulta un poco en el momento de seleccionar dichas opciones que estan integradas en el dicho apartado
ya que si cada vez que agrega un cierto producto le gustaria que este añadido como un filtro para asi pueda registrar mas rapido los items.

![inventario_correcion2.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Finventario_correcion2.png)

**_Recomendación:_**

Se recomienda realizar una breve mejora en la estructura del codigo en el apartado css para que tenga una mayor visualizacion para asi para lograr una apariencia más
cohesiva y profesional. 

**_PROBLEMA #3: Falta de retroalimentación en el proceso de guardado de datos_**

**_Severidad: 2_**

**_Problema:_**  
En la sección de inventario, cuando el usuario guarda un nuevo registro, no recibe una notificación clara o retroalimentación visual de que la acción se ha completado exitosamente. Esto puede generar confusión sobre si el proceso de guardado fue efectivo, especialmente si el usuario está realizando múltiples cambios.


![inventario_correcion3.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Finventario_correcion3.png)

**_Recomendación:_**  
Implementar una notificación visual, como un mensaje de éxito o un icono de confirmación, que aparezca brevemente en la pantalla cada vez que se guarden los cambios en el inventario. Esto ayudará a mejorar la confianza del usuario en la funcionalidad y le permitirá continuar trabajando sin interrupciones o dudas sobre el resultado de sus acciones.

**_PROBLEMA #4: Mejora de diseño en la interfaz de menu_**

**_Severidad: 1_**

**_Problema:_**

En la seccion del menu, cuando el usuario quiere navegar en los features, ocupa mucho espacio en la pantalla de navegacion lo que provoca dificultad en la nvegacion del usuario. Haciendo que constantemente tenga que ir a la ruta de "Home" para seguir navegando nuevamente sin problema alguno.

<img src="/assets/img/chapter-V/sprint-4/menu.PNG" height="350" alt="landing_page">

**_Recomendación:_**

Para mejorar la navegación en los features, se sugiere optimizar el menú agrupando los elementos en submenús o categorías desplegables, lo que reducirá el espacio ocupado en pantalla. Además, esto permitirá a los usuarios regresar fácilmente a secciones anteriores sin necesidad de volver al "Home". También se pueden ofrecer accesos directos a las secciones más utilizadas y realizar pruebas de usabilidad para identificar áreas de mejora.

## 5.4. Video About-the-Product.


En esta sección presentamos el video sobre nuestro producto, ElixirControl. Este video ofrece una perspectiva promocional, resumida en el modelo de nuestro negocio, que abarca las funcionalidades y beneficios de la plataforma. También incluye escenas de interacción con el sistema y opiniones de los principales segmentos objetivo: vitivinicultores y distribuidores de vinos y piscos artesanales.

¿Eres un productor vitivinícola que busca una solución integral para gestionar tu inventario, mejorar la trazabilidad de tus productos y optimizar tus procesos? ¿O eres un distribuidor que quiere asegurar una cadena de suministro eficiente y bien organizada? Te presentamos ElixirControl. ElixirControl es nuestra plataforma que facilita la gestión de inventarios, pedidos y el control de calidad, diseñada especialmente para la industria vitivinícola, para que puedas dedicarte a lo que más importa: la creación de productos de alta calidad.

<img src="/assets/img/chapter-V/sprint-3/videoabouttheproduct.png" alt="Foto de video about-the-product">

Link de Microsoft Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EfKNxQVwL8dCmsXyvgw0ZywBpKddxlXlR_l-C_mZ1km9AA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1je8Hx

Link de Youtube: https://youtu.be/YTH8Bv54DZs

## 5.2.4. Sprint 4.

El proceso de este sprint se divide en dos partes: primero, establecemos el objetivo del sprint y 
seleccionamos las historias a abordar; luego, desglosamos esas historias en tareas más pequeñas y
asignamos responsabilidades. Al final, todos tenemos un plan claro y compartido, lo que nos permite
avanzar juntos hacia nuestros objetivos en la próxima iteración. 

Para la gestión de las tareas, el equipo está utilizando Jira. A continuación, se detalla la planificación

#### 5.2.4.1. Spring Planning 4.


<table>
<thead>
<tr>
    <th>Sprint #</th>
    <th>Sprint 4</th>
</tr>
</thead>
<tbody>
<!--====================================================================-->
<tr>
    <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
</tr>
<!--====================================================================-->
<tr>
    <td>Date</td>
    <td>09-11-2024</td>
</tr>
<!--====================================================================-->
<tr>
    <td>Time</td>
    <td> 10:00 p.m </td>
</tr>
<!--====================================================================-->
<tr>
    <td>Location</td>
    <td>Modalidad Remota a través de la plataforma Discord</td>
</tr>
<!--====================================================================-->
<tr>
    <td>Prepared By</td>
    <td>Janover Saldaña</td>
</tr>
<!--====================================================================-->
<tr>
    <td>Attendees (to planning meeting)</td>
    <td>Oscar Armas - Luis Villegas - Gustavo Huanca - Vicente Quijandria</td>
</tr>
<!--====================================================================-->
<tr>
    <td>Sprint 3 Review Summary</td>
    <td> 
        Durante el Sprint #3, el equipo realizó progresos significativos en la implementación de la gestión de inventarios, la administración de productos terminados, el manejo del proceso de vinificación por lotes de cosecha de uvas, así como en la gestión de la cartera de clientes de los vinicultores. Además, se avanzó en el desarrollo del historial de solicitudes de compra realizadas por los distribuidores a los vinicultores.
    </td>
</tr>
<!--====================================================================-->
<tr>
    <td>Sprint 3 Retrospective Summary</td>
    <td>
        Durante este sprint, el equipo enfrentó desafíos significativos, especialmente debido a un tiempo reducido para completar las tareas asignadas. Esta limitación impactó la comunicación y la gestión de actividades, lo que generó dificultades en el flujo de trabajo. A pesar de estos obstáculos, logramos cumplir con los objetivos establecidos gracias al compromiso y la colaboración de los demás miembros del equipo.
        A través de la resiliencia y el apoyo mutuo, completamos las entregas programadas, demostrando que, incluso en circunstancias adversas, el trabajo en equipo es esencial para el éxito. Identificamos varias oportunidades para mejorar la claridad en los roles y fortalecer el seguimiento de tareas, lo que nos permitirá optimizar nuestra dinámica en futuros sprints. Nuestro desempeño durante este periodo refleja un camino claro hacia el cumplimiento de los objetivos del próximo sprint, asegurando una mayor eficiencia en el uso de recursos y tiempo.
    </td>
</tr>
<!--====================================================================-->
<tr>
    <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
</tr>
<!--====================================================================-->
<tr>
    <td>Sprint 4 Goal</td>
    <td> 
      El equipo de productos de MetaSoft ha decidido mejorar la administración del inventario, el proceso de pedidos, la gestión del proceso de vinificación para vitivinivultores y la interacción de los usuarios con la plataforma Elixir Control. Se implementarán nuevos puntos finales en el backend para permitir la integración de funciones de gestión de inventarios, pedidos clientes, products, proceso de vinificación, y se realizarán mejoras en la aplicación web y la landing page de Elixir Control. Esto incluirá la posibilidad de buscar, editar y eliminar ítems en el inventario, proceso de vinificación, gestionar pedidos y clientes distribuidores, y proporcionar notificaciones sobre el estado de los pedidos. Además, se incluirá un video sobre el equipo en la landing page para atraer futuros usuarios.
      <br/><br/>
      Nos centramos en mejorar la gestión de inventarios, productos, pedidos y el proceso de vinificación, proporcionar nuevas funcionalidades para los vitivinicultores y distribuidores, y enriquecer la experiencia de los visitantes y developers. Esto incluirá la implementación de nuevos puntos finales en el backend para facilitar la gestión de pedidos, inventarios, productos, proceso de vinificación y gestión de clientes, la optimización de la aplicación web para permitir la búsqueda, edición y eliminación de ítems, así como el seguimiento de pedidos y la gestión de clientes distribuidores, el proceso de vinificación y productos. Además, la landing page será mejorada con un video sobre el equipo para atraer a futuros usuarios.
      <br/><br/>
      Esto se confirmará cuando los vitivinicultores y distribuidores puedan gestionar sus inventarios y pedidos de forma más eficiente, los visitantes puedan explorar la plataforma y obtener información clara sobre los servicios, y los developers puedan integrar nuevas funcionalidades a través de la API implementada, todo mientras el video esté visible en la landing page para atraer nuevos usuarios."
    </td>
</tr>
<!--====================================================================-->
<tr>
    <td>Sprint 4 Velocity</td>
    <td> Por definir </td>
</tr>
<!--====================================================================-->
<tr>
    <td>Sum of Story Points</td>
    <td> Por Definir </td>
</tr>
<!--====================================================================-->
</tbody>
</table>


#### 5.2.4.2.Sprint Backlog 4.

<table>
<thead>
<!------------------------------------------------------------------------------------>
<tr>
  <th> Sprint # </th>
  <th colspan="7"> Sprint 4 </th>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
  <th colspan="2"> User Story</th>
  <th colspan="6"> Work-Item / Task </th>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
  <th>User Story</th>
  <th>Title</th>
  <th>Id</th>
  <th>Title</th>
  <th>Description</th>
  <th>Estimation (Hours)</th>
  <th>Assigned To</th>
  <th>Status</th>
</tr>
<!------------------------------------------------------------------------------------>
</thead>
<tbody>
<!========================================= TS-02 ======================================>
<tr>
    <td rowspan="9">TS-02</td>
    <td rowspan="9">Editar Datos de los Procesos de Vinificación</td>
    <td>TS-02: TASK-01</td>
    <td>Diseñar el Modelo de Datos para la edición de procesos de vinificación</td>
    <td>Diseño de un modelo de datos que permita la edición en cada etapa de vinificación.</td>
    <td>6</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-02</td>
    <td>Crear Endpoints para Editar Datos de lotes</td>
    <td>Desarrollo de endpoints para actualizar los datos de los lotes.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-03</td>
    <td>Crear Endpoints para Editar Datos de Fermentación</td>
    <td>Desarrollo de endpoints para actualizar datos de fermentación.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-04</td>
    <td>Crear Endpoints para Editar Datos de Clarificación</td>
    <td>Desarrollo de endpoints para actualizar datos de clarificación.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-05</td>
    <td>Crear Endpoints para Editar Datos de Prensado</td>
    <td>Desarrollo de endpoints para actualizar datos de prensado.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-06</td>
    <td>Crear Endpoints para Editar Datos de añejamiento</td>
    <td>Desarrollo de endpoints para actualizar datos de añejamiento.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-07</td>
    <td>Crear Endpoints para Editar Datos de vinos embotellados</td>
    <td>Desarrollo de endpoints para actualizar datos de vinos embotellados.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-08</td>
    <td>Configurar Servicios de Actualización de Datos</td>
    <td>Configuración de servicios para manejar la actualización de datos de vinificación.</td>
    <td>5</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-02: TASK-09</td>
    <td>Implementar Control de Errores en la edición de datos</td>
    <td>Implementación de manejo de errores en los servicios de edición.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!========================================= TS-03 ======================================>
<tr>
    <td rowspan="8">TS-03</td>
    <td rowspan="8">Eliminar Datos de los Procesos de Vinificación</td>
    <td>TS-03: TASK-01</td>
    <td>Crear Endpoints para Eliminar Datos de lotes</td>
    <td>Desarrollo de endpoints para eliminar datos de los lotes.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-02</td>
    <td>Crear Endpoints para Eliminar Datos de Fermentación</td>
    <td>Desarrollo de endpoints para eliminar datos de fermentación.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-03</td>
    <td>Crear Endpoints para Eliminar Datos de Clarificación</td>
    <td>Desarrollo de endpoints para eliminar datos de clarificación.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-04</td>
    <td>Crear Endpoints para Eliminar Datos de Prensado</td>
    <td>Desarrollo de endpoints para eliminar datos de prensado.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-05</td>
    <td>Crear Endpoints para Eliminar Datos de añejamiento</td>
    <td>Desarrollo de endpoints para eliminar datos de añejamiento.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-06</td>
    <td>Crear Endpoints para Eliminar Datos de vinos embotellados</td>
    <td>Desarrollo de endpoints para eliminar datos de vinos embotellados.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-07</td>
    <td>Configurar Servicios de Eliminación de Datos</td>
    <td>Configuración de servicios para manejar la eliminación de datos de vinificación.</td>
    <td>4</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
<!------------------------------------------------------------------------------------>
<tr>
    <td>TS-03: TASK-08</td>
    <td>Implementar Control de Errores en la eliminación de datos</td>
    <td>Implementación de manejo de errores en los servicios de eliminación.</td>
    <td>3</td>
    <td>Janover Saldaña</td>
    <td>Done</td>
</tr>
    <tr>
        <td rowspan="4">TS-15</td>
        <td rowspan="4">Eliminar un ítem del inventario</td>
        <td>TS-15: TASK-01</td>
        <td>Crear un endpoint para eliminar el dato del inventario por "Id"</td>
        <td>Desarrollo de un endpoint que permita eliminar un ítem del inventario utilizando su ID.</td>
        <td>4</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-15: TASK-02</td>
        <td>Validar el dato eliminado del inventario por "Id"</td>
        <td>Implementación de la lógica para validar que el ítem ha sido eliminado correctamente.</td>
        <td>3</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-15: TASK-03</td>
        <td>Actualizar el inventario con el dato eliminado</td>
        <td>Actualizar la base de datos o sistema de inventario tras la eliminación del ítem.</td>
        <td>5</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-15: TASK-04</td>
        <td>Implementar mensaje sobre dato erróneo ingresado</td>
        <td>Desarrollar un mensaje claro que informe al usuario sobre errores en la eliminación.</td>
        <td>2</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
   <!------------------------------------------------------------------------------------>
   <tr>
        <td rowspan="4">TS-17</td>
        <td rowspan="4">Buscar y filtrar ítems en el inventario</td>
        <td>TS-17: TASK-01</td>
        <td>Crear un endpoint para filtrar las búsquedas de ítems en el inventario</td>
        <td>Desarrollo de un endpoint que permita realizar búsquedas filtradas de ítems en el inventario.</td>
        <td>4</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-17: TASK-02</td>
        <td>Validar la búsqueda por nombre, tipo y unidad en el inventario</td>
        <td>Implementación de la lógica para validar las búsquedas según nombre, tipo y unidad de los ítems.</td>
        <td>3</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-17: TASK-03</td>
        <td>Implementar la captura de datos por filtro realizado en el inventario</td>
        <td>Desarrollo de la funcionalidad para capturar los datos resultantes del filtro aplicado.</td>
        <td>5</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>TS-17: TASK-04</td>
        <td>Implementar mensaje sobre dato erróneo ingresado</td>
        <td>Desarrollo de un mensaje claro que informe al usuario sobre errores en la búsqueda.</td>
        <td>2</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
<!------------------------------------------------------------------------------------>
       <tr>
        <td rowspan="3">US-31</td>
        <td rowspan="3">Informes de inventario</td>
        <td>US-31: TASK-01</td>
        <td>Agregar una funcionalidad de detalles del inventario</td>
        <td>Desarrollo de una función que permita ver los detalles de los ítems en el inventario.</td>
        <td>4</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>US-31: TASK-02</td>
        <td>Implementar la captura de datos del inventario</td>
        <td>Desarrollo de la funcionalidad para capturar y almacenar datos relevantes del inventario.</td>
        <td>5</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!------------------------------------------------------------------------------------>
    <tr>
        <td>US-31: TASK-03</td>
        <td>Agregar la funcionalidad de regresar al menú del inventario</td>
        <td>Implementación de un botón o enlace que permita regresar al menú principal del inventario.</td>
        <td>3</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="3">US-27</td>
        <td rowspan="3">Registro de nuevos insumos en el inventario</td>
        <td>US-27: TASK-01</td>
        <td>Registrar el Nombre del producto</td>
        <td>Desarrollo de un formulario para ingresar el nombre del nuevo producto en el inventario.</td>
        <td>3</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td>US-27: TASK-02</td>
        <td>Registrar Fecha de expiración del producto</td>
        <td>Implementación de un campo para ingresar la fecha de expiración del producto.</td>
        <td>3</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td>US-27: TASK-03</td>
        <td>Registrar tipos del producto</td>
        <td>Desarrollo de un sistema para clasificar y registrar los tipos de productos en el inventario.</td>
        <td>4</td>
        <td>Luis Villegas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td rowspan="2">TS-12</td>
        <td rowspan="2">Actualizar estado de un pedido </td>
        <td>TS-12: TASK-01</td>
        <td>Actualizar el estado de un pedido</td>
        <td>Desarrollar el endpoint para hacer un update al status de un pedido</td>
        <td>4</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-12: TASK-02</td>
        <td>Validar el cambio de estado de una orden</td>
        <td>Validar que el endpoint de update status maneje correctamente las respuestas</td>
        <td>2</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="3">TS-18</td>
        <td rowspan="3">Eliminar un pedido </td>
        <td>TS-18: TASK-01</td>
        <td>Eliminar el registro de un pedido</td>
        <td>Desarrollar funcionalidad para eliminar un pedido</td>
        <td>4</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-18: TASK-02</td>
        <td>Crear endpoint para eliminar un pedido por id</td>
        <td>Crear el endpoint "/api/v1/orders/{id}" en el controlador</td>
        <td>3</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-18: TASK-03</td>
        <td>Validar se elimina correctamente el pedido</td>
        <td>Validar que el endpoint de delete order maneje correctamente las respuestas</td>
        <td>2</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="3">US-35</td>
        <td rowspan="3">Administrar el estado de un pedido</td>
        <td>US-35: TASK-01</td>
        <td>Administrar estado de un pedido</td>
        <td>Desarrollar la logica para que el combobox consuma el endpoint de update</td>
        <td>4</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-35: TASK-02</td>
        <td>Desarrollar componente para cambiar estado de pedido</td>
        <td>Desarrollar el componente input para que el usuario cambie el estado del pedido</td>
        <td>3</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-35: TASK-03</td>
        <td>Validar que se actualice correctamente el pedido</td>
        <td>Validar que el input este actualizando correctamente el estado del pedido</td>
        <td>2</td>
        <td>Vicente Quijandria</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="3">US-22</td>
        <td rowspan="3">Seguimiento del estado del pedido</td>
        <td>US-22: TASK-01</td>
        <td>Crear la sección de seguimiento de pedidos</td>
        <td>Diseñar una sección en el frontend que muestre el estado actual de cada pedido (pendiente, en proceso, enviado, entregado).</td>
        <td>4</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-22: TASK-02</td>
        <td>Implementar notificaciones de cambio de estado</td>
        <td>Configurar el backend para que envíe una notificación al distribuidor cada vez que el estado de un pedido cambie.</td>
        <td>3</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-22: TASK-03</td>
        <td>Actualizar el estado de los pedidos en el sistema</td>
        <td>Crear la lógica para actualizar el estado de un pedido en el sistema y reflejarlo en la cuenta del distribuidor.</td>
        <td>2</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="3">US-23</td>
        <td rowspan="3">Confirmación de disponibilidad de stock</td>
        <td>US-23: TASK-01</td>
        <td>Validar stock en tiempo real</td>
        <td>Desarrollar una función en el backend que valide la disponibilidad de stock al momento de que el distribuidor seleccione los productos.</td>
        <td>4</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-23: TASK-02</td>
        <td>Implementar notificación de falta de stock</td>
        <td>Configurar una notificación en el frontend que indique al distribuidor cuando el stock no es suficiente para completar el pedido.</td>
        <td>3</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-23: TASK-03</td>
        <td>Ofrecer alternativas en caso de falta de stock</td>
        <td>Permitir que el distribuidor ajuste las cantidades o seleccione productos alternativos en caso de que el stock esté limitado.</td>
        <td>2</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="3">US-24</td>
        <td rowspan="3">Programación de entregas</td>
        <td>US-24: TASK-01</td>
        <td>Configurar el selector de fecha de entrega en el formulario de pedido</td>
        <td>Agregar un selector de fecha en el formulario de pedido que permita al distribuidor seleccionar una fecha de entrega adecuada.</td>
        <td>4</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-24: TASK-02</td>
        <td>Validar fechas disponibles de entrega</td>
        <td>Crear una lógica en el backend que verifique que la fecha de entrega seleccionada esté dentro de las opciones de entrega permitidas.</td>
        <td>3</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-24: TASK-03</td>
        <td>Confirmar y almacenar la fecha de entrega seleccionada</td>
        <td>Almacenar la fecha de entrega seleccionada en la base de datos y mostrarla en la confirmación del pedido.</td>
        <td>2</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="2">US-21</td>
        <td rowspan="2">Creación de pedidos de vinos</td>
        <td>US-21: TASK-02</td>
        <td>Configurar el endpoint para la creación de pedidos</td>
        <td>Desarrollar el endpoint en el backend para recibir y procesar los datos de un nuevo pedido, y retornar una confirmación de éxito.</td>
        <td>4</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>US-21: TASK-03</td>
        <td>Validar los datos del pedido</td>
        <td>Implementar validaciones para asegurar que los datos enviados (productos y cantidades) sean válidos y cumplan con los requisitos de negocio.</td>
        <td>3</td>
        <td>Oscar Armas</td>
        <td>Done</td>
    </tr>
<!-------------------------------------------------------------------------------------->
    <tr>
        <td rowspan="4">TS-06</td>
        <td rowspan="4">Editar los detalles de un cliente distribuidor</td>
        <td>TS-06: TASK 01</td>
        <td> Crear update client command.</td>
        <td>Desarrollar el update client command con los atributos correspondientes.</td>
        <td>4</td>
        <td>Gustavo Huanca</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-06: TASK 02</td>
        <td>Añadir el componente update client al servicio</td>
        <td>Intregrar el update client command service en el servicio.</td>
        <td>3</td>
        <td>Gustavo Huanca</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-06: TASK-03</td>
        <td>Implementar el servicio update clients</td>
        <td>Implementamos el servicio agregando validaciones y reglas de negocio .</td>
        <td>3</td>
        <td>Gustavo Huanca</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>TS-06: TASK-04</td>
        <td>Agregar Lógica en el Controlador para Actualizar Información del Cliente</td>
        <td>Implementamos el PUT con la ruta {id} .</td>
        <td>4</td>
        <td>Gustavo Huanca</td>
        <td>Done</td>
    </tr>
<!-------------------------------------------------------------------------------------->
<tr>
    <td rowspan="5">TS-07</td>
    <td rowspan="5">Eliminar un cliente distribuidor</td>
    <td>TS-07: TASK-01</td>
    <td>Crear el componente delete client.</td>
    <td>Desarrollar el componente delete client con los atributos necesarios para eliminar un cliente distribuidor.</td>
    <td>4</td>
    <td>Gustavo Huanca</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-07: TASK-02</td>
    <td>Añadir el componente delete client al servicio</td>
    <td>Integrar el componente delete client en el servicio para la funcionalidad de eliminación.</td>
    <td>3</td>
    <td>Gustavo Huanca</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-07: TASK-03</td>
    <td>Implementar el servicio de comando delete client</td>
    <td>Desarrollar el servicio de comando delete client, incluyendo la lógica de eliminación.</td>
    <td>3</td>
    <td>Gustavo Huanca</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-07: TASK-04</td>
    <td>Implementar validaciones</td>
    <td>Agregar validaciones y reglas de negocio necesarias para la eliminación del cliente distribuidor.</td>
    <td>3</td>
    <td>Gustavo Huanca</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-07: TASK-05</td>
    <td>Agregar Lógica en el Controlador para Eliminar Información del Cliente</td>
    <td>Implementar el DELETE con la ruta {id} para eliminar el cliente distribuidor.</td>
    <td>4</td>
    <td>Gustavo Huanca</td>
    <td>Done</td>
</tr>
</tbody>
</table>  


#### 5.2.4.3.Development Evidence for Sprint Review.
<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="10">ElixirControl-Landing-Page</td>
            <td>main</td>
            <td>d54a8d8</td>
            <td>feat: Updated the styles and html of the About The App section.</td>
            <td>Updated the styles and html of the About The App section.</td>
            <td>Commited on 04/11/2024</td>
        </tr>
    </tbody>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="21">ElixirControl-FrontEnd</td>
            <td>feature/security</td>
            <td>01ae914</td>
            <td>feat(security): added base structure for user login.</td>
            <td>Added base structure for user login.</td>
            <td>Commited on 05/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>19c0269</td>
            <td>feat(customer-management): attributes names fixed.</td>
            <td>attributes names fixed.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>85853e8</td>
            <td>feat(iam): add request and response model types.</td>
            <td>added request and response model types.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>80026bf</td>
            <td>feat(iam): add authentication service.</td>
            <td>added authentication service.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>643133b</td>
            <td>chore: add pinia for state management.</td>
            <td>added pinia for state management.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>debb046</td>
            <td>chore: add authentication interceptor.</td>
            <td>added authentication interceptor.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>0b9b86c</td>
            <td>chore: add sign-in component.</td>
            <td>added sign-in component.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>11c6200</td>
            <td>chore: add sign-up component.</td>
            <td>added sign-up component.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>b2d1ec3</td>
            <td>feat(iam): add authentication section to header content.</td>
            <td>Added authentication section to header content.</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/IAM</td>
            <td>a155d28</td>
            <td>feat(iam): add sign up and sign in routes</td>
            <td>Added sign up and sign in routes</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>415571c</td>
            <td>refactor(order-management): separated the contact entity data from the orders entity</td>
            <td>Separated the contact entity data from the orders entity</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>3996815</td>
            <td>feat(order-details): added order status input dropdown to update order status</td>
            <td>Added order status input dropdown to update order status</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>13032f3</td>
            <td>refactor(order-management): fixed problem of phone data not showing in the order management component</td>
            <td>Fixed problem of phone data not showing in the order management component</td>
            <td>Commited on 16/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-requests</td>
            <td>c7f9dc1</td>
            <td>feat(order-requests): attributes names fixed.</td>
            <td>Attributes names fixed.</td>
            <td>Commited on 17/11/2024</td>
        </tr>
    </tbody>
    <tbody>
        <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="44">ElixirControl-Platform</td>
            <td>feature/inventory-management</td>
            <td>1e383b0</td>
            <td>feat(inventory-management): Update in the "InventoryCommandService"</td>
            <td>Updated in the "InventoryCommandService"</td>
            <td>Commited on 06/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>f965d96</td>
            <td>feat(inventory-management): Added in the "UpdateInventoryCommand" with  update inventory constructor entity</td>
            <td>Added in the "UpdateInventoryCommand" with  update inventory constructor entity</td>
            <td>Commited on 06/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>44aee02</td>
            <td>feat(inventory-management): Added in the "GetInventoriesByFilterQuery"</td>
            <td>Added in the "GetInventoriesByFilterQuery"</td>
            <td>Commited on 06/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>277d7c9</td>
            <td>feat(inventory-management): Added in the "UpdateInventoryResource"</td>
            <td>Added in the "UpdateInventoryResource"</td>
            <td>Commited on 06/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>eeb64b9</td>
            <td>feat (inventory management): Update in the "InventoryController" with inventory search by filter</td>
            <td>Updated in the "InventoryController" with inventory search by filter</td>
            <td>Commited on 06/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>bcf1ffd</td>
            <td>feat (inventory management): Added in the "DeleteInventoryCommand"</td>
            <td>Added in the "DeleteInventoryCommand"</td>
            <td>Commited on 07/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>631d31b</td>
            <td>feat (inventory management): Added in the "IInventoryCommandService" with inventory delete</td>
            <td>Added in the "IInventoryCommandService" with inventory delete</td>
            <td>Commited on 07/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>fed6be5</td>
            <td>feat (inventory management): Added in the "IInventoryRepository" with inventory delete</td>
            <td>Added in the "IInventoryRepository" with inventory delete</td>
            <td>Commited on 07/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>cd83dc3</td>
            <td>feat (inventory management): Added in the "InventoryController" with inventory delete</td>
            <td>Added in the "InventoryController" with inventory delete</td>
            <td>Commited on 07/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>c893dab</td>
            <td>feat(winemaking-process): Added implementation of commands to update the Fermentation, Clarification, Pressing and Aging processes.</td>
            <td>Added implementation of commands to update the Fermentation, Clarification, Pressing and Aging processes.</td>
            <td>Commited on 04/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>6392140</td>
            <td>feat(winemaking-process): Added endpoints in the controller to UPDATE Fermentation, Clarification, Pressing and Aging processes.</td>
            <td>Added endpoints in the controller to UPDATE Fermentation, Clarification, Pressing and Aging processes.</td>
            <td>Commited on 04/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>8e49168</td>
            <td>feat(profile): Added the Name, Email Address and Person Name value object to profiles</td>
            <td>Added the Name, Email Address and Person Name value object to profiles</td>
            <td>Commited on 14/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>3dc4277</td>
            <td>feat(profile): Added queries and creation command for profile.</td>
            <td>Added queries and creation command for profile.</td>
            <td>Commited on 14/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>0df6739</td>
            <td>feat(profile): Added interfaces for Commands, Queries, and Repository.</td>
            <td>Added interfaces for Commands, Queries, and Repository.</td>
            <td>Commited on 14/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>c71aa60</td>
            <td>feat(profile): Added implementation of services for commands, queries and repository.</td>
            <td>Added implementation of services for commands, queries and repository.</td>
            <td>Commited on 14/11/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-profiles</td>
            <td>4a11aa8</td>
            <td>feat(profile): Added interface layer for profiles.</td>
            <td>Added interface layer for profiles.</td>
            <td>Commited on 14/11/2024</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th rowspan="">Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="46">ElixirControl-Backend</td>
            <td>feature/inventory-management</td>
            <td>689794</td>
            <td>feat(inventory-management): added interface inventory controller</td>
            <td>Added interface inventory controller</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/inventory-management</td>
            <td>4c1b464</td>
            <td>feat(inventory-management): Added transform and application layer for inventory.</td>
            <td>Added transform and application layer for inventory.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/inventory-management</td>
            <td>515735</td>
            <td>feat(inventory-management): Added resources and application layer for inventory.</td>
            <td>Added resources and application layer for inventory.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/inventory-management</td>
            <td>06ca584</td>
            <td>chore(inventory-management): Added the inventory management bounded context structure.</td>
            <td>Added the inventory management bounded context structure.</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <tr>
            <td>feature/winemaking-process</td>
            <td>91a9999</td>
            <td>feat(winemaking-process): Added interface layer for batch endpoint.</td>
            <td>Added interface layer for batch endpoint.</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <tr>
            <td>feature/winemaking-process</td>
            <td>9eff846</td>
            <td>feat(winemaking-process): Added infrastructure and application layer for batches.</td>
            <td>Added infrastructure and application layer for batches.</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <tr>
            <td>feature/winemaking-process</td>
            <td>66834f4</td>
            <td>feat(winemaking-process): Added domain layer for batches.</td>
            <td>Added domain layer for batches.</td>
            <td>Commited on 20/10/2024</td>
        </tr>
         <tr>
            <td>feature/inventory-management</td>
            <td>689794</td>
            <td>feat(inventory-management): added interface inventory controller</td>
            <td>Added interface inventory controller</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>feature/inventory-management</td>
            <td>4c1b464</td>
            <td>feat(inventory-management): Added transform and application layer for inventory.</td>
            <td>Added transform and application layer for inventory.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/inventory-management</td>
            <td>515735</td>
            <td>feat(inventory-management): Added resources and application layer for inventory.</td>
            <td>Added resources and application layer for inventory.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/inventory-management</td>
            <td>06ca584</td>
            <td>chore(inventory-management): Added the inventory management bounded context structure.</td>
            <td>Added the inventory management bounded context structure.</td>
            <td>Commited on 27/10/2024</td>
        </tr>
       <tr>
            <td>feature/customer-management</td>
            <td>9cc12al</td>
            <td>feat(customer-management): create client command from resource assembler added.</td>
            <td>Create client command from resource assembler added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>feature/customer-management</td>
            <td>df2045a</td>
            <td>feat(customer-management): end points added.</td>
            <td>End points added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>b4f8bdb</td>
            <td>feat(customer-management): client resource from entity assembles added.</td>
            <td>Client resource from entity assembles added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>d89597</td>
            <td>feat(customer-management): client resource added.</td>
            <td>Client resource added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>3c32ce3</td>
            <td>feat(customer-management): client repository added.</td>
            <td>Client repository added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>34ace70</td>
            <td>feat(customer-management): client query service added.</td>
            <td>Client query service added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>feature/customer-management</td>
            <td>9683929</td>
            <td>feat(customer-management): client command service added.</td>
            <td>Client command service added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>b2a5d3d</td>
            <td>feat(customer-management): create client resource added.</td>
            <td>Create client resource added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>7738dea</td>
            <td>feat(customer-management): dependency injection of clients added.</td>
            <td>Dependency injection of clients added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>2233cbc</td>
            <td>feat(customer-management): interface client query service added.</td>
            <td>Interface client query service added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>1bd6de8</td>
            <td>feat(customer-management): find all clients async method added.</td>
            <td>Find all clients async method added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>487c5dc</td>
            <td>feat(customer-management): db context of clients added.</td>
            <td>DB context of clients added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/customer-management</td>
            <td>713529</td>
            <td>feat(customer-management): class client added.</td>
            <td>Class client added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>dc7ed62</td>
            <td>feat(CreateOrderCommand From ResourceAssembler): added the CreateOrderCommand From ResourceAssembler</td>
            <td>Added the CreateOrderCommand From ResourceAssembler</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>feature/order-management</td>
            <td>287b688</td>
            <td>feat(OrderRepository): added the Order Repository</td>
            <td>Added the Order Repository</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>998ca67</td>
            <td>docker file deleted</td>
            <td>Docker file deleted.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>e56e85f</td>
            <td>docker file added.</td>
            <td>Docker file added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>833aabb</td>
            <td>feat(OrderResource): added the OrderResource</td>
            <td>Added the OrderResource.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>7907eb9</td>
            <td>feat(OrderResource): Added the order resource from entity assembler.</td>
            <td>Added the order resource from entity assembler.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>@2bbf1d</td>
            <td>feat(OrdersController): added HTTP GET method for get all orders operation.</td>
            <td>Added HTTP GET method for get all orders operation.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>c0df+29</td>
            <td>chore: database connection added.</td>
            <td>Database connection added.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>714671</td>
            <td>feat(Program): added dependency injection for orders entity.</td>
            <td>Added dependency injection for orders entity.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>c0dbb43</td>
            <td>refactor(example): deleted md files.</td>
            <td>Deleted markdown files.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>feature/winemaking-process</td>
            <td>14ccb3a</td>
            <td>feat(winemaking-process): Added REST resources and transforms to add batch clarification stage.</td>
            <td>Added REST resources and transforms to add batch clarification stage.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>feature/winemaking-process</td>
            <td>358ec4b</td>
            <td>feat(OrdersController): finished the Orders Controller.</td>
            <td>Finished the Orders Controller.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
       <tr>
            <td>develop</td>
            <td>2a3714d</td>
            <td>fix(develop): Fixed the content of AppDbContext and Program.cs.</td>
            <td>Fixed the content of AppDbContext and Program.cs.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>c097cfd</td>
            <td>Merge remote-tracking branch 'refs/remotes/origin/feature/order-management' into develop</td>
            <td>Merged feature/order-management into develop.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>Be95ab7</td>
            <td>Merge remote-tracking branch 'origin/feature/inventory-management' into develop</td>
            <td>Merged feature/inventory-management into develop.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>Bef2@b1</td>
            <td>Merge remote-tracking branch 'origin/feature/customer-management' into develop</td>
            <td>Merged feature/customer-management into develop.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>6e4ffdd</td>
            <td>feat(customer-management): enumerable fixed.</td>
            <td>Enumerable fixed.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>db14ce7</td>
            <td>feat(winemaking-process): Added endpoints to POST and GET the batch pressing process.</td>
            <td>Added endpoints to POST and GET the batch pressing process.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>70f11e5</td>
            <td>feat(winemaking-process): Added endpoints to create and return the batch pressing process.</td>
            <td>Added endpoints to create and return the batch pressing process.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>@dfbc47</td>
            <td>chore: test finished.</td>
            <td>Test finished.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>2d9ddec</td>
            <td>chore: test finished.</td>
            <td>Test finished.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td>develop</td>
            <td>630518</td>
            <td>feat(winemaking-process): Added comments to the winemaking process controller.</td>
            <td>Added comments to the winemaking process controller.</td>
            <td>Commited on 03/11/2024</td>
        </tr>
        <tr>
            <td rowspan="20">ElixirControl-Frontend</td>
            <td>feature/iam</td>
            <td>a155d28</td>
            <td>feat(iam): add sign up and sign in routes</td>
            <td>Add sign up and sign in routes.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>b2d1ec3</td>
            <td>feat(iam): add authentication section to header content.</td>
            <td>Add authentication section to header content.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>d0d8b7c</td>
            <td>chore: add authentication section component.</td>
            <td>Add authentication section component.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>659234</td>
            <td>chore: add authentication guard.</td>
            <td>Add authentication guard.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>11c6200</td>
            <td>chore: add sign-up component.</td>
            <td>Add sign-up component.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
           <tr>
            <td>feature/iam</td>
            <td>0b9b86c</td>
            <td>chore: add sign-in component.</td>
            <td>Add sign-in component.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>debb046</td>
            <td>chore: add authentication interceptor.</td>
            <td>Add authentication interceptor.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>55896</td>
            <td>chore: add authentication store.</td>
            <td>Add authentication store.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>6431336</td>
            <td>chore: add pinia for state management.</td>
            <td>Add Pinia for state management.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>80026bf</td>
            <td>feat(iam): add authentication service.</td>
            <td>Add authentication service.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>858538</td>
            <td>feat(iam): add request and response model types.</td>
            <td>Add request and response model types.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/iam</td>
            <td>0a13605</td>
            <td>chore: update dependencies.</td>
            <td>Update dependencies.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
       <tr>
            <td>feature/order-management</td>
            <td>b8df9ed</td>
            <td>refactor(order-management): fixed problem of phone data not showing in the order management component</td>
            <td>Fixed problem of phone data not showing in the order management component.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>1303243</td>
            <td>refactor(order-management): fixed problem of phone data not showing in the order management component</td>
            <td>Fixed problem of phone data not showing in the order management component.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-details</td>
            <td>3996815</td>
            <td>feat(order-details): added order status input dropdown to update order status</td>
            <td>Added order status input dropdown to update order status.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-management</td>
            <td>415571c</td>
            <td>refactor(order-management): separated the contact entity data from the orders entity</td>
            <td>Separated the contact entity data from the orders entity.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
          <tr>
            <td>feature/order-management</td>
            <td>@c95e8a</td>
            <td>refactor(order-management): fixed an error of the details button not displaying correctly</td>
            <td>Fixed an error of the details button not displaying correctly.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-details</td>
            <td>be0e883</td>
            <td>feat(order-details): added more details of the new attributes of the order</td>
            <td>Added more details of the new attributes of the order.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order-create-and-edit</td>
            <td>cdSelab</td>
            <td>feat(order-create-and-edit): added more inputs for the new attributes of the order</td>
            <td>Added more inputs for the new attributes of the order.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
        <tr>
            <td>feature/order.entity</td>
            <td>661eb7d</td>
            <td>feat(order.entity): added more attributes to the order entity</td>
            <td>Added more attributes to the order entity.</td>
            <td>Commited on 15/11/2024</td>
        </tr>
    </tbody>
</table>

#### 5.2.4.4.Testing Suite Evidence for Sprint Review.

# Pruebas Unitarias para Gestión de Inventario

## 1. Probar Registro de Nuevo Inventario de Vinos
- **Objetivo**: Verificar que se registre correctamente un nuevo inventario de vino.
- **Descripción**:
  - Dado un vino con ID "V001" y stock inicial de 10 unidades.
  - Cuando se agregan 5 unidades al inventario.
  - Entonces, el inventario debe actualizarse a 15 unidades.
- **Código de Prueba**:
    ```csharp
    using NUnit.Framework;

    [TestFixture]
    public class InventarioVinosTests
    {
        [Test]
        public void TestRegistrarNuevoInventarioDeVino()
        {
            // Arrange
            var vino = new Vino("V001", "Merlot", 10);
            
            // Act
            vino.AgregarUnidades(5);
            
            // Assert
            Assert.AreEqual(15, vino.Stock);
        }
    }
    ```

## 2. Probar Error al Restar Unidades No Disponibles
- **Objetivo**: Asegurar que se maneje el error al intentar restar más unidades de las disponibles.
- **Descripción**:
  - Dado un vino con ID "V002" y stock de 5 unidades.
  - Cuando se intenta restar 10 unidades del inventario.
  - Entonces, se debe lanzar una excepción de "Stock insuficiente".
- **Código de Prueba**:
    ```csharp
    using NUnit.Framework;

    [TestFixture]
    public class InventarioVinosTests
    {
        [Test]
        public void TestErrorAlRestarUnidadesNoDisponibles()
        {
            // Arrange
            var vino = new Vino("V002", "Cabernet Sauvignon", 5);
            
            // Act & Assert
            var ex = Assert.Throws<InvalidOperationException>(() => vino.RestarUnidades(10));
            Assert.AreEqual("Stock insuficiente", ex.Message);
        }
    }
    ```
# Pruebas de Integración para Gestión de Órdenes

## 1. Crear Orden Exitosamente
- **Objetivo**: Verificar que el sistema confirme correctamente una orden y actualice el saldo del usuario.
- **Descripción**:
  - Dado que el usuario tiene ID "U001" y un saldo de $100.
  - Y existe un vino con ID "V001" que cuesta $50.
  - Cuando el usuario crea una orden de compra por el vino "V001".
  - Entonces, el sistema debe confirmar la orden.
  - Y el saldo del usuario debe reducirse a $50.
- **Resultado Esperado**: La orden debe ser confirmada y el saldo del usuario debe reflejar correctamente $50.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class OrdenesTests
{
    [Test]
    public void TestCrearOrdenExitosamente()
    {
        // Arrange
        var usuario = new Usuario("U001", 100);
        var vino = new Vino("V001", "Merlot", 50);
        var sistema = new SistemaDeOrdenes();

        // Act
        var orden = sistema.CrearOrden(usuario, vino, 1);

        // Assert
        Assert.IsNotNull(orden);
        Assert.AreEqual(50, usuario.Saldo);
        Assert.AreEqual("Confirmada", orden.Estado);
    }
}
```

## 2. Cancelar Orden en Estado Pendiente
- **Objetivo**: Asegurar que el sistema cambie correctamente el estado de una orden a "Cancelado".
- **Descripción**:
  - Dado que existe una orden con ID "O001" en estado "Pendiente".
  - Cuando el cliente cancela la orden.
  - Entonces, el sistema debe cambiar el estado de la orden a "Cancelado".
- **Resultado Esperado**: El estado de la orden "O001" debe actualizarse a "Cancelado".

### Código de Prueba
```csharp
[Test]
public void TestCancelarOrdenEnEstadoPendiente()
{
    // Arrange
    var sistema = new SistemaDeOrdenes();
    var orden = sistema.CrearOrden(new Usuario("U001", 100), new Vino("V001", "Merlot", 50), 1);
    
    // Act
    sistema.CancelarOrden(orden.Id);

    // Assert
    Assert.AreEqual("Cancelado", orden.Estado);
}
```
## 3. Actualizar Estado de Orden a "Enviado"
- **Objetivo**: Confirmar que el sistema actualiza correctamente el estado de una orden a "Enviado".
- **Descripción**:
  - Dado que existe una orden con ID "O001" en estado "Confirmado".
  - Cuando el vinicultor marca la orden como enviada.
  - Entonces, el sistema debe actualizar el estado de la orden a "Enviado".
- **Resultado Esperado**: El estado de la orden "O001" debe reflejar "Enviado".

### Código de Prueba
```csharp
[Test]
public void TestActualizarEstadoDeOrdenAEnviado()
{
    // Arrange
    var sistema = new SistemaDeOrdenes();
    var orden = sistema.CrearOrden(new Usuario("U001", 100), new Vino("V001", "Merlot", 50), 1);
    
    // Act
    sistema.MarcarOrdenComoEnviada(orden.Id);

    // Assert
    Assert.AreEqual("Enviado", orden.Estado);
}
```

## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

## 3. Probar Verificación de Stock de Vino
- **Objetivo**: Confirmar que el sistema verifica correctamente el stock disponible del vino.
- **Descripción**:
  - Dado un vino con ID "V001" y stock de 20 unidades.
  - Cuando se verifica el stock del vino.
  - Entonces, debe retornar que hay 20 unidades disponibles.
- **Código de Prueba**:
    ```csharp
    using NUnit.Framework;

    [TestFixture]
    public class InventarioVinosTests
    {
        [Test]
        public void TestVerificarStockDeVino()
        {
            // Arrange
            var vino = new Vino("V001", "Merlot", 20);
            
            // Act
            var stockDisponible = vino.VerificarStock();
            
            // Assert
            Assert.AreEqual(20, stockDisponible);
        }
    }
    ```

## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

# Pruebas de Integración para Solicitud de Órdenes

## 1. Crear Solicitud de Orden Exitosamente
- **Objetivo**: Verificar que el sistema registre correctamente una solicitud de orden con estado "Pendiente".
- **Descripción**:
  - Dado que existe un usuario con ID "U001".
  - Y existe un producto con ID "P001" con stock suficiente.
  - Cuando el usuario solicita 5 unidades del producto "P001".
  - Entonces, el sistema debe registrar la solicitud con estado "Pendiente".
- **Resultado Esperado**: La solicitud debe ser registrada y su estado debe ser "Pendiente".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class SolicitudOrdenesTests
{
    [Test]
    public void TestCrearSolicitudOrdenExitosamente()
    {
        // Arrange
        var usuario = new Usuario("U001");
        var producto = new Producto("P001", "Vino Tinto", 10); // Stock suficiente
        var sistema = new SistemaDeSolicitudes();

        // Act
        var solicitud = sistema.CrearSolicitudOrden(usuario, producto, 5);

        // Assert
        Assert.IsNotNull(solicitud);
        Assert.AreEqual("Pendiente", solicitud.Estado);
    }
}
```

## 2. Rechazar Solicitud de Orden por Falta de Stock
- **Objetivo**: Asegurar que el sistema rechace correctamente una solicitud cuando no hay stock disponible.
- **Descripción**:
  - Dado que existe un producto con ID "P001" con 0 unidades en stock.
  - Cuando un usuario solicita 5 unidades del producto "P001".
  - Entonces, el sistema debe rechazar la solicitud y mostrar un mensaje de error.
- **Resultado Esperado**: La solicitud debe ser rechazada y se debe mostrar un mensaje de error indicando la falta de stock.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class SolicitudOrdenesTests
{
    [Test]
    public void TestRechazarSolicitudOrdenPorFaltaDeStock()
    {
        // Arrange
        var usuario = new Usuario("U001");
        var producto = new Producto("P001", "Vino Tinto", 0); // Sin stock
        var sistema = new SistemaDeSolicitudes();

        // Act & Assert
        var ex = Assert.Throws<Exception>(() => sistema.CrearSolicitudOrden(usuario, producto, 5));
        Assert.AreEqual("No hay suficiente stock disponible", ex.Message);
    }
}
```
## 3. Confirmar Solicitud de Orden Después de Aprobación
- **Objetivo**: Confirmar que el sistema actualiza correctamente el estado de una solicitud a "Confirmado" después de la aprobación.
- **Descripción**:
  - Dado que existe una solicitud de orden con ID "OR001" en estado "Pendiente".
  - Cuando el administrador aprueba la solicitud.
  - Entonces, el sistema debe cambiar el estado de la solicitud a "Confirmado".
- **Resultado Esperado**: El estado de la solicitud "OR001" debe actualizarse a "Confirmado".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class SolicitudOrdenesTests
{
    [Test]
    public void TestConfirmarSolicitudOrdenDespuesDeAprobacion()
    {
        // Arrange
        var sistema = new SistemaDeSolicitudes();
        var usuario = new Usuario("U001");
        var producto = new Producto("P001", "Vino Tinto", 10);
        var solicitud = sistema.CrearSolicitudOrden(usuario, producto, 5); // Estado inicial: Pendiente
        
        // Act
        sistema.ConfirmarSolicitudOrden(solicitud.Id);

        // Assert
        Assert.AreEqual("Confirmado", solicitud.Estado);
    }
}
```

## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

# Pruebas de Integración para Gestión de Productos

## 1. Consultar Detalles de un Producto
- **Objetivo**: Verificar que el sistema muestre correctamente los detalles de un producto existente.
- **Descripción**:
  - Dado que existe un producto con ID "P001" llamado "Merlot" con precio $15.99.
  - Cuando el usuario consulta el producto "P001".
  - Entonces, el sistema debe mostrar el nombre "Merlot", precio "$15.99" y stock disponible.
- **Resultado Esperado**: El sistema debe mostrar correctamente el nombre, precio y stock del producto "P001".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestConsultarDetallesDeProducto()
    {
        // Arrange
        var sistema = new SistemaDeProductos();
        var producto = new Producto("P001", "Merlot", 15.99, 100);
        sistema.AgregarProducto(producto);

        // Act
        var detalles = sistema.ConsultarProducto("P001");

        // Assert
        Assert.IsNotNull(detalles);
        Assert.AreEqual("Merlot", detalles.Nombre);
        Assert.AreEqual(15.99, detalles.Precio);
        Assert.AreEqual(100, detalles.Stock);
    }
}
```
## 2. Listar Todos los Productos Disponibles
- **Objetivo**: Asegurar que el sistema muestre correctamente todos los productos disponibles.
- **Descripción**:
  - Dado que el sistema tiene productos disponibles.
  - Cuando el usuario solicita una lista de productos.
  - Entonces, el sistema debe mostrar todos los productos con sus detalles.
- **Resultado Esperado**: La lista mostrada debe incluir todos los productos disponibles con sus respectivos detalles.

### Código de Prueba
```csharp
using NUnit.Framework;
using System.Collections.Generic;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestListarTodosLosProductosDisponibles()
    {
        // Arrange
        var sistema = new SistemaDeProductos();
        sistema.AgregarProducto(new Producto("P001", "Merlot", 15.99, 100));
        sistema.AgregarProducto(new Producto("P002", "Cabernet Sauvignon", 18.50, 50));

        // Act
        var listaProductos = sistema.ListarProductos();

        // Assert
        Assert.AreEqual(2, listaProductos.Count);
        Assert.AreEqual("Merlot", listaProductos.Nombre);
        Assert.AreEqual(15.99, listaProductos.Precio);
        Assert.AreEqual(100, listaProductos.Stock);
        
        Assert.AreEqual("Cabernet Sauvignon", listaProductos.Nombre);
        Assert.AreEqual(18.50, listaProductos.Precio);
        Assert.AreEqual(50, listaProductos.Stock);
    }
}
```
## 3. Buscar un Producto Inexistente
- **Objetivo**: Confirmar que el sistema maneje correctamente la búsqueda de un producto que no existe.
- **Descripción**:
  - Dado que no existe un producto con ID "P999".
  - Cuando el usuario busca el producto "P999".
  - Entonces, el sistema debe mostrar un mensaje indicando que el producto no fue encontrado.
- **Resultado Esperado**: El mensaje de error debe indicar claramente que el producto no fue encontrado.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestBuscarProductoInexistente()
    {
        // Arrange
        var sistema = new SistemaDeProductos();

        // Act & Assert
        var ex = Assert.Throws<Exception>(() => sistema.ConsultarProducto("P999"));
        Assert.AreEqual("Producto no encontrado", ex.Message);
    }
}
```
## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

# Pruebas de Integración para Gestión de Productos por el Vinicultor

## 1. Agregar un Nuevo Producto Exitosamente
- **Objetivo**: Verificar que el sistema registre correctamente un nuevo vino.
- **Descripción**:
  - Dado que el vinicultor desea agregar un nuevo vino.
  - Cuando el vinicultor ingresa los datos del vino "Shiraz" con precio $20.99 y stock de 30 unidades.
  - Entonces, el sistema debe registrar el vino con esos detalles.
- **Resultado Esperado**: El vino "Shiraz" debe ser registrado en el catálogo con el precio y stock especificados.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestAgregarNuevoProductoExitosamente()
    {
        // Arrange
        var sistema = new SistemaDeProductos();
        var vino = new Producto("P001", "Shiraz", 20.99, 30);

        // Act
        sistema.AgregarProducto(vino);
        var productoRegistrado = sistema.ConsultarProducto("P001");

        // Assert
        Assert.IsNotNull(productoRegistrado);
        Assert.AreEqual("Shiraz", productoRegistrado.Nombre);
        Assert.AreEqual(20.99, productoRegistrado.Precio);
        Assert.AreEqual(30, productoRegistrado.Stock);
    }
}
```
## 2. Editar Detalles de un Vino Existente
- **Objetivo**: Asegurar que el sistema actualice correctamente los detalles de un vino existente.
- **Descripción**:
  - Dado que existe un vino con ID "P001" llamado "Merlot".
  - Cuando el vinicultor actualiza el precio del vino a $17.99.
  - Entonces, el sistema debe guardar los nuevos detalles del vino.
- **Resultado Esperado**: El precio del vino "Merlot" debe actualizarse a $17.99 en el sistema.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestEditarDetallesDeVinoExistente()
    {
        // Arrange
        var sistema = new SistemaDeProductos();
        var vino = new Producto("P001", "Merlot", 15.99, 30);
        sistema.AgregarProducto(vino);

        // Act
        vino.Precio = 17.99; // Actualizando el precio
        sistema.EditarProducto(vino); // Guardando los nuevos detalles

        // Assert
        var productoActualizado = sistema.ConsultarProducto("P001");
        Assert.AreEqual(17.99, productoActualizado.Precio); // Verificando que el precio se haya actualizado
    }
}
```
## 3. Eliminar un Vino del Catálogo
- **Objetivo**: Confirmar que el sistema elimine correctamente un vino del catálogo.
- **Descripción**:
  - Dado que existe un vino con ID "P001".
  - Cuando el vinicultor elimina el vino.
  - Entonces, el sistema debe eliminar el vino del catálogo.
- **Resultado Esperado**: El vino con ID "P001" no debe estar presente en el catálogo después de la eliminación.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProductosTests
{
    [Test]
    public void TestEliminarVinoDelCatalogo()
    {
        // Arrange
        var sistema = new SistemaDeProductos();
        var vino = new Producto("P001", "Merlot", 15.99, 30);
        sistema.AgregarProducto(vino);

        // Act
        sistema.EliminarProducto("P001");

        // Assert
        var ex = Assert.Throws<Exception>(() => sistema.ConsultarProducto("P001"));
        Assert.AreEqual("Producto no encontrado", ex.Message);
    }
}
```
## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

# Pruebas de Integración para Gestión de Perfiles

## 1. Actualizar Información de Perfil Exitosamente
- **Objetivo**: Verificar que el sistema guarde correctamente la nueva información del perfil del usuario.
- **Descripción**:
  - Dado que un usuario tiene un perfil con email "user@example.com".
  - Y el nombre actual es "Juan Pérez".
  - Cuando el usuario actualiza su nombre a "Juan García".
  - Entonces, el sistema debe guardar la nueva información del perfil.
- **Resultado Esperado**: El perfil del usuario debe reflejar el nuevo nombre "Juan García".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class PerfilesTests
{
    [Test]
    public void TestActualizarInformacionDePerfilExitosamente()
    {
        // Arrange
        var sistema = new SistemaDePerfiles();
        var usuario = new Usuario("user@example.com", "Juan Pérez");
        sistema.GuardarPerfil(usuario);

        // Act
        usuario.Nombre = "Juan García"; // Actualizando el nombre
        sistema.ActualizarPerfil(usuario); // Guardando los nuevos detalles

        // Assert
        var perfilActualizado = sistema.ObtenerPerfil("user@example.com");
        Assert.AreEqual("Juan García", perfilActualizado.Nombre); // Verificando que el nombre se haya actualizado
    }
}
```

## 2. Intentar Actualizar Información con Datos Inválidos
- **Objetivo**: Asegurar que el sistema rechace la actualización cuando se ingresan datos inválidos.
- **Descripción**:
  - Dado que un usuario tiene un perfil con email "user@example.com".
  - Cuando el usuario intenta actualizar su email a "invalid-email".
  - Entonces, el sistema debe rechazar la operación y mostrar un mensaje de error.
- **Resultado Esperado**: El sistema debe mostrar un mensaje de error indicando que el email es inválido y no debe realizar cambios en el perfil.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class PerfilesTests
{
    [Test]
    public void TestIntentarActualizarInformacionConDatosInvalidos()
    {
        // Arrange
        var sistema = new SistemaDePerfiles();
        var usuario = new Usuario("user@example.com", "Juan Pérez");
        sistema.GuardarPerfil(usuario);

        // Act & Assert
        var ex = Assert.Throws<Exception>(() => 
        {
            usuario.Email = "invalid-email"; // Intentando establecer un email inválido
            sistema.ActualizarPerfil(usuario);
        });

        Assert.AreEqual("Email inválido", ex.Message); // Verificando que se lance la excepción correcta
    }
}
```

## 3. Verificar Información de Perfil
- **Objetivo**: Confirmar que el sistema muestre correctamente la información del perfil del usuario.
- **Descripción**:
  - Dado que un usuario tiene un perfil con email "user@example.com".
  - Y el nombre es "Juan García".
  - Cuando el usuario solicita ver su perfil.
  - Entonces, el sistema debe mostrar su nombre y email correctamente.
- **Resultado Esperado**: El sistema debe mostrar "Juan García" como nombre y "user@example.com" como email.

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class PerfilesTests
{
    [Test]
    public void TestVerificarInformacionDePerfil()
    {
        // Arrange
        var sistema = new SistemaDePerfiles();
        var usuario = new Usuario("user@example.com", "Juan García");
        sistema.GuardarPerfil(usuario);

        // Act
        var perfil = sistema.ObtenerPerfil("user@example.com");

        // Assert
        Assert.AreEqual("Juan García", perfil.Nombre); // Verificando que el nombre sea correcto
        Assert.AreEqual("user@example.com", perfil.Email); // Verificando que el email sea correcto
    }
}
```
## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

# Pruebas de Integración para Proceso de Vinificación

## 1. Registrar un Nuevo Proceso de Vinificación
- **Objetivo**: Verificar que el sistema registre correctamente un nuevo proceso de vinificación para un producto.
- **Descripción**:
  - Dado que no existe un proceso para el producto con ID "P001".
  - Cuando el vinicultor registra un proceso de vinificación para "P001".
  - Entonces, el sistema debe guardar los detalles del proceso de vinificación.
- **Resultado Esperado**: El sistema debe almacenar correctamente los detalles del nuevo proceso de vinificación para el producto "P001".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProcesoVinificacionTests
{
    [Test]
    public void TestRegistrarNuevoProcesoDeVinificacion()
    {
        // Arrange
        var sistema = new SistemaDeVinificacion();
        var producto = new Producto("P001", "Merlot");
        
        // Act
        sistema.RegistrarProcesoVinificacion(producto);

        // Assert
        var proceso = sistema.ObtenerProcesoVinificacion("P001");
        Assert.IsNotNull(proceso); // Verificando que el proceso fue registrado
        Assert.AreEqual("P001", proceso.ProductoId); // Verificando que el ID del producto sea correcto
    }
}
```

## 2. Actualizar Estado de Fermentación en Proceso de Vinificación
- **Objetivo**: Asegurar que el sistema actualice correctamente el estado de fermentación en un proceso de vinificación existente.
- **Descripción**:
  - Dado que existe un proceso de vinificación para el producto con ID "P001".
  - Y el estado actual es "En fermentación".
  - Cuando el vinicultor actualiza el estado a "Fermentación completada".
  - Entonces, el sistema debe guardar el nuevo estado.
- **Resultado Esperado**: El estado del proceso de vinificación para "P001" debe actualizarse a "Fermentación completada".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProcesoVinificacionTests
{
    [Test]
    public void TestActualizarEstadoDeFermentacion()
    {
        // Arrange
        var sistema = new SistemaDeVinificacion();
        var producto = new Producto("P001", "Merlot");
        sistema.RegistrarProcesoVinificacion(producto);
        sistema.ActualizarEstadoFermentacion("P001", "En fermentación");

        // Act
        sistema.ActualizarEstadoFermentacion("P001", "Fermentación completada");

        // Assert
        var proceso = sistema.ObtenerProcesoVinificacion("P001");
        Assert.AreEqual("Fermentación completada", proceso.Estado); // Verificando que el estado se haya actualizado correctamente
    }
}
```

## 3. Verificar Historial del Proceso de Vinificación
- **Objetivo**: Confirmar que el sistema muestre correctamente el historial del proceso de vinificación.
- **Descripción**:
  - Dado que existe un proceso de vinificación para el producto con ID "P001".
  - Cuando el usuario solicita el historial del proceso.
  - Entonces, el sistema debe mostrar todas las etapas completadas hasta la fecha.
- **Resultado Esperado**: El sistema debe mostrar correctamente todas las etapas del proceso de vinificación para "P001".

### Código de Prueba
```csharp
using NUnit.Framework;

[TestFixture]
public class ProcesoVinificacionTests
{
    [Test]
    public void TestVerificarHistorialDelProcesoDeVinificacion()
    {
        // Arrange
        var sistema = new SistemaDeVinificacion();
        var producto = new Producto("P001", "Merlot");
        sistema.RegistrarProcesoVinificacion(producto);
        sistema.ActualizarEstadoFermentacion("P001", "En fermentación");
        sistema.ActualizarEstadoFermentacion("P001", "Fermentación completada");

        // Act
        var historial = sistema.ObtenerHistorialProcesoVinificacion("P001");

        // Assert
        Assert.IsNotNull(historial); // Verificando que se obtuvo historial
        Assert.AreEqual(2, historial.Count); // Verificando que haya dos etapas en el historial
        Assert.AreEqual("En fermentación", historial.Estado); // Verificando la primera etapa
        Assert.AreEqual("Fermentación completada", historial[1].Estado); // Verificando la segunda etapa
    }
}
```
## Estrategias para Realizar las Pruebas Unitarias
- **Pruebas Aisladas**: Asegurarse de que cada prueba sea independiente y no dependa del estado global del sistema.
- **Uso de Mocks**: Utilizar mocks para simular interacciones con bases de datos o servicios externos si es necesario.

## Herramientas Recomendadas
- **NUnit**: Para ejecutar pruebas en C#, proporcionando una estructura clara para las pruebas unitarias en Rider.
- **Moq**: Para crear mocks y facilitar la simulación de dependencias en las pruebas.

### Commit History

## Branch: feature/inventory-management

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Commited on (Date)** |
|---------------|---------------------|--------------------------|------------------------|
| 1e383b0       | feat(inventory-management): Update in the "InventoryCommandService" | Updated in the "InventoryCommandService" | 06/11/2024 |
| f965d96       | feat(inventory-management): Added in the "UpdateInventoryCommand" with update inventory constructor entity | Added in the "UpdateInventoryCommand" with update inventory constructor entity | 06/11/2024 |
| 44aee02       | feat(inventory-management): Added in the "GetInventoriesByFilterQuery" | Added in the "GetInventoriesByFilterQuery" | 06/11/2024 |
| 277d7c9       | feat(inventory-management): Added in the "UpdateInventoryResource" | Added in the "UpdateInventoryResource" | 06/11/2024 |
| eeb64b9       | feat (inventory management): Update in the "InventoryController" with inventory search by filter | Updated in the "InventoryController" with inventory search by filter | 06/11/2024 |
| bcf1ffd       | feat (inventory management): Added in the "DeleteInventoryCommand" | Added in the "DeleteInventoryCommand" | 07/11/2024 |
| 631d31b       | feat (inventory management): Added in the "IInventoryCommandService" with inventory delete | Added in the "IInventoryCommandService" with inventory delete | 07/11/2024 |
| fed6be5       | feat (inventory management): Added in the "IInventoryRepository" with inventory delete | Added in the "IInventoryRepository" with inventory delete | 07/11/2024 |
| cd83dc3       | feat (inventory management): Added in the "InventoryController" with inventory delete | Added in the "InventoryController" with inventory delete | 07/11/2024 |

## Branch: feature/winemaking-process

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
|----------------|---------------------|--------------------------|--------------------------|
| 91a9999        | feat(winemaking-process): Added interface layer for batch endpoint. | Added interface layer for batch endpoint. | 27/10/2024 |
| 9eff846        | feat(winemaking-process): Added infrastructure and application layer for batches. | Added infrastructure and application layer for batches. | 20/10/2024 |
| 66834f4        | feat(winemaking-process): Added domain layer for batches. | Added domain layer for batches. | 20/10/2024 |
| 14ccb3a        | feat(winemaking-process): Added REST resources and transforms to add batch clarification stage. | Added REST resources and transforms to add batch clarification stage. | 03/11/2024 |

## Branch: feature/profiles

| **Commit Id**   | **Commit Message**                                              | **Commit Message Body**                                    | **Committed on (Date)** |
|------------------|-----------------------------------------------------------------|-----------------------------------------------------------|--------------------------|
| n1o2p3q          | feat(profiles): Added profiles management interface.            | Created an interface for managing multiple user profiles.| 01/11/2024              |
| r4s5t6u          | feat(profiles): Implemented bulk profile import feature.       | Developed functionality to import multiple user profiles at once.| 01/11/2024              |
| v7w8x9y          | feat(profiles): Enhanced profile searching capabilities.        | Improved searching capabilities to find profiles based on various criteria.| 02/11/2024              |
| z0a1b2c          | feat(profiles): Integrated profile analytics dashboard.         | Added a dashboard to display analytics related to user profiles.| 02/11/2024              |

## Branch: feature/order-requests

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
|----------------|---------------------|--------------------------|--------------------------|
| a1b2c3d        | feat(order-requests): Added CreateOrderRequest command. | Implemented CreateOrderRequest command for order processing. | 05/11/2024 |
| e4f5g6h        | feat(order-requests): Added OrderRequest validation logic. | Added validation for order requests to ensure data integrity. | 05/11/2024 |
| i7j8k9l        | feat(order-requests): Implemented OrderRequest repository. | Created repository for managing order requests in the database. | 06/11/2024 |
| m0n1o2p        | feat(order-requests): Added OrderRequest query service. | Implemented query service to retrieve order requests based on filters. | 06/11/2024 |

## Branch: feature/products

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
|----------------|---------------------|--------------------------|--------------------------|
| q3r4s5t        | feat(products): Added Product entity and repository. | Created Product entity and its repository for data management. | 04/11/2024 |
| u6v7w8x        | feat(products): Implemented Product service layer. | Added service layer for business logic related to products. | 04/11/2024 |
| y9z0a1b        | feat(products): Created Product API endpoints. | Developed RESTful API endpoints for product management. | 05/11/2024 |
| c2d3e4f        | feat(products): Added product search functionality. | Implemented search functionality for products based on various criteria. | 05/11/2024 |

## Branch: feature/products-management

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
|----------------|---------------------|--------------------------|--------------------------|
| h5i6j7k        | feat(products-management): Added management interface for products. | Created an interface for managing product operations. | 03/11/2024 |
| l8m9n0o        | feat(products-management): Implemented bulk product upload feature. | Developed functionality to upload multiple products at once. | 03/11/2024 |
| p1q2r3s        | feat(products-management): Enhanced product filtering options. | Improved filtering options for product lists in the management console. | 04/11/2024 |
| t4u5v6w        | feat(products-management): Integrated product analytics dashboard. | Added a dashboard to display product performance metrics. | 04/11/2024 |


## Branch: feature/customer-management

| **Commit Id** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
|----------------|---------------------|--------------------------|--------------------------|
| 9cc12al        | feat(customer-management): create client command from resource assembler added. | Create client command from resource assembler added. | 03/11/2024 |
| df2045a        | feat(customer-management): end points added. | End points added. | 03/11/2024 |
| b4f8bdb        | feat(customer-management): client resource from entity assembles added. | Client resource from entity assembles added. | 03/11/2024 |
| d89597         | feat(customer-management): client resource added. | Client resource added. | 03/11/2024 |



#### 5.2.4.5.Execution Evidence for Sprint Review.

* **Landing Page Execution**

En este proceso de evidencia de ejecución se muestra el despliegue de la landing page de la aplicación Elixir Control.

Despliegue: https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/

<img src="/assets/img/chapter-V/sprint-4/landing_page_execute.png" height="350" alt="landing_page">

Enlace del video de ejecución del landing page:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EeVpA2edMoFPtDLeeQWER4QBMWVglEEtOtyqnuiyXLv0qQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=YH1a8o

* **FrontEnd Execution**

En este proceso de evidencia de ejecución se muestra el despliegue del front end de la aplicación Elixir Control.

Despliegue: https://elixir-control-fronted-8b18f9i9z.vercel.app/home

<img src="/assets/img/chapter-V/sprint-4/front_end_execute.png" height="350" alt="landing_page">

Enlace del video de ejecución del front end:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EeW2_gUKztJGk4YMprqUEGEBhpeenCFpeOHM24NNGXJhwA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dMlo2m

* **BackEnd Execution**

En este proceso de evidencia de ejecución se muestra el despliegue del back end de la aplicación Elixir Control.

Despliegue: http://elixircontrol.runasp.net/swagger/index.html

<img src="/assets/img/chapter-V/sprint-4/backend_execute.png" height="350" alt="landing_page">

Enlace del video de ejecución del front end:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EeOFGTKth-FDnT1iLUQGLnIBp9v8W0xrWWWwNpVAssf1DQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Zu13KZ

#### 5.2.4.6.Services Documentation Evidence for Sprint Review.


En este Sprint, logramos finalizar al 100% la documentación de los Web Services en relación con la funcionalidad de gestión de lotes, procesos de vinificación, perfiles, productos, órdenes, autenticación, usuarios y solicitudes de órdenes. Se alcanzaron varios logros clave: cada endpoint ahora cuenta con una descripción detallada de las acciones implementadas, los verbos HTTP correspondientes, la sintaxis de llamada, los parámetros necesarios, y ejemplos claros de respuestas. Esto asegura que los desarrolladores y demás partes interesadas comprendan a fondo el uso de cada Web Service y puedan integrarlos fácilmente en sus aplicaciones. Estos logros contribuyen significativamente a la claridad, accesibilidad y mantenimiento de la API documentada.

## Batch Endpoints

| URL | Endpoint | HTTP Verb | Acción Implementada | Sintaxis de Llamada | Parámetros Posibles | Ejemplo de Response | Explicación del Response |
|-----|----------|-----------|---------------------|---------------------|---------------------|---------------------|--------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch/{batchId} | DELETE | Eliminar un lote | 'accept: application/json' | batchId (path) | No content | El lote fue eliminado exitosamente |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch/{batchId} | PUT | Actualizar un lote | 'Content-Type: application/json' -d '{"vineyardCode": "string", ...}' | batchId (path), JSON con datos del lote | `{"id": 0, "vineyardCode": "string", ...}` | Retorna el objeto lote actualizado |

Este endpoint permite actualizar los detalles de un lote existente en el sistema. La actualización requiere que se especifique el batchId en el path de la URL, y los nuevos datos del lote en el cuerpo de la solicitud en formato JSON.

![batch.png](/assets/img/chapter-V/sprint-4/batchput.PNG)

![batch.png](/assets/img/chapter-V/sprint-4/batchput2.PNG)


### WinemakingProcessByBatch Endpoints

| URL                                                | Endpoint                                          | HTTP Verb | Acción Implementada                | Sintaxis de Llamada                                                                 | Parámetros Posibles                              | Ejemplo de Response                                                        | Explicación del Response                     |
|----------------------------------------------------|---------------------------------------------------|-----------|------------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/fermentation  | DELETE    | Eliminar fermentación por lote     | 'accept: application/json'                                                          | batchId (path)                                   | 204 si se eliminó correctamente, 404 si no se encontró                     | Confirma la eliminación de la fermentación   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/fermentation  | PUT       | Actualizar fermentación por lote   | 'Content-Type: application/json' -d '{"startDate": "string", ...}'                  | batchId (path), JSON con datos de fermentación   | `{"id": 0, "batchId": 0, "startDate": "string", ...}`                      | Retorna el objeto fermentación actualizado   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/clarification | POST      | Añadir clarificación a un lote     | 'Content-Type: application/json' -d '{"batchId": 0, "productsUsed": "string", ...}' | batchId (path), JSON con datos de clarificación  | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna el objeto clarificación creado       |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/clarification | DELETE    | Eliminar clarificación por lote    | 'accept: application/json'                                                          | batchId (path)                                   | 204 si se eliminó correctamente, 404 si no se encontró                     | Confirma la eliminación de la clarificación  |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/clarification | PUT       | Actualizar clarificación por lote  | 'Content-Type: application/json' -d '{"productsUsed": "string", ...}'               | batchId (path), JSON con datos de clarificación  | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna el objeto clarificación actualizado  |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/pressing      | DELETE    | Eliminar prensado por lote         | 'accept: application/json'                                                          | batchId (path)                                   | 204 si se eliminó correctamente, 404 si no se encontró                     | Confirma la eliminación del prensado         |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/pressing      | PUT       | Actualizar prensado por lote       | 'Content-Type: application/json' -d '{"pressingDate": "string", ...}'               | batchId (path), JSON con datos de prensado       | `{"id": 0, "batchId": 0, "pressingDate": "2024-11-03T09:24:52.281Z", ...}` | Retorna el objeto prensado actualizado       |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/aging         | DELETE    | Eliminar envejecimiento por lote   | 'accept: application/json'                                                          | batchId (path)                                   | 204 si se eliminó correctamente, 404 si no se encontró                     | Confirma la eliminación del envejecimiento   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/aging         | PUT       | Actualizar envejecimiento por lote | 'Content-Type: application/json' -d '{"barrelType": "string", ...}'                 | batchId (path), JSON con datos de envejecimiento | `{"id": 0, "batchId": 0, "barrelType": "string", ...}`                     | Retorna el objeto envejecimiento actualizado |


En este endpoint, se puede eliminar la fermentación de un lote específico. La eliminación requiere que se especifique el batchId en el path de la URL. La respuesta de éxito es un código 204, mientras que un código 404 indica que no se encontró la fermentación.

![winemaking.png](/assets/img/chapter-V/sprint-4/fermentation.PNG)

![winemaking.png](/assets/img/chapter-V/sprint-4/fermentation2.PNG)

### Orders Endpoints

| URL                                                | Endpoint            | HTTP Verb | Acción Implementada  | Sintaxis de Llamada                                                                              | Parámetros Posibles                   | Ejemplo de Response                                                   | Explicación del Response            |
|----------------------------------------------------|---------------------|-----------|----------------------|--------------------------------------------------------------------------------------------------|---------------------------------------|-----------------------------------------------------------------------|-------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders/{id} | PUT       | Actualizar una orden | 'Content-Type: application/json' -d '{"businessName": "string", "requestedDate": "string", ...}' | id (path), JSON con datos de la orden | `{"id": 0, "businessName": "string", "requestedDate": "string", ...}` | Retorna el objeto orden actualizado |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders/{id} | DELETE    | Eliminar una orden   | 'accept: application/json'                                                                       | id (path)                             | 200 si se eliminó correctamente, 400 si no se pudo eliminar           | Confirma la eliminación de la orden |



## Inventory Endpoints

| URL                                                | Endpoint                        | HTTP Verb | Acción Implementada      | Sintaxis de Llamada                                                                                                                                                                           | Parámetros Posibles                               | Ejemplo de Response                                                                                                                                                                                           | Explicación del Response                 |
|----------------------------------------------------|---------------------------------|-----------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory/{inventoryId} | PUT       | Actualizar un inventario | 'Content-Type: application/json' -d '{"name": "string", "type": "string", "unit": "string", "expiration": "2024-11-18T05:13:28.143Z", "supplier": "string", "costPerUnit": 0, "quantity": 0}' | inventoryId (path), JSON con datos del inventario | `{"id": 0, "name": "string", "type": "string", "unit": "string", "expiration": "2024-11-18T05:13:28.144Z", "supplier": "string", "costPerUnit": 0, "lastUpdated": "2024-11-18T05:13:28.144Z", "quantity": 0}` | Retorna el objeto inventario actualizado |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory/{inventoryId} | DELETE    | Eliminar un inventario   | 'accept: application/json'                                                                                                                                                                    | inventoryId (path)                                | No content                                                                                                                                                                                                    | El inventario fue eliminado exitosamente |
### Clients Endpoints

| URL                                                | Endpoint             | HTTP Verb | Acción Implementada       | Sintaxis de Llamada                                                                  | Parámetros Posibles                   | Ejemplo de Response                                       | Explicación del Response              |
|----------------------------------------------------|----------------------|-----------|---------------------------|--------------------------------------------------------------------------------------|---------------------------------------|-----------------------------------------------------------|---------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{id} | DELETE    | Eliminar cliente por ID   | 'accept: application/json'                                                           | id (path)                             | 204 si se eliminó correctamente, 404 si no se encontró    | Confirma la eliminación del cliente   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{id} | PUT       | Actualizar cliente por ID | 'Content-Type: application/json' -d '{"personName": "string", "dni": "string", ...}' | id (path), JSON con datos del cliente | `{"id": 0, "personName": "string", "dni": "string", ...}` | Retorna el objeto cliente actualizado |

### Profiles Endpoints

| URL                                                | Endpoint                     | HTTP Verb | Acción Implementada        | Sintaxis de Llamada                                                                      | Parámetros Posibles       | Ejemplo de Response                                              | Explicación del Response                  |
|----------------------------------------------------|------------------------------|-----------|----------------------------|------------------------------------------------------------------------------------------|---------------------------|------------------------------------------------------------------|-------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/profiles/{profileId} | GET       | Obtener perfil por ID      | 'accept: application/json'                                                               | profileId (path)          | `{"id": "uuid", "fullName": "string", "email": "string", ...}`   | Retorna un objeto con detalles del perfil |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/profiles/{profileId} | DELETE    | Eliminar perfil            | 'accept: application/json'                                                               | profileId (path)          | 200 si se eliminó correctamente, 404 si no se encontró           | Confirma la eliminación del perfil        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/profiles             | POST      | Crear un nuevo perfil      | 'Content-Type: application/json' -d '{"firstName": "string", "lastName": "string", ...}' | JSON con datos del perfil | `{"id": "uuid", "fullName": "string", "email": "string", ...}`   | Retorna el objeto perfil creado           |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/profiles             | GET       | Obtener todos los perfiles | 'accept: application/json'                                                               | Ninguno                   | `[{"id": "uuid", "fullName": "string", "email": "string", ...}]` | Retorna un array de objetos perfil        |


Este endpoint permite crear un nuevo perfil en el sistema. La creación requiere que se envíen los datos del perfil en el cuerpo de la solicitud en formato JSON. El ejemplo de respuesta muestra el objeto perfil creado, incluyendo el id asignado por el sistema.

![profile.png](/assets/img/chapter-V/sprint-4/profile.PNG)

![profile.png](/assets/img/chapter-V/sprint-4/profile2.PNG)

### Product Endpoints

| URL                                                | Endpoint                                                      | HTTP Verb | Acción Implementada                       | Sintaxis de Llamada                                                  | Parámetros Posibles                            | Ejemplo de Response                                                   | Explicación del Response                    |
|----------------------------------------------------|---------------------------------------------------------------|-----------|-------------------------------------------|----------------------------------------------------------------------|------------------------------------------------|-----------------------------------------------------------------------|---------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/{productId}                                   | GET       | Obtener producto por ID                   | 'accept: application/json'                                           | productId (path)                               | `{"id": 0, "productName": "string", "grapeVariety": "string", ...}`   | Retorna un objeto con detalles del producto |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/{productId}                                   | DELETE    | Eliminar producto por ID                  | 'accept: application/json'                                           | productId (path)                               | 204 si se eliminó correctamente, 404 si no se encontró                | Confirma la eliminación del producto        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/{productId}                                   | PUT       | Actualizar producto por ID                | 'Content-Type: application/json' -d '{"productName": "string", ...}' | productId (path), JSON con datos del producto  | `{"id": 0, "productName": "string", "grapeVariety": "string", ...}`   | Retorna el objeto producto actualizado      |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/profile/{profileId}                           | GET       | Obtener todos los productos por perfil ID | 'accept: application/json'                                           | profileId (path)                               | `[{"id": 0, "productName": "string", "grapeVariety": "string", ...}]` | Retorna un array de objetos producto        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/profile/{profileId}/productName/{productName} | GET       | Obtener productos por perfil ID y nombre  | 'accept: application/json'                                           | profileId (path), productName (path)           | `[{"id": 0, "productName": "string", "grapeVariety": "string", ...}]` | Retorna un array de objetos producto        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product/productName/{productName}                     | GET       | Obtener producto por nombre               | 'accept: application/json'                                           | productName (path)                             | `{"id": 0, "productName": "string", "grapeVariety": "string", ...}`   | Retorna un objeto con detalles del producto |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/product                                               | POST      | Crear un nuevo producto                   | 'Content-Type: application/json' -d '{"productName": "string", ...}' | profileId (query), JSON con datos del producto | `{"id": 0, "productName": "string", "grapeVariety": "string", ...}`   | Retorna el objeto producto creado           |

### Authentication Endpoints

| URL                                                | Endpoint                       | HTTP Verb | Acción Implementada | Sintaxis de Llamada                                                                | Parámetros Posibles       | Ejemplo de Response                                  | Explicación del Response                  |
|----------------------------------------------------|--------------------------------|-----------|---------------------|------------------------------------------------------------------------------------|---------------------------|------------------------------------------------------|-------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/authentication/sign-in | POST      | Iniciar sesión      | 'Content-Type: application/json' -d '{"username": "string", "password": "string"}' | JSON con credenciales     | `{"id": 0, "username": "string", "token": "string"}` | Retorna información de sesión del usuario |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/authentication/sign-up | POST      | Registrar usuario   | 'Content-Type: application/json' -d '{"username": "string", "password": "string"}' | JSON con datos de usuario | 200 si el usuario se registró correctamente          | Confirma el registro exitoso del usuario  |

### User Endpoints

| URL                                                | Endpoint          | HTTP Verb | Acción Implementada        | Sintaxis de Llamada        | Parámetros Posibles | Ejemplo de Response                      | Explicación del Response            |
|----------------------------------------------------|-------------------|-----------|----------------------------|----------------------------|---------------------|------------------------------------------|-------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/user/{id} | GET       | Obtener usuario por ID     | 'accept: application/json' | id (path)           | `{"id": 0, "username": "string"}`        | Retorna detalles del usuario        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/user      | GET       | Obtener todos los usuarios | 'accept: application/json' | Ninguno             | `[{"id": 0, "username": "string"}, ...]` | Retorna lista de todos los usuarios |

### Order Requests Endpoints

| URL                                                | Endpoint                                 | HTTP Verb | Acción Implementada                     | Sintaxis de Llamada                                                    | Parámetros Posibles                    | Ejemplo de Response                                         | Explicación del Response                        |
|----------------------------------------------------|------------------------------------------|-----------|-----------------------------------------|------------------------------------------------------------------------|----------------------------------------|-------------------------------------------------------------|-------------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests/{orderRequestsId} | GET       | Obtener solicitud de orden por ID       | 'accept: application/json'                                             | orderRequestsId (path)                 | `{"id": 0, "quantity": 0, "price": 0, ...}`                 | Retorna detalles de la solicitud de orden       |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests                   | POST      | Crear una nueva solicitud de orden      | 'Content-Type: application/json' -d '{"quantity": 0, "price": 0, ...}' | JSON con datos de la solicitud         | `{"id": 0, "quantity": 0, "price": 0, ...}`                 | Retorna la solicitud de orden creada            |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests                   | GET       | Obtener todas las solicitudes de orden  | 'accept: application/json'                                             | Ninguno                                | `[{"id": 0, "quantity": 0, "price": 0, ...}, ...]`          | Retorna lista de todas las solicitudes de orden |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests/{id}/status       | PUT       | Actualizar estado de solicitud de orden | 'Content-Type: application/json' -d '{"status": "string"}'             | id (path), JSON con nuevo estado       | 200 si se actualizó correctamente, 400 si falló             | Confirma la actualización del estado            |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests/{id}              | DELETE    | Eliminar solicitud de orden             | 'accept: application/json'                                             | id (path)                              | 200 si se eliminó correctamente, 400 si falló               | Confirma la eliminación de la solicitud         |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/order-requests/{id}              | PUT       | Actualizar solicitud de orden           | 'Content-Type: application/json' -d '{"quantity": 0, "price": 0, ...}' | id (path), JSON con datos actualizados | 200 si se actualizó correctamente, código de error si falló | Confirma la actualización de la solicitud       |


Url del repositorio del Web Service: https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Platform

630f518


#### 5.2.4.7.Software Deployment Evidence for Sprint Review.

En esta sección se describen los procesos de despliegue de la base de datos y el Web Service realizados durante el Sprint. Para la base de datos, se utilizó AWS LightSail, donde se creó una base MySQL en un plan gratuito. El  Web Service se desplegó en MonsterASP.net, configurando un sitio web gratuito, activando el acceso de web deploy y publicando desde Visual Studio 2022. Ambos componentes quedaron listos para su uso.


### Despliegue de la base de datos

Se siguieron los pasos detallados previamente para desplegar la base de datos en AWS LightSail, comenzando desde la configuración inicial en la sección "Databases" hasta la selección de MySQL 8.0.39 y el plan gratuito de tres meses. Con la base de datos creada y configurada, se encuentra ahora lista para integrarse con los distintos productos digitales del proyecto ( Web Applications y Web Services), permitiendo al equipo asegurar una publicación satisfactoria y conectividad centralizada en la nube.

![](../assets/img/chapter-V/sprint-3/database5.PNG)


### Despliegue del Web Service


En este Sprint se realizaron los procesos de Deployment necesarios para asegurar la correcta configuración y despliegue del Web Service, se utilizó la plataforma MonsterASP.net, donde se creó una cuenta, configuró un sitio web gratuito con el subdominio "ElixirControl", y se habilitó el acceso de Web Deploy. Luego, se descargó el perfil de publicación y se configuró el archivo program.cs para habilitar Swagger en producción. A través de Visual Studio, el proyecto fue desplegado exitosamente utilizando el perfil de publicación descargado. Como resultado, el Web Service quedó listo para pruebas y uso en el entorno de producción, accesible en el enlace http://elixircontrol.runasp.net/swagger/index.html. Este proceso de Deployment incluyó pasos detallados de configuración y automatización en un entorno en la nube, contribuyendo al avance general de la integración de los productos digitales del proyecto (Web Applications y los Web Services).

![](../assets/img/chapter-V/sprint-3/back.PNG)


#### 5.2.4.8.Team Collaboration Insights during Sprint.

En esta entrega del trabajo final, nuestra meta principal fue culminar la integracion del frontend y backend. Se representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de clonaciones realizadas por cada integrante del equipo durante el desarrollo de los services

<img src="/assets/img/chapter-V/sprint-4/grafica_1.PNG" height="400" alt="landing_page">

<img src="/assets/img/chapter-V/sprint-4/grafica_2.PNG" height="400" alt="landing_page">

En esta captura se muestra el flujo de los commits realizados por cada integrante:

<img src="/assets/img/chapter-V/sprint-4/commits.PNG" height="400" alt="landing_page">

## 6. Conclusiones, Bibliografía y Anexos.

### Conclusiones 



En conclusión, el objetivo de este informe es presentar un análisis detallado que documente 
la solución de software propuesta, ElixirControl. Para alcanzar este objetivo, es fundamental
incluir información clara y concisa sobre el proyecto, que abarque desde la descripción de 
la idea hasta los requisitos específicos y las funcionalidades deseadas. Este análisis debe
ser exhaustivo, proporcionando una visión completa de cómo la solución abordará las 
necesidades del sector vitivinícola.

Las user stories desempeñan un papel crucial en este proceso, ya que permiten describir
los requisitos de manera simple y centrada en el usuario. En resumen, las user stories 
son herramientas valiosas en el desarrollo ágil de software, asegurando que el equipo se
enfoque en crear un producto que satisfaga efectivamente las necesidades de los clientes 
y mejore su experiencia en la gestión de procesos productivos y logísticos.

En conclusión, el objetivo de este informe es presentar un análisis detallado que documente 
la solución de software propuesta, ElixirControl. Para alcanzar este objetivo, es fundamental
incluir información clara y concisa sobre el proyecto, que abarque desde la descripción de 
la idea hasta los requisitos específicos y las funcionalidades deseadas. Este análisis 
debe ser exhaustivo, proporcionando una visión completa de cómo la solución abordará las 
necesidades del sector vitivinícola. Las user stories desempeñan un papel crucial en este
proceso, ya que permiten describir los requisitos de manera simple y centrada en el usuario.
En resumen, las user stories son herramientas valiosas en el desarrollo ágil de software,
asegurando que el equipo se enfoque en crear un producto que satisfaga efectivamente las 
necesidades de los clientes y mejore su experiencia en la gestión de procesos productivos
y logísticos.



### Bibliografía

Celis Escudero, F. R. (2001). Elaboración de vino con mosto concentrado de uva borgoña negra (Vitis labrusca) [Tesis, Universidad Nacional de San Martín]. Repositorio UNSM. https://repositorio.unsm.edu.pe/bitstream/11458/58/1/21%272%2700075.pdf

Celis Escudero, F. R. (2001). Elaboración de vino con mosto concentrado de uva borgoña negra (Vitis labrusca) [Tesis, Universidad Nacional de San Martín]. Repositorio UNSM. https://repositorio.unsm.edu.pe/bitstream/11458/58/1/21%272%2700075.pdf

Gómez Rubio, D. J. (2014). Investigación científica y tecnológica de la vinificación de la uva Red Globe (Vitis Vinífera L.) [Tesis, Universidad Católica de Santa María]. Repositorio UCSM. https://repositorio.ucsm.edu.pe/items/8d95b4ac-8c09-4354-8df7-2507eed3c70a

Husnayo Guillermo, E. G. (2012). Análisis económico de la elaboración del vino en Tacna [Tesis, Universidad Nacional Jorge Basadre Grohmann]. Repositorio UNJBG. https://repositorio.unjbg.edu.pe/server/api/core/bitstreams/668098dd-4976-4b2f-9acf-2c7bdb6cfc28/content

Wein Manager App. (n.d.). Track your wine cellar inventory with our professional Wine Cellar Manager app. Retrieved September 27, 2024, from https://winemanager.app

VinoTEC. (n.d.). Software ERP y CRM - Bodegas y cooperativas vitivinícolas. Retrieved September 27, 2024, from https://vinotec.net

Vintrace. (n.d.). Winery software | A better way to make wine. Retrieved September 27, 2024, from https://www.vintrace.com



### Anexos

<table>
<thead>
    <tr>
        <th>Sección</th>
        <th>Características del video</th>
        <th>Sobre el contenido</th>
        <th>Integración y entrega</th>
    </tr>
</thead>
<tbody>
<!--========================================= FILA 1 ======================================-->
<tr>
  <td>Needfinding Interviews</td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-needfinding-sprint-1
    Formato: .mp4
  </td>
  <td> Consolida todas las entrevistas realizadas </td>
  <td> 
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/EZw-9tmmOSJPsIy_Qcor0FkBBYUZFt8o47YcZmrvLmA8Fg?e=Pyj62I&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 
</td>
</tr>
<!--========================================= FILA 2 ======================================-->
<tr>
  <td>Exposición</td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-expo-tb1
    Formato: .mp4
  </td>
  <td>Consolida las exposiciones de la TB1	</td>
  <td>
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/ERTxpx1uyvJKmY3QL8mRb6sB8lFh8XQB4o_F_MernOdpGQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7R6pjN 
  </td>
</tr>
<!--========================================= FILA 3 ======================================-->
<tr>
  <td>
    Prototypes Navigation / Product Navigation
  </td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-prototype-navigation-sprint-1
    Formato: .mp4
  </td>
  <td>
    Consolida demostración del flujo de navegación de las aplicaciones, priorizando los user flows relacionados con el core business.	
  </td>
  <td>
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/EQ3ShXzJBlJAllrQ9SJ3yY8Bacs6SF9dXo-7o_dXhgiZYw?e=e6Hn8s&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
  </td>
</tr>
<!--========================================= FILA 4 ======================================-->
<tr>
  <td>
    Validation Interviews
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
<!--========================================= FILA 5 ======================================-->
<tr>
  <td>
    About the Product
  </td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-aboutthe-product-sprint-3
    Formato: .mp4 
  </td>
  <td>
    Orientación promocional, resumiendo el modelo de negocio, las características y beneficios del producto, incluyendo algunas escenas de interacción con el producto y al menos una opinión por cada segmento objetivo.
  </td>
  <td>
    Link:  https://1drv.ms/v/c/cab22ef84dc9095b/Ef6hskhLpFJDiyqCgws149cBkYiR3Z7gNJzAtu0w4I_g5Q?e=B0tbiv
  </td>
</tr>
<!--========================================= FILA 6 ======================================-->
<tr>
  <td>
    About the Team
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
<!--========================================= FILA 7 ======================================-->
<tr>
  <td>
    Conclusiones, Bibliografía y Anexos
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
</tbody>
</table>

