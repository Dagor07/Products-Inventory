# 🐍 Sistema de Gestión de Inventario en Python
Este proyecto implementa un sistema básico de gestión de inventario para una tienda utilizando Python. El sistema permite al usuario agregar productos, buscarlos, actualizar precios, eliminarlos y calcular el valor total del inventario.

## Funcionalidades del sistema
### 1. Agregar productos
El sistema solicita al usuario:
Nombre del producto
Precio del producto (debe ser un número positivo)
Cantidad (debe ser un número entero positivo)

![alt text](image.png)

Si los datos son válidos, el producto se guarda en una lista llamada Inventary.


### 2. Buscar productos
Permite buscar un producto por su nombre.Si el producto existe en el inventario, se muestra su nombre, precio y cantidad.

### 3. Actualizar el precio de un producto
Permite actualizar el precio y la cantidad de un producto existente en el inventario.
Si el producto se encuentra y el nuevo precio y cantidad es válido, el cambio se realiza correctamente.

### 4. Eliminar un producto
Permite eliminar un producto del inventario a partir de su nombre.
Si la cantidad del producto es 0, se elimina de la lista.

### 5. Mostrar el valor total del inventario
Calcula el valor total de todos los productos en el inventario multiplicando el precio por la cantidad de cada uno.
El resultado es la suma de todos los valores individuales.

### 6. Salir del sistema
Finaliza la ejecución del programa.

Instrucciones de uso
Ejecuta el archivo Python desde la terminal.

Se mostrará un menú con las opciones del sistema.

Elige una opción ingresando el número correspondiente (del 1 al 6).

Sigue las instrucciones en pantalla para cada acción.

### Consideraciones adicionales
El precio debe ser un número mayor que cero.

La cantidad debe ser un número entero mayor a cero.

La lista global Inventary es donde se almacenan todos los productos.
