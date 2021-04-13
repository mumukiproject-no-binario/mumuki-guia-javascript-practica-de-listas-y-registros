En una conocida red social trabajamos con publicaciones, que son registros que tienen el apodo de quien sube la publicación y el texto que contiene la misma:

``` javascript
{ apodo: "feli", texto: "tengo sueño" }
```

Las publicaciones por sí mismas no son muy interesantes, por eso en general contamos con hilos, que no son más que listas de publicaciones:

``` javascript
let hiloDeEjemplo = [
{ apodo: "jor", mensaje: "Aguante la ciencia ficción" },
{ apodo: "tere", mensaje: "A mi no me gusta mucho" },
{ apodo: "jor", mensaje: "¡Lee fundación!" }
]
```

¿Y qué tienen de especiales estas publicaciones? :thinking: Aunque como siempre podés enviar tu solución las veces que quieras, no la vamos a evaluar automáticamente por lo que **el ejercicio quedará en color celeste**. :open_mouth: Si querés verla en funcionamiento, ¡te invitamos a que la pruebes en la consola!

> Como último desafío, definí una función `publicacionesCortasDelHilo` que tome un apodo por parámetro y un hilo, y retorne las publicaciones de esa persona que tengan menos de 20 caracteres. Por ejemplo:
>
```javascript
ム publicacionesCortasDelHilo("jor", hiloDeEjemplo)
=> [{ apodo: "jor", mensaje: "¡Lee fundación!" }]
```


<style>
  .notify-problem-box {
    display: none;
  }
  .submission-results h4::after {
    content: "¡Gracias por enviar tu solución!";
    font-weight: bold;
  }
  .submission-results h4 strong { 
    display: none;
  }
</style>
