---
layout: page
title: Mappa
permalink: /mappa/
nav_order: 1
parent: Mappa e utenze

map: view_map.jpg
panel: user_detail_panel.jpg
iconSupervisor: icon-supervisor.jpg
iconSupervisorInactive: icon-supervisor-inactive.jpg
iconActA: icon-active-acknowledged.jpg
iconActNa: icon-active-unacknowledged.jpg
iconNsNa: icon-unsilenced-unacknowledged.jpg
---

# Mappa

La schermata mappa è la visualizzazione principale di Libero e mostra sulla mappa le varie utenze, il loro stato e la loro posizione.

![La visualizzazione a mappa](/assets/img/{{page.map}})
{: .py-5 }

Facendo click sul bottone *Filtri* [1] potete mostrare o nascondere i **filtri** che vi permettono di trovare rapidamente supervisor per nome, città, indirizzo, categoria, nodo e stato.

Potete scorrere la mappa facendo click e trascinando con il mouse nella direzione desiderata. Con i bottoni di **regolazione dello zoom** [2] o con la rotella del mouse potete regolare il livello di zoom sulla mappa.

Per alternare tra visualizzazione su mappa e visualizzazione tabellare dei supervisor fate click sull'apposito bottone di **selezione visualizzazione** [3].

Con il **bottone contestuale di aggiunta rapida** [4] potete rapidamente aggiungere utenze, categorie, nodi, reti TLR e centrali.

Le utenze sono rappresentate da marker colorati che ne distinguono lo stato e la presenza di allarmi come segue:

  * <img src="/assets/img/icons/{{ page.iconSupervisor }}" width="16"> Utenza attiva.
  * <img src="/assets/img/icons/{{ page.iconSupervisorInactive }}" width="16"> Utenza disattivata.
  * <img src="/assets/img/icons/{{ page.iconActA }}" width="16"> Utenza con allarme attivo riconosciuto.
  * <img src="/assets/img/icons/{{ page.iconActNa }}" width="16"> Utenza con allarme attivo non riconosciuto.
  * <img src="/assets/img/icons/{{ page.iconNsNa }}" width="16"> Utenza con allarme attivo non silenziato e non riconosciuto.

Se il livello di zoom non è sufficiente a mostrare con precisione la posizione di alcune utenze esse sarano raccolte in un **cluster** [5] rappresentato da un cerchio riportante il numero di utenze facenti parte del cluster. Il colore del cerchio indica lo stato di allarme più urgente presente all'interno del cluster.

Selezionando un'utenza dalla mappa, nella parte destra della finestra viene mostrato un **pannello contestuale riepilogativo** dei dettagli e degli allarmi relativi all'utenza selezionata:

![Il pannello riepilogativo di un'utenza](/assets/img/{{page.panel}})
{: .py-5 }
