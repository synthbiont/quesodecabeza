---
title: Los trucos de esta página
feed: hide
date: 25-06-2022
---

Estos son algunos de los trucos que he descubierto al modificar la plantilla con la que construí esta página:

- Para que esto se integre bien con Obsidian, es importante que cada nota en el vault "\_notes" tenga el mismo nombre que lo que se escribe en el campo "title" de la nota. Por ejemplo, el archivo en Obsidian de esta nota es "Los trucos de esta página" y el campo "title" tiene exactamente el mismo texto, incluídas las tildes.
- No poner un "date" más reciente que hoy en ninguna nota. Si se hace esto, la nota saldrá en el feed, pero redireccionará a 404 al hacer click.
- Sólo las notas en la carpeta "Public" se sincronizarán con GitHub. Notas privadas (por ejemplo, aún no listas para ser publicadas) se pueden poner temporalmente en una carpeta "Private"
- Para las imágenes, en Obsidian es necesario referenciar la ubicación que esperamos que la imagen tenga en /assets/img/... Lastimosamente esto hace que en Obsidian no podamos ver la imagen insertada en la nota.