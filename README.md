# Frontend Challenge - CoreStack

## 🧠 Ragionamento Iniziale
- **Primo step:** Ho configurato l'ambiente con React e Bootstrap, dando priorità al fetching dei dati e alla gestione degli stati di loading/error.
- **Importanza:** Ho puntato sulla UX: un'applicazione deve essere parlante. Ho aggiunto feedback visivi per ogni azione (caricamento, validazione form, risultati vuoti).
- **Ambiguità:** Dato che l'API è mock, ho gestito l'aggiunta dei post localmente per simulare la persistenza immediata nell'interfaccia.

## 🚀 Scelte Implementative
- **Paginazione (Bonus):** Ho diviso i post in pagine da 10 elementi per migliorare la leggibilità e le performance di rendering.
- **Filtro con Highlight (Bonus):** Ho aggiunto una barra di ricerca che filtra in tempo reale titolo e corpo del post, evidenziando il testo corrispondente per guidare l'occhio dell'utente.
- **Validazione:** Il form impedisce l'invio di campi vuoti mostrando un messaggio d'errore contestuale invece di un alert bloccante. Mentre in caso di successo mostro un mesaggio di successo

## 🔴 Cosa non è stato fatto
- **Persistence:** I dati aggiunti non sopravvivono al refresh del browser (servirebbe il LocalStorage o un database reale).

## ⚙️ Miglioramenti futuri
- Implementazione di **Persistenza** dei dati.