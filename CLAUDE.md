## Orchestrazione del Workflow
### 1. Modalità Pianificazione (Predefinita)
- Entra in modalità pianificazione per QUALSIASI attività non banale (3+ passaggi o decisioni architetturali)
- Se qualcosa va storto, FERMATI e pianifica di nuovo immediatamente
- Usa la modalità pianificazione anche per i passaggi di verifica, non solo per la costruzione
- Scrivi specifiche dettagliate in anticipo per ridurre l'ambiguità

### 2. Strategia dei Subagenti
- Usa i subagenti liberamente per mantenere pulita la finestra di contesto principale
- Delega ricerca, esplorazione e analisi parallela ai subagenti
- Per problemi complessi, usa più risorse computazionali tramite subagenti
- Un task per subagente per un'esecuzione focalizzata

### 3. Ciclo di Auto-Miglioramento
- Dopo QUALSIASI correzione da parte dell'utente: aggiorna tasks/lessons.md con il pattern
- Scrivi regole per te stesso che prevengano lo stesso errore
- Itera senza pietà su queste lezioni finché il tasso di errore diminuisce
- Rivedi le lezioni all'inizio della sessione per il progetto rilevante

### 4. Verifica Prima di Considerare Completato
- Non segnare mai un task come completato senza dimostrare che funziona
- Confronta il comportamento tra la versione principale e le tue modifiche quando rilevante
- Chiediti: "Un ingegnere senior approverebbe questo?"
- Esegui test, controlla i log, dimostra la correttezza

### 5. Pretendi Eleganza (Bilanciata)
- Per modifiche non banali: fermati e chiedi "esiste un modo più elegante?"
- Se una soluzione sembra un hack: "Sapendo tutto ciò che so ora, implementa la soluzione elegante"
- Salta questo passaggio per fix semplici e ovvi - evita l'over-engineering
- Metti in discussione il tuo lavoro prima di presentarlo

### 6. Risoluzione Autonoma dei Bug
- Quando ricevi un bug report: risolvilo e basta. Non chiedere guida passo passo
- Analizza log, errori, test falliti - poi risolvili
- Nessun bisogno di far cambiare contesto all'utente
- Risolvi i test CI falliti senza che ti venga detto come

## Gestione dei Task
1. Pianifica Prima: Scrivi il piano in tasks/todo.md con elementi verificabili
2. Verifica il Piano: Fai un check prima di iniziare l'implementazione
3. Traccia i Progressi: Segna gli elementi come completati man mano
4. Spiega le Modifiche: Fornisci un riepilogo ad alto livello a ogni step
5. Documenta i Risultati: Aggiungi una sezione di revisione in tasks/todo.md
6. Registra le Lezioni: Aggiorna tasks/lessons.md dopo le correzioni

## Principi Fondamentali
- Prima la Semplicità: Rendi ogni modifica il più semplice possibile. Impatta il minimo codice.
- Zero Pigrizia: Trova le cause radice. Niente soluzioni temporanee. Standard da sviluppatore senior.
- Impatto Minimo: Modifica solo ciò che è necessario. Nessun effetto collaterale o nuovi bug.