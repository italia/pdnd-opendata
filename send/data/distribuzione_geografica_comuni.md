
# Distribuzione geografica dei Comuni su SEND

Il file riporta, per ciascuna regione italiana, il numero di comuni su SEND, sia in termini assoluti (numero di comuni su SEND), sia in termini percentuali (percentuale di comuni su SEND rispetto al totale dei comuni in una data regione). La distribuzione geografica è riportata sia per anno (ultimi 3 anni), sia complessivamente da inizio storico (indicata con anno = "Complessivo").

## Aggiornamento dati

- Quotidiano, alle 11:00 (UTC).

## Formato dati

**Reference file:**

- distribuzione_geografica_comuni.csv<br>

| Campo               | Tipo di dati | Descrizione                    | Formato               |
| ------------------- | ------------ | ---------------------------    | --------------------- |
| anno                | string       | Anno di riferimento            | YYYY o "Complessivo"  |
| regione             | string       | Regione italiana               |                       |
| numero_comuni       | integer      | Numero di comuni su SEND       |                       |
| percentuale_comuni  | float        | Percentuale di comuni su SEND  | [0;1]                 |

Questi dati sono disponibili anche in formato json.