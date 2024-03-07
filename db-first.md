# Descrizione
- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## "Cars" Table
|FIELD|TYPE|ATTRIBUTES|INDEX|
|-----|----|----------------------------------|-----------|
|id   |INT |NOT NULL, UNSIGNED, AUTO INCREMENT|PRIMARY KEY|
|marca|VARCHAR(12)|NOT NULL|     |
|modello|VARCHAR(15)|NOT NULL|     |
|anno produzione|YEAR |NOT NULL|     |
|cambio|VARCHAR(10)|NOT NULL, DEFAULT(maunuale)|     |
|cavalli|INT|NOT NULL|     |
|nPorte|INT|NOT NULL|      |
|nSedili|INT|NOT NULL|     |
|colore|VARCHAR(20)|NOT NULL|    |
|carburante|VARCHAR(20)|NOT NULL, DEFAULT(benzina)|    |
|prezzo|DECIMAL(6,2)|NOT NULL|   |