# CARS TABLE

# Memorizzare i dati delle auto usate messe in vendita da un concessionario

| NAME         | TYPE          | ATTRIBUTES                           | KEY     |
| ------------ | ------------- | ------------------------------------ | ------- |
| id           | BIGINT(20)    | NOT NULL - AUTO_INCREMENT - UNSIGNED | PRIMARY |
| brand        | VARCHAR(30)   | NOT NULL                             |         |
| model        | VARCHAR(40)   | NOT NULL                             |         |
| year         | YEAR          | NOT NULL                             |         |
| car_plate    | CHAR(7)       | NOT NULL                             | UNIQUE  |
| car_km       | INT           | NOT NULL                             |         |
| price        | DECIMAL(8, 4) | NOT NULL - UNSIGNED                  |         |
| fuel         | ENUM          | NOT NULL                             |         |
| transmission | ENUM          | NOT NULL                             |         |
| color        | VARCHAR(20)   | NOT NULL - DEFAULT("White")          |         |
| date_added   | DATETIME      | CURRENT_TIMESTAMP()                  |         |
| description  | TEXT          | NULL                                 |         |
