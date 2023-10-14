---
title: Bilder in Hexo-Postings einbinden
date: 2023-10-14 11:57:34
tags: [ Technik, Hexo ]
---

In Hexo-Postings und Artikeln lassen sich auch Bilder in den gängigen Formaten für das Web verwenden, siehe z.B. [hier in der offiziellen Doku](https://hexo.io/docs/asset-folders.html).

<!-- more -->

<br>

Als Beispiel binden wir hier ein Katzenfotos (was sonst?) ein:

![Foto von Pixabay-Nutzer "Kirgiz03", Quelle: https://bit.ly/46prkxE](/bilder/Katze.jpg)

<br>

Wenn man öfters Bilder in Postings einbinden möchte, dann sollte man in der Datei `_config.yml`die Eigenschaft `post_asset_folder` auf den Wert `true` setzen; damit erreicht man, dass für jedes neue Posting auch ein eigener Ordner für die Bilder dieses Postings erzeugt wird.
