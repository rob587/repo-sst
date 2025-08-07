sst
===
Il cliente è BooRoad: come sai, organizza spesso viaggi con accompagnatori in diverse
destinazioni.
Lʼesigenza è quella di fornire al team di accompagnatori una rubrica coi dati (nome cognome e
num. di telefono) dei partecipanti, in modo da poterli contattare tempestivamente in caso di
necessità mentre si trovano in viaggio.
Per questo motivo, lʼagenzia ha bisogno di una soluzione “digitaleˮ.

Domande da porre al cliente

<!-- 1. Chiedere al cliente come si immagina il prodotto finale.(app o sito)
D -->

2. Chiedere se ha deadline.
M

<!-- 3. Sapere se fa parte di un applicativo esistente oppure uno standalone.
R -->

<!-- 4. Chiedere se ci sono più operatori per gruppo
A -->

5. Come riceviamo le informazioni dei clienti.
D

6. Quali dati può gestire l'operatore (nome-cognome-numero-destinazione)
A



Bozza app

l'operatore ha a disposizione un quadro generale sul viaggio e dei partecipanti, attraverso questo quadro l'operatore può ricavare le informazioni di ogni partecipante per contattarlo in caso di necessità.

Chiedere se vuole la funzionalità di ricerca e una check list di presenze



gruppo 2 domande

esportazione dati

quanti partecipanti/suddivisione


gruppo 4 domande

semplicità, minimal

























Alexandru: Obiettivo del Progetto
Realizzare un applicativo interno per la gestione dei dati dei viaggiatori dell’azienda, attraverso una web-app. Sarà utilizzata principalmente dai coordinatori e altri utenti interni, con con la possibilità di aggiungere viaggiatori, organizzare viaggi e visualizzare e contattare i partecipanti.
Esperienza Utente e Utilizzo
L’app sarà usata principalmente da mobile o da desktop?
  Sarà utilizzata sia da mobile che da desktop.
Quanto è importante che la piattaforma funzioni anche offline?
  Non richiesto per la prima versione. In futuro si. 
L’interfaccia dovrà adattarsi a tutti i dispositivi (smartphone, tablet, desktop)?
  Sì, è necessaria una visualizzazione responsive.
L’app dovrà supportare più lingue?
 No, solo italiano inizialmente.
Ci sono funzionalità specifiche di sicurezza che desiderate per proteggere i dati?
  Non specificate, ma si assume protezione dati standard (es. login sicuro, accesso riservato, ruoli).
Serve un sistema di login?
  Sì, login tramite crede

Damiano: Funzionalità e Contenuti

tipologia di utenti:{

amministrazione,
coordinatori

}

[amministrazione: crea i viaggi, assegna coordinatori,ha accesso completo
coordinatori: ha accesso ai viaggi a lui assegnati e ne può modificare la lista dei viaggiatori]



il cliente rispondendo alle domande richiede un'applicativo interno per la propria azienda
l'applicativo prevede l'inserimento dei dati relativi a ogni singolo viaggiatore.
non hanno avuto un'applicativo in precedenza quindi non abbiamo una base specifica. al momento utilizzano il foglio di calcolo, quindi come inizio si potrebbe creare una funzionalità per recuperare i dati da esso


la struttura dati del viaggiatore è composta da : {
nome,
email,
phone,
codiceFiscale,
emergenza
}

un'altra struttura dati è quella degli user (chi effettivamente utilizza l'applicativo)

gli user hanno una gerarchia
l'applicativo può essere utilizzato sia mobile che desktop

status bar per ogni viaggio


l'utente richiede la possibilità oltre che poter avere controllo totale sulla lista di viaggiatori, anche la possibilità di visualizzarne le info e contattarli via mail o telefono

