Water-drop logo — favicon package
==================================

Three color schemes, pick one folder:
  azure/       blue drop, ink ripples       (recommended default)
  tonal-blue/  all blue, tone-on-tone
  crimson/     red drop, ink ripples

Each folder contains:
  icon.svg              scalable mark, transparent — use for the site header & favicon.svg
  favicon-16.png        browser tab
  favicon-32.png        browser tab / bookmarks
  favicon-48.png        Windows / high-dpi tab
  apple-touch-icon.png  180px, dark rounded tile — iOS home screen
  apple-touch-icon.svg  same, scalable
  icon-192.png          Android / PWA
  icon-512.png          Android / PWA / store

HTML — drop into <head> (example uses the azure folder):

  <link rel="icon" href="/favicon/azure/icon.svg" type="image/svg+xml">
  <link rel="icon" href="/favicon/azure/favicon-32.png" sizes="32x32">
  <link rel="apple-touch-icon" href="/favicon/azure/apple-touch-icon.png">

For a web manifest (PWA), reference icon-192.png and icon-512.png.
