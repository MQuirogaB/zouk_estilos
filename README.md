# Música para bailar zouk brasileño

Página estática con los estilos musicales que se bailan en zouk brasileño: descripción, tempo orientativo y tres canciones representativas por estilo.

## Cómo añadir canciones

Abre `index.html` y busca la lista `ESTILOS` al principio del script. Cada estilo tiene tres huecos:

```js
canciones: [
  { t: "Título", a: "Artista", u: "https://enlace-opcional" },
  { t: "", a: "", u: "" },   // vacío = se muestra como placeholder
  { t: "", a: "", u: "" },
]
```

- `t`: título de la canción
- `a`: artista
- `u`: enlace (Spotify, YouTube…). Es opcional; si lo pones, la canción se vuelve clicable.

## Publicar con GitHub Pages

Sube `index.html` a la raíz del repo y activa Pages en *Settings → Pages → Deploy from a branch*.
