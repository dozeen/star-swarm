# Star Swarm

Gioco arcade per browser di Onofrio Cannone: formazioni di alieni, picchiate, cattura della nave e potenziamenti. Ispirato agli sparatutto arcade classici; progetto non affiliato ai loro produttori.

## Giocare

Apri `index.html` in un browser moderno. Nessuna installazione o compilazione, nessuna dipendenza esterna. Gli effetti sonori sono sintetizzati con Web Audio. Il record viene salvato nel browser.

| Comando | Azione |
| --- | --- |
| Frecce oppure A / D | Movimento |
| Spazio | Spara |
| Spazio tenuto premuto | Raffiche dopo aver sbloccato la mitragliatrice |
| P | Pausa / riprendi |
| R | Nuova partita |
| V | Cambia velocità |
| M | Attiva / disattiva audio |
| C | Attiva / disattiva effetto CRT |

Pulsanti per schermo intero e comandi touch inclusi. Cambiando finestra la partita va in pausa.

## Potenziamenti

- Gli alieni rosa in picchiata valgono punti doppi.
- Con almeno due vite, entra nel raggio del boss viola per farti catturare una nave. Abbatti il boss in picchiata per liberarla e ottenere il doppio cannone.
- Il boss viola resta nascosto con due cannoni e torna dopo la perdita del secondo.
- Con due cannoni appare il boss dorato: colpiscilo quattro volte durante le picchiate per ottenere raffiche doppie e 1.000 punti. Il potenziamento si perde insieme al secondo cannone.

## Pubblicare su GitHub Pages

1. Crea un repository pubblico chiamato `star-swarm` e carica i file di questa cartella, inclusa `.github`.
2. In **Settings → Pages → Build and deployment**, seleziona **GitHub Actions**.
3. Avvia il workflow **Deploy Star Swarm** oppure invia un commit al ramo `main`.
4. Il workflow mostra il collegamento al gioco pubblicato.

Il workflow pubblica solo `index.html` e `favicon.svg`. Non richiede credenziali aggiuntive: usa il token temporaneo di GitHub Actions.

## Privacy e stato

Nessuna telemetria o chiamata di rete da parte del gioco. Il record usa solo localStorage. Le meccaniche sono state controllate con simulazioni JavaScript; il collaudo visivo e su dispositivi touch resta da completare.

## Licenza

Codice distribuito con licenza MIT; vedi [LICENSE](LICENSE). I marchi dei giochi classici appartengono ai rispettivi titolari.
