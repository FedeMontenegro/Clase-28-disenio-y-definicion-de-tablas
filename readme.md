## Notas

- La carpeta 'DER' contiene el Diagrama Entidad Relación de la base de datos.

- La carpeta 'script' contiene el script de la base de datos 'tp_notes_db' y la subcarpeta 'tables', la cual se describe en el ítem siguiente.

- En la carpeta 'tables' están almacenados los scripts de cada tabla que fué creada en Mockaroo, y cada script contiene, a su vez, la sentencia de creación de tablas y de inserción de registros, a excepción de 'notes_categories', el cual solo contiene las sentencias de inserción de datos.

- Tabla 'history_notes': Contiene registros sobre creación, modificación y eliminación de notas. Incluye las columnas id, type(debería recibir registros del tipo 'nuevo', 'modificado', 'eliminado'), date(almacena la fecha de cada registro) y notes_id (clave foránea para la unión con la tabla 'notes'). La intención de esta tabla es guardar un historial de la actividad que desarrollan los usuarios al interactuar con el sitio web.

- Los registros que contiene cada tabla fueron creados en Mockaroo, por lo que podrían tener algunas inconsistencias.