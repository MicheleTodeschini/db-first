Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Nome tabella: Macchine (nome entità: Macchina)

Colonne:

-id NOTNULL UNIQUE
-Marca NOTNULL VARCHAR(33)
-Modello NOTNULL VARCHAR(20)
-Posti NULL VARCHAR(2)
-Porte NULL CHAR(2)
-Anno NOTNULL YEAR
-Carburante NOTNULL VARCHAR(25)
-Classe_Euro NOTNULL CHAR(1)
-cambio NOTNULL VARCHAR(10)
-Trazione NOTNULL VARCHAR(10)
-Cavalli NOTNULL VARCHAR(3)
-Cilindrata NOTNULL VARCHAR(4)
-Proprietari NOTNULL VARCHAR(2)
-Per_Neopatentati NULL CHAR(2)
-Peso_a_Vuoto NOTNULL VARCHAR(4)
-colore NOTNULL VARCHAR(20)
-Descrizione NULL TEXT
-disponibile_subito NULL CHAR(2)
-Prezzo NOTNULL VARCHAR(6)
-creato DEFAULT(now()) DATETIME
-aggiornato DEFAULT(now()) DATETIME