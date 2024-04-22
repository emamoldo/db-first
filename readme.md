Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.


DB_NAME: car_dealer

Table name: used_cars

- id | INT or BIGINT | AUTO_ICREMENT
- car | VARCHAR(20) | UNIQUE
- model | VARCHAR(25) | UNIQUE
- year | YEAR | 
- its_avaible | TINYINT |
- condition | VARCHAT(50) |
- note | TEXT | 