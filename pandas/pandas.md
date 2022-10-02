# Pandas

### Arrays

-  1D Arrays : Series
-  2D Arrays : Dataframes

En pandas principalmente se trabaja con dataframes

##### ¿Que es un dataframe?
Un dataframe es lo que en excel es una hoja de cálculo, tiene dos dimensiones, filas y columnas

| | States | Population | Postal | <- Features o caracteristicas|
|---|---|---|---|---|
|0| California | 989166| CA | Filas/ROw |
|1| Texas | 1135 | CA | Filas/ROw |
|2| Florida | 11941 | CA | Filas/ROw |
|3| New York | 49191 | CA | Filas/ROw |
| Index | Series | Series | Series |
| ^ Observaciones|

- El indice o Index por defecto comienzan desde cero.
- La intersección entre una fila y una columna es un dato
- Se pueden almacenar diferentes tipos de datos
- Procura no mezclar diferentes tipos de datos en una misma columna

### Pandas Terminología
| Excel | Pandas |
|---|---|
| Worksheet | Dataframe |
| Column | Series |
| Row heading | Index |
| Row | Row |
| Empty cell | Nan |

### Como crear un dataframe: Arrays

##### Con Numpy Array

    np.array([1,5],[5,6],[6,8])

##### List Arrays

    data = [[1,35],[3,6],[7,2]]

#### Con diccionarios

    my_dict = {'key':value1,'key2':value2}

#### Archivo CSV
    Leer un archivo csv

### Atributos
Valor asociado con un objeto ( referenciado por un nombre usando el punto ".")

    df.columns

### Funcion
Grupo de sentencias relacionadas que hacen una tarea específica. 
    
    Por ejemplo:
    -   max()
    -   min()
    .   len()

### Métodos

Una funcion que es definida dentro del cuerpo de una clase.
    
    df.head()