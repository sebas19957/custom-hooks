# useForm

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }
    const [values, handleInputChange, reset] = useForm(initialForm);
```

```
Ejemplo
     <div className="col-5">
        <form onSubmit={ handleSearch }>
            <input 
                type="text"
                placeholder="Find your pokémon"
                className="form-control"
                name="searchText" //Debe tener el mimo nombre el estado inicial
                autoComplete="off"
                value={ searchText }
                onChange={ handleInputChange } funcion del hook state
            />

            <button
                type="submit"
                className="btn mt-2 btn-block btn-outline-primary"
            >
                Search...
            </button>
        </form>
    </div>
                
    const [ formValues, handleInputChange, reset ] = useForm({
        searchText: '' //mismo nombre del name en el input
    });
```

Devuelve un arreglo 
