TALENT TECH
Sistema de Inventario en Python con SQLite
Descripción:
Es un sencillo sistema de inventario utilizando una base de datos SQLite.
Permite registrar, consultar, actualizar y eliminar productos, 
así como generar reportes de productos con bajo stock.
Se ulitizo Python como lenguaje de programacion.

Funcionalidades:

Creación de base de datos y tabla: 
Al ejecutar el script por primera vez, se crea automáticamente una base de datos SQLite 
llamada inventario.db y una tabla productos para almacenar la información de los productos.

Registro de productos: Permite agregar nuevos productos al inventario, 
solicitando al usuario el nombre, descripción, cantidad, precio y categoría.

Consulta de productos: Muestra una lista completa de todos los productos 
registrados en el inventario, incluyendo su ID, nombre, descripción, cantidad, precio y categoría.

Actualización de cantidad: Permite modificar la cantidad de un producto existente en el inventario.
Eliminación de productos: Permite eliminar un producto del inventario, identificándolo por su ID.

Búsqueda de productos: Permite buscar un producto específico por su ID y muestra sus detalles.
Reporte de bajo stock: Genera un reporte de todos los productos cuya cantidad está por debajo de un límite establecido por el usuario.
Cómo utilizar:

Ejecutar el script: Ejecuta el script de Python desde tu terminal o entorno de desarrollo.
Interactuar con el menú: El script presentará un menú interactivo que te permitirá seleccionar las diferentes opciones disponibles.
Seguir las instrucciones: Sigue las instrucciones en pantalla para realizar las operaciones deseadas.

Estructura del código:
conectar_db(): Función para establecer la conexión a la base de datos SQLite.
crear_tabla(): Función para crear la tabla productos si no existe.
registrar_producto(): Función para agregar un nuevo producto al inventario.
mostrar_productos(): Función para mostrar todos los productos.
actualizar_cantidad(): Función para actualizar la cantidad de un producto.
eliminar_producto(): Función para eliminar un producto.
buscar_producto(): Función para buscar un producto por ID.
reporte_bajo_stock(): Función para generar un reporte de productos con bajo stock.
menu(): Función principal que muestra el menú y gestiona las opciones del usuario.
Requisitos:

Python
Módulo sqlite3 (viene incluido en la instalación estándar de Python)
ELB
