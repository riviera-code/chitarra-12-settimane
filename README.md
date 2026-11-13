# Chitarra in 12 settimane

Un'app web per imparare a strimpellare e accompagnare canzoni con la chitarra acustica in 12 settimane.

**Sito:** https://riviera-code.github.io/chitarra-12-settimane/

## Cosa contiene

- **Percorso** di 12 settimane: accordi nuovi, routine del giorno, traguardi da spuntare e giorni praticati.
- **Sessione guidata**: ti accompagna passo per passo nella routine con timer, metronomo e accordi già impostati.
- **Spiegazione vocale** della settimana 1, con trascrizione (voce generata con ElevenLabs).
- **Accordi**: 17 diagrammi con diteggiatura e ascolto. Nomi in notazione internazionale, italiana o entrambe.
- **Esercizi**: test dei cambi di accordo in un minuto con storico, pattern ritmici, esercizi da ripetere.
- **Metronomo**: pattern suonati con la chitarra, cambi di accordo a tempo, swing, capotasto.
- **Accordatore**: toni di riferimento e accordatore con microfono.

I progressi si salvano nel browser del dispositivo che usi.

## File

| File | Cosa fa |
|---|---|
| `index.html` | L'intera app: struttura, stile e codice |
| `manifest.webmanifest`, `icon*` | Installazione sul telefono come app |
| `sw.js` | Funzionamento offline |

## Aggiornare il sito

Modifica i file, poi:

```bash
git add -A && git commit -m "Descrizione della modifica" && git push
```

GitHub Pages pubblica la nuova versione in un paio di minuti.
