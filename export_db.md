# Tarea en Clase semana 8

## La función count

### Creación de la tabla 

El siguiente código genera la tabla **client**:
```sql
CREATE TABLE client (
    id SERIAL,
    nui VARCHAR (10) NOT NULL,
    fullname VARCHAR (100) NOT NULL,
    phone VARCHAR (10),
    type_of_client VARCHAR (10) DEFAULT 'BASIC',
    city VARCHAR (10), 
    credit_limit DECIMAL(7,2),
    PRIMARY KEY (id)
);
