# 📸 Álbum de Fotos
----------------------------------------------------------------------------
Bienvenido a mi álbum personal. Aquí voy guardando una foto por día.

## 📂 Contenido del Álbum
- 📑 **Consultas SQL** → Scripts usados en el proyecto.  
- 🖼️ **Evidencias visuales** → Capturas de resultados (screenshots).  
- 🗂️ **Base de datos** → Archivos `.sql` y documentación relacionada.
 
----------------------------------------------------------------------------
![Imagen1](Imagen1.png)

![Imagen2](Imagen2.png)

![Imagen3](Imagen3.png)

![Imagen4](Imagen4.png)

![Imagen5](Imagen5.png)

![Imagen6](Imagen6.png)

![Imagen7](Imagen7.png)

![Imagen8](Imagen8.png)

![Imagen9](Imagen9.png)    

![Imagen10](Imagen10.png)    

![Imagen11](Imagen11.png)    

![Imagen12](Imagen12.png)

...
...
...
...
...
...
SEMANA 6
...
...
...
...
...
...
...

![Imagen13](Imagen13.png)

![Imagen14](Imagen14.png)

![Imagen15](Imagen15.png)

![Imagen16](Imagen16.png)

![Imagen17](Imagen17.png)

![Imagen18](Imagen18.png)

![Imagen19](Imagen19.png)

![Imagen20](Imagen20.png)

-- Esta consulta devuelve la lista de empleados con su respectivo departamento.
-- Se usa RIGHT JOIN para asegurar que aparezcan todos los empleados,
-- incluso aquellos que no tengan un departamento asignado (en ese caso, el campo Departamento será NULL).
-- La relación se hace a través de la tabla EmployeeDepartmentHistory.

![Imagen21](Imagen21.png)

-- FULL JOIN devuelve todas las filas de ambas tablas:
-- coincidencias, más los registros que no tienen pareja en la otra tabla.

![Imagen22](Imagen22.png)

-- CROSS JOIN genera el producto cartesiano:
-- combina cada empleado con cada departamento,
-- sin importar si realmente trabaja allí.

...
...
...
...
...
...
SEMANA 7
...
...
...
...
...
...
...

![Imagen23](Imagen23.png)

![Imagen24](Imagen24.png)

![Imagen25](Imagen25.png)

![Imagen26](Imagen26.png)
...
...
...
...
...
...
...
SEMANA 8
...
...
...
...
...
...   
![Imagen27](Imagen27.png)

-- Este procedimiento usa una transacción para actualizar el estado de un pedido 
-- en la tabla Sales.SalesOrderHeader de AdventureWorks2022. 
-- Si todo sale bien hace COMMIT; si ocurre un error hace ROLLBACK y lanza la excepción.

![Imagen28](Imagen28.png)

-- Este procedimiento almacenado llamado dbo.BuscarPersonasPorApellido
-- recibe un parámetro de entrada llamado @Apellido (de tipo NVARCHAR(50)).
-- Al ejecutarlo, realiza una consulta a la tabla Person.Person de la base de datos AdventureWorks2022,
-- buscando todas las personas cuyo apellido coincida exactamente con el valor pasado en @Apellido.
-- La consulta devuelve el BusinessEntityID, FirstName y LastName de las personas que cumplen con ese criterio.
-- Finalmente, se muestra un ejemplo de ejecución del procedimiento para buscar todas las personas con apellido 'Smith'.
-- La última consulta (SELECT * FROM Person.Person) es para mostrar todos los registros de la tabla Person.Person.

![Imagen29](Imagen29.png)

----------------------------------------------------------------------------
