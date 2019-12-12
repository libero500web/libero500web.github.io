---
layout: page
title: Mappa
permalink: /amministrazione/impostazioni/mappa
nav_order: 7
parent: Impostazioni
mapConfig: imp_map_config.jpg
mapVars: imp_map_variables.jpg
---

# Mappa

La schermata **Mappa** permette di configurare le impostazioni relative a mappa, tracciati e variabili.
All’interno della tab **Impostazioni** si trovano le configurazioni relative alla mappa e ai tracciati del teleriscaldamento:

![La configurazione dei parametri della mappa](/assets/images/{{page.mapConfig}})
{: .py-5 }

Il campo **Token mapbox** ospita il token generato da Mapbox che consente il funzionamento della mappa; il campo **TLR Style** ospita l’url relativo allo stile del tracciato di teleriscaldamento (questo campo è opzionale); Il campo **Visibilità tracciato TLR** specifica la tipologia di utente abilitato a vedere il tracciato di teleriscaldamento sulla mappa; il campo **Google Geocode API Key** ospita la chiave Api relativa al servizio di geolocalizzazione di Google.

All’interno della tab **Variabili** si trova la tabella che elenca le variabili visualizzate sulla mappa con un marker specifico:

![Le variabili mostrate sulla mappa](/assets/images/{{page.mapVars}})
{: .py-5 }

Le variabili già presenti sono elencate divise per supervisor e device di riferimento e possono essere modificate o eliminate con gli appositi bottoni. Tramite il bottone **Aggiungi** è possibile inserire una nuova variabile da visualizzare sulla mappa.
