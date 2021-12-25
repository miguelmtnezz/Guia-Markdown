# Listas  
A diferencia de lo que ocurre con HTML, generar listas en Markdown es totalmente sencillo. Nos encontramos dos tipos de listas:

## Listas desordenadas
Para crear listas desordenadas utilizamos  `*` asteriscos, `-` guiones, o `+` simbolos de suma.

### Codigo  
```
- Elemento 1  
- Elemento 2
+ Elemento 3
+ Elemento 4
* Elemento 5
* Elemento 6
```

### Resultado  
- Elemento 1  
- Elemento 2
+ Elemento 3
+ Elemento 4
* Elemento 5
* Elemento 6

Para la creacion de listas adinadas dentro de otras, simplemente tenemos que insertar una tabulacion antes del siguiente `*`, `-` o `+`.   

### Codigo  
```
- Elemento 1  
- Elemento 2
    - Elemento 3
    - Elemento 4
        - Elemento 5
        - Elemento 6
```

### Resultado  
- Elemento 1  
- Elemento 2
    - Elemento 3
    - Elemento 4
        - Elemento 5
        - Elemento 6


## Listas ordenadas
Para crear las listas ordenadas haremos uso de sintaxix numérica `1.`. Al igual que ocurre con las listas desordenadas, tambien pueden ser anidadas o combinarlas.  

### Código
```
1. Elemento 1  
2. Elemento 2
    - Elemento 3
    - Elemento 4
        1. Elemento 5
        2. Elemento 6
```

### Resultado  
1. Elemento 1  
2. Elemento 2
    - Elemento 3
    - Elemento 4
        1. Elemento 5
        2. Elemento 6