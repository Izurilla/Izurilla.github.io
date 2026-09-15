# Izurilla.github.io
Web oficial de Irene Zurilla.

## Cuaderno de autora
Las entradas públicas del diario se editan en `cuaderno-data.js`.

Cada entrada sigue esta estructura:

```js
{
  date: "2026-09-15",
  title: "Título de la entrada",
  project: "Proyecto o categoría",
  status: "En proceso",
  text: "Texto de la entrada"
}
```

Añade siempre las nuevas entradas dentro de `window.CUADERNO_ENTRIES = [ ... ];` separadas por comas. La web las ordena automáticamente por fecha y muestra las tres más recientes en la portada.
