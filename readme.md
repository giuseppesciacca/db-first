### Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
## cars_warehouse.db

- id (SMALLINT, PRIMARY_KEY, NOT NULL, UNIQUE, AUTO_INCREMENT, INDEX)
- marca (VARCHAR(40), NOT NULL, INDEX)
- modello (VARCHAR(60), NULL)
- km (MEDIUMINT, NOT NULL)
- anno (YEAR, NOT NULL, INDEX)
- prezzo (DECIMAL(8,2), NOT NULL, INDEX) <!-- 999.999,99 -->
- carburante (VARCHAR(10), NOT NULL, INDEX)
- colore (VARCHAR(30), NULL)
- regione (VARCHAR(50), DEFAULT(SICILIA))
- provincia (VARCHAR(50), DEFAULT(TP))
- comune (VARCHAR(30), NOT NULL, DEFAULT(TP), INDEX)

p.es. di default la città, provincia e regione del luogo dove è sito il concessionario