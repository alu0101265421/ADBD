## Historial de comandos
- CREATE USER miusuario
- ALTER ROLE miusuario WITH password '123456'
- \l
- \c dbname miusuario
- \c dbname template0
- \dt
- \?
- \s
- \i
- CREATE DATABASE pract1 WITH OWNER miusuario;
- CREATE DATABASE pract1 WITH OWNER miusuario
- CREATE TABLE USUARIOS(
  Nombre varchar(30),
  Clave varchar(10))
- \s
- INSERT INTO USUARIOS(Nombre, Clave) values('lsa','asdf')
- \l
- \d
- \d USUARIOS
- INSERT INTO USUARIOS(Nombre, Clave) values('Pablo','jfx344')
- INSERT INTO USUARIOS(Nombre, Clave) values('Ana','tru3fal')
- SELECT * FROM USUARIOS
- ;
