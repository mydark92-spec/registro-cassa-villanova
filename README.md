# Registro di cassa - Circolo Tennis Villanova

Piccola cassa web per registrare campi e articoli, indicare il campo di gioco e il nome del cliente, distinguere pagamenti in contanti e POS, calcolare il resto in base ai tagli disponibili, chiudere la giornata e scaricare i resoconti.

## Avvio

Aprire `index.html` con un browser. Il logo deve restare nella stessa cartella della pagina.

## Dati

Fondo cassa e movimenti sono salvati nel browser utilizzato. Non vengono sincronizzati con GitHub né trasferiti tra dispositivi o browser. Usa **Scarica backup** per salvare un file JSON completo e **Ripristina da file** per recuperarlo in seguito. Conserva il backup anche fuori da questo dispositivo.

## Chiusura giornaliera

**Chiudi cassa** salva l'orario di chiusura, scarica il resoconto e blocca nuovi incassi fino al giorno successivo. **Riapri cassa** consente di correggere la giornata; lo storico rimane invariato.

## Prezzi

I prezzi sono impostati secondo le tariffe fornite dal circolo. L'importo Under 18 è registrato come articolo da 6,00 €.
