![](http://banot.etsii.ull.es/alu4103/STW/tictactoe.jpg)

TicTacToe
================================

**Paso 1.** Cogemos la práctica `tictactoe` 

**Paso 2.** Crearemos la BBDD con DataMapper, para ello creamos el fichero `usuarios.rb` donde tendremos el modelo de la BBDD.

**Paso 3.** En `app.rb` crearemos la BBDD y la guardaremos en `development.db`

**Paso 4.** Una vez hecho esto, en el mismo fichero `app.rb` se guardarán las partidas jugadas, ganadas y perdidas del usuario creado.

**Paso 5.** Crearemos las vistas del Ranking en `views/usuarios.haml`

**Paso 6.** Para modificar la apariencia simplemente tenemos que ir a `styles.scss`


##IMPORTANTE##

Si da fallo el sql posiblemente tengas que instalar:
    
    sudo apt-get install libecpg-dev
    sudo apt-get install postgresql-client
    sudo apt-get install postgresql
    
## EJECUCIÓN ##

app.rb

    rake css
    rake

## VISTA ##

    TicTacToe: htpp://localhost:4567
    
    Heroku: http://tictactoe-stw1314.herokuapp.com/

## DESARROLLADOR ##

Madelaine Martin

alu0100537130@ull.edu.es

ETSII. Universidad de La Laguna