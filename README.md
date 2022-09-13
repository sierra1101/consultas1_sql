# consultas1.sql

## CONSULTAS SQL

![alt text](/images/cuhoo.png)

1. Para visualizar toda la informacion que contiene la tabla `usuario`s se puede incluir con lainstruccion SELECT el caracter '*' o cada uno de los campos de la tabla

`select * from usuario`
![alt text](/images/CONSULTA1.png)

2. Visualizar solamente la identificación del usuario.
`select Identificacion from usuario`
![consulta 2](/images/consulta2%7D.png "consulta 2")
3. si se desea obtener los registros cuya identificacion sean mayoreso iguales a 150, se debe utulizar la clausula WHERE que espicifica las condiciones que deben reunir los registros que se van a seleccionar.

`SELECT` * FROM usuario WHERE Identificación>=`150`
![consulta 2](/images/consulta3.png)
