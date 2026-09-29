# Gym Reel

Lettore video verticale per la galleria del telefono. I video si importano una volta, restano
salvati dentro l'app (IndexedDB) e si riproducono in playlist, in ordine o in casuale.

## Pubblicazione su GitHub Pages

1. Su [github.com](https://github.com) crea un nuovo repository **pubblico** chiamato `gym-reel`.
   Non aggiungere README, licenza o `.gitignore`: deve restare vuoto.
2. Nella pagina del repository vuoto clicca **uploading an existing file**.
3. Trascina dentro questi cinque file (i file, non la cartella che li contiene):
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
4. In fondo clicca **Commit changes**.
5. Vai su **Settings** → **Pages**. Alla voce *Source* scegli **Deploy from a branch**,
   ramo `main`, cartella `/ (root)`, e clicca **Save**.
6. Dopo un paio di minuti la app è online a:
   `https://TUONOME.github.io/gym-reel/`

## Installazione sull'iPhone

1. Apri quell'indirizzo in **Safari**.
2. Tocca **Condividi** → **Aggiungi a Home**.
3. Apri l'app dall'icona: si avvia a schermo pieno, senza barre del browser.

## Note

- I video restano sul telefono, dentro l'app. Non vengono caricati da nessuna parte:
  il repository contiene solo il codice.
- Il repository è pubblico, quindi chiunque può vedere e usare la app — ma non i tuoi video,
  che non escono mai dal telefono.
- Per aggiornare la app: carica di nuovo `index.html` sul repository e aumenta il numero
  della cache in `sw.js` (`gym-reel-v1` → `gym-reel-v2`).
