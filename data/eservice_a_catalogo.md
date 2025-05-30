
# Totale richieste di accesso

## Aggiornamento dati

- Quotidiano, alle 6:45 (UTC).

## Formato dati

**Reference file:**

- eservice_a_catalogo.csv<br>

| Campo                    | Tipo di dati | Descrizione                                                      | Formato |
| ------------------------ | ------------ | ---------------------------------------------------------------- | ------- |
| id                       | string       | Id dell'e-service su PDND Interoperabilità                       |         |
| name                     | string       | Nome dell'e-service                                              |         |
| description              | string       | Descrizione dell'e-service                                       |         |
| technology               | string       | Tecnologia dell'API: REST o SOAP                                 |         |
| producerId               | string       | Id dell'ente erogatore su PDND Interoperabilità                  |         |
| producerName             | string       | Nome dell'ente erogatore                                         |         |
| producerFiscalCode       | string       | Codice fiscale dell'erogatore (se non presente nell'indice IPA)  |         |
| producerIpaCode          | string       | Codice IPA dell'erogatore (se presente nell'indice IPA)          |         |
| attributes               | array        | Attributi posseduti dall'ente su PDND Interoperabilità           |         |
| activeDescriptorId       | string       | Id della versione di e-service a catalogo                        |         |
| activeDescriptorState    | string       | Stato della versione di e-service a catalogo                     |         |
| activeDescriptorVersion  | string       | Numero della versione di e-service a catalogo                    |         |

Questi dati sono disponibili anche in formato json.
