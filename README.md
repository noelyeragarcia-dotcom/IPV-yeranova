# IPV Control de Inventario

Aplicación web sencilla para llevar el inventario diario con el formato IPV. Es una plantilla para cualquier negocio y funciona en tablets, teléfonos y computadoras, sin instalar nada.

## Fórmulas

- Venta = Inicio + Entrada
- Vendido = Venta − Final
- Importe = Vendido × Precio
- Total = suma de todos los Importes

El Final de un día pasa solo como Inicio del día siguiente.

## Cómo empezar

1. Escriba el nombre de su negocio en el campo **Negocio**, arriba. Se guarda solo.
2. En **Productos**, añada su lista una sola vez: nombre, existencia inicial y precio. También puede pegar la lista, un producto por línea.
3. En **Día**, escriba el dependiente, la Entrada y el Final de cada producto. Lo demás se calcula.
4. **Resumen** muestra el total de cada día.

## En la tablet

Abra la página en Chrome (Android) o Safari (iPad) y use **Añadir a pantalla de inicio**.

## Importante sobre los datos

Los datos se guardan solo en el navegador de cada dispositivo. No se suben a ningún servidor. Si borra los datos del navegador, se pierden. Use la pestaña **Respaldo** para copiar una copia de seguridad y guárdela en un mensaje o nota.

## Publicación

Es un sitio estático (un solo `index.html`). En GitHub: Settings > Pages > Deploy from a branch > `main` > `/ (root)`.
