# projectExercice_B
This is a DGP exercise where we start with Git and GitHub repositories.


 Primera parte : Haremos uso de GitHub como repositorio central, tal y como se usa realmente.
1. --
2. Clona el repositorio:
    $ git clone https://github.com/USERNAME/projecttwo
3. --
4. Ahora te puedes traer a tu repositorio local el trabajo de tu compañero:
        $ git fetch
$ git rebase
5. Haz cambios en exactamente la misma parte del código que tu compañero.
6. --
7. Haz add , commit , fetch y rebase . ¡Ahora toca arreglar conflictos ! Cuando estén cuando estén
solucionados:
    $ git rebase --continue
    $ git push
8. --

Segunda parte : Pondremos en práctica la parte social, crear un issue y hacer un pull request .
1. Realiza un issue en el repositorio de tu compañero:
2. --
3. Crea una rama local , por ejemplo, fix/issue :
    $ git branch fix/issue
    $ git checkout fix/issue
4. Realiza los cambios necesarios, y haz add , commit y push . Al no existir la rama tendrás que
hacer el siguiente push :
    $ git push -u origin fix/issue
5. Realiza un pull request en el repositorio de tu compañero:
6. Selecciona correctamente el origen y el destino ( base y compare ). En el último paso del pull
request puedes añadir una descripción.
7. --
