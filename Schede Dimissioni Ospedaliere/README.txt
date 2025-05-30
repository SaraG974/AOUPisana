#Dataset: Schede Di Dimissioni Ospedaliere Per Gruppo Diagnostico Correlato 2024

## Descrizione
Il presente dataset riporta il numero di ricoveri relativi ai **Gruppi Diagnostici Correlati (DRG)** registrati dall’Azienda Ospedaliero-Universitaria Pisana (AOUP) per l’anno **2024**.

Contiene:
- Il nome del DRG (diagnosi/intervento)
- Il numero assoluto di ricoveri associati
- Una classificazione qualitativa (bassa/media/alta) basata sul volume di ricoveri, utile per confronti e visualizzazioni aggregate

---

## Struttura del Dataset

| Colonna                    | Descrizione                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `Gruppo Diagnostico Correlato` | Descrizione del DRG (Diagnosi o Intervento principale associato al ricovero) |
| `Numero Di Ricoveri`       | Totale dei ricoveri associati al DRG per il 2024                            |
| `Frequenza Ricovero`       | Classe qualitativa della frequenza: **Bassa**, **Media** o **Alta**, calcolata tramite binning sui valori numerici |

---

## Classificazione Frequenza Ricovero

La colonna `Frequenza Ricovero` è una variabile derivata, ottenuta suddividendo i ricoveri in 3 fasce secondo la seguente logica:

| Etichetta | Intervallo (Numero di Ricoveri) |
|----------|-------------------------------|
| Bassa    | da 1 a 33                     |
| Media    | da 34 a 99                   |
| Alta     | da 100 a 2973                |

Questa classificazione consente di:
- Semplificare l’interpretazione della variabile numerica
- Facilitare analisi comparative tra gruppi
- Supportare la modellazione predittiva o aggregazioni visive

---

## Periodo di Riferimento
**Anno 2024**

## 🏥 Fonte
**Azienda Ospedaliero-Universitaria Pisana (AOUP)**

## 📄 Formato File
- **Tipo**: CSV (Comma-Separated Values)
- **Separatore**: `,` (virgola)
- **Encoding**: UTF-8
- **Compatibilità**: Excel, Google Sheets, Python (pandas), R, strumenti BI

---

## Autore
**AOUPisana**

## Licenza
**CC BY 4.0 – Creative Commons Attribution 4.0 International**
È consentito:
- **Utilizzare** il dataset
- **Condividerlo** e **modificarlo**
- **Adattarlo** anche per fini commerciali
A condizione di citare la fonte: *AOUPisana*

---

## Finalità e Applicazioni
Il dataset può essere utilizzato per:
- Analisi della distribuzione dei ricoveri per tipologia di diagnosi/intervento
- Identificazione di DRG ad alta pressione assistenziale
- Supporto a decisioni organizzative e pianificazione sanitaria
- Studio di carichi di lavoro ospedalieri per reparto o specialità

---

## Nome del File
`Schede Di Dimissioni Ospedaliere 2024.csv`

---
