# Live Click Pro

Metronomo per il live, con scaletta, cambi di tempo e comandi vocali. È una Progressive Web App: si apre nel browser e si può installare sul telefono.

**Apri l'app:** https://stefanobera92-create.github.io/live-click-pro/

## Installazione sulla schermata Home

### Android (Chrome)

1. Apri il link qui sopra in Chrome.
2. Tocca il menu (tre puntini) e scegli **Aggiungi a schermata Home** oppure **Installa app**.
3. Conferma. L'icona di Live Click Pro compare tra le app.

### iPhone e iPad (Safari)

1. Apri il link qui sopra in Safari.
2. Tocca **Condividi** (il quadrato con la freccia).
3. Scegli **Aggiungi a Home**.
4. Conferma con **Aggiungi**.

Dopo il primo caricamento l'app resta disponibile anche offline e si apre a schermo intero. Se l'app è già installata, all'uscita di una nuova versione compare il tasto **Ricarica**.

## Pre-conteggio

Prima della battuta 1 si possono far sentire delle battute di ingresso, sempre da 4 colpi, al tempo di partenza del brano. È acceso di default con **2 battute**: le prime per sentire il tempo, l'ultima con un click più alto per contare con le bacchette. Sul pannello compare `PRE 1/2`, poi `PRE 2/2`. Si può scegliere **0, 1, 2 o 4** battute, oppure spegnere il pre-conteggio. La scelta resta sul telefono e nel file di backup. Comandi vocali e cambi di tempo restano sulla battuta del brano: niente scatta durante il pre-conteggio.

## Cambi di tempo

In **Cambi di tempo** si può mettere più di un cambio nello stesso brano, in ordine di battuta. Per ognuno: dalla battuta N, il nuovo BPM, di colpo (**istantaneo**) oppure in **rampa** su un certo numero di battute. **Torna al tempo iniziale** scrive il BPM di partenza del brano, per esempio per tornare al tempo originale più avanti. Durante il pezzo il numero grande è il BPM di quel momento e sotto c'è il prossimo cambio (per esempio «Prossimo: 140 BPM a battuta 33»). Il pre-conteggio resta sempre al tempo di partenza.

## Backup della scaletta

Sotto la scaletta c'è la sezione **Backup**.

- **Esporta scaletta** crea un file `scaletta-live-click-AAAA-MM-GG.json` con brani, BPM, cambi di tempo e comandi vocali (l'audio è dentro il file). Sul telefono, se il sistema lo permette, il file si condivide (WhatsApp, Drive e simili); altrimenti viene scaricato.
- **Importa scaletta** legge quel file. Puoi sostituire la scaletta attuale oppure aggiungere i brani. I comandi vocali tornano nella memoria del telefono.
