---
layout: page
title: Allarmi
permalink: /allarmi
nav_order: 11
has_children: true

deviceAlarms: device-alarms.jpg
dropdown: alarms-dropdown.jpg
---

# Allarmi

Il modulo *Allarmi* consente la visualizzazione e la configurazione degli **allarmi di dispositivo** e degli **allarmi di sistema**, nonché la definizione e la configurazione degli **operatori**.

Un allarme rappresenta un **malfunzionamento su un'utenza** della centrale e viene evidenziato tramite colorazione ed icone condizionali. Gli allarmi non più attivi vengono archiviati e conservati nello storico. Potete visualizzare e gestire gli allarmi nella sezione *Allarmi* del menu principale:

![La schermata di gestione degli allarmi](/assets/img/{{ page.deviceAlarms }})
{: .py-5 }

Gli allarmi più recenti sono rappresentati anche nel relativo menu a discesa nella topbar [1]:

![Il menu a discesa Allarmi](/assets/img/{{ page.dropdown }})
{: .py-5 }

Quando viene rilevato un nuovo allarme **il sistema emette un tono di warning** ed una notifica viene mostrata nella schermata *Mappa*.

## Stato di un allarme

Un allarme può essere **attivo** oppure **inattivo**.

## Riconoscere un allarme

Un allarme è classificato come **non riconosciuto** fino a quando non viene riconosciuto.
Una volta riconosciuto l'allarme il sistema smetterà di riprodurre il tono di warning.

## Silenziare un allarme

Un'allarme può essere silenziato tramite bottone silenzia. **Nota**: silenziare un allarme è un'azione che ha effetto solo per l'utente e non influenza lo stato di tutto il sistema.

## Archiviare un allarme

Quando un allarme viene disattivato rimane visibile nello storico ed il suo stato non viene modificato.
