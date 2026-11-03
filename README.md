# Piloto SMAAgro · TNC México · Grupo Herdez

Presentación HTML de una sola página (24 láminas). Sitio estático, sin build.

- `index.html` · deck completo (estilos, scripts y logo incluidos)
- `netlify.toml` · encabezados noindex y sin caché
- `robots.txt` · bloquea buscadores
- `images/favicon.svg`

## Datos en vivo
- Mapa: Mapbox GL con relieve y curvas de nivel (token en `CONFIG.mapboxToken`). Restringe el token al dominio de Netlify en el panel de Mapbox.
- Lámina 15 · API: humedad y temperatura del suelo modeladas de Open-Meteo para Culiacán y Durango (sin llave). Se cambia por el API de SMAA OS cuando los equipos SMAAgro estén en línea.

- Lámina 7 · Parcela en Sinaloa: ventana satelital de Mapbox (satellite-streets) a nivel de predio.

- Entregables, hitos y pagos: un solo catálogo (`HITOS` en el script) alimenta el cronograma, los pagos y la lámina 23.

## Versión ejecutiva
- Selector Completa / Ejecutiva en el pie. La presentación abre en la completa (24 láminas).
- Enlace directo a la ejecutiva (13 láminas): agrega `#e1` al final de la URL. `#n` abre la lámina n de la completa; `#en`, la lámina n de la ejecutiva.
- En la ejecutiva, "Ver detalle" abre la lámina correspondiente de la completa.

## Navegación
← → láminas · M índice · F pantalla completa · `#n` en la URL abre la lámina n.
