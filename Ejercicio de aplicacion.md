# Practica-Dir.-1
# Postgres SQL
CREATE TABLE empleado (
nombre VARCHAR(100) NOT NULL,
fecha_contratación DATE NOT NULL,
salario INT NOT NULL,
departamento VARCHAR(50) NOT NULL,
rol VARCHAR(150) NOT NULL
);

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Luis Enrique Osis', '12/02/2032', 8000, 'Mexico', 'Ejectivo');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Andres Mercado', '17/10/2024', 12000, 'Alemania', 'Administrador');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Julio Martinez', '18/09/2026', 4000, 'Japon', 'Ejectivo');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Francisco Araujo', '02/07/2027', 3000, 'Brasil', 'Empleado');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Pedro Perez', '16/12/2027', 17000, 'Peru', 'Empleado');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Manuel Avellaneda', '23/01/2025', 1500, 'Inglaterra', 'Administrador');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Ivan Salgado', '11/11/2027', 9050, 'USA', 'Ejectivo');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Antonio Contreras', '15/04/2026', 12000, 'Mexico', 'Empleado');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Julio Loayza', '12/02/2032', 20000, 'USA', 'Ejectivo');

INSERT INTO empleado(nombre, "fecha_contratación", salario, departamento, rol)
VALUES ('Ernesto Zunhiga', '12/02/2032', 12050, 'Mexico', 'Administrador');

SELECT * FROM empleado
WHERE salario between 4500 and 15000

SELECT nombre, departamento
FROM empleado

SELECT * FROM empleado
WHERE departamento is 'Mexico' or 'USA'

SELECT * FROM empleado
WHERE departamento is 'Inglaterra'
