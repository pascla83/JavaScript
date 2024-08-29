# Javascript

Concetto fondamentale

## Descrizione

è bene comprendere l'importanza di JavaScript


Funzione di CallBack


Una funzione di callback è una funzione che viene eseguita dopo che un'altra funzione ha completato la sua esecuzione. In genere viene fornito come input in un'altra funzione.



Le Promises in JavaScript sono un meccanismo per gestire operazioni asincrone. Quando eseguiamo un'operazione che richiede del tempo, come una richiesta a un server o la lettura di un file, 
non possiamo permettere che il nostro codice si blocchi aspettando il completamento di tale operazione. Le Promises ci consentono di scrivere codice che gestisce queste operazioni in modo
 non bloccante, continuando a eseguire altro codice nel frattempo.
Cos'è una Promise?

Una Promise è un oggetto che rappresenta il risultato futuro di un'operazione asincrona. Può trovarsi in uno di questi tre stati:

    Pending (In attesa): la Promise è in corso, l'operazione non è ancora completata.
    Fulfilled (Completata): l'operazione è stata completata con successo e la Promise ha un valore.
    Rejected (Rifiutata): l'operazione è fallita e la Promise ha una ragione per il fallimento (un errore).

Creazione di una Promise

Puoi creare una Promise usando il costruttore Promise. Prende una funzione chiamata "executor" che ha due parametri, resolve e reject. Questi due parametri sono a loro volta funzioni:

    resolve(value): viene chiamata se l'operazione è completata con successo e passa il risultato.
    reject(reason): viene chiamata se l'operazione fallisce e passa il motivo del fallimento.


## Impostante

La funzione fetch() è una delle API più moderne e potenti in JavaScript per eseguire richieste HTTP asincrone. Viene utilizzata per fare richieste di rete, recuperare risorse come file o dati 
da un server, ed è supportata dalla maggior parte dei browser moderni.
Funzionalità di fetch()

Ecco alcune delle principali funzionalità e caratteristiche di fetch():

    Richieste HTTP: Con fetch() puoi effettuare richieste HTTP di vari tipi (GET, POST, PUT, DELETE, etc.) per interagire con le API o server web.


Promesse: fetch() è basato sulle Promises, il che significa che restituisce una Promise. Questo ti consente di scrivere codice asincrono in modo più semplice e gestire le risposte (e gli errori) in 
modo strutturato.


```bash



```