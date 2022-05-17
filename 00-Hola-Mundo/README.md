# Primer Programa en C++

- Un programa en C++ se compone en dos partes, las librerías y la funcion principal.

* Como agregar las librerías a nuestro programa:

```cpp
#include <iostream> // iostream significa, input output stream.

using namespace std; // para no agregar std:: cada vez que queramos imprimir algo.
```

* Como agregamos nuestra función principal:

```cpp
int main(){
    // Aquí va nuestro cod.

    cout<<"Hola Mundo\n"; // El \n es para el salto de línea

    return 0; // Debemos retornar esto para que el programa sepa que finalizamos correctamente.
}
```