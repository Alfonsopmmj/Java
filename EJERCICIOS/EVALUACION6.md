# Práctica 6.

### ARREGLOS

Objetivo: Verificar el dominio teórico y técnico del concepto de arreglos en el lenguaje de
java mediante ejercicios para desarrollar su código y preguntas de respuesta múltiple.
Indicaciones: Pedir responder cada una de las preguntas de manera acertada, breve y
clara, según sea el caso.

1. ¿Qué es un arreglo? (Valor 1 punto)
    
       
        c. Conjunto de variables del mismo tipo cuyo acceso se realiza por índice
        


2. De la siguiente ilustración de un arreglo, coloca los elementos según corresponda.
(Valor 1 punto)



![imagen](https://user-images.githubusercontent.com/107777143/185739615-36d42d18-f594-4c23-b34e-33b8f9b1db5b.png)






3. Tomando el siguiente arreglo, contesta las siguientes preguntas: (Valor 2 puntos)

![image](https://user-images.githubusercontent.com/91554777/176980222-c9ac9e57-a50d-4329-9db6-b2b1c02aeae4.png)

      a. ¿Qué tipo de dato tiene el arreglo?
         R= Double (decimal)
      b. ¿Qué valor se encuentra en la posición con el índice 4?
         R= 8.3
      c. ¿Cuál es el rango de índices del arreglo?
         R= Del 0 al 9 (io, i1, i2, i3, i4, i5, i6, i7, i8, i9)
      
      
 4. ¿Qué tipo de ciclo se adapta fácilmente para el manejo de un arreglo? (Valor 1
punto)

     
      b. For
    
      
 5. ¿Cómo se le conoce a los arreglos unidimensionales? (Valor 1 punto)
 
          
        c. Vector
   
   
6. Un arreglo bidimensional es aquel que consta de: (Valor 1 punto)

 
        c. m filas y n columnas
        
        
7. Sea un arreglo vector[] conformado por 10 elementos, ¿Qué muestra si se escribe
en el código vector[10]? (Valor 1 punto)

       
      a. Nada.
  
  
8. Si se ejecuta el siguiente código, ¿Qué imprime la línea 5 y la línea 7? (Valor 2
puntos)

![image](https://user-images.githubusercontent.com/91554777/176980300-634ec85b-39d3-4b54-8101-962128d7252f.png)

      a. Lista de productos
      Paleta 2.50
      Papas 14.00
      Galletas de chocolate 15.50
      Refresco 34.70



    
 9. Crea un programa en java considerando las siguientes instrucciones: (Valor 2
puntos)

      a. Crea un arreglo llamado números el cual tenga los siguientes elementos 12,
      10, 4, 24, 5 y 9.
      b. Realiza un ciclo que recorra todo el arreglo y en cada pasada, imprima El
      arreglo en la posición “número de posición” tiene el número “imprimir el
      número que se encuentre en esa posición”.
      i. Ejemplo. El arreglo en la posición 2 tiene el número 4.


        RESPUESTA

        public class ArregloUnidNumEnteros{

                public static void main(String[] args){

                        int[] numeros = {12, 10, 4, 24, 5, 9};

                        for(int i= 0; i<6; i=i+1){
                                System.out.println("El arreglo en la posicion " + i + " tiene el numero " + numeros[i]);
                        }
                }
        }


        SALIDA:

        java -cp /tmp/VrTIX5PFj5 ArregloUnidNumEnteros
        El arreglo en la posicion 0 tiene el numero 12
        El arreglo en la posicion 1 tiene el numero 10
        El arreglo en la posicion 2 tiene el numero 4
        El arreglo en la posicion 3 tiene el numero 24
        El arreglo en la posicion 4 tiene el numero 5
        El arreglo en la posicion 5 tiene el numero 9


