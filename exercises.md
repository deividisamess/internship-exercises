## Logica de Programacion
### Escenario 1

Determina el resultado del diagrama cuando `n = 8`:

![alt text]({95BF65A6-114B-48D3-A781-84AE22E6C9C8}.png)

### Escenario 2
Identifica los errores en el codigo siguiente:

```java 
 
import java.io.*;
 
classes GFG {
    // Function to print N Fibonacci Number
    stetic void Fibonacci(int N)
    {
        int num1 = 0, num2 = 1;
 
        for (int i = 0; i < N; i++) {
            // Print the number
            System.out.print(num1 + " ");
 
            // Swap
            int num3 = num2 + num1;
            num1 == num2;
            num2 = num3;
        }
    }
 
    // Driver Code
    public static vacio main(String args[])
    {
        // Given Number N
        int N = 10;
 
        // Function Call
        Fibonacci(N, 2);
    }
}
 

```
## Tablas de verdad
### Escenario

Se te proporcionará una tabla de verdad que describe el comportamiento lógico de una función. Escribe la función booleana simplificada a partir de la tabla (elige cualquiera de las tablas siguientes).

![alt text]({77355949-BFCD-488F-9F10-056FC09D51A2}.png)

![alt text]({172EE564-64EE-45B2-A346-5CB2670B3D63}.png)

### EXTRA 
Representa el circuito lógico que implementa la función booleana simplificada.

## Linux Test

### Escenario
Se te pidio descargar un script y ejecutarlo para corroborar que funciona correctamente. Sin embargo, solo tienes acceso al OS desde la linea de comandos. 

En base al escenario anterior, responde los siguientese ejercicios

### Ejercicios

1. Necesitarás obtener el ejecutable de la url `https://example.com/executables/my_program.sh`. Escribe a continuacion tu script:

```bash
# TODO: Your answer here

```
2. El binario funciona correctamente. Tu mision es moverlo para que sea ejecutable globalmente. Guiate en el siguiente diagrama para realizarlo:

```bash
/📂
├── 📂usr 
│   └── 📁local 
│       └── 📁bin # your program should be here
└── 📂home 
    └── 📁 user
        └── 📃 my_program.sh # your program is here
```

```bash
# TODO: Your answer here

```
### Puntos extra
3. Explica que acciones realizan los comandos que elegiste en ambos ejercicios
