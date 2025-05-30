## Metadati del Dataset

## Descrizione del Dataset
Il dataset contiene informazioni relative alle dimissioni registrate dal Pronto Soccorso per l’anno 2024. Include dati su esiti di dimissione, codici associati e numero di accessi, oltre a una variabile derivata che sintetizza gli esiti in categorie significative per facilitare l’analisi e la comprensione dei dati.

## Struttura del Dataset
Il dataset è organizzato in colonne, ciascuna delle quali rappresenta una specifica informazione relativa alle dimissioni di pronto soccorso.

### Colonne e Descrizione

- **Descrizione Esito Dimissione**: Testo descrittivo dell’esito della dimissione.
- **Codice Esito Dimissione**: Codice associato all’esito della dimissione.
- **Numero Di Accessi Pronto Soccorso**: Numero totale di accessi registrati per la combinazione delle altre variabili.
- **Esito Generale**: Categoria sintetica derivata dalla descrizione esito, raggruppata in base a parole chiave; può assumere i seguenti valori:
  - *Uscita Autonoma*: include “Abbandona”, “Dimissione Volontaria”, “Rifiuta Ricovero”
  - *Esito Critico*: include “Deceduto”, “Cadavere”
  - *Ricovero*: include “Ricovero”
  - *Trasferimento*: include “Trasferimento”, “Trasferito”
  - *Dimissioni*: include “Dimissione A Domicilio”
  - *Non Classificato*: nessuna parola chiave corrispondente

## Fonte
**AOUPisana**

## Periodo di Riferimento
**Anno 2024**

## Formato
Il dataset è fornito in formato **CSV** (Comma-Separated Values), con separatore di campo “,” (virgola).
Questo formato è ampiamente compatibile con la maggior parte degli strumenti di analisi dati, fogli di calcolo e ambienti di programmazione.

## Autore
**AOUPisana**

## Licenza
Il dataset è rilasciato sotto licenza **CC-BY 4.0**.

## Utilizzo del Dataset
Il dataset può essere utilizzato per analisi statistiche, monitoraggio degli esiti dei pazienti dimessi dai pronto soccorso e per supportare la pianificazione e l’ottimizzazione dei servizi sanitari.
La categorizzazione degli esiti generali favorisce l’aggregazione dei dati e la comprensione dei principali flussi di dimissione.
