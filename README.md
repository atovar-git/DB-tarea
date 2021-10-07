# DB-tarea
Tarea de BBDD del curso FullStack de DH

## Consigna
- 1. Definicion de relaciones y 5 ejemplos de c/u (uno a uno / uno a muchos / muchos a muchos).
- 2. Investigar qué es un SGBD (cuales son los mas famosos). 
- 3. En que se diferencian las BBDD relacionales y las no relacionales.

1)

Las relaciones de bases de datos son asociaciones entre tablas que se crean utilizando SENTENCIAS DE UNION para recuperar datos.

Indica cómo se relacionan las distinta tablas dentro de la base de datos, para esto se utiliza un sistema de claves (o identificadores) donde la clave de una tabla apunta a la tabla relacionada.

### Relaciones de bases de datos:

- Unívoca (uno a uno): las dos tablas pueden tener sólo un registro en cada lado de la relación.

Cada valor de clave primaria se relaciona con sólo un (o ningún) registro en la tabla relacionada.

La mayoría de relaciones unívocas están impuestas por las reglas de negocio y no fluyen con naturalidad a partir de los datos. Sin este tipo de regla, generalmente podrá combinar ambas tablas sin incumplir ninguna regla de normalización.

- Uno a varios: la tabla de claves primaria sólo contiene un registro que se relaciona con ninguno, uno o varios registros en la tabla relacionada.

- Varios a varios: 	cada registro en ambas tablas puede estar relacionado con varios registros (o con ninguno) en la otra tabla. 

Estas relaciones requieren una tercera tabla, denominada tabla de enlace o asociación, porque los sistemas relacionales no pueden alojar directamente la relación.

#### Ejemplo:

#### Unívoca (uno a uno):
- Persona - Pasaporte
- Auto - Patente
- Producto - Código de barra
- Presidente - País
- Doctor - MAtrícula

#### Uno a varios:
- Empresa - Empleados
- Persona - Tarjeta de crédito
- Escritor - Libros
- Usuario - Celulares
- Músico - Canciones

#### Varios a varios:
- Peliculas – Actores
- Alumnos– Materias
- Clubes – Socios
- Usuarios – Redes social
- Profesores - Cursos

2)

Un sistema gestor de bases de datos (SGBD) es un software del sistema para crear y administrar bases de datos. Esta solución brinda a los usuarios y programadores una forma sistemática de crear, recuperar, actualizar y administrar su información almacenada dentro de la base.

Ejemplos: SQL Server, MySQL, Oracle Database, MongoDB, Cassandra, Microsoft Access.

3)

Las bases de datos relacionales organizan su información en partes pequeñas y las cuales se relacionan con un identificador y de forma directa.

Las bases de datos no relacionales no tienen un identificador que permita relacionarlas y no siguen el sistema de filas y columnas.
