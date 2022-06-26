---
title: Los trucos de esta página
feed: hide
date: 25-06-2022
---

Estos son algunos de los trucos que he descubierto al modificar la plantilla con la que construí esta página:

- Para que esto se integre bien con Obsidian, es importante que cada nota en el vault "\_notes" tenga el mismo nombre que lo que se escribe en el campo "title" de la nota. Por ejemplo, el archivo en Obsidian de esta nota es "Los trucos de esta página" y el campo "title" tiene exactamente el mismo texto, incluídas las tildes.
- No poner un "date" más reciente que hoy en ninguna nota. Si se hace esto, la nota saldrá en el feed, pero redireccionará a 404 al hacer click.
- Sólo las notas en la carpeta "Public" se sincronizarán con GitHub. Notas privadas (por ejemplo, aún no listas para ser publicadas) se pueden poner temporalmente en una carpeta "Private"
- Para las imágenes, en Obsidian es necesario referenciar la ubicación que esperamos que la imagen tenga en /assets/img/... Un ejemplo se puede ver en [[Exhalation - Ted Chiang]]. Lastimosamente esto hace que en Obsidian no podamos ver la imagen insertada en la nota.
- Las notas ocultas (feed: hide) están sincronizadas con Github, tienen una URL de acceso, y se pueden hiperlinkear. Es decir, "hide" no significa que la información de la página esté protegida.
- Una forma de ver una lista de todas las páginas es via el [sitemap](https://www.quesodecabeza.com/sitemap.xml).
- Aunque es útil hacer el build de la página de manera local antes de sincronizar el repo via Github, da un poco de tedio hacerlo si estás desde Windows y no tienes Ruby o Jekyll instalados. Una alternativa es ir a Github.com, ir al repo, clickear en Actions y descargar el artifact generado en uno de los "pages build and deployment". Es un archivo comprimido que se puede explorar. Esto es útil para revisar si, por ejemplo, una página se ha generado para una nota. También para revisar hipervínculos.