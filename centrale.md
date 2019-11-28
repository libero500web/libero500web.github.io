---
layout: page
title: Centrale
permalink: /centrale/
nav_order: 8
information: cen_info.jpg
graph: cen_graph.jpg
tabular: cen_graph_tabular.jpg
daily_trend: cen_daily_trend.jpg
---

# Centrale

Tramite la funzione *Centrale* si potranno visualizzare informazioni in merito a **variabili e consumi della centrale** del teleriscaldamento.

Accedendo alla funzione verranno visualizzate nella parte superiore le informazioni relative all’**indirizzo e posizione della centrale ed eventuali allarmi attivi**:

![Pannello di riepilogo delle informazioni sulla centrale](/assets/images/{{page.information}})
{: .py-5 }

Di seguito saranno invece visualizzati i pannelli contenenti i grafici e la fascia per impostare la ricerca. **I grafici sono impostati nell’area amministrativa e potranno visualizzare fino ad un massimo di due variabili**. Sarà possibile intervenire sulla fascia di ricerca per modificare il periodo di visualizzazione o la frequenza dei dati.

![Fascia di ricerca e grafici di energia e potenza](/assets/images/{{page.graph}})
{: .py-5 }

Cliccando sul pulsante *Analisi consumi* si passerà alla visualizzazione dello **storico dei consumi** della centrale, o in caso sia attivo il modulo Realtime, cliccando sul pulsante *Andamento giornaliero* si potranno visualizzare i **consumi giornalieri** della centrale.
Per ogni pannello grafico sarà sempre possibile passare alla **visualizzazione tabellare** o viceversa:

![Visualizzazione tabellare dei dati della centrale](/assets/images/{{page.tabular}})
{: .py-5 }

Nella visualizzazione dell’Andamento giornaliero non sarà presente la fascia di ricerca e **verranno visualizzati i dati con frequenza di un’ora della giornata corrente**. In caso non fossero disponibili gli ultimi dati, LiberoWeb effettuerà una **stima del consumo medio** per valorizzare le fasce orarie mancanti.

![Visualizzazione dell'andamento giornaliero](/assets/images/{{page.daily_trend}})
{: .py-5 }
