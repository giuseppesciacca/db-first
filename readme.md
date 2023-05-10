# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

- id (SMALLINT, PRIMARY_KEY, NOT NULL, UNIQUE, AUTO_INCREMENT)
- marca (VARCHAR(40), NOT NULL)
- modello (VARCHAR(60), NULL)
- km (MEDIUMINT, NOT NULL)
- anno (YEAR, NOT NULL)
- prezzo (DECIMAL(8,2), NOT NULL) <!-- 999.999,99 -->
- carburante (VARCHAR(10), NOT NULL)
- colore (VARCHAR(30), NULL)
- regione (VARCHAR(50), DEFAULT(SICILIA))
- provincia (VARCHAR(50), DEFAULT(TP))
- comune (VARCHAR(30), NOT NULL, DEFAULT(TP))

p.es. di default la città, provincia e regione del luogo dove è sito il concessionario