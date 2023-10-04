# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo! Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

COLONNA | TIPO | ATTRIBUTI
-|-|-
marca | varchar(50) | NOT NULL
modello | varchar(50) | NOT NULL


COLONNA | TIPO | ATTRIBUTI
-|-|-
id_auto | bigInt| PRIMARY KEY, AUTO_INCREMENT
brand | varchar(50) | NOT NULL
model| varchar(50) | NOT NULL
color | varchar(20) | NOT NULL
price | DECIMAL(7,2)| NULL
fuel | varchar(1)| NOT NULL
km | DECIMAL (8, 2)| NULL
production_country | char(20) | NOT NULL
manifacture_date | YEAR | NOT NULL
purchased_date | DATE | NOT NULL
sale_date | DATE | NULL
status | char(1) | NOT NULL
