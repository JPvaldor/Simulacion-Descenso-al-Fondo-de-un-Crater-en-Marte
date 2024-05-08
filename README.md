# Proyecto de Búsqueda Local en Terreno Irregular

Implementé y evalué dos algoritmos de búsqueda local, búsqueda codiciosa y recocido simulado, para explorar y descender en un terreno irregular con el objetivo de alcanzar el fondo de un cráter.

Al realizar este proyecto, tomé un modelo de terreno digital de https://www.uahirise.org/dtm/, y se experimentó con los algoritmos de búsqueda codiciosa, recocido simulado, A*, costo uniforme, BFS, y profundidad limitada para ver qué tanto lograba cada algoritmo aproximarse al fondo de un cráter.

Desafíos y resultados:

- Búsqueda Codiciosa: Logró avanzar desde diferentes posiciones iniciales, pero tendía a estancarse en óptimos locales al seguir vecinos de menor altura.
- Recocido Simulado: Descendió más profundamente y sorteó mejor los obstáculos, aunque requería ajustes cuidadosos de los parámetros para evitar desviaciones.
- A*: Proporcionó una estrategia heurística eficiente para encontrar caminos cortos hacia el objetivo, pero su rendimiento dependía de la precisión de la heurística.
-´Costo Uniforme: Ofreció resultados precisos al priorizar el menor costo acumulado, aunque a veces requería un mayor tiempo de cálculo.
- BFS: Cubrió eficientemente el espacio de búsqueda y encontró soluciones óptimas en ciertos casos, pero era menos eficiente para explorar áreas extensas y complejas.
- Profundidad Limitada: Permitió explorar zonas específicas del espacio de búsqueda, pero se limitaba a una profundidad predefinida.

Impacto:

- Identifiqué las fortalezas y limitaciones de cada algoritmo, contribuyendo a la formulación de estrategias híbridas o alternativas en exploración robótica.
- Aporté conocimiento sobre el comportamiento de los algoritmos en terrenos complejos y su efectividad para la exploración.

