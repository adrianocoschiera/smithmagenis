# Smith-Magenis Oggi
Replica grafica e funzionale del sito Klinefelter Oggi, adattata a Smith-Magenis.

Destinazione: `adrianocoschiera/smithmagenis` (branch `main`).
Dominio: `www.sindromedismithmagenis.it`.

## Pubblicazione
Caricare i file nella root del repository senza eliminare gli articoli esistenti.
Il sito usa GitHub Pages / Jekyll e mostra automaticamente:
- file con front matter dentro `_posts/` (es. `2026-10-14-titolo.html`)
- file Markdown con front matter dentro `_articoli/`

ATTENZIONE: nel repository attuale ci sono file Markdown in `articoli/` **senza front matter**.
Questi non vengono automaticamente mostrati dalla homepage: occorre migrarli a `_articoli/` aggiungendo front matter
oppure creare un importatore. Il workflow n8n collegato deve scrivere in `_posts/` per i nuovi contenuti.
Non eliminare i file originali.

## GitHub Pages
Il repository è stato rilevato come **privato**. Verificare le condizioni del proprio piano GitHub,
la configurazione Pages, il dominio personalizzato e i record DNS.
La presenza del file CNAME non garantisce che il sito sia online.


## Branding
Il sito usa il logo fornito da Smith Magenis Italia e una palette derivata dai colori del marchio (verde, arancione, fucsia, azzurro e grigio).
