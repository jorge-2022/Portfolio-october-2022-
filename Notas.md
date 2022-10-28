## Observaciones Iniciales

- Recomendación: usar nombres más estándar hace más fácil la lectura del código, por ejemplo para directorios:
```
    |- assets
        |----img
            |----pic.jpg
    |- index.html
    |- style.css
```
En cualquier caso, el nombre no afecta salvo para hacer las rutas más sencillas.

* También, cuando hay varias hojas de estilo se pueden nombrar según las secciones que estilan... `navbar.css`, `footer.css`, etc.
* La hoja de estilos principal suele ser `main.css`, `styles.css` o `style.css` (mas habituales).

## Cambios Sugeridos

- Usar [grid](https://www.w3schools.com/css/css_grid.asp) o [flexbox](https://www.w3schools.com/css/css3_flexbox.asp) para hacer responsive la sección de libros
- Usar pocos media queries (solo cuando sea necesario)
- Añadir padding al `body` y/o `container`
- Colocar `footer` y las demás secciones con contenido dummy o `lorem` para ver la idea más visualmente

## Trabajo Futuro

- Añadir [Bootstrap](https://www.w3schools.com/bootstrap5/index.php) para contenido responsive?
- Crear más páginas?
- Hacer páginas de cada libro? Del autor? Etc.