# APD1
## Ideas para los benchmarks
### Variables a tener en cuenta
- Distintos tamaños de vector
- ~~Distintos tipos de elemento (int, float, char...)~~ Solo importa el tamaño del elemento  
- ~~Tipos con tamaño variable (?)~~ Tamaño de tipos
- Distintos niveles de organización del vector inicial
    - Ordenado
    - Aleatorio
    - Reverso
    - Array lleno de pares (x, x -1) con x > 0
- Distiontos niveles de repetición de elementos
- Distintos lenguajes/niveles de optimización
- Distinto hardware con maquinas virtuales, ram, paralielización (?)
- Versiones recursivas vs iterativas
### Métricas
- Tiempo de ejecución
- Nº de permutaciones -> Peor para tipos grandes, peor para linked lists
- Uso de memoria, llamadas maximo y total recursivas y variables intermedias
- Distancia de posición en memoria de accesos consecutivos -> Importante para cache