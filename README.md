
# PROGETTO APP – SCOUNTING
### Il tuo talento, il tuo futuro. Scendi in campo con i professionisti.

---

## 1. Descrizione del progetto

Scounting è un'applicazione progettata per mettere in contatto calciatori e scout.

La piattaforma permette ai calciatori di creare un profilo personale e sportivo completo, inserendo le proprie statistiche, i video delle prestazioni e le informazioni relative alla propria disponibilità per provini o trasferimenti.

Gli scout possono consultare i profili, effettuare ricerche attraverso appositi filtri e contattare i giocatori ritenuti interessanti.

## 2. Problema da risolvere

Molti calciatori giocano in società sportive poco osservate da scout e allenatori di altre squadre. Questo può limitare la loro visibilità e ridurre le possibilità di essere individuati da società di livello superiore.

## 3. Target di riferimento

L'applicazione si rivolge a due categorie di utenti:

- Calciatori
- Scout e società calcistiche

## 4. Analisi dei competitor

- Tuttocampo
- Hudl
  
---

# 5. Funzionalità dell'applicazione

## 5.1 Funzionalità per il calciatore

### A. Creazione del profilo
Il calciatore può creare un profilo personale e sportivo inserendo:

- Foto del profilo
- Nome e cognome
- Età
- Città di residenza
- Ruolo in campo
- Piede preferito
- Altezza
- Società di appartenenza

### B. Inserimento delle statistiche sportive
Il calciatore può inserire e aggiornare le proprie statistiche, tra cui:

- Presenze
- Gol
- Assist
- Minuti giocati
- Ammonizioni
- Espulsioni

### C. Caricamento di video e highlights
Il calciatore può caricare video e highlights delle proprie prestazioni, consentendo agli scout di valutare le sue capacità tecniche e il suo comportamento in campo.

### D. Gestione delle richieste di contatto
Il calciatore può ricevere richieste di contatto da scout e società calcistiche e decidere se accettarle o rifiutarle.

In caso di accettazione, può avviare una conversazione tramite la chat.

### E. Disponibilità per provini e trasferimenti
Il calciatore può indicare se è disponibile per:

- Provini
- Trasferimenti

### F. Preferenze sportive
Il calciatore può specificare le proprie preferenze relative a:

- Città o area geografica
- Società calcistiche

## 5.2 Funzionalità per lo scout

### A. Ricerca dei calciatori
Lo scout può cercare i giocatori attraverso filtri specifici:

- Età
- Ruolo
- Città
- Società
- Piede preferito
- Statistiche sportive
- Disponibilità per provini

### B. Creazione di liste di osservazione
Lo scout può creare liste personalizzate contenenti i calciatori di proprio interesse.

### C. Invio di richieste di contatto
Lo scout può inviare una richiesta di contatto a un calciatore.

Se il giocatore accetta la richiesta, diventa possibile comunicare attraverso la chat.

---

# 6. Requisiti funzionali

I requisiti funzionali descrivono le operazioni che il sistema deve consentire agli utenti di eseguire.

Per ciascun requisito viene utilizzato il formato *User Story*:

**Come [utente], voglio [funzionalità], così da [obiettivo].**

## 6.1 Requisiti relativi al calciatore

### RF01 – Creazione del profilo del calciatore
Come calciatore, voglio creare il mio profilo inserendo foto, nome, età, città, ruolo, piede preferito, altezza, società, così da presentare in modo completo le mie informazioni agli scout e alle società.

### RF02 – Inserimento delle statistiche sportive
Come calciatore, voglio inserire le mie statistiche sportive, tra cui presenze, gol, assist, minuti giocati, ammonizioni ed espulsioni, così da mostrare le mie prestazioni sportive.

### RF03 – Inserimento di video e highlights
Come calciatore, voglio caricare video e highlights delle mie prestazioni, così da permettere agli scout di valutare direttamente le mie capacità sul campo.

### RF04 – Ricezione e gestione delle richieste di contatto
Come calciatore, voglio ricevere richieste di contatto da scout e poterle accettare o rifiutare, così da decidere con chi entrare in contatto.

### RF05 – Gestione della disponibilità
Come calciatore, voglio indicare se sono disponibile per provini o trasferimenti, così da rendere nota la mia disponibilità agli scout interessati.

### RF06 – Indicazione delle preferenze sportive
Come calciatore, voglio indicare le mie preferenze riguardo a città e società, così da individuare opportunità più adatte alle mie esigenze.

## 6.2 Requisiti relativi allo scout

### RF07 – Ricerca dei calciatori tramite filtri
Come scout, voglio cercare calciatori utilizzando filtri come età, ruolo, città, categoria, piede preferito, statistiche e disponibilità per provini, così da individuare rapidamente i profili più adatti alle mie esigenze.

### RF08 – Creazione di liste di osservazione
Come scout, voglio creare liste di calciatori da osservare, così da organizzare e gestire più facilmente i giocatori di mio interesse.

### RF09 – Contatto e chat con il calciatore
Come scout, voglio inviare una richiesta di contatto a un calciatore e, se accettata, poter comunicare tramite una chat, così da avviare un confronto diretto con il giocatore.


---

# 7. Diagramma UML

[Calciatore]-(Inserire le proprie caratteristiche) 
[Calciatore]-(Inserire le proprie statistiche)
[Calciatore]-(Inserire le proprie statistiche)  
[Calciatore]-(Inserire video) 
[Calciatore]-(Ricevere messaggi dallo scout) > (Aver accettato la richiesta la prima volta)
[Calciatore]-(Indicare disponibilità per provini)
[Calciatore]-(Indicare preferenze riguardanti società e categoria) 

[Scout]-(Ricercare calciatori attraverso filtri)
[Scout]-(Salvare i giocatori interessati) 
[Scout]-(Contattare il giocatore tramite una richiesta) 

[Calciatore]^[Utente]
[Scout]^[Utente]

[Utente]-(Registrarsi all'applicazione)
[Utente]-(Accedere all'applicazione)

[Amministratore]-(Accedere all'applicazione come amministratore)
[Amministratore]-(Gestire profili e messaggi)
[Amministratore]-(Gestire segnalazioni)


<img width="4204" height="3368" alt="image" src="https://github.com/user-attachments/assets/122e288c-bac8-4de4-a844-8229e44819d3" />

---

# 8. Obiettivo finale del progetto

L'obiettivo di Scounting è realizzare una piattaforma digitale che faciliti l'incontro tra calciatori emergenti e scout.

**Scounting: il tuo talento, il tuo futuro. Scendi in campo con i professionisti.**
