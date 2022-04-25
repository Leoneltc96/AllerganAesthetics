# AllerganAesthetics - Versiones/Desarrollo


```sh
Versión 1.0.0 [25-Marzo-2022] [Leonel_Torres]
```

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `assets\js\funciones.js` | `18-21` |  |
| `assets\js\funciones.js` | `662-687` |  |
| `controllers\setStatus.php` | `0` | **Nuevo archivo** |
| `controllers\observadorUsuarios.php` | `0` | **Nuevo archivo** |
| `controllers\guardaEstadisticas.php` | `49/55/105` | Modificamos para que cierre sesion y se registre en la tabla / agregamos este SET para corregir el timestamo 0 |
| `controllers\login.php` | `47-59` | Modificamos para registrar cuando cierra sesion en la tabla |



```sh
Versión 1.1.0 [28-Marzo-2022] [Orlando_Carranza]
```
`Cambios para cierre de sesion despues de 30 min cuando se cierra la pestaña`

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `controllers\login.php` | `37-38` | Creamos una cookie #3 para guardar el usuario firmado y el timestamp del timeLogin |
| `controllers\actualizaCookie.php` | `0` | **Nuevo archivo** |
| `controllers\guardaEstadisticas.php` | `11-15` | Actualizacion de codigo para que funcione en produccion y locales |
| `assets\js\funciones.js` | `690-701` | Hacemos la solicitud al controlador para actualizar la cookie con el timestamp actual |
| `aprendizaje\aprendizaje.php` | `6-20/285` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |
| `materiales\botox.php` | `6-20/312` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |
| `materiales\juvederm.php` | `6-20/376` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |
| `materiales\salaEspera.php` | `6-20/255` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |
| `Galeria\galerias.php` | `6-20/468` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |
| `allerganAesthetics.php` | `8-22/827` | Validamos que exista una cookie si es mayor a 1800s cerramos sesion y pedimos credenciales |



```sh
Versión 1.2.0 [29-Marzo-2022] [Orlando_Carranza]
```
`Cambios para mostrar botonera de redes sociales en el menu desplegable (en celulares)`

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `assets\js\funciones.js` | `59-61/90-92` | Agregamos una propiedad en el estilo lineal para alinear los elementos en una sola fila |
| `assets\css\style.css` | `2088-2092` | Comentamos para que la botonera sea visible en el menu desplegable |



```sh
Version 1.3.0 [29-Marzo-2022] [Liliana Alvarado]
```
`Cambios de texto en la Base de datos`

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `manager_home_carrusel` | `0` | Se modifico el texto de la base de datos del ID #2, en el campo slide_title_03, se modificaron las tablas de AllerganPro y AllerganPro/desarrollo |



```sh
Version 1.4.0 [30-Marzo-2022] [Liliana Alvarado]
```
`Cambios de materiales de Botox a Juvederm`

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `manager_materiales_botox` | `0` | Se eliminaron los materiales que se pasaron a Juvederm, se modificaron las tablas de AllerganPro y AllerganPro/desarrollo |
| `manager_materiales_juviderm` | `0` | Se agregaron 3 materiales que se pasaron a Juvederm desde Botox, los materiales se llaman 'Materiales JUVÉDERM® - Realce belleza 1, Materiales JUVÉDERM® - Realce belleza 2, Materiales JUVÉDERM® - Realce belleza 3' se modificaron las tablas de AllerganPro y AllerganPro/desarrollo |

```sh
Versión 1.0.0 [22-Abril-2022] [Leonel_Torres]
```

| Archivos Modificados | Lineas Modificadas     | Description                |
| :-------- | :------- | :------------------------- |
| `controllers/actualizarPass.php` | `28` | Se agrego una linea de codigo, el cual permite guardar el nuevo pass en el campo password_original de la tabla en BD |









