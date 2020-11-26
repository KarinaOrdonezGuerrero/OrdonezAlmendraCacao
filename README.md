# OrdonezAlmendraCacao
####BASE DE DATOS
createdb almendracacao
psql almendracacao

create table casoestudio (idcasoestudio DECIMAL(4),nombre VARCHAR(50),dominio VARCHAR(50),reino VARCHAR(50),phylum VARCHAR(50),clase VARCHAR(50),subclase VARCHAR(50),orden VARCHAR(50),familia VARCHAR(50),genero VARCHAR(50),especie VARCHAR(50),primary key(idcasoestudio));

create table localizacion (idlocalizacion DECIMAL(4),idcasoestudio DECIMAL(4),direccion VARCHAR(50),lote VARCHAR(50),primary key (idlocalizacion),constraint fk_localizacion foreign key (idcasoestudio) references casoestudio (idcasoestudio));
