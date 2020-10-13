# Entrega 4 - Diseño del reticulado

* Se realiza el siguiente reticulado de largo = 15 m, ancho = 2 m y alto = 3,5 m, compuesto por barras de sección circular de radio R = 8 cm y espesor t = 5 mm. Los nodos 0 y 7 están completamente fijos, mientras que 3 y 10 son libres de deslizar solo en la dirección X (longitudinal). Se considera que además de la carga muerta (D) de peso propio, este se debe diseñar para una sobrecarga de uso (L) que corresponde a una carga distribuida sobre el tablero central de qL = 400 kg/m^2. Se consideran para su análisis 2 casos de combinaciones de carga. Las cuales son: Caso 1: 1.4 D  , Caso 2: 1.2 D + 1.6 L.

* Inicialmente el programa de reticulado entrega los siguientes resultados para tensiones y factores de utilización respectivos:

![1](https://user-images.githubusercontent.com/69275311/95888168-217ba800-0d57-11eb-8585-9700c260adf2.png)
![2](https://user-images.githubusercontent.com/69275311/95888183-25a7c580-0d57-11eb-876d-a47fa34dca22.png)
![3](https://user-images.githubusercontent.com/69275311/95888187-27718900-0d57-11eb-987a-767d817d98a0.png)
![4](https://user-images.githubusercontent.com/69275311/95888195-28a2b600-0d57-11eb-9745-675070fe3e92.png)
![5](https://user-images.githubusercontent.com/69275311/95888202-29d3e300-0d57-11eb-8eac-41f32483e1b2.png)

* El Peso total de la estructura inicial resulta: 24197.43808 [N]

## 1) 
* Luego de determinar que la combinacion de carga con mayor valor absoluto es la que involucra cargas vivas y muertas (1,2 D + 1,6 L), se escogieron las barras 3, 4, 18, 19 y 29, cuyo nodos son (4,5), (5,6), (0,4), (7,4) y (6,3) respectivamente. Para elegir las barras se escribió un codigo que identifique las barras que poseen mayor fuerza para así rediseñarlas y optimizar la estructura. Las fuerzas de las barras 3 y 4 antes de ser rediseñadas son iguales a 50.800N y un facto de utilización igual a 0,06, mientras que las tres restantes tienen una fuerza de 23.140N y factor de utilizacion 0,03. Luego de aplicar el rediseño se disminuyen las fuerzas de las barras 3 y 4 a 50.577N y 50.354N, con un factor de utilización de 0,98 y 0,97. Por otro lado las barras 18, y 29 disminuyeron su fuerza a 22.559N y 22.165N con un factor de utilización de 1 y 0,96, mientras que la barra 19 aumento a 23.524 con un factor de utilización de 0,94. Si biene la barra 19 aumento en algo su fuerza, la estrucutura mejoró la distribución de las fuerzas y el peso notablemente, ya que las barras rediseñadas poseen factores de utulización muy cercanos a 1. 



## 2)


## 3)


## 4)


## 5)
