# OrdonezAlmendraCacao
####BASE DE DATOS
createdb almendracacao
psql almendracacao

create table casoestudio (idcasoestudio SERIAL CONSTRAINT pkeyid PRIMARY KEY,nombre VARCHAR(50),dominio VARCHAR(50),reino VARCHAR(50),phylum VARCHAR(50),clase VARCHAR(50),subclase VARCHAR(50),orden VARCHAR(50),familia VARCHAR(50),genero VARCHAR(50),especie VARCHAR(50),direccion VARCHAR(50));

