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

