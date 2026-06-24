CONTROL FACTURAS - PUBLICACION DE ACTUALIZACION
===============================================

Esta carpeta es la unica que debe usarse para el repositorio publico de releases.
No contiene codigo fuente, config.json real, base de datos ni logs reales.

Archivos:
- version.json: manifiesto publico que lee la app para saber si hay version nueva.
- ControlFacturas_Portable.zip: paquete que se adjunta tambien al GitHub Release.

En GitHub publico:
1. Sube version.json al branch main.
2. Crea un Release nuevo.
3. Adjunta ControlFacturas_Portable.zip al Release.
4. Verifica que download_url en version.json apunte a ese asset.
