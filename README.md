# fotos-ebay

Staging publico de fotos de producto para la carga CSV de eBay (File Exchange, columna PicURL).

Una carpeta por SKU. Sin EXIF: las fotos pasan por scripts/preparar_fotos.py, que borra el GPS.

eBay copia la imagen a sus servidores al crear el listado, asi que una vez publicado el listado la carpeta se puede borrar.
