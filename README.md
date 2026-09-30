# Circuit Construction Kit: DC — Creatività

Versione modificata della simulazione open-source **Circuit Construction Kit: DC** di PhET Interactive Simulations (University of Colorado Boulder), con l'aggiunta di una terza schermata, **Creatività**, pensata per sperimentare liberamente con circuiti elettrici e componenti "fuori standard".


## Cosa aggiunge rispetto all'originale

- **Pulsante cestino** accanto a qualsiasi componente selezionato, in ogni schermata: elimina e scollega l'elemento con un click.
- **Nuova schermata "Creatività"**, con un pannello impostazioni avanzate molto più configurabile:
  - Componenti indistruttibili (niente fusibili che saltano o lampadine che si bruciano)
  - Intervalli min/max personalizzabili per resistenza, tensione, ecc.
  - Disattivazione di animazioni ed effetti fuoco
  - Colore della luce delle lampadine personalizzabile
- **Nessun limite** al numero di componenti piazzabili (fino a 999 per tipo)
- **Oggetti creativi** con comportamenti unici legati alla corrente:
  - 🦆 Paperella — cambia colore al passaggio di corrente
  - 🍔 Hamburger — lampeggia (resistenza ad intermittenza)
  - ⚡ Fulmine — batteria ultra potente, niente si brucia finché è nel circuito
  - 🔦 Torcia — bagliore di fiamma, consumo inferiore a una lampadina
  - 💧 Bottiglia d'acqua chiusa — corto circuito che manda in "caos" le altre correnti del circuito
  - 🐌 Cavo lento — grigio/nero, dimezza la velocità delle cariche animate
  - 🌀 Ventilatore — le pale girano più veloce con più corrente
  - 🪩 Sfera da discoteca — cicla colori mentre passa corrente
  - 🌡️ Termometro — la colonnina sale/scende con il calore accumulato dalla corrente nel tempo
  - 🚦 Semaforo — cicla rosso/giallo/verde a tempo, e la resistenza cambia col colore
- **Slider di resistenza** per tutti gli oggetti con resistenza fissa (ventilatore, sfera, termometro, papera, torcia, bottiglia, moneta, graffetta, matite), come per resistore e lampadina
- Vari bug fix (crash al Reset con certe combinazioni di componenti, errore di zoom/scorrimento all'apertura)

## Come si usa

Non serve installare nulla: scarica il file HTML della build (`circuit-construction-creativita_it.html` per l'italiano, `_en.html` per l'inglese) e aprilo con un browser.

## Crediti

Basato su [Circuit Construction Kit: DC](https://github.com/phetsims/circuit-construction-kit-dc) di **PhET Interactive Simulations**, University of Colorado Boulder, rilasciato sotto licenza [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

Questo progetto non è affiliato né approvato da PhET o dalla University of Colorado Boulder.

## Licenza

Questo lavoro derivato è rilasciato, come richiesto dalla licenza originale, sotto **[CC BY-NC 4.0](LICENSE)** — Attribuzione, Non commerciale.
