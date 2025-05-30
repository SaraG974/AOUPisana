## Metadati del Dataset

## Descrizione del Dataset
Il dataset contiene informazioni relative alle Prestazioni Specialistiche Ambulatoriali erogate nel corso dell'anno 2024.
Include dati sui codici e le descrizioni delle prestazioni, la modalità di accesso e il **Numero Prestazioni Erogate**.
Inoltre, presenta una variabile derivata che aggrega la frequenza di erogazione in categorie significative per facilitare l’analisi e la comprensione dei dati.

## Struttura del Dataset
Il dataset è organizzato in colonne, ciascuna delle quali rappresenta una specifica informazione relativa alle prestazioni specialistiche ambulatoriali.

### Colonne e Descrizione

- **Nuovo Codice Prestazione Catalogo**: Codice identificativo della prestazione specialistica ambulatoriale.
- **Nuova Descrizione Prestazione**: Descrizione testuale della prestazione specialistica ambulatoriale.
- **Accesso**: Modalità di accesso alla prestazione.
- **Numero Prestazioni Erogate**: Numero totale di volte in cui la specifica prestazione è stata erogata.
- **Descrizione Completa Prestazione**: Concatenazione delle prime tre colonne, fornendo una descrizione più estesa della prestazione e della modalità di accesso.
- **Frequenza Erogazione**: Categoria sintetica derivata dal '**Numero Prestazioni Erogate**', raggruppata in base alla frequenza di erogazione; può assumere i seguenti valori:
  - *Bassa*: da 1 a 2 erogazioni
  - *Media*: da 3 a 107 erogazioni
  - *Alta*: da 108 a 181637 erogazioni

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
Il dataset può essere utilizzato per analisi statistiche relative all'erogazione di prestazioni specialistiche ambulatoriali, monitoraggio della frequenza delle diverse tipologie di prestazioni e per supportare la pianificazione e l’ottimizzazione dei servizi sanitari ambulatoriali.
La categorizzazione della **Frequenza Erogazione** favorisce l’aggregazione dei dati e la comprensione dei volumi di attività per diverse fasce di frequenza.