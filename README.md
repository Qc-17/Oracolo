# Oracolo

Un oracolo interattivo scritto in [LINE 3.0](https://github.com/qc-17/LINE) e HTML puro.

Consulta la sfera per ricevere un responso: favorevole, oscuro, misterioso — o rarissimo.  
Ogni tanto è l'oracolo a chiedere qualcosa a te.

**[→ Prova dal vivo](https://qc-17.github.io/Oracolo/)**

---

## Come funziona

Tutta la logica è scritta in LINE 3.0 direttamente nell'HTML, tramite il framework **LINE-DOM**.  
Il JavaScript nell'HTML è ridotto al minimo assoluto.

Il responso viene scelto in base a:
- un dado casuale ponderato sull'ora del giorno
- tre livelli di intensità per categoria
- un evento rarissimo (1 su 20)

Ogni tre consulte circa, l'oracolo inverte i ruoli e chiede una domanda a te.

---

## Struttura

```
index.html   — il sito completo (HTML + CSS + LINE)
```

L'interprete LINE e il framework LINE-DOM vengono caricati da CDN:

```html
<script src="https://qc-17.github.io/LINE/interpreter.js"></script>
<script src="https://qc-17.github.io/LINE/line-dom.js"></script>
```

---

## Licenza

Copyright © Qc-17  
Distribuito sotto licenza **GNU General Public License v3.0**  
[https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)
