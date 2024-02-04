    Explicacion del style_Juan Feliep Rubio Sanabria J1
    
En la primera line puse un *{    font-family: Arial, Helvetica, sans-serif; } : Lo que esto significa el tipo de letra que se va a manejar en toda la pagina.

-En el body puse un background: linear-gradient, esta función sirve para hacer un desvanecido de los colores que el programador utilice, en este caso utilice 3.
-Defini la imagen de la empresa como Logo y le puse un width y heigth, para la altura y el ancho.
-El nobre de la empresa le agregue un:
    display: flex;
    align-items: center;
    margin: 15px;
Para la separacion y ubicacion de esta.

-En items tambien le agregue un:
    display: flex;
    justify-content: space-between;
    margin: 50px;
Para la separacion y ubicacion de esta.

-Para navegador le puese un padding para la separacion de lso elementos, un color: black para que la letra sea de color negra y le defini su tamaño y el largo, ahora para navegador:hover le puse estos codigos:
    border: solid gainsboro;   Este hace un borde solido y el color que se le indica.
    background-color: white;   Este el color se sera visializado dentro de el borde.
    border-radius: 10px;       Este es para quitarle las esquinas a un objeto, en este caso, le indique 10px, que es lo que se le quita a las 4 esquinas.

-El en banner le puse los siguientes codigos:
    border: 5px dashed palevioletred;  Genera un borde y un color que se le esta indicando.
    display: flex;                     El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos. 
    justify-content: center;           Esta fubcion hace que la imagen quede en el centro de la pagina.
    margin: auto;                      Hace que la imagen se centre.
    height: 250px;                     Genera el largo de la imagen.

-Img lo defini a las 3 imagenes principales, las cules poseen un grid-template-columns: 1fr 1fr 1fr; esto hace que se genere una cuadricula
    text-align:center; Centra las imagenes.
    display:block; hace que las iamgenes queden juntas.
    transition: all 0.4s ease-in-out;
img:hover {
    transform: scale(1.05); A la hora de que el cursor pase se acerque la imagen.
}  

-Sorpresa,Peluches y desayunos se le indica un borde de 5px y su respectivo color, igual que el ancho y el largo.

-Para la clasificacion le coloque esotos codigos:
    display: flex;           El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos. 
    justify-content: center; Hace que quede en el centro de la pagina.
    font-size: 25px;         Indica el tamaño de letra de esa clase.

-Para .finalizacion {
    display: grid;                  El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos. 
    justify-content: space-around;  Pone la informacion en el centro de la pagina.
    font-size: 20px;                Indica el tipo de letra de esa clase.
}

-Para .finish {
    display: grid;                      El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos. 
    text-align: center;                 Pone la informacion en le centro.
    grid-template-columns: 1fr 1fr 1fr; Las defini en 3 columnas.
    grid-template-rows: auto;           Hace que para las filas sea automatico.
    padding-top: 35px;                  Separacion de fi alizacion y la informacion.
}

-Para finish1, finish2, finish3 : Le indique un display: grid porque finish es el papá de estas clases. 

-Para decoraciones, desayunos1, llavero, a cada uno se le pone un borde con su respetivo color, tambein un ancho y largo.

-.navegador1 {
    display: flex;                  El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos. 
    justify-content: space-around;  Muestra elementos con la misma separacion. 
    color: black;                   Que la letra sea de colro negra.
    text-decoration: none;          Le quita la decoracion de la letra que en este caso seria el guion bajo.
    padding: 2px;                   Separacion
    width: 110px;                   Ancho
    height: 40px;                   Largo
}
.navegador1:hover {
    color: purple;                  Color que se pone cuando el mouse pase por esa palabra.
}

-Para fotosCategorias, fotosCategorias1, fotosCategorias2, info, info1, info2, le agregue este codigo:

    display: flex;                 El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos.
    justify-content: space-around; Muestra elementos con la misma separacion. 

