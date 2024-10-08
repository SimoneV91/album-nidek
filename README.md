Album Nidek è un'applicazione web che permette di visualizzare e gestire album fotografici, con funzionalità di ricerca e ordinamento. L'app consente di sfogliare i titoli degli album e visualizzare il proprietario, offrendo una navigazione interattiva verso i dettagli degli album, inclusa una galleria fotografica con titoli.

![desktop](https://github.com/user-attachments/assets/f6b32587-d762-4d1d-8bef-59ddfb93c3a6)

![desktop2](https://github.com/user-attachments/assets/5529768f-114a-4b0b-8317-f001cb35b05d)

## Funzionalità

- **Tabella ordinabile**: Gli album possono essere ordinati in modo crescente o decrescente sia per titolo dell'album che per nome utente del proprietario.
- **Barra di ricerca**: Un campo di ricerca permette di filtrare gli album in base al titolo, facilitando la navigazione tra i contenuti.
- **Dettaglio dell'album**: Cliccando su una riga della tabella si accede alla pagina di dettaglio, dove vengono mostrati:
  - Nome del proprietario dell'album
  - Titolo dell'album
  - Galleria di tutte le foto dell'album, ognuna con il suo titolo.

![smartphone](https://github.com/user-attachments/assets/9a7ae41b-5d3a-4d53-953e-cadc51ad83dd)                           
![smartphone2](https://github.com/user-attachments/assets/d9e5cbd6-c67e-41f5-bf60-617b07604525)

## Installazione

Segui questi semplici passaggi per installare e avviare l'applicazione sul tuo ambiente locale:

```bash
# Clona il repository
git clone https://github.com/SimoneV91/album-nidek.git

# Vai nella directory del progetto
cd album-nidek

# Installa le dipendenze
npm install

# Avvia l'applicazione
npm start

L'app sarà disponibile all'indirizzo http://localhost:3000 di default.

Tecnologie utilizzate
React + Vite: Per la creazione dell'interfaccia utente dinamica e componentizzata.
TypeScript: Per una tipizzazione sicura e robusta del codice JavaScript.
React Router: Per la gestione della navigazione all'interno dell'app.
Tailwind CSS: Per lo styling flessibile e reattivo dell'interfaccia.
Fetch API: Per effettuare chiamate HTTP e ottenere i dati da servizi REST.
