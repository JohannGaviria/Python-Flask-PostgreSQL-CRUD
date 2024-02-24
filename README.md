# Python-Flask-PostgreSQL-CRUD

Este repositorio contiene un CRUD (Crear, Leer, Actualizar, Eliminar) de usuarios desarrollado con Python, Flask, PostgreSQL y JavaScript. La aplicación permite la gestión completa de usuarios, incluyendo la creación, visualización, actualización y eliminación de registros de usuarios en una base de datos PostgreSQL.


Perfecto, ahora vamos a detallar cómo podrías abordar el punto dos, que es la instalación. Aquí tienes un ejemplo de cómo podrías estructurar esa sección en tu README:

---

## Instalación

A continuación se detallan los pasos para instalar y configurar este proyecto en tu entorno local.

### Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

- Python (versión 3.12.2)
- PostgreSQL (versión 16)
- pip (administrador de paquetes de Python)

### Pasos de Instalación

1. **Clonar el repositorio:**

   ```
   git clone https://github.com/JohannGaviria/Python-Flask-PostgreSQL-CRUD.git
   ```

2. **Crear el entorno virtual:**

   Utiliza `virtualenv` o otro gestor de entornos virtuales
   ```
   pip install virtualenv
   python -m virtualenv nombre_del_entorno
   ```

3. **Instalar las dependencias:**

   ```
   cd tu_proyecto
   pip install -r requirements.txt
   ```

4. **Configurar la base de datos:**

   - Crea una base de datos PostgreSQL en tu entorno.
   - Crea un archivo `.env` en la ruta raiz de tu proyecto y crea las variables de entorno con los datos correpodientes.

5. **Ejecutar el servidor:**

   ```
   python .\app.py
   ```

¡Listo! El proyecto ahora debería estar en funcionamiento en tu entorno local. Puedes acceder a él desde tu navegador web visitando `http://localhost:5000`.

---

Excelente, sigamos con el siguiente punto, que es el uso del proyecto. Aquí te muestro cómo podrías abordarlo en tu README:

---

## Uso

A continuación se detallan las instrucciones sobre cómo utilizar este proyecto una vez que esté instalado y en funcionamiento en tu entorno local.

### Ejecución del Servidor

Para ejecutar el servidor de Flask, simplemente ejecuta el siguiente comando en tu terminal dentro del directorio del proyecto:

```
python .\app.py
```

El servidor se iniciará y estará disponible en `http://localhost:5000`.

### Interacción con la Aplicación

Este proyecto proporciona una interfaz de usuario para gestionar usuarios, permitiendo realizar las siguientes acciones:

1. **Agregar un Usuario:**
   - Completa el formulario con el nombre de usuario, correo electrónico y contraseña.
   - Haz clic en el botón "Agregar Usuario" para guardar los datos en la base de datos.
   - Los nuevos usuarios se mostrarán automáticamente debajo del formulario.

2. **Editar un Usuario:**
   - Para editar un usuario existente, haz clic en el botón "Editar" junto a sus datos.
   - Los campos del formulario se llenarán automáticamente con los datos del usuario seleccionado.
   - Realiza los cambios necesarios y haz clic en el botón "Actualizar" para guardar los cambios en la base de datos.

3. **Eliminar un Usuario:**
   - Para eliminar un usuario, haz clic en el botón "Eliminar" junto a sus datos.
   - El usuario seleccionado será eliminado de la base de datos y desaparecerá de la lista.

### Interfaz

![Interfaz de Usuario](https://github.com/JohannGaviria/Python-Flask-PostgreSQL-CRUD/blob/main/static/img/Interfaz_Usuario.png)

### Detener el Servidor

Para detener el servidor Flask, simplemente presiona `Ctrl + C` en tu terminal. Esto detendrá la ejecución del servidor y liberará el puerto `5000`.

---

Por supuesto, aquí está la actualización para incluir Cryptography como parte de las tecnologías utilizadas en tu proyecto:

---

## Tecnologías Utilizadas

El proyecto está desarrollado utilizando las siguientes tecnologías y herramientas:

- **Python**: Lenguaje de programación utilizado para el desarrollo del backend de la aplicación.
- **Flask**: Framework web de Python utilizado para construir la aplicación web.
- **PostgreSQL**: Sistema de gestión de bases de datos relacional utilizado para almacenar los datos de usuario.
- **psycopg2**: Adaptador de base de datos PostgreSQL para Python, utilizado para conectarse y realizar operaciones en la base de datos desde la aplicación Flask.
- **dotenv**: Módulo utilizado para cargar variables de entorno desde un archivo `.env`, lo que facilita la configuración de la aplicación en diferentes entornos.
- **Cryptography**: Biblioteca de Python utilizada para cifrar y descifrar contraseñas almacenadas en la base de datos, proporcionando seguridad adicional a los datos sensibles de los usuarios.
- HTML: Lenguajes de marcado para definir la estructura de las páginas web.
- **Bootswatch**: Temas de Bootstrap personalizados utilizados para estilizar la interfaz de usuario de la aplicación web.
- **JavaScript**: Lenguaje de programación utilizado para agregar interactividad a la interfaz de usuario y consumir una API para mostrar datos dinámicamente.

Estas tecnologías se combinan para crear una aplicación web funcional y robusta que permite a los usuarios registrar, editar y eliminar información de usuario, así como también mostrar datos dinámicamente utilizando JavaScript para consumir la API.

---
