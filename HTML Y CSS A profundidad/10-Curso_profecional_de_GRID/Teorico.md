# Curso profecional de CSS GRID
## Tecnicas de alineamiento 

### Margin 

Margin se lo utiliza para alinear objetos dentro de sus contenedores este acepta 4 valores de manera horaria 

    margin : arriba derecha abajo izquierda 

***mas ejemplos en Margin.html***

### Text-align vertical-align line-height

* Text-align : Esta propiedad nos permite alinear textos de manera horizonral
* Line-heigth : Controla los altos de los textos y si hay dos o mas filas las separa de manera vertical 
* Vertical-align : Nos permite alinear objetos de manera vertical 


Ejemplo, hace que el texto y el su contenedor se alineen al centro de otro contenedor div
      
      text-1{
         text-align: center ;
         line-height: 25px;
      }  

      contenedor_text-1{
        vertical-align : midle;
      }

### Table-cell 
Lo que permite table-cell es acoplar nuestros objetos en html como tablas 

* Tenemos un conenedor que tiene en su interior a un texto 

        .container{
            display: table-cell; //Hace que nuestros elementos se acomoden como tablas 
            text-align: center; // Alinea el objeto hijo de manera horizontal
            vertical-align: middle; // Alinea el objeto hijo de manera vertical 
        }

        .text{
            width: 60px;
            height: 60px;
            text-align: center;        
        }
### Position 
Position nos sirve para acomodar objetos dentro de un contenedor  

    position: relative; 
    position: absolute;
    position: top;
    position: rigth;
    position: bottom;
    position: left;
    trasform: traslate()

Ejemplo para acomodar un elemento a la parte superior izquierda ojo el elemento padre debe de tener el position relative para asi el hijo moverse con libertad dentro de el

    .padre{
        width: 200px;
        height: 200px;        
        position:relative;
    }

    .hijo{
        width: 20px;
        height: 20px;        
        position:absolute;
        left: 0;
        top: 0;
    }
    
    .hijo-2{
        width: 20px;
        height: 20px;        
        position:absolute;
        left: 0;
        top: 50%;
        transform: translate(0, -50%);//Calculo para que esto se vaya al medio ya que lo que va al centro es donde comienza el elemento 
    }
