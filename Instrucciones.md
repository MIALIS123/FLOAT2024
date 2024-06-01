# Tarea: Crear una Página Web con Bootstrap

## Crear un nuevo repositorio en GitHub llamado `tarea-bootstrap`.

### Página Home.html

1. Crea un archivo `Home.html` en el repositorio.

### Incluir Bootstrap

2. Añade Bootstrap a tu proyecto utilizando un CDN o descargándolo localmente.

### Estructura de la Página

3. Dentro de `Home.html`, crea un `div` con la clase `container`.
4. Dentro de este `div`, añade otro `div` con la clase `jumbotron`.

### Comandos Flex

5. Dentro del `div` con clase `jumbotron`, crea un encabezado `h3` con la clase `display-3` y el texto `Comandos Flex`.
6. Debajo del encabezado, añade una lista con los comandos de Flexbox en CSS. Puedes consultar los comandos en el enlace proporcionado.

### Comandos Grid

7. Crea otro encabezado `h3` con la clase `display-3` y el texto `Comandos Grid`.
8. Debajo del encabezado, añade una lista con los comandos de Grid en CSS. Puedes consultar los comandos en el enlace proporcionado.

### Enlace a Propiedades CSS

9. Asegúrate de utilizar el siguiente   archivo PDF con las propiedades de Flex y Grid CSS para completar tu tarea:

```html
<a href="Assets/Propiedades CSS Flex y Grid.pdf">enlace con los comandos </a>
```
### Ejemplo 
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <div class="jumbotron">
            <h3 class="display-3">Comandos Flex</h3>
            <p>Lista con los comandos de Flex CSS:</p>
            <!-- Añade aquí la lista de comandos Flex -->
            
            <h3 class="display-3">Comandos Grid</h3>
            <p>Lista con los comandos de Grid CSS:</p>
            <!-- Añade aquí la lista de comandos Grid -->
            
            <a href="Assets/Propiedades CSS Flex y Grid.pdf">Enlace con los comandos</a>
        </div>
    </div>
</body>
</html>
```
