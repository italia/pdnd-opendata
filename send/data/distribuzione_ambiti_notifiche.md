
# Distribuzione geografica dei Comuni su SEND

Il file fornisce una ripartizione delle notifiche inviate tramite SEND (Servizio Notifiche Digitali) in base alla categoria di ente e all'ambito di notifica a partire dalla nascita della piattaforma. Sono inclusi i 10 principali ambiti di notifica, classificati in ordine di importanza. I dati possono essere consultati in diverse viste:
* Per ambito e categoria di ente;
* Per ambito (con i dati complessivi per tutte le categorie di ente).

## Aggiornamento dati

- Quotidiano, alle 11:00 (UTC).

## Formato dati

**Reference file:**

- distribuzione_ambiti_notifiche.csv<br>

| Campo             | Tipo di dati | Descrizione                               | Formato               |
| ----------------- | ------------ | ----------------------------------------- | --------------------- |
| categoria_ente    | string       | Categoria dell'ente che invia la notifica |                       |
| ambito            | string       | Ambito della notifica                     |                       |
| numero_notifiche  | integer      | Numero di notifiche                       |                       |
| ranking           | integer      | Ranking                                   | [1;10]                |

Questi dati sono disponibili anche in formato json.