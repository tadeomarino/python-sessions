# Sesión 1/2

# Configuración del entorno de desarrollo Python en Windows

Como primer paso, vamos a ver cómo configurar un entorno de desarrollo Python en Visual Studio Code y cómo ejecutar código Python en la consola, específicamente para usuarios de Windows.

## Roadmap
1. Instalación de Visual Studio Code en Windows
2. Instalación de Python
3. Instalación de la extensión Python para Visual Studio Code
4. Creación de carpeta y archivo .py en Visual Studio Code
5. Ejecución de código Python en la consola de Visual Studio Code

## Instalación de Visual Studio Code en Windows

Visual Studio Code es un editor de código fuente desarrollado por Microsoft que recomendamos y vamos a estar utilizando en estas sesiónes para desarrollar automatizaciones que necesitemos en nuestro día a día. Se puede descargar desde la página oficial de [Visual Studio Code](https://code.visualstudio.com/download) o desde Microsoft Store buscando 'Visual Studio Code'.

## Instalación de Python

Python, nuestro lenguaje de programación de alto nivel de elección para este curso, se puede descargar desde la página oficial de [Python](https://www.python.org/) o desde Microsofr Store buscando 'Python'. Recomendamos instalar la ultima versión o en su defecto una de las últimas.

Para verificar si Python está correctamente instalado en tu sistema y conocer su versión, puedes seguir estos pasos:

- Abre una nueva terminal.
- Escribe el siguiente comando y presiona Enter: 'python --version' o 'python3 --version'

Este comando debería mostrar la versión de Python que tienes instalada. Por ejemplo, podría aparecer algo como 'Python 3.8.5'.

## Instalación de la extensión Python para Visual Studio Code

La extensión de Python para Visual Studio Code es proporcionada por Microsoft. Esta extensión ofrece un soporte completo para el lenguaje Python y viene con una variedad de características:

- **IntelliSense (Pylance)**: Proporciona autocompletado de código y ayuda a entender el código más rápidamente, ofreciendo sugerencias de código y mostrando información útil sobre las funciones y los módulos mientras escribes.
- **Linting**: Ayuda a detectar errores y problemas de estilo en tu código.
- **Debugging (Python Debugger)**: Te permite ejecutar tu código paso a paso, inspeccionar variables y evaluar expresiones en tiempo real.
- **Code Navigation:** Facilita la navegación a través del código, permitiéndote saltar a la definición de una variable o función.
- **Code Formatting**: Formatea automáticamente tu código de acuerdo a las guías de estilo de Python.
- **Refactoring**: Te ayuda a reestructurar tu código sin cambiar su comportamiento.

- Paso a paso:

1. **Abre la pestaña de Extensiones**: Haciendo clic en el icono de Extensiones en la barra lateral izquierda (el icono parece como un bloque con una onda en el medio).
2. **Busca la extensión de Python**: En el cuadro de búsqueda en la parte superior de la pestaña de Extensiones, escribe “Python”. Esto te mostrará una lista de todas las extensiones relacionadas con Python.
3. **Selecciona la extensión de Python proporcionada por Microsoft**: Deberías ver una extensión llamada simplemente “Python”, y el proveedor debe ser Microsoft. Esta es la extensión que vamos a instalar.
4. ***Instala la extensión**: Haz clic en el botón “Instalar” que se encuentra en la tarjeta de la extensión de Python. Esto iniciará el proceso de instalación.
5. **Espera a que se complete la instalación**: La instalación puede tardar unos momentos. Una vez que se complete, el botón “Instalar” se cambiará a “Desinstalar”, lo que indica que la extensión se ha instalado correctamente.

## Creación de carpeta y archivo .py en Visual Studio Code

Una vez que ya tengamos todo instalado vamos a crear nuestra carpeta del proyecto para posteriormente crear nuestro primer archivo.py.

1. En la barra lateral izquierda, en la parte superior nos dirigimos al 'Explorer'.
2. Seleccionamos la acción 'Abrir carpeta' y abrimos la carpeta del proyecto.
3. Dentro de la carpeta, buscámos el icono de 'Nuevo archivo' para crear nuestro archivo.
4. Nombramos el nuevo archivo 'main.py'

Como resultado deberíamos tener abierto nuestro archivo.py dentro de la carpeta seleccionada previamente.

## Ejecución de código Python en la consola de Visual Studio Code

Para ejecutar nuestro archivo.py que contiene nuestro código primero tenemos que escribir una línea de código para poder ver el output por consola. Paso a detallar los pasos:

1. Dentro del 'archivo.py' escribimos la siguiente linea: 'print("Hola mundo!")'
2. Guardamos los cambios con el comando: command + s
3. Abrimos una nueva terminal desde el menu superior, buscando 'Terminal' > 'Nueva terminal'
4. Escribimos el siguiente comando para ejecutar el archvio: 'python archivo.py'

A continuación deberíamos visualizar por consola el mensaje 'Hola mundo!'. Para ejecutar un archivo de python por consola necesitamos hacer uso de la palabra reservada 'python' seguido del nombre del archivo con su extensión, en este caso fue 'archivo.py'