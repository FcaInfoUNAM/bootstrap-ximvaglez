[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22784449)
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/bilopNxu)
# Bootstrap básico

Este repositorio tiene como objetivo reflexionar, repasar y comprender el uso de las clases en documentos HTML.

Escribe en un archivo de texto llamado entregable.txt las respuestas a las preguntas del laboratrorio

## Paso1

Clona el repositorio en tu local

1. Visualiza el navbar en el navegador
2. Agrega una clase "bg-dark" a la etiqueta nav de la linea 9
```html
<nav class="navbar bg-dark">
```
3. Modifica agregando una nueva clase "navbar-dark"
```html
<nav class="navbar navbar-dark bg-dark">
```
4. Explica en entregable.txt qué es lo que hace bg-dark y escribe el color hexadecimal del fondo del navbar
5. cambia el tamaño d ela imagen del nav a 40  

## Paso2

1. Responde en entregable.txt ¿qué es lo que permite que en el formulario la contraseña esté oculta?
2. Agrega un nuevo input de tipo pasword que diga repeat password en su leable y cambiale el nombre y los id a "passwordRepeat"
```html
<div class="mb-3">
    <label for="passwordRepeat" class="form-label">Repeat reppassword</label>
    <input type="passwordRepeat" class="form-control" id="passwordRepeat">
</div>
```
3. Agrega inputs para nombre de usuario, telefono, y un select para tipo de usuario (alumno, profesor, empleado)
```html
<div class="mb-3">
    <label for="userName" class="form-label">Usuario</label>
    <input type="text" class="form-control" id="userName" placeholder="elBarto666">
</div>
<div class="mb-3">
    <label for="phone" class="form-label">Phone</label>
    <input type="tel" class="form-control" id="phone" placeholder="5510101010">
</div>
<div class="mb-3">
    <label for="password" class="form-label">Password</label>
    <input type="password" class="form-control" id="password">
</div>
<div class="mb-3">
    <label for="userType" class="form-label">User Type</label>
    <select class="form-select" aria-label="Tipo_de_usuario" id="userType">
        <option selected disabled>Seleccioanr</option>
        <option value="1">Alumno</option>
        <option value="2">Profesor</option>
        <option value="3">Epleado</option>
    </select>
</div>
```
## Paso3

1. Commenta la imagen del card
2. Agrega un mensaje al usuario para indicarle que tiene que llenar los datos para registrarse
3. Cambia el texto del boton a "Sing Up"


## Paso4

1. Cambia el fonto del sito a la imagen que se comentó
2. Pon transparencia al card del formulario
3. Cambia el color del botón para que coincida con el navbar

## Paso5
1. Responde las siguientes preguntas
¿Dónde deberías agregar CSS en el documento si modificas el estilo de algúna clase?
¿Bootstrap incorpora algún mecanismo para realizar los cambios del paso 4?
¿Cómo cambiarias el fondo por un video?
## Paso6
1. Guarda los cambios
2. Agrega los cambios a tu repositorio junto al archivo entregable.txt
``` git add entreganle.txt ```
``` git add inbdex.html ```
3. Haz una rama llamada entregable
``` git branch entregable ```
4. Cambiate a la rama recién creada
``` git checkout entregable ```
5. Realza un push sobre la rama
``` git commit -m "entregable" ```
``` git push origin entregable ```
6. solicita un pullrequest en github