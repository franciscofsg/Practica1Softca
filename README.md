
## Practica1Softca

## Crear repositorio
1. Se crea un repositorio en nuestro GitHub llamado Practica1Softca

[Crear repositorio](https://github.com/new)

2. Se clona nuestro repositorio en local con el comando

	git clone https://github.com/franciscofsg/Practica1Softca.git

    
## Screenshots

![Screenshot2](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/2.gitclone.png?raw=true)

# README
3. Se crea en nuestro repositorio local un documento README.md con el comando touch README.md, y tambien se crea una carpeta con los screenshots de los comandos usados hasta el momento

## Screenshots

![Screenshot2](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/3.readme.png?raw=true)

4. Añadimos al README.md los comandos utilizados hasta ahora.

![Screenshot4.1](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/4.1.readme.png?raw=true)

5. Hacemos un commit inicial con el mensaje commit inicial.

![Screenshot5](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/5.inic.png?raw=true)

6. Subimos los cambios al repositorio remoto.

![Screenshot6](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/6.push.png?raw=true)

				## Ignorar archivos

7. Creamos en el repositorio local un fichero llamado privado.txt.

![Screenshot7](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/7.priv.png?raw=true)

8. Creamos en el repositorio local una carpeta llamada privada.

![Screenshot8](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/8.pri.png?raw=true)

9. Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.

![Screenshot9](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/9.ign.png?raw=true)

10. Añadimos el fichero 1.txt al repositorio local.

![Screenshot10](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/10.fic.png?raw=true)

11. Crear el tag v0.1

![Screenshot11](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/11.tag.png?raw=true)

12. Subimos los cambios al repositorio remoto.

![Screenshot12](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/12.rem.png?raw=true)

    ## Crear una rama v0.2

13. Creamos una rama v0.2

![Screenshot13](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/13.ram.png?raw=true)

14. Posicionamos nuestra carpeta de trabajo en esta rama.

    git checkout v0.2

![Screenshot14](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/14.check.png?raw=true)

## Añadir fichero 2.txt

15. Añadimos un fichero 2.txt en la rama v0.2.
    ~~~
    touch 2.txt
    git add .
    git commit -m "añadido 2.txt"
    ~~~
    
    ## Crear rama remota v0.2

16. Subimos los cambios al repositorio remoto

    git push origin v0.2

![Screenshot16](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/16.pu.png?raw=true)

17. Nos posicionamos en la rama main

    git checkout main

## Merge directo

18. Hacemos un merge de la rama v0.2 en la rama master. 

![Screenshot17](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/18.mer.png?raw=true)
   
## Merge con conflicto

19. En la rama main ponemos Hola en el fichero 1.txt y hacemos commit.
    
    ![Screenshot19](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/19.png?raw=true)

 20. Nos Posicionamos en la rama v0.2 y ponemos Adios en el fichero "1.txt" y hacer commit.

 ![Screenshot20](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/20.png?raw=true)

 21. Nos posicionamos de nuevo en la rama main y hacemos un merge con la rama v0.2

 ![Screenshot21](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/21.png?raw=true)

 ![Screenshot211](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/211.png?raw=true)

 ## Listado de ramas

 22. Listamos las ramas con merge y las ramas sin merge

 git branch --merged

 git branch --no-merged

  ![Screenshot22](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/lis.png?raw=true)

## Borrar rama

23. Creamos un tag v0.2

git tag v0.2 

24. Borramos la rama v0.2

git branch -d v0.2

![Screenshot2324](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/2324.png?raw=true)

## Listado de cambios

25. Listamos los distintos commits con sus ramas y sus tags, para esto usamos el alias list. 

![Screenshot25](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/25.png?raw=true)


 





    






 

