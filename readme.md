# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

- id (SMALLINT, PRIMARY_KEY, NOT NULL, UNIQUE, AUTO_INCREMENT)
- marca (NOT NULL)
- modello (NULL)
- km (MEDIUMINT, NOT NULL)
- anno (YEAR, NOT NULL)
- prezzo (MEDIUMINT, NOT NULL)
- carburante (NOT NULL)
- colore (NULL)
- regione (DEFAULT(SICILIA))
- provincia (DEFAULT(TP))
- comune (NOT NULL, DEFAULT(TP))    <!-- p.es. di default la città, provincia e regione del luogo dove è sito il concessionario -->