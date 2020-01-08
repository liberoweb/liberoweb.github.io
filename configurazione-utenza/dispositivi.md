---
layout: page
title: Dispositivi
permalink: /configurazione-utenza/dispositivi
nav_order: 2
parent: Configurazione utenza

devices: user_devices.jpg
function: device_function.jpg
---

# Dispositivi

La tab *Dispositivi* raccoglie tutti i device associati all'utenza. Da questa schermata potete aggiungere, gestire o rimuovere dispositivi:

![I dispositivi associati ad un'utenza](/assets/img/{{page.devices}})
{: .py-5 }

Ogni dispositivo è rappresentato dalle sue informazioni di base:

  * Tipologia
  * Matricola
  * Modello
  * Indirizzo Mbus
  * Baudrate

Tramite il bottone contestuale [1] è possibile gestire le funzioni associate al dispositivo, configurarne gli allarmi, eseguire un test per verificare la correttezza della configurazione, rimuovere il dispositivo o cambiarlo di ordine.

Facendo click su *Aggiungi dispositivo* appariranno i campi in cui inserire matricola, modello, indirizzo Mbus e baudrate del nuovo dispositivo, una volta inseriti questi dati fate click sul bottone *salva* per inserire il dispositivo. Il nuovo dispositivo comparirà quindi nella lista dispositivo e potrete procedere con le configurazioni avanzate.

## Gestire le funzioni del dispositivo

Facendo click sul bottone contestuale [1] e selezionando la voce *Gestisci funzioni* si aprirà una finestra modale in cui vengono mostrate le funzioni associate al dispositivo.

Per aggiungere una funzione fate click sul bottone *Aggiungi funzione*. Per ciascuna funzione sarà necessario definirne il tipo, sarà inoltre possibile specificare unità di misura, codice contatore, codice imposta, potenza, flusso, limite temperatura di ritorno, impulsi litri contatore, regolatore, registro volume, un massimo di cinque registri, periodo di validità ed eventualmente un dispositivo padre.

![La schermata di una funzione](/assets/img/{{ page.function }})
{: .py-5}

Una volta creata una funzione sarà possibile **attivarla** e disattivarla all'occorrenza mediante l'apposito interruttore. Per eliminare una funzione fare click sul bottone *Elimina*.
