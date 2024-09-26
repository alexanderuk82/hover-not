# Uso Correcto de `:not` y `:hover` en CSS para Resaltar Elementos

![Portada del Proyecto](./cover.jpg)

## Descripción

Este proyecto es una demostración básica que explica cómo utilizar correctamente los selectores `:not` y `:hover` en CSS al mismo tiempo para seleccionar únicamente un elemento específico. Al pasar el cursor sobre una imagen, se aplica un filtro al resto de las imágenes, resaltando así la imagen sobre la cual se está haciendo hover.

## Código Clave

La única línea de código necesaria para lograr este efecto es:

```css
.footer .imagesContainer:hover img:not(:hover) {
    filter: grayscale(1) blur(1px);
}
```

## Cómo Funciona

- **`.footer .imagesContainer:hover`**: Selecciona el contenedor de imágenes cuando se hace hover sobre él.
- **`img:not(:hover)`**: Dentro de ese contenedor, selecciona todas las imágenes que **no** están siendo hover.
- **`filter: grayscale(1) blur(1px);`**: Aplica un filtro de escala de grises y desenfoque a esas imágenes, dejando intacta la imagen sobre la que se hace hover.

## Visita Mi Canal de YouTube

Para más videos y tutoriales relacionados con diseño web y CSS, visita mi canal de YouTube:

[UxUi Conexión Creativa](https://www.youtube.com/@uxuiconexioncreativa)

---

¡Gracias por visitar el proyecto! Si tienes dudas o sugerencias, no dudes en dejar un comentario.
