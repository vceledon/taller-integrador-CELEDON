| #  | Problema                                                                                                | Solución                                                             |
| -- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| 1  | <title>pagina</title> no describe la página.                                                          | Cambiar a `<title>Calculadora de Promedio</title>`.                  |
| 2  | Archivos con espacios y extensiones en mayúsculas (`Estilos Del Sitio.CSS`, `Mi Pagina De Notas.HTML`). | Renombrar en minúsculas y sin espacios: `estilos.css`, `index.html`. |
| 3  | Variables `a`, `b`, `c` poco descriptivas.                                                              | Renombrar a `nota1`, `nota2`, `nota3`.                               |
| 4  | `x = 3` es un número mágico y poco claro.                                                               | Renombrar a `cantidadNotas`.                                         |
| 5  | `TempValue2` no describe su contenido y rompe el estilo de nombres.                                     | Renombrar a `promedio` usando camelCase.                             |
| 6  | `data1 = []` nunca se utiliza.                                                                          | Eliminar la variable.                                                |
| 7  | Existe código comentado (`calcularAntiguo`).                                                            | Eliminar el bloque comentado.                                        |
| 8  | Hay `console.log` usados para depuración.                                                               | Eliminarlos en la versión final.                                     |
| 9  | IDs `r` y `r2` no son descriptivos.                                                                     | Renombrar a `resultadoPromedio` y `resultadoEstado`.                 |
| 10 | Clase `.cont1` poco descriptiva.                                                                        | Renombrar a `.contenedor` o `.tarjeta`.                              |
| 11 | `TempValue2` y `x` son variables globales innecesarias.                                                 | Declararlas con `let` dentro de `calc()`.                            |
