
# Project name: CRUD en Python 2.7 y SQLite 3
***
	- Desarrollo de un CRUD (C.L.I.) con Python 2.7 y SQLite 3 en GNU/Linux Debian 8.


## General info
***
Se libera el siguiente código para ser estudiado, reutilizado y redistribuido con sus modificaciones.
	- Junio de 2017 Versión 1 - Profesor Mussis Pablo
	- Script en Python 2.7 como A. B. M. con base de datos en SQlite3. 
	- sobre el sistema de base Debian 8 en estado de prototipo Versión 0.1. 
	- Desarrollado en el laboratorio de la E.E.S.T.N°2 de Florencio Varela Buenos Aires Argentina.
	- Con el propósito práctico profesional.


### Author developer
***
Pablo Mussis
	- gitlab @pablomussis
	- github @pablomussis


### Nota:
***
Para su próxima versión se requiere: 
	- Verificar el sistema operativo base para ejecutar clear en equipos UNIX o cls en M.Windows.
	- Modularizar tareas.
	- Mejorar salida de consulta en la opción 1.

### Estructura de la base de datos
***
Base: 	contacto
Tabla: 	contactos
campos 	id INTEGER PRIMARY KEY AUTOINCREMENT 
		nombre TEXT NOT NULL	(nombre completo)
		contacto TEXT NOT NULL	(email, teléfono movil, etc)

### Ejecución del programa
***
Terminal o símbolos de sistema
$ python main.py