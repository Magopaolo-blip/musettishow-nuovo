# MusettiShow — nuova homepage

Sito statico, pronto per GitHub Pages.

## Idea centrale
Non quattro personaggi separati, ma **un solo autore e quattro linguaggi**:
- Mentalismo
- Close-up
- Bubble Experience
- Tarocchi

Il sito parte dall'identità di Paolo e poi porta il visitatore a scegliere l'esperienza più adatta al proprio evento.

## Prima di pubblicare
Apri `index.html` e cerca:

`const WHATSAPP_NUMBER = "39XXXXXXXXXX";`

Sostituisci `39XXXXXXXXXX` con il numero WhatsApp corretto, solo cifre e con prefisso internazionale.

Esempio:
`393331234567`

## Pubblicazione su GitHub Pages
1. Crea un nuovo repository su GitHub.
2. Carica `index.html` nella root del repository.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona `main` e cartella `/root`.
6. Salva.
7. GitHub mostrerà l'indirizzo pubblico del sito.

## Dominio personalizzato
Quando vorrai collegare `musettishow.it`, fallo dopo aver verificato bene la nuova versione sul dominio GitHub Pages.

## Foto
Questa versione è volutamente funzionante anche senza fotografie, perché la nuova identità deve emergere prima dalle parole e dalla struttura.

In una seconda fase conviene inserire:
- una foto forte di Paolo nella hero;
- una foto per ENTANGLED;
- una foto close-up;
- una foto Bubble Experience;
- una foto Tarocchi.

Meglio **foto reali di Paolo** che immagini stock.

## Modifiche rapide
Tutto il sito è contenuto in un solo file: `index.html`.
CSS e JavaScript sono già inclusi, quindi per GitHub basta caricare quel file.
