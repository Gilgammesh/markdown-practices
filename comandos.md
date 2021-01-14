# h1

## h2

### h3

#### h4

##### h5

###### h6

normal text

### Citas

> Esto es una cita y su contenido

### Listas

* Head1
    * head2
        * test1
        * test2
    * head3
* Head2

+ Head1
    + head2
        + test1
        + test2
    + head3
+ Head2

- Head1
    - head2
        - test1
        - test2
    - head3
- Head2

### Listas anidadas

1. algo1
2. algo2
    1. subalgo21
    2. subalgo22
        1. asdad
        2. asdad
3. asdad

### Otro ejemplo de lista

1. list1
1. list2
1. list3
1. list4
1. list5

## Tablas simples

| col1 | col2 | col3 |
|------|------|------|
| uno  | 2    | 4    |
| dos  | 5    | 6    |

## Tablas con tabulación

| columna izquierda | columna centrada | columna derecha |
|:------------------|:----------------:|----------------:|
| Carlos Enrique | 25 | 1,500.00 |
| Santander Ruiz | 34 | 4,300.50 |
| Materiales | 10 | 600.20 |

## Código de Javascript

```javascript
    function handleInputChange(evt) {
        var pepe = "algo";
        const { name, value } = evt.target;
        setForm({
            ...form,
            [name]: value
        })
        console.log("se actualizó el formulario");
    }
```

## Código de html

```html
    <div>
        <table>
            <thead>
                <th>col1</th>
                <th>col2</th>
                <th>col3</th>
            </thead>
            <tbody>
                <tr></tr>
            </tbody>
            <tfoot></tfoot>
        </table>
    </div>
```

## Código en palabras

El ejemplo `<br>` está demostrado.

Otro ejemplo `<input type="text" name="user">` demostrado.

## Insertar imágenes

![imagen de usuario](https://www.adslzone.net/app/uploads-adslzone.net/2019/06/aper-1.jpg)

![imagen de usuario](https://www.adslzone.net/app/uploads-adslzone.net/2019/06/aper-1.jpg "comentario de la imagen")

[img1]: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPZ1vQCo9x8P85l48CahiMmidonLicITQlQQ&usqp=CAU

[img2]: https://i.blogs.es/aa76de/libro/450_1000.jpg

![][img1] ![][img2]

## Caracteres de escape

\# no ejecuta encabezado

\> no ejecuta cita

\+ no ejecuta listas

\* no ejecuta listas

## Link

[visita mi blog](https://www.javiercordero.com/)
