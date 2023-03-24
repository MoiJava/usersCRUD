Para que funcione, debe haberse creado el usuario alumno con contraseña alumno.
Y también la BD "dbjoes" con la siguiente tabla:

CREATE TABLE users (
  ID int(11) NOT NULL AUTO_INCREMENT,
  NAME varchar(50) DEFAULT NULL,
  AGE int(11) DEFAULT NULL,
  CITY varchar(50) DEFAULT NULL,
  PRIMARY KEY (ID)
) ENGINE=InnoDB AUTO_INCREMENT=4;
 
 
INSERT INTO users (ID,NAME,AGE,CITY) VALUES 
 (1,'Juan',25,'Valencia'),
 (2,'Ana',30,'Madrid'),
 (3,'Pedro',25,'Zaragoza');

Parámetros de conexión por defecto: 127.0.0.1 y puerto 3307
(MV en modo NAT con VirtualBox)