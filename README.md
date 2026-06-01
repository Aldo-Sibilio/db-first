# Schema Tabella: `auto`

| Nome Colonna | Tipo | Attributi | Indice |
|---|---|---|---|
| id | INT | PRIMARY KEY, AUTO_INCREMENT, NOT NULL | PRIMARY |
| marca | TEXT | NOT NULL | INDEX |
| modello | TEXT | NOT NULL | |
| carrozzeria | TEXT | NOT NULL | |
| anno | INT | NOT NULL | |
| colore | TEXT | NOT NULL | |
| chilometri | INT | NOT NULL | |
| carburante | TEXT | NOT NULL | |
| cilindrata | INT | NOT NULL | |
| cavalli | INT | NOT NULL | |
| cambio | TEXT | NOT NULL | |
| porte | INT | NOT NULL | |
| targa | TEXT | NOT NULL, UNIQUE | UNIQUE |
| danni | TEXT | NULL | |
| prezzo | DECIMAL(10,2) | NOT NULL | |
| disponibile | BOOLEAN | NOT NULL, DEFAULT TRUE | |
| creato_il | DATETIME | NOT NULL, DEFAULT CURRENT_TIMESTAMP | |