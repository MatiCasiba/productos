* Nombre: Matias Casiba
* Link Github Repo:
* Link Netlify:

# Página Productos

## Colocando titulo, subtitulos, textos y nombres de las imágenes
Para ir armando esta página, voy a estar usando de momento los siguientes elementos
```sh
<h1> Titulo </h1>
<h2> Subtitulos </h2>
<img src="acá-va-imagen" alt="nombre de la imagen"> # acá llamaré a las imágenes.
<p> Texto <p>
```

## Color de fondo y letras
Al momento de darle color al fondo lo haré de la siguiente manera en css:
```sh
body{
    background-color: rgb(52, 62, 85); # nuestro color de fondo
    color: white; # es el color de la letra en textos
}
```

### Color de letra y fondo para el título
El elemento h1 tendrá un color aparte tanto en su fondo como en la letra, lo hago de esta forma:
```sh
h1{
    background-color: white; # su color de fondo
    text-align: center;
    color: rgb(93, 110, 148); # su color de letra
}
```
* Nota: para centrar el título utilizo el text-align: center;

### Color a los elementos h2
Cáda elemento h2 tendrá un color distino, para lograr esto, en cada elemento h2 del archivo index.html, le agrego una clase con distinos valores, estos son:
```sh
<h2 class="color-1">Aspiradoras</h2>
<h2 class="color-2">Celulares</h2>
<h2 class="color-3">Consolas</h2>
<h2 class="color-4">Home theaters</h2>
<h2 class="color-5">Televisores</h2>
```
Esto me permitirá en css darles color a cada uno:
```sh
.color-1{
    color: bisque;

}
.color-2{
    color: rgb(127, 145, 177);
}
.color-3{
    color: rgb(200, 212, 212);
}
.color-4{
    color: rgb(162, 157, 157);
}
.color-5{
    color: rgb(239, 229, 216);
}
```

