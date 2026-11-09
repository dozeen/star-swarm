# Star Swarm

Gioco arcade per browser di Onofrio Cannone: formazioni di alieni, picchiate, cattura della nave e potenziamenti. Ispirato agli sparatutto arcade classici; progetto non affiliato ai loro produttori.

## Prova il videogioco direttamente sul server Dozeen

🎮 **[▶ GIOCA ORA — Star Swarm sul server Dozeen](https://dozeen.ns0.it/star-swarm/game.html)**

📖 **[Scopri come funziona il gioco: boss, potenziamenti e comandi](https://dozeen.ns0.it/star-swarm/)**

Puoi giocare direttamente dal browser, anche da smartphone, senza scaricare o installare nulla. La pagina di presentazione include anche una versione giocabile incorporata.

## Classifica online sul server Dozeen

Al termine della partita, il giocatore può pubblicare nome, punteggio e, facoltativamente, nome visualizzato su Facebook, con consenso esplicito. La classifica condivisa è disponibile nella [versione sul server Dozeen](https://dozeen.ns0.it/star-swarm/game.html) e mostra i 20 migliori risultati. Il nome Facebook è dichiarato dal giocatore e **non è verificato** tramite Facebook. La versione statica di GitHub Pages non include il servizio server per la classifica.

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

## Versione online e distribuzione

- **Demo sul server Dozeen:** https://dozeen.ns0.it/star-swarm/game.html
- **Presentazione e guida:** https://dozeen.ns0.it/star-swarm/
- **GitHub Pages:** https://dozeen.github.io/star-swarm/

Il repository pubblico contiene il gioco statico. GitHub Pages usa il ramo `main` dalla radice del repository.

## Privacy e stato

Nessuna telemetria o chiamata di rete da parte del gioco. Il record usa solo localStorage. Le meccaniche sono state controllate con simulazioni JavaScript; il collaudo visivo e su dispositivi touch resta da completare.

## Licenza

Codice distribuito con licenza MIT; vedi [LICENSE](LICENSE). I marchi dei giochi classici appartengono ai rispettivi titolari.
