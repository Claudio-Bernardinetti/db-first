# Car Shop Database

## Table name

- used_cars

## Table  colums

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- make | VARCHAR(50), NOT NULL
- model | CHAR(13), NOT NULL, UNIQUE
- year | YEAR, NULL
- mileage | SMALLINT, NULL
- price | DECIMAL(7, 2), NULL // 99999,99
- color | TEXT, NULL
- vote | FLOAT(2,1), DEFAULT(0) // 9.9
- is_available | TINYINT, DEFAULT(0)
- location | VARCHAR(10) 
- fuel_typr | VARCHAR(50)


- condition (not here)

