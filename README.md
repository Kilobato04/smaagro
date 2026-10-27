# Piloto SMAAgro · TNC México · Grupo Herdez

Presentación HTML de una sola página (23 láminas). Sitio estático, sin build.

- `index.html` · deck completo (estilos, scripts y logo incluidos)
- `netlify.toml` · encabezados noindex y sin caché
- `robots.txt` · bloquea buscadores
- `images/favicon.svg`

## Datos en vivo
- Mapa: Mapbox GL con relieve y curvas de nivel (token en `CONFIG.mapboxToken`). Restringe el token al dominio de Netlify en el panel de Mapbox.
- Lámina 14 · API: humedad y temperatura del suelo modeladas de Open-Meteo para Culiacán y Durango (sin llave). Se cambia por el API de SMAA OS cuando los equipos SMAAgro estén en línea.

- Lámina 7 · Parcelas candidatas: dos ventanas satelitales de Mapbox (satellite-streets) a nivel de predio.

- Entregables, hitos y pagos: un solo catálogo (`HITOS` en el script) alimenta el cronograma, los pagos y la lámina 22.

## Navegación
← → láminas · M índice · F pantalla completa · `#n` en la URL abre la lámina n.
