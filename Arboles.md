[Regresar](Unidad3.md)
# ÁRBOLES
- [Definición](#Definición)
- [Tipos de Árboles y sus Aplicaciones](#Tipos_de_Árboles_y_sus_Aplicaciones)
- [Optimización y Codificación de Huffman](#Optimización_y_Codificación_de_Huffman)
- [Árboles de Búsqueda Binaria (BST) y Recorridos](#Árboles_de_Búsqueda_Binaria_(BST)_y_Recorridos)
- [Estructuras Avanzadas e IA](#Estructuras_Avanzadas_e_IA)
- [Conclusiones](Conclusiones)
  
## Definición
En matemáticas discretas, un árbol se define como un grafo conexo que no contiene ciclos
Esta estructura permite organizar información de manera jerárquica y eficiente, garantizando que todos sus vértices estén conectados por un único camino posible, lo que evita redundancias. Matemáticamente, un árbol con n vértices siempre posee n-1 aristas. Si se elimina una arista, el árbol deja de ser conexo; si se añade una, se forma un ciclo. <br>
<img width="644" height="310" alt="image" src="https://github.com/user-attachments/assets/cc6af805-4dcd-4bdf-a6af-bf428a7ace91" />


## Tipos de Árboles y sus Aplicaciones
Existen diversas clasificaciones dependiendo de su organización:
- Árboles libres y enraizados: Los primeros no tienen un nodo raíz definido, mientras que los enraizados se organizan en niveles a partir de un nodo principal
- Árboles binarios: Cada nodo tiene un máximo de dos hijos
- Incluyen variantes como los completos, perfectos y balanceados (AVL), estos últimos optimizados para búsquedas rápidas al mantener una altura mínima
- Árboles B y B+: Utilizados en sistemas de archivos y bases de datos para manejar grandes volúmenes de datos con pocos accesos a disco

Sus aplicaciones abarcan desde la organización de directorios en sistemas operativos hasta el desarrollo de algoritmos de inteligencia artificial y motores de búsqueda

## Optimización y Codificación de Huffman

Los árboles son la base de técnicas de compresión de datos como los códigos de prefijos o algoritmos de Huffman
Este método asigna códigos binarios más cortos a los símbolos frecuentes y más largos a los infrecuentes, asegurando que ningún código sea prefijo de otro para evitar ambigüedades
Es fundamental en formatos como ZIP, JPEG, PNG y MP3

## Árboles de Búsqueda Binaria (BST) y Recorridos
Un BST es una estructura donde los valores menores al nodo se ubican a la izquierda y los mayores a la derecha, facilitando búsquedas rápidas. Para procesar su información, existen tres recorridos principales en profundidad:
- Preorden (Raíz-Izquierda-Derecha): Útil para duplicar la estructura del árbol
  <img width="452" height="322" alt="image" src="https://github.com/user-attachments/assets/cf6aa419-5f9a-49d3-b4ae-9cf443477807" />


- Inorden (Izquierda-Raíz-Derecha): En un BST, devuelve los valores en orden ascendente
  <img width="494" height="288" alt="image" src="https://github.com/user-attachments/assets/5831bbd8-3620-4fe2-bf17-468809460163" />

- Postorden (Izquierda-Derecha-Raíz): Utilizado para eliminar nodos o evaluar expresiones postfijas
  <img width="451" height="309" alt="image" src="https://github.com/user-attachments/assets/3645434d-d7c2-43a0-99fb-bee072222dee" />

## Estructuras Avanzadas e IA
La teoría de árboles se extiende a estructuras especializadas como:
- Heaps (Montones): Cruciales para colas de prioridad y el algoritmo de Dijkstra
- Tries: Árboles digitales usados en correctores ortográficos y autocompletado
- Árboles de Decisión: Base del aprendizaje automático para clasificar información y automatizar la toma de decisiones

## Conclusiones
El estudio de los árboles demuestra cómo una estructura matemática puede optimizar significativamente el almacenamiento y la búsqueda de información
Hacia el futuro, estas estructuras se están adaptando para responder a los retos del Big Data, Blockchain, computación cuántica y ciberseguridad
