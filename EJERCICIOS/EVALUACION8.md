# 8. VARIABLES DE TEXTO

Objetivo: Verificar el dominio teórico y técnico del uso y manipulación de texto en java
mediante ejercicios para desarrollar su código, preguntas de respuesta múltiple y
abiertas.

Indicaciones: Pedir responder cada una de las preguntas de manera breve y clara.

1. De los siguientes métodos de la clase Scanner, escribe cuál es la función que
realiza cada uno de ellos. (Valor 1 punto por respuesta, valor total 8 puntos)


![imagen](https://user-images.githubusercontent.com/107777143/187044253-4ada4a12-e1f7-42d8-8d50-5be1e8b58191.png)




2. De las siguientes dos líneas de código, ¿Cuál será el resultado de aplicar ese
método? (Valor 1 punto)

String cadena = "hola MUNDO";

System.out.println(cadena.toLowerCase());
    
    a. hola mundo


    
3. De las siguientes dos líneas de código, ¿Cuál será el resultado de aplicar ese
método? (Valor 1 punto)

String cadena = "hola MUNDO";

System.out.println(cadena.toUpperCase());


      b. HOLA MUNDO

      
4. De las siguientes dos líneas de código, ¿Cuál será el resultado de aplicar ese
método? (Valor 1 punto)

String cadena = new String("Hola mundo");

System.out.println("El tamaño de " + cadena + " es de " + cadena.length() + "caracteres");

      a. El tamaño de Hola mundo es de 10 caracteres

 
      
5. Crea el código en java considerando las siguientes instrucciones: (Valor 3 puntos)

    a. Importa la clase Scanner para la lectura de datos.

    b. Crea un objeto de la clase Scanner llamado datos.

    c. Crea las variables nombre y edad.

    d. Imprime el mensaje Ingresa tu nombre completo:, lee el dato desde
    teclado y almacena el valor en la variable nombre.

    e. Imprime el mensaje Ingresa tu edad:, lee el dato desde teclado y almacena
    el valor en la variable edad.

    f. Crea una condicional en la cual si el usuario es mayor a 18 años imprima el
    texto Tu nombre es “nombre”, tienes “edad” años y eres mayor de edad.

    g. Si es menor a 18 años, entonces imprima el texto Tu nombre es “nombre”,
    tienes “edad” años y eres menor de edad.

    h. Finalmente, imprimir el mensaje Tu nombre tiene “Número de caracteres”
    caracteres.
    
        
        
        RESPUESTA
        
        import java.util.Scanner;

        public class Usuario{
            public static void main(String[] args){

                Scanner datos = new Scanner(System.in);
                String nombre;
                int edad;

                System.out.println("Ingresa tu nombre completo: ");
                nombre = datos.nextLine();
                System.out.println("Ingresa tu edad: ");
                edad = datos.nextInt();

                if(edad >= 18 ){
                    System.out.println("Tu nombre es " + nombre + " tienes " + edad + " a\u00f1os y eres mayor de edad");
                }	else {
                        System.out.println("Tu nombre es " + nombre + " tienes " + edad + " a\u00f1os y eres menor de edad");
                    }

                int numcaracteres = nombre.length();

                System.out.println("Tu nombre tiene: " + numcaracteres + " caracteres");

            }

        }
        
        Output

        java -cp /tmp/RPqxGnAHIc Usuario
        Ingresa tu nombre completo: 
        Alfonso Sanchez Alfaro
        Ingresa tu edad: 
        50
        Tu nombre es Alfonso Sanchez Alfaro tienes 50 a?os y eres mayor de edad
        Tu nombre tiene: 22 caracteres
        
      
