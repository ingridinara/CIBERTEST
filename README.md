[![Generic badge](https://img.shields.io/badge/<SUBJECT>-<STATUS>-<COLOR>.svg)](https://shields.io/)
[![GitHub contributors](https://img.shields.io/github/contributors/Naereen/StrapDown.js.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/contributors/)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![Badge for version for Visual Studio Code extension naereen.makefiles-support-for-vscode](https://vsmarketplacebadge.apphb.com/version/naereen.makefiles-support-for-vscode.svg)](https://marketplace.visualstudio.com/items?itemName=naereen.makefiles-support-for-vscode)
<br />



# CIBERTEST :computer:


## El proceso es el siguiente 

#### *1-     Subir la rama master o main  al comienzo de los ejercicios.* 
<br />

1.1 Crear el repositorio de GitHub SIN el archivo README


1.2 ``` $ git commit -m "[descriptive message]" ``` Para empaquetar el archivo 


1.3 ``` $ git branch -M main ``` Este comando cambia el nombre de Master para Main 


1.4 ```$ git remote add origin https://github.com/ingridinara/CIBERTEST.git```Paso para asociar tu carpeta del ordenador a la url de git hub 


1.5 ```$ git push -u origin main``` Carga todos los commits de la rama local al Git Hub 



#### *2-	Crear una rama con vuestros desarrollos.*
<br />

2.1
```$ git branch desarrollo ``` Para crear una rama nueva que se llama desarrollo  en LOCAL 


2.2 ```$ git checkout desarrollo ```  Es para ir a la rama desarrollo si estas en la rama main



#### *3-	Hacer commit y push con los cambios a la rama creada.*
<br />

3.1- 
```$ git add .```  Primero tienes que hacer un cambio, luego haces git add.
Comando para adicionar el cambio en la rama 

3.2-
``` $ git commit -m "[descriptive message]"``` Comando para adicionar el cambio en la rama 


3.3-
```$ git status ``` Si quieres ver el status 

3.4- 
``` $ git push  - u origin desarrollo``` Desarrollo es el nombre de la rama creada
_-u = upstream_ Carga todos los commits de la rama local al GitHub



#### *4-	Cuando acabéis, tendríais que invitar al usuario itacademyReact al repo del ejercicio.*
<br />

4.1- 
__GitHub / REPOSITORIO / MANAGE ACCESS / NOMBRE DEL USUARIO A QUIEN VAS A INVITAR__
La persona recibe un email para aceptar 



#### *5-	Crear pull request de la rama con el desarrollo a master, poniendo como persona encargada de la corrección a  itacademyReact*
<br />

5.1- 
``` $ git clone [url]``` La persona acepta la invitacion y clona el proyecto para hacer cambios
(Aquí hubo una discursion si hay que hacer git clone o git pull?)

__Nota de comando que puedes utilizar en la consola en este punto:__

 _LS_
 _CD  NombreDelProyectoEj.CIBERTEST_
 
 _CIBERTEST(nombre de la carpeta)_
 
 _CD CIBERTEST (para entrar en el directorio)_
 
 _``` code.```  – sirve para abrir_
 
 _DIR (para ver lo que hay dentro del directorio)_

#### *6-	Os reviso el código y pongo comentarios en el pull request.*
<br />

6.1-
``` $ git pull ``` 
Descarga el historial del marcador e incorpora cambios
Nota: pull seria mas o menos como un F5, actualizar

#### *7-	Modificáis el código y hacéis commit+push*
<br />

7.1- 
``` $ git add .``` 
Hacer cambio antes + git add
7.2- 
``` $ git commit -m "[descriptive message]"``` 

7.3- 
``` $ git push  - u origin desarrollo``` 


#### *8-	Vuelvo a revisar, y hago más comentarios  o  lo doy por valido y acepto pull request*
<br />

8.1- En el GitHub:

- [ ] Pull request 

- [ ] Merge pull request 

- [ ] Te aparece la informacion que puedes elimitar la rama 
