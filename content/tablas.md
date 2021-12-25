# Tablas
En mi opnion personal la generación de tablas con Markdown ha sido lo mas dificultoso durante este proyecto.

La primera parte sera especificar los elementos de la cabecera de cada columna, han de ser encerrados entre barras verticales `|`.  
```
| Primera columna | Segunda Columna | Tercera columna |
```

Las filas de contenido se crean exactamente igual que la linea de cabecera, pero Markdown es capaz de diferenciarlo gracias a la sintaxis que se muestra a continuacion:  
```
| Cabecera  |
|    --     |
| Contenido |
```

Y si todo esto lo aplicamos junto obtendriamos un resultado como el siguiente:

| Primera columna | Segunda columna | Tercera columna |
|       --        |       --        |        --       |
| Contenido 1-1   | Contenido 1-2   | Contenido 1-3   |
| Contenido 2-1   | Contenido 2-2   | Contenido 2-3   |
| Contenido 3-1   | Contenido 3-2   | Contenido 3-3   |