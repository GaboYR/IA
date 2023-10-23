# Solu del parcial
- Ventajas del backtracking:

Puede volver a un estado anterior.
- Desventaja:

Si el spacio de busqueda es muy grande, no es eficiente.

- Explique heuristica admisible:

Cuando la heuristica nucnca sobreestima el coste de alcanzar el objetivo, es decir, que en el punto actual la estimación del coste de alcanzar el objetivo nunca es mayor que el menor coste posible.

# Semana 9
1. Medicion
Cuando el conjunto es homogeneo,la forma adecuada de sacar una muestra es de forma aleatoria.

Si el conjunto no es homogéneo, conviene segmentar o particionar el espacio de búsqueda.
sigma: desviacion estandar, d: baya

## PSA (Analisis de los componentes prncipales)
- Prbablemente una de las técnicas maás antiguas de **IA**
- ¿Qué componentes son importantes mantenerlos en el procesamiento?
**Los algoritmos inteligentes reconocen la significancia(varianza)**

Calculo de la varianza:

$$\sigma² =\frac{1}{N-1}XX^{T}$$

Matriz de covarianza:

$$\begin{bmatrix}
x_1 & x_2 & ... & x_N\\
x_1^{2} & ...& & x_1x_n\\
\end{bmatrix}
$$

Importancia de la covarianza:
$$A^{-1} = A^{T}$$ -> valido para matrices ortogonales

$$Cu_{i} = \lambda u_i$$

$$u_{i} = A(x_{i} - m)$$

$$x_{i} = m + A^{T}u_{i}$$

$$A^{-1} = A^{T}$$

$$C^{'} = ACA^{T}$$

$$C^{'} = \begin{pmatrix}
\lambda_1 & & & ...&\\
& & \lambda_2 & & ...\\
\\
& & & ... &\lambda_n\\
\end{pmatrix}$$

$$\{ \lambda_1, \lambda_2, ... \lambda_{n-1}, \lambda_n \}$$

Importancia                    Significancia

Es importante comenzar con menos datos y a apartir de ahi incrementarlos segun sea necesario




