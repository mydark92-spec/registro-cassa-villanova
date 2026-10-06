# Manuale d'uso della cassa

## 1. Avviare la cassa

1. Tieni `index.html` e `logo_tennis_villanova.jpg` nella stessa cartella.
2. Apri `index.html` con Chrome o Edge.
3. Usa sempre lo stesso browser e computer: movimenti e fondo cassa vengono salvati localmente nel browser e non si sincronizzano con GitHub o con altri dispositivi.

## 2. Impostare il fondo cassa

Prima di registrare pagamenti, nella sezione **Fondo cassa** inserisci il numero di banconote e monete presenti per ogni taglio. Lascia `0` per i tagli che non hai. Il totale del fondo si aggiorna automaticamente.

Aggiorna le quantità se aggiungi o togli contante dalla cassa. Gli incassi POS non modificano questo fondo.

## 3. Registrare un incasso

1. Seleziona **Socio** o **Non socio**.
2. Aggiungi il campo o gli articoli premendo i relativi pulsanti. Il prezzo viene aggiunto al riepilogo; usa `+` e `−` per cambiare la quantità.
3. Facoltativamente, inserisci il **Nome cliente** e seleziona il **Campo di gioco**. Per gli acquisti senza prenotazione scegli **Non indicato / solo articoli**.
4. Seleziona **Contanti** o **POS**.
5. Controlla il totale e premi **Registra incasso**.

### Pagamento in contanti

Premi una volta ciascun taglio ricevuto dal cliente. La cassa mostra il totale ricevuto e calcola il resto usando i tagli disponibili nel fondo, compreso il denaro appena ricevuto. La schermata indica quanti pezzi di ogni taglio preparare.

Se il resto non è componibile con il denaro disponibile, **Registra incasso** resta disabilitato: aggiorna il fondo o modifica il denaro ricevuto prima di proseguire. **Azzera** cancella solo i tagli inseriti per il pagamento in corso.

### Pagamento POS

Seleziona **POS**: il pagamento viene registrato per l'importo esatto, senza resto e senza modificare il fondo cassa.

Dopo la registrazione, nome e campo vengono svuotati per il pagamento successivo. Il metodo di pagamento, il nome e il campo scelto restano associati al movimento nello storico e nei resoconti.

## 4. Tariffe

| Servizio | Socio | Non socio |
| --- | ---: | ---: |
| Tennis singolo con luce | 10,00 € | 12,00 € |
| Tennis doppio con luce | 12,00 € | 8,50 € |
| Tennis singolo senza luce | 9,00 € | 11,00 € |
| Tennis doppio senza luce | 6,00 € | 8,00 € |
| Padel | 9,00 € | 10,00 € |

| Articolo o quota | Prezzo |
| --- | ---: |
| Under 18 | 6,00 € |
| Tubo palline tennis | 8,50 € |
| Tubo palline padel | 6,50 € |
| Overgrip | 2,50 € |

## 5. Storico e resoconti

- **Incassi di oggi** mostra il totale degli incassi della giornata, sia POS sia contanti.
- **Resoconto oggi** scarica il riepilogo giornaliero con incassi POS, contanti, resto e dettaglio dei movimenti.
- **Tutto lo storico** scarica il CSV di tutti i movimenti registrati.
- **Stampa** apre la funzione di stampa del browser.

## 6. Chiudere la giornata

A fine giornata premi **Chiudi cassa** e controlla il riepilogo di contanti e POS nella richiesta di conferma. Confermando:

- la cassa salva l'orario di chiusura e scarica il resoconto giornaliero;
- il carrello non ancora registrato viene annullato;
- nuovi incassi e modifiche al fondo vengono bloccati fino al giorno successivo.

Per correggere o aggiungere un movimento dopo la chiusura, premi **Riapri cassa** e conferma. Lo storico già registrato non viene cancellato. La giornata successiva si apre automaticamente.

## 7. Backup e ripristino

- Premi **Scarica backup** per salvare un file JSON con movimenti, nomi, campi di gioco, metodi di pagamento, fondo cassa e chiusure.
- Conserva il file fuori dal computer della cassa, ad esempio su una chiavetta o in uno spazio cloud.
- Per recuperare i dati, premi **Ripristina da file**, seleziona il backup e conferma. Il ripristino **sostituisce** i dati presenti nel browser; non li unisce.

I CSV sono resoconti, non backup completi. Scarica regolarmente il JSON per poter recuperare l'intero stato della cassa.