-Para decoration, decoration1, decoration2, decoration3, decoration4, le agregue este codigo:

    border: 5px solid plum; Genera un border solido de 5px con su respectivo color.
    width: 350px;   Ancho.
    height: 350px;  Largo.

-Para Container le puse los siguientes codigos:

    display: grid; El display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos.
    grid-template-columns: 1fr 1fr; Crea 2 columnas.
    border: solid 2px black; Genera un border solido de 2px con su respectivo color.
    width: 98%;         Ancho
    padding: 5px;       Separacion

-Para containerimg le puse los siguientes codigos:

    display: grid; l display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos.
    grid-template-rows: 1fr 1fr 1fr 1fr; Crea 4 filas.

-Para foto1, foto2, foto3 y foto4, le puse los siguientes codigos:

    width: 100px;   Ancho, cada uno con sus respectivos tamaños.
    height: 110px;  Largo, cada uno con sus respectivos tamaños.
    border: 3px solid black; Crea un borde solido de 3px de color negro.
    border-radius: 5px; Este es para quitarle las esquinas a un objeto, en este caso, le indique 5px, que es lo que se le quita a las 4 esquinas.

-Para f1, f2, f3, f4, g1, g2, g3, g4 le puse los siguientes codigos:

    width: 100%; Es el ancho que se le esta indicando.

-Para photo1, photo2, photo3, photo4, le puse los siguientes codigos:

    grid-column: 2/2; Especifica el tamaño y la ubicación de un elemento de la cuadrícula dentro de una columna.

    grid-row: 1/span 4; specifica el tamaño y la ubicación de un elemento de la cuadrícula dentro de una fila.

    visibility: hidden; Hace que no sea visble hasta que el cursor pase.

    overflow: hidden;  establece el comportamiento deseado cuando el contenido no cabe en el cuadro del elemento principal (se desborda) en dirección horizontal y/o vertical.

    width: 230px; Ancho

    height: auto; Que el largo sea automatico, dependiendo del ancho.

    border-radius: 15px; Este es para quitarle las esquinas a un objeto, en este caso, le indique 15px, que es lo que se le quita a las 4 esquinas.

-Para texto1, texto2, texto3, texto4, le puse los siguientes codigos:

    width: 280px;   Ancho
    height: auto;   Que el largo sea automatico, dependiendo del ancho.

-Para foto1:hover~.photo1, foto2:hover~.photo2, foto3:hover~.photo3, foto4:hover~.photo4, le puse el siguiente codigo:

    visibility: visible; Hace que el texto sea visible.
    
 -Para hola, le puse los siguientes codigos:

    text-decoration: none; Le quita la decoracion de la letra que en este caso seria el guion bajo.
    color: black; El color de la letra es negro.   

-Para texto y party1 le puse los siguientes codigos:

    text-align: center;     Pone el elemento en le centro.
    align-items: center;    Pone el elemento en le centro.

-Para party, le puse los siguientes codigos:

    width: 340px; Le defini el ancho.
    height: 340px;  Le defino el largo.

-Para video, le puse los siguientes codigos:

    text-decoration: none; Le quita la decoracion de la letra que en este caso seria el guion bajo.
    color: black; Hace que el color de la letra sea negro.

-Para video1, le puse los siguientes codigos:

    text-align: center;  Pone el elemento en le centro.
    align-items: center; Pone el elemento en le centro.
    font-size: 25px;     Indica el tamaño de letra de esa clase.

-Para el @media, utilice los siguientes codigos:

    @media screen and  (max-width: 1200px) {
    .container{
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 1fr;
    }
    .img{
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 1fr 1fr;
    }
    .finish{
        display: grid;
        grid-template-columns: 1fr ;
        grid-template-rows: 1fr 1fr 1fr;
    }
    .finalizacion{ 
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 1fr 1fr;
    }
}

Las funciones grid, nos sirve para hacer responsiva la pagina, en otras palabras nos sirve para telefono movil, se utiliza las clases que más se repiten, para que a la hora de hacer responsiva la clase afecto a las demas clases que esran dentro de estas. 
