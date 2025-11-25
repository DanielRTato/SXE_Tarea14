## Creacion de la base de datos e instalacion de los modulos

![1.png](img/1.png)
![2.png](img/2.png)

# Apartado 1
create table EmpresasFCT(
	idEmpresa serial,
	nombre varchar(40),
	quiereAlumnos boolean,
	numAlumnos integer,
	fechaContacto date,
	primary key(idEmpresa)
)
![3.png](img/3.png)
---
# Apartado 2
insert into empresasFCT (nombre, quiereAlumnos, numAlumnos, fechaContacto) values
    ('Plastmeca', true, 2, '2025-05-10'),
    ('Cercaplast', false, 0, '2025-05-11'),
    ('Erictega', false, 0, '2025-05-09'),
    ('Hermasa', false, 0, '2025-06-10'),
    ('Plastmeca', true, 1, '2025-03-23');

![4.png](img/4.png)
----


