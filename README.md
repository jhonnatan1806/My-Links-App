# My Links

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

![alt text](img/guide/image-0.png)

![alt text](img/guide/image-1.png)

![alt text](img/guide/image-2.png)

![alt text](img/guide/image-3.png)

![alt text](img/guide/image-4.png)

![alt text](img/guide/image-5.png)

![alt text](img/guide/image-7.png)

> **Nota:** Debemos tener una cuenta en GitHub para poder clonar el repositorio para eso nos dirigimos a [GitHub](https://github.com) y creamos una cuenta.

![alt text](img/guide/image-8.png)

![alt text](img/guide/image-9.png)

### 3.2. Configuración de Git

Después de instalar Git, debemos configurar nuestro nombre de usuario y correo electrónico. Para ello, abrimos la consola de Git y ejecutamos los siguientes comandos:

```bash
git config --global user.name "tu nombre"
git config --global user.email "tu correo"
```

![alt text](img/guide/image-10.png)

![alt text](img/guide/image-11.png)

![alt text](img/guide/image-12.png)

### 3.3. Instalación de Visual Studio Code

![alt text](img/guide/image-13.png)

![alt text](img/guide/image-14.png)

![alt text](img/guide/image-15.png)

![alt text](img/guide/image-16.png)

![alt text](img/guide/image-17.png)

![alt text](img/guide/image-18.png)

![alt text](img/guide/image-19.png)

### 3.4. Configuración de Visual Studio Code

Después de instalar Visual Studio Code, debemos instalar las siguientes extensiones:

Extensión | Descripción
------------ | -------------
Live Server | Permite visualizar los cambios en tiempo real en el navegador.
Prettier | Formatea el código automáticamente.

Para instalar las extensiones, debemos abrir Visual Studio Code y buscar la extensión en la barra lateral izquierda.

![alt text](img/guide/image-21.png)

![alt text](img/guide/image-22.png)

![alt text](img/guide/image-23.png)

![alt text](img/guide/image-24.png)

## 4. Clonar el repositorio

Para poder trabajar en el proyecto, debemos crear un fork del repositorio. Para ello, debemos seguir los siguientes pasos:

Ingresamos al repositorio del proyecto: [My Links](https://github.com/jhonnatan1806/my-links-ieee-cs-uni) y hacemos clic en el botón "Fork" que se encuentra en la parte superior derecha de la pantalla.

![alt text](img/guide/image-25.png)

![alt text](img/guide/image-26.png)

![alt text](img/guide/image-27.png)

Clonamos el repositorio en nuestra máquina local. Para ello, abrimos la consola de Git y ejecutamos el siguiente comando:

```bash
  git clone <url de nuestro repo>
```

Nos ubicamos en la carpeta del proyecto:

```bash
cd my-links
```

![alt text](img/guide/image-28.png)

![alt text](img/guide/image-29.png)

![alt text](img/guide/image-30.png)

![alt text](img/guide/image-31.png)

## 5. Crear una rama

Para crear una rama, debemos ejecutar el siguiente comando:

```bash
git branch feature/<nombre-apellido>
```

Para cambiar de rama, debemos ejecutar el siguiente comando:

```bash
git checkout feature/<nombre-apellido>
```

![alt text](img/guide/image-32.png)

![alt text](img/guide/image-33.png)

---

## 6. Actividad: Personalizar mi perfil

Primero debemos ingresar al proyecto para ello debemos ejecutar el siguiente comando:

```bash
code .
```

![alt text](img/guide/image-34.png)

![alt text](img/guide/image-35.png)

Luego debemos enceder el servidor de Live Server para ello debemos hacer clic en el botón "Go Live" que se encuentra en la parte inferior derecha de la pantalla.

![alt text](img/guide/image-36.png)

![alt text](img/guide/image-37.png)

![alt text](img/guide/image-38.png)

### 6.1. Crear un archivo HTML

Para crear un archivo podemos usar la siguiente forma `nombre_apellido.html` en la carpeta principal del proyecto.

![alt text](img/guide/image-39.png)

![alt text](img/guide/image-40.png)

> **Nota:** Puedes utilizar el archivo `jane_doe.html` como referencia.

#### Estructura para subir archivos

Si necesitas agregar archivos puedes hacerlos en la carpeta `files` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-41.png)

```html
<a href="files/jane_doe.cv.pdf" download>Descargar CV</a>
```

#### Estructura para subir imagenes

Si necesitas agregar imagenes puedes hacerlos en la carpeta `img` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-42.png)

```html
<img src="img/jane_doe.profile.jpg" alt="Imagen de perfil de Jane Doe">
```

#### Estructura para subir estilos

Si necesitas agregar estilos puedes hacerlos en la carpeta `css` con el formato `<nombre>.<tipo>.<extension>` y referenciarlas en tu archivo HTML.

![alt text](img/guide/image-43.png)

```html
<!-- Los estilos deben estar en el head del archivo HTML -->
<link rel="stylesheet" href="css/jane_doe.styles.css">
```

![alt text](img/guide/image-44.png)

### 6.2. Subir los cambios al repositorio remoto

Para subir los cambios a nuestro repositorio remoto, debemos ejecutar los siguientes comandos:

```bash
git add .
git commit -m "feat: Agregado archivo <nombre-apellido>.html"
git push origin feature/<nombre-apellido>
```

![alt text](img/guide/image-45.png)

![alt text](img/guide/image-6.png)

![alt text](img/guide/image-47.png)

![alt text](img/guide/image-48.png)

![alt text](img/guide/image-49.png)

![alt text](img/guide/image-50.png)

### 6.3. Crear un Pull Request

Ahora entraremos a nuestro repositorio en GitHub y haremos clic en el botón "Compare & pull request". Luego, escribiremos un mensaje y haremos clic en el botón "Create pull request".

![alt text](img/guide/image-51.png)

![alt text](img/guide/image-52.png)

![alt text](img/guide/image-53.png)
