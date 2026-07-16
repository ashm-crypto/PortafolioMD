[Regresar](Unidad3.md)

#GRÁFOS

- 

## Origen y Definición de los Grafos
La teoría de grafos se originó formalmente en 1736 con Leonhard Euler y el problema de los siete puentes de Königsberg. Un grafo se define como una estructura matemática compuesta por un conjunto de puntos (vértices) unidos por líneas (aristas), lo que permite modelar relaciones binarias entre objetos de forma abstracta. En computación, es una pieza fundamental para el desarrollo de inteligencia artificial, sistemas operativos y redes como el internet.

## Propiedades y Clasificación
A diferencia de otras figuras, un grafo se define por su topología (cómo están conectados sus elementos) y no por distancias o ángulos. Se clasifican principalmente en:
- Grafos dirigidos (dígrafos): Las aristas tienen una dirección definida.
- Grafos no dirigidos: La relación entre nodos es simétrica.
- Magnitud: El orden se refiere al número de vértices y el tamaño al número de aristas.

## Diferencias en los Recorridos: Euler vs. Hamilton
<img width="752" height="356" alt="image" src="https://github.com/user-attachments/assets/947c9d89-2b22-4e2b-9c6a-49a2df332f72" />

## Algoritmos de Optimización
La teoría se aplica a la resolución de problemas reales mediante algoritmos lógicos:

### Algoritmo de Fleury: Método estándar para construir caminos eulerianos, evitando cruzar "puentes" que desconecten el grafo prematuramente.
<img width="594" height="211" alt="image" src="https://github.com/user-attachments/assets/160fb868-a294-4542-afa3-2fd39cbe1efe" />

### Algoritmo de Dijkstra: Motor de los sistemas GPS, diseñado para encontrar la ruta más corta desde un origen hacia otros nodos en grafos con pesos positivos.
<img width="416" height="269" alt="image" src="https://github.com/user-attachments/assets/17720d83-e519-4605-bcec-f55eaa12074e" />

## Representación Digital (Matrices)
Para que las computadoras procesen grafos, se utilizan representaciones numéricas.
- Matriz de Adyacencia (n×n): Utiliza ceros y unos para indicar conexiones. Elevar esta matriz a la potencia k permite calcular el número de caminos de longitud k.
- Matriz de Incidencia (n×m): Vincula nodos con aristas. Es ideal para modelar multígrafos con lazos o aristas paralelas que la matriz de adyacencia no puede representar con precisión.
  
## Isomorfismo, Planaridad y Coloreado
- Isomorfismo: Dos grafos son isomorfos si comparten la misma estructura, número de vértices, aristas y los mismos grados de los vértices.
- Grafos Planos: Cumplen con la Fórmula de Euler (V – A + C = 2), que establece una relación constante entre vértices, aristas y caras o regiones.
- Coloreado: Busca el número mínimo de colores para que nodos adyacentes no compartan color. Por ejemplo, un cubo solo requiere 2 colores por ser un grafo bipartito.
  
## Emparejamiento y Cobertura
En grafos bipartitos, existe una relación estrecha entre el emparejamiento máximo (conjunto de aristas independientes) y la cobertura de vértices mínima (nodos que tocan todas las aristas). En estos casos específicos, el tamaño de ambos suele coincidir, lo cual es vital para problemas de asignación de recursos.

[Volver al inicio](indice)
