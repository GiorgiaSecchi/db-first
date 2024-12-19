# CARS TABLE

# Memorizzare i dati delle auto usate messe in vendita da un concessionario

| NAME         | TYPE        | ATTRIBUTES                          | KEY |
| ------------ | ----------- | ----------------------------------- | --- |
| id           | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED |
| brand        | VARCHAR(30) |
| model        | VARCHAR(40) |
| year         | YEAR        |
| mileage      | INT         |
| price        | DECIMAL(?)  |
| fuel         | ENUM        |
| transmission | ENUM        |
| color        | VARCHAR(20) |
| date_added   | DATETIME    |
