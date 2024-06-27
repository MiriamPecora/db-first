# Consegna: 

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Svolgimento del problema: 

- Divido il diagramma in tre tabelle: quella con gli attributi per il concessionario, quella degli orari di apertura e chiusura e quella per gli attributi delle auto in vendita;
- Inserisco gli attributi del concessionario senza incremento automatico, dal momento che è unico e attribuisco a quasi tutto VARCHAR anzichè CHAR in previsione di un possibile cambio di gestione (nome e indirizzo) o di informazioni (num. di telefono o email);
- Inserisco gli attributi degli orari lavorativi che ho diviso dalla tabella del concessionario per essere più specifica con i tipi di dati;
- Infine, inserisco gli attributi all'interno della tabella dei veicoli.
