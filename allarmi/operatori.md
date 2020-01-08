---
layout: page
title: Operatori
permalink: /allarmi/operatori
nav_order: 5
parent: Allarmi

opList: operator_list.jpg
opAvailability: operator_availability.jpg
opAvailabilityConf: operator_availability_modal.jpg
---

# Operatori

La schermata *operatori* mostra l’elenco del personale abilitato alla ricezione e gestione degli allarmi. Per ciascun operatore vengono mostrati anche il gruppo di appartenenza ed i contatti autorizzati.

![La schermata operatori](/assets/img/{{page.opList}})
{: .py-5 }

All'interno della scheda di un operatore è possibile specificare i gruppi di cui l'operatore fa parte così come i relativi contatti.

## Contatti ed autorizzazione

Per ogni operatore è possibile specificare un indirizzo **e-mail**, un numero di telefono per le **chiamate** ed un numero di telefono per l'invio di **SMS** compilando gli appositi campi.
Ciascun contatto necessita di essere convalidato ed autorizzato prima di poter essere utilizzato.

Per **convalidare un contatto** fare click sul bottone *convalida*, verrà inviata una comunicazione all'operatore tramite il medium specifico per convalidalro.

Aggiungete la spunta alla casella *Autorizza il contatto* per autorizzare i canali di contatto desiderati.

## Reperibilità

Dalla tab reperibilità è possibile configurare e visualizzare i giorni e gli orari di reperibilità dell'operatore anche tramite un calendario configurabile [3].

![La schermata reperibilità dell'operatore](/assets/img/{{page.opAvailability}})
{: .py-5 }

Sotto la voce *Reperibilità standard* [1] vengono visualizzati i giorni e gli orari di reperibilità standard per il relativo lasso temporale. Tramite l'apposito bottone è possibile impostare l'operatore come **reperibile 24 ore su 24**.
La voce *Reperibilità variazioni* mostra invece le variazioni impostate rispetto alla reperibilità standard dell'operatore.

Per configurare le reperibilità fate click sul bottone **Aggiungi reperibilità**. Nella finestra modale che apparirà potrete specificare il lasso temporale di validità della reperibilità, i relativi giorni della settimana, l'orario di inizio e fine reperibilità ed il livello di priorità. In caso stiate inserendo una variazione di reperibilità mettete la spunta alla relativa casella *Variazione*.

![La finestra modale per la configurazione delle reperibilità](/assets/img/{{page.opAvailabilityConf}})
{: .py-5 }
