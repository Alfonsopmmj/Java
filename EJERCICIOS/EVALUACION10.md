# Práctica 10.

10. COLAS

Objetivo: Verificar el dominio teórico y técnico del uso y manipulación de colas en java
mediante ejercicios para desarrollar su código, preguntas de respuesta múltiple y
abiertas.

Indicaciones: Pedir responder cada una de las preguntas de manera breve y clara.

1. ¿Las operaciones FIFO (First In, First Out), son características de las colas en
programación? (Valor 1 punto)

              a. Verdadero


2. Se tiene la siguiente lista con 6 elementos, teniendo en cuenta que es una cola
contesta lo siguiente: (Valor 1 punto)

            a. ¿Cuál fue el último elemento en entrar? 5
            b. ¿Cuál fue el primer elemento en salir? 8

![image](https://user-images.githubusercontent.com/91554777/181846519-d3a5f664-1e13-4f1d-be3d-30d232fb5f2e.png)

3. ¿Qué método no se utiliza para remover un elemento de la cola? (Valor 1 punto)

            a. peek()
 
   

4. ¿Para qué sirven los métodos peek() y element() en las colas? (Valor 1 punto)

           
            c. Para recuperar o buscar el elemento de la cabecera de la cola e imprime los
            elementos que tiene.


5. Se quiere agregar un elemento a una cola, cuál o cuáles son las sintaxis correctas
para hacerlo: (Valor 1 punto)

              a. variable.add(“Perro”)
  
              c. variable.offer(“Perro”)




6. Escribe un programa en java con las siguientes indicaciones: (Valor 3 puntos)

a. Importa las clases necesarias para construir una cola.

b. Crea una cola llamada usuarios y agrega 5 nombres de tus compañeros de
clase.

c. Una vez agregados, elimina 3 elementos de la cola e imprime el mensaje El
nombre a eliminar es: “Nombre a eliminar”.

i. Ejemplo. El nombre a eliminar es: Nombre 1.

d. Finalmente, imprime otro mensaje que diga: El próximo nombre a eliminar
es: “Nombre a eliminar”.

i. Ejemplo. El próximo nombre a eliminar es: Nombre 4.

      Tu código aqui
      
                RESPUESTA

          import java.util.Queue;
          import java.util.LinkedList;

          public class Preg6Evaluacion10{

            public static void main(String[] args){

              //Crear Cola llamada usuarios
              Queue<String> usuarios = new LinkedList<>();

              //Agregar 5 nombres
              usuarios.add("Carlos");
              usuarios.add("Antonia");
              usuarios.add("Heriberto");
              usuarios.add("Mario");
              usuarios.add("Carmen");

              System.out.println("Cola: " + usuarios);

              //Eliminar 3 elementos de la Cola
              String nombre1 = usuarios.poll();
              String nombre2 = usuarios.poll();
              String nombre3 = usuarios.poll();

              //Elementos eliminados
              System.out.println("El nombre a eliminar es: " + nombre1);
              System.out.println("El nombre a eliminar es: " + nombre2);
              System.out.println("El nombre a eliminar es: " + nombre3);

              System.out.println("Cola actualizada: " + usuarios);

              String nombre4 = usuarios.peek();

              System.out.println("El proximo nombre a eliminar es: " + nombre4);

            }
          }


          Output

          java -cp /tmp/h5TFNbb4fF Preg6Evaluacion10
          Cola: [Carlos, Antonia, Heriberto, Mario, Carmen]
          El nombre a eliminar es: Carlos
          El nombre a eliminar es: Antonia
          El nombre a eliminar es: Heriberto
          Cola actualizada: [Mario, Carmen]
          El proximo nombre a eliminar es: Mario

                  
           
