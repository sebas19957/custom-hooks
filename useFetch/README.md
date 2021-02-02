# useFetch

Ejemplo:
```
    const url = 'endpoint de una api'
    const {data: null, loading: true, error: null} = useFetch(url);
```
data -> inicialmente esta en null pero cuando se ejecuta exitosamente devuelve la data correspondiente de la api 

loading -> inicialmente esta en true, cuando se optienen la data de la api sea un caso de exito o de error su valor cambia a false

error -> Si al ejecuatarse el hook ocurre un error devolvera un mensaje de con contrario su valor sigue siendo null