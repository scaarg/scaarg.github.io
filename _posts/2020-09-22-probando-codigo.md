---
layout: post
title: Bloques de código CSS
published: true
---

Que tal lectorsillo. Éste será seguramente la publicación más inútil que verás en Acento en la O. La realidad es que solo existe para probar el formato de los bloques de código.

¿Por qué? Tal vez algún día lo necesite para una publicación técnica en el futuro y no quiero tener que esperar a encontrar el formato CSS que me guste y tener que estar viendo prueba y error para poder publicar algo en lo que trabaje. Entonces, al mal tiempo darle prisa.

No sé que formato tienen los bloques de codigo en este momento, pero la intención es que el fondo sea negro y el _back end_ pueda identificar el idioma y hacer highlight de las variables y formato en base a eso. Veamos si lo puedo lograr.

Estos son mis cuadros de código:

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

Quiza debería usar una publicación de _"sample"_, ¿no? Tal vez luego. Y sólo para los nerds, este blog esta escrito en [Markdown](http://daringfireball.net/projects/markdown/) pero con un _back end_ como el mío &ndash; Jekyll colgado en GitHub Pages &ndash; no es fácil crear un ambiente de desarrollo de preproducción como si solamente fuera HTML y CSS. Bueno, al menos yo no he podido configurarlo.

---

## Update #1

Al publicar por primera vez este post, así se veían los bloques de código:

<figure>
    <img src="/images/post/codecss.png" alt="Bloques de codigo con formato horrible">
    <figcaption>¡El horror encarnado!</figcaption>
</figure>

## Update #2

Las propiedades que permitieron que el codigo se viera bien fueron:

```css
pre {
  color: #e5e5e5;
  background-color: #121212;
  border-left: 3px solid #cc4b23;
  border-radius: 8px;
  padding: 1em 1.5em;
  margin-bottom: 1.5em;
  page-break-inside: avoid;
  display: block;
  overflow-x: auto;
  word-break: normal;
  word-wrap: normal;
  white-space: pre;
  tab-size: 2;
}
```

Fin del update

---

Muchas gracias por formar parte de ésta prueba. Obviamente lo lograré poner en formato, sólo quería darles una oportunidad de ver como hago las cosas. Hasta el día de hoy, no le he dado formato a elemento HTML hasta no necesitarlo y ha sido un dolor de cabeza. Publicar algo y que no se vea de la forma que quieres... Creo que no hay un sentimiento más horrible.

En fin, gracias otra vez si leíste esto. Prometo que el siguiente si será interesante.
