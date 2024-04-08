# Aprendiendo GIT: My Links APP

## 1. Introducción

Proyecto simple que permite a cada usuario crear sus propios enlaces, los cuales pueden ser visualizados por cualquier persona que tenga el link de acceso.

## 2. Objetivos

- Crear un proyecto simple que permita a los usuarios crear sus propios enlaces.
- Permitir a los usuarios compartir sus enlaces con otras personas.

## 3. Requisitos

Tenemos que tener instaladas las siguientes herramientas:

Herramienta | Enlace de descarga
------------ | -------------
Git | [Descargar](https://git-scm.com/)
Visual Studio Code | [Descargar](https://code.visualstudio.com/)

### 3.1. Instalación de Git

Para instalar Git, debemos seguir los siguientes pasos:

Ingresamos a la página oficial de Git: [Git](https://git-scm.com/)

![alt text](img/guide/image-0.png)

Luego hacemos clic en el botón "Download" para descargar el instalador de Git.

![alt text](img/guide/image-1.png)

Una vez descargado el instalador, lo ejecutamos y hacemos clic en el botón "Ejecutar".

![alt text](img/guide/image-2.png)

Aceptar los términos de la licencia y hacer clic en el botón "Siguiente".

![alt text](img/guide/image-3.png)

Seleccionar la ubicación de instalación y hacer clic en el botón "Siguiente".

![alt text](img/guide/image-4.png)

Seleccionamos siguiente y esperamos a que termine la instalación.

![alt text](img/guide/image-5.png)

Una vez finalizada la instalación, hacemos clic en el botón "Finalizar".

![alt text](img/guide/image-7.png)

> **Nota:** Debemos tener una cuenta en GitHub para poder clonar el repositorio para eso nos dirigimos a [GitHub](https://github.com) y creamos una cuenta.

#### Crear una cuenta en GitHub

Ingresamos a la página oficial de GitHub: [GitHub](https://github.com)

![alt text](img/guide/image-8.png)

Ingresamos nuestro nombre de usuario, correo electrónico y contraseña. Luego hacemos clic en el botón "Sign up for GitHub".

![alt text](img/guide/image-9.png)

### 3.2. Configuración de Git

Después de instalar Git, debemos configurar nuestro nombre de usuario y correo electrónico. Para ello, abrimos la consola de Git y ejecutamos los siguientes comandos:

```bash
git config --global user.name "tu nombre"
git config --global user.email "tu correo"
```

Primero hacemos click derecho en el escritorio y seleccionamos la opción "Git Bash Here".

![alt text](img/guide/image-10.png)

Luego ejecutamos los comandos en la consola de Git.

```bash
git config --global user.name "Omar Vite"
git config --global user.email "omar******@uni.pe"
```

![alt text](img/guide/image-11.png)

Para verificar que la configuración se haya realizado correctamente, ejecutamos el siguiente comando:

```bash
git config --list
```

![alt text](img/guide/image-12.png)

### 3.3. Instalación de Visual Studio Code

Para instalar Visual Studio Code, debemos seguir los siguientes pasos:

Ingresamos a la página oficial de Visual Studio Code: [Visual Studio Code](https://code.visualstudio.com/) y hacemos clic en el botón del sitema operativo que estemos utilizando en este caso Windows.

![alt text](img/guide/image-13.png)

Descargamos el instalador de Visual Studio Code.

![alt text](img/guide/image-14.png)

Una vez descargado el instalador, lo ejecutamos haciendo doble clic y hacemos clic en el botón "Ejecutar".

![alt text](img/guide/image-15.png)

Aceptamos los términos de la licencia y hacemos clic en el botón "Siguiente".

![alt text](img/guide/image-16.png)

Seleccionamos la ubicación de instalación y hacemos clic en el botón "Siguiente".

![alt text](img/guide/image-17.png)

Seleccionamos el path de inicio y hacemos clic en el botón "Siguiente".

![alt text](img/guide/image-18.png)

Finalizamos la instalación haciendo clic en el botón "Finalizar".

![alt text](img/guide/image-19.png)

### 3.4. Configuración de Visual Studio Code

Después de instalar Visual Studio Code, debemos instalar las siguientes extensiones:

Extensión | Descripción
------------ | -------------
Live Server | Permite visualizar los cambios en tiempo real en el navegador.
Prettier | Formatea el código automáticamente.

Para instalar las extensiones, debemos abrir Visual Studio Code y buscar la extensión en la barra lateral izquierda.

![alt text](img/guide/image-6.png)

Luego escribimos liver server en la barra de búsqueda y hacemos clic en el botón "Install".

![alt text](img/guide/image-21.png)

![alt text](img/guide/image-22.png)

De igual forma, podemos instalar la extensión de Prettier.

![alt text](img/guide/image-23.png)

![alt text](img/guide/image-24.png)

## 4. Crear un fork del repositorio

Para poder trabajar en el proyecto, debemos crear un fork del repositorio. Para ello, debemos seguir los siguientes pasos:

Ingresamos al repositorio del proyecto: [My Links - IEEE CS UNI](https://github.com/jhonnatan1806/my-links-ieee-cs-uni) y hacemos clic en el botón "Fork" que se encuentra en la parte superior derecha de la pantalla.

![alt text](img/guide/image-25.png)

Luego el nombre de nuestro repositorio y le damos en el botón "Create fork".

![alt text](img/guide/image-26.png)

Verificamos que se haya creado nuestro repositorio.

![alt text](img/guide/image-27.png)

## 5. Clonar el repositorio

Copiamos la URL de nuestro repositorio.

![alt text](img/guide/image-28.png)

Abriremos la consola de Git y nos ubicaremos en la carpeta donde queremos clonar el repositorio.

![alt text](img/guide/image-29.png)

Clonamos el repositorio en nuestra máquina local. Para ello, abrimos la consola de Git y ejecutamos el siguiente comando:

```bash
  git clone <url de nuestro repo>
```

![alt text](img/guide/image-30.png)

Nos ubicamos en la carpeta del proyecto:

```bash
cd my-links-ieee-cs-uni
```

![alt text](img/guide/image-31.png)

## 6. Crear un branch

Para crear una rama, debemos ejecutar el siguiente comando:

```bash
git branch feature/<nombre-apellido>
```

![alt text](img/guide/image-32.png)

Para cambiar de rama, debemos ejecutar el siguiente comando:

```bash
git checkout feature/<nombre-apellido>
```

![alt text](img/guide/image-33.png)

---

## 7. Actividad: Personalizar mi perfil

Primero debemos ingresar al proyecto para ello debemos ejecutar el siguiente comando:

```bash
code .
```

![alt text](img/guide/image-34.png)

Si es la primera vez que utilizamos el directorio nos aparecera una ventana para aceptar que es un directorio de trabajo seguro.

![alt text](img/guide/image-35.png)

Luego debemos enceder el servidor de Live Server para ello debemos hacer clic en el botón "Go Live" que se encuentra en la parte inferior derecha de la pantalla.

![alt text](img/guide/image-36.png)

La primera vez nos pedira que permitamos el acceso a la red privada.

![alt text](img/guide/image-37.png)

Ahora podremos visualizar nuestro proyecto en el navegador.

![alt text](img/guide/image-38.png)

### 7.1. Crear un archivo HTML

Para crear un archivo podemos usar la siguiente forma `nombre_apellido.html` en la carpeta principal del proyecto.

![alt text](img/guide/image-39.png)

![alt text](img/guide/image-40.png)

> **Nota:** Puedes utilizar el archivo `jane_doe.html` como referencia.

### 7.2. Estructura para subir archivos

Si necesitas agregar archivos puedes hacerlos en la carpeta `files` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-41.png)

```html
<a href="files/jane_doe.cv.pdf" download>Descargar CV</a>
```

### 7.3. Estructura para subir imagenes

Si necesitas agregar imagenes puedes hacerlos en la carpeta `img` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-42.png)

```html
<img src="img/jane_doe.profile.jpg" alt="Imagen de perfil de Jane Doe">
```

### 7.4. Estructura para subir estilos

Si necesitas agregar estilos puedes hacerlos en la carpeta `css` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-43.png)

```html
<!-- Los estilos deben estar en el head del archivo HTML -->
<link rel="stylesheet" href="css/jane_doe.styles.css">
```

![alt text](img/guide/image-44.png)

### 7.5. Subir los cambios al repositorio remoto

Para subir los cambios a nuestro repositorio remoto, primero revisaremos el estado de nuestro repositorio con el siguiente comando:

```bash
git status
```

![alt text](img/guide/image-45.png)

Luego agregamos los cambios con el siguiente comando:

```bash
git add .
```

![alt text](img/guide/image-46.png)

luego verificamos que los cambios se hayan agregado correctamente.

```bash
git status
```

![alt text](img/guide/image-54.png)

Ahora haremos un commit con el siguiente comando:

```bash
git commit -m "feat: Agregado archivo <nombre-apellido>.html"
```

![alt text](img/guide/image-47.png)

Por último subimos los cambios a nuestro repositorio remoto con el siguiente comando:

```bash
git push origin feature/<nombre-apellido>
```

![alt text](img/guide/image-48.png)

Si es la primera vez que subimos los cambios nos pedira que iniciemos sesión en GitHub.

![alt text](img/guide/image-49.png)

Luego de iniciar sesión podremos ver que los cambios se subieron correctamente.

![alt text](img/guide/image-50.png)

### 7.6. Crear un Pull Request

Nos dirigimos a nuestro repositorio en GitHub y hacemos clic en el botón "Compare & pull request".

![alt text](img/guide/image-51.png)

Escribimos un mensaje y hacemos clic en el botón "Create pull request".

![alt text](img/guide/image-52.png)

Una vez creada nuestra pull request, esperaremos a que sea revisada y aprobada por el administrador del proyecto.

![alt text](img/guide/image-53.png)
