# useForm hook 


Ejemplo de uso:
```
    const initialForm: {
        nombre:'',
        edad:0,
        email:''
    }

    const [values, handleInputChange, reset] = useForm(initialForm);

```