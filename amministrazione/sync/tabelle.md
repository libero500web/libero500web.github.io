---
layout: page
title: Tabelle
permalink: /amministrazione/sync/tabelle
nav_order: 2
parent: Sync
grand_parent: Amministrazione
tables: amm_sync_tables.jpg
---

# Tabelle

La tabella riporta informazioni circa lo stato di sincronizzazione delle tabelle da Libero500 a Liberoweb.

![La tabella di sincronizzazione con Libero500](/assets/images/{{page.tables}})
{: .py-5 }

La colonna **tabella** riporta il nome di riferimento della tabella del database di Libero500; la colonna **stato** indica se la tabella è stata correttamente sincronizzata; La colonna **Data Sync** riporta la data dell’ultima sincronizzazione della relativa tabella;  La colonna **Checksum** riporta il checksum della tabella di riferimento, utile per verificare manualmente lo stato di sincronizzazione; Tramite la voce **forza sync** nella colonna **Azioni** è possibile forzare la sincronizzazione della tabella, che avrà luogo durante il successivo task di sincronzzazione.
