---
layout: page
title: Importa fatture
permalink: /amministrazione/gestione/importa-fatture
nav_order: 3
parent: Gestione
import: ges_if.jpg
pattern: ges_if_pattern.jpg
fromFile: ges_if_fromfile.jpg
fromUrl: ges_if_fromurl.jpg
---

# Importa fatture

![La schermata di importazione delle fatture](/assets/images/{{page.import}})
{: .py-5 }

La schermata **Importa fatture** permette l’importazione di documenti di fatturazione relativi a supervisor specifici.
Importante: per importare documenti di fatturazione ed attribuirli correttamente ai rispettivi supervisor è necessario che i nomi dei file .PDF corrispondano precisamente al pattern di nomenclatura definito in Liberoweb.

![Il pattern dei file PDF](/assets/images/{{page.pattern}})
{: .py-5 }

Tramite il pannello **Pattern file** è possibile visualizzare il pattern attuale, facendo click sull’icona della rotella si accede alla schermata di impostazione del pattern per poterlo modificare.

Tramite il campo **Metodo** è possibile selezionare il metodo di importazione delle fatture tra:
  * **Caricamento file**: consente di caricare un file direttamente dal computer (dimensione massima consentita 50MB).
  * **File da url esterno**: consente di importare il file inserendone l’url pubblico previo caricamento su servizi terzi.

Il campo **file** permetterà la selezione ed il caricamento del documento qualora sia stato selezionato il metodo “Caricamento file”.

![L'interfaccia di caricamento di file](/assets/images/{{page.fromFile}})
{: .py-5 }

Il campo **File’s public url** sarà invece visibile quando è stato selezionato il metodo “File da url esterno” e permetterà di inserire l’url pubblico da cui importare il file.

![L'interfaccia di caricamento di file tramite url esterno](/assets/images/{{page.fromUrl}})
{: .py-5 }
