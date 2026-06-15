# Day 01 — 🔐 Password Generator

Un generatore di password sicure, single-file, che gira interamente nel tuo browser.

## Caratteristiche
- Lunghezza regolabile (6–40)
- Maiuscole, minuscole, numeri, simboli selezionabili
- Indicatore di robustezza (stima dell'entropia)
- Generazione crittograficamente sicura (`crypto.getRandomValues`)
- Copia negli appunti con un click

## Uso
Apri `index.html` nel browser. Nessuna installazione, nessun account.

## Privacy & sicurezza
- **100% offline**: tutto avviene nel tuo browser, nessun dato lascia il dispositivo.
- **Zero dipendenze esterne**: niente librerie, CDN, font remoti o chiamate di rete.
- **Nessuna raccolta dati**: le password non vengono salvate, registrate (`console`) o inviate da nessuna parte.
- **Casualità sicura**: usa l'API crittografica del browser (`crypto.getRandomValues`), non `Math.random()`.
- Codice breve e leggibile: puoi verificarlo in pochi secondi prima di usarlo.

---
Parte della mia serie *daily-tools*: un piccolo tool ogni giorno.
