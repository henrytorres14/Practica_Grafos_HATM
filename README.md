# Practica_Grafos_HATM
# Práctica Grafos: Optimización de Rutas de Entrega

#Descripción del Proyecto
Una empresa de comidas debe llevar materia prima a 5 sedes diferentes antes de abrir.  
El objetivo es encontrar la **ruta más económica de entrega**, minimizando el costo total de transporte.

#Algoritmos Utilizados
- **Prim:** Calcula el árbol de expansión mínima para conectar las sedes con el menor costo.
- **Backtracking:** Explora todas las combinaciones posibles de rutas para encontrar la ruta de entrega más corta.

#Supuestos del Modelo
- El grafo es **no dirigido y ponderado** (los costos de transporte son iguales en ambos sentidos).
- El costo se calcula con la fórmula:
costo = distancia (km) * valor_galon_diesel / rendimiento_camion
