# CalculadoraBasica
# CalculadoraBasica - Solidity (PMM2627E01)


## Funciones
* `sumar(a, b)`: Devuelve la suma.
* `restar(a, b)`: Devuelve la resta (requiere `a >= b`).
* `multiplicar(a, b)`: Devuelve el producto.
* `obtenerUltimoResultado()`: Consulta el ultimo resultado.
* `obtenerHistorial()`: Consulta el total de operaciones.
* `resetear()`: Pone a 0 los dos contadores.

## Pasos a Remix IDE
1. Crear el fichero `PMM2627E01.sol` a la carpeta `contracts/`.
2. Enganchar el codigo y compilarlo con la versión `^0.8.34`.
3. Ir a **Deploy & run transactions** y prémer **Deploy**.
4. Ejecutar operaciones y probar que `restar` falla si `a < b`.
