<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. -->

VENDITA AUTO USATE

- id                            BIGINT              NOTNULL / PRIMARY KEY
- marca                         VARCHAR(30)         NOTNULL
- modello                       VARCHAR(30)         NOTNULL
- anno_di_immatricolazione      YEAR                NULL
- kilometri                     DOUBLE(9,3)         NOTNULL
- prezzo                        DOUBLE(6,3)         NOTNULL
- targa                         VAR(7)              NULL
- colore                        VARCHAR(20)         NOTNULL                   
- alimentazione                 VARCHAR(15)         NOTNULL
- cambio                        VARCHAR(15)         NOTNULL
- porte                         TINYINT             NOTNULL
- interni                       VARCHAR(20)         NULL                
