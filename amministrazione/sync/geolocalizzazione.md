---
layout: page
title: Geolocalizzazione
permalink: /amministrazione/sync/geolocalizzazione
nav_order: 3
parent: Sync
status: amm_sync_geo_status.jpg
noCity: amm_sync_geo_nocity.jpg
noGeo: amm_sync_geo_nogeo.jpg
custom: amm_sync_geo_custom.jpg
customSetup: amm_sync_geo_custom_setup.jpg
---

# Geolocalizzazione

La schermata permette di gestire la geolocalizzazione dei supervisor presenti all’interno del sistema.

![Lo stato di geolocalizzazione delle utenze](/assets/images/{{page.status}})
{: .py-5 }

La tabella di riepilogo riporta informazioni in merito ai supervisor presenti nel sistema. La colonna **Stato** indica lo stato di geolocalizzazione; la colonna **Supervisors** riporta il numero totale di supervisor presenti in Liberoweb; le colonne **Geolocalizzati** e **Non geolocalizzati** riportano rispettivamente il numero di supervisor geolocalizzati correttamente ed il numero di supervisor che risultano non geolocalizzati; la colonna **Senza città** specifica il numero di supervisor non geolocalizzati a causa dell’assenza del valore città nella scheda anagrafica.
Nella colonna **Azioni** sono visualizzate le azioni che è possibile compiere:

   * **Aggiornamento dei geocode**: tramite questo comando il sistema procede a geolocalizzare i supervisor privi di geolocalizzazione.
   * **Forza aggiornamento geolocalizzazione**: tramite questo comando il sistema procede a geolocalizzare nuovamente tutti i supervisor presenti su Liberoweb.

![La tabella delle utenze senza città](/assets/images/{{page.noCity}})
{: .py-5 }

La tabella **Supervisor senza città** elenca i supervisor il cui campo città non è valorizzato. Per geolocalizzare queste utenze è necessario aggiornarne la relativa scheda anagrafica nel pannello di Libero500. Liberoweb sincronizzerà la modifica e sarà quindi possibile procedere con l’aggiornamento dei geocode.

![La tabella delle utenze senza geolocalizzazione](/assets/images/{{page.noGeo}})
{: .py-5 }

La tabella **Supervisor senza geolocalizzazione** elenca i supervisor non geolocalizzati come conseguenza di errori nella scheda anagrafica quali:

   * Valore del campo **indirizzo** nullo o errato.
   * Valore del campo **città** errato.

Per geolocalizzare i supervisor è necessario aggiornarne la scheda anagrafica nel pannello di Libero 500. Liberoweb sincronizzerà la modifica e sarà quindi possibile procedere con l’aggiornamento dei geocode.

![La tabella delle utenze con geolocalizzazione custom](/assets/images/{{page.custom}})
{: .py-5 }

La tabella **Indirizzi custom** elenca i supervisor con geolocalizzazione custom. Tramite il bottone **modifica** è possibile modificare le coordinate inserite in precedenza. I valori di geolocalizzazione personalizzati possono essere eliminati tramite il bottone **elimina**.

![Setup della geolocalizzazione custom](/assets/images/{{page.customSetup}})
{: .py-5 }
