# Practica-Dir.-1
# Postgres SQL
CREATE TABLE empleado (
codigo_emp VARCHAR(7) NOT NULL,
nombre VARCHAR(100) NOT NULL,
fecha_contratación DATE NOT NULL,
salario INT NOT NULL,
departamento VARCHAR(50) NOT NULL,
pais VARCHAR (50) NOT NULL,
continente VARCHAR (50) NOT NULL,
rol VARCHAR(150) NOT NULL
);

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0001', Luis Enrique Osis', '12/02/2032', 8000, 'Ciudad de Mexico', 'Mexico', 'America', 'Ejectivo');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0002', 'Andres Mercado', '17/10/2024', 12000, 'Berlin', 'Alemania', 'Europa', 'Administrador');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0003', 'Julio Martinez', '18/09/2026', 4000, 'Tokio', 'Japon', 'Asia', 'Ejectivo');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0004', 'Francisco Araujo', '02/07/2027', 3000, 'Brasilia', 'Brasil', 'America', 'Empleado');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0005', 'Pedro Perez', '16/12/2027', 17000, 'Lima', 'Peru', 'America', 'Empleado');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0006', 'Manuel Avellaneda', '23/01/2025', 1500, 'Londres', 'Inglaterra', 'Europa', 'Administrador');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0007', 'Ivan Salgado', '11/11/2027', 9050, 'Los Angeles', 'USA', 'America', 'Ejectivo');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0008', 'Antonio Contreras', '15/04/2026', 12000, 'Toluca', 'Mexico', 'America', 'Empleado');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0009', 'Julio Loayza', '12/02/2032', 20000, 'Nueva York', 'USA', 'America', 'Ejectivo');

INSERT INTO empleado(codigo_emp, nombre, "fecha_contratación", salario, departamento, pais, continente, rol)
VALUES ('EMP0010', 'Ernesto Zunhiga', '12/02/2032', 12050, 'Mazatlán', 'Mexico', 'America', 'Administrador');

SELECT * FROM empleado
WHERE salario between 4500 and 15000

SELECT nombre, departamento
FROM empleado

SELECT * FROM empleado
WHERE departamento is 'Mexico' or 'USA'

SELECT * FROM empleado
WHERE departamento is 'Inglaterra'
