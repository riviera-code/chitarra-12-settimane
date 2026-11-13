# Chitarra in 12 settimane

App web statica in italiano, tutta in `index.html` (HTML, CSS e JS senza dipendenze, solo Google Fonts).
Pubblicata con GitHub Pages dal branch `main`: https://riviera-code.github.io/chitarra-12-settimane/

- Ogni push su `main` aggiorna il sito in un paio di minuti.
- Quando cambia un file in cache offline, aumenta la versione di `CACHE` in `sw.js`.
- Esiste anche una copia come Artifact su claude.ai (https://claude.ai/artifact/QTBP4Pcb6J2mX3Yhyo5TVJ), uguale al primo commit e non si aggiorna da sola. La fonte principale è questo repository.
- I progressi dell'utente stanno in `localStorage` con chiave `chitarra12-v1`: non cambiarne la forma senza migrare i dati.
- Il codice dei testi usa `applyNote()` per convertire i nomi degli accordi: va chiamata una sola volta per nodo appena renderizzato. Le parti che non vanno convertite hanno `data-nonote`.
