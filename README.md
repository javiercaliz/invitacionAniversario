# Luci & Javi · 10 años

Invitación interactiva para el aniversario: un comecocos (sapito) de papel en 3D. Los invitados juegan y van descubriendo los datos de la fiesta.

## Cómo editar los datos

Todo está en `index.html`, en el bloque `CONFIG` al principio del script:

```js
const CONFIG = {
  date: '2026-12-19',
  dateLabel: 'Sábado 19 de diciembre',
  time: '',       // ej: '21:00'
  venue: '',      // ej: 'Salón Los Aromos'
  address: '',    // para el botón de Google Maps
  dressCode: '',
  rsvpBy: '',     // ej: '10 de diciembre'
  whatsapp: '',   // solo números, con código de país
  alias: '',      // alias para regalos
  since: '2016-12-02',
};
```

Lo que quede vacío se muestra como "a confirmar" o se oculta su botón.

## Publicar

Es un solo archivo estático. Para publicarlo con GitHub Pages: *Settings → Pages → Deploy from a branch → `main` / root*.
