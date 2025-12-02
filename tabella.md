Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Nome tabella: Macchine (nome entità: Macchina)

Colonne:

-id NOTNULL UNIQUE
-Marca NOTNULL VARCHAR(33)
-Modello NOTNULL VARCHAR(20)
-Posti NULL TINYINT
-Porte NULL TINYINT
-Anno NOTNULL YEAR
-Carburante NOTNULL VARCHAR(25)
-Classe_Euro NOTNULL TINYINT
-cambio NOTNULL VARCHAR(10)
-Trazione NOTNULL VARCHAR(10)
-Cavalli NOTNULL SMALL
-Cilindrata NOTNULL SMALL
-Proprietari NOTNULL TINYINT
-Per_Neopatentati NULL CHAR(2)
-Peso_a_Vuoto NOTNULL SMALL
-colore NOTNULL VARCHAR(28)
-Descrizione NULL TEXT
-disponibile_subito NULL CHAR(2)
-Prezzo NOTNULL MEDIUMINT
-creato DEFAULT(now()) DATETIME
-aggiornato DEFAULT(now()) DATETIME