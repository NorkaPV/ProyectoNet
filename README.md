# ProyectoNet Usuario
**Herramientas de Uso:**

- Sql Server 2022
- Visual Studio 2022

#### 1.  Base de datos 
Se debe restaurar la base de datos **ProyectoUsuario.bak** en SQL Server

#### 2.  Visual Studio 2022
Abrir el proyecto **SolucionNetCore** en el  Visual Studio 2022, luego no dirigimos **appsettings.json** que se encuentra dentro de  la Capa de Presentación para realizar la conexión de Base de datos. Ver la siguiente imagen.
![](https://github.com/NorkaPV/ProyectoNet/blob/main/Imagen.png)

Una vez realizado la conexión de BD, ejecutaremos el proyecto lo cual mostrará la **lista de usuarios creados**
![](https://github.com/NorkaPV/ProyectoNet/blob/main/ListaUsuario.png)

Para realizar la creación de un nuevo Usuario, dar click en `CrearNuevo`

![](https://github.com/NorkaPV/ProyectoNet/blob/main/BotonCreaar%20Usuario.png)

Ingresar todos los datos necesarios, luego click en **Create**. Para verificar la creación de un usuario nuevo click en`Regresar`, donde nos dirigirá  a la pantalla principal.

Además, para ver la información detallada de un Usuario click en `Detalle`
![](https://github.com/NorkaPV/ProyectoNet/blob/main/Detalle.png)

Finalmente, en caso que se desea eliminar un usurio click en **Eliminar**, antes de eliminar  habrá una nota *Estas seguro que deseas eliminar este regristro?*, de ser confirmado click en `Eliminar` 

![](https://github.com/NorkaPV/ProyectoNet/blob/main/Eliminar.png)


