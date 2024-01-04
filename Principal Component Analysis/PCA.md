Los grandes conjuntos de datos están cada vez más extendidos en muchas disciplinas. Para interpretar dichos conjuntos de datos, se requieren métodos para reducir drásticamente su dimensionalidad
de una manera eficiente, de modo que se conserve la mayor parte de la información de los datos. Muchas técnicas han sido desarrolladas para este propósito, pero el análisis de componentes principales (PCA) 
ha tomado mayor importancia en los últimos años.

PCA es una herramienta de análisis estadístico para analisis de datos exploratorio. Un conjunto de datos grande es de la forma $p$ variables numéricas, para cada $n$ entidades o individuos. Estos valores de datos definen $p$ vectores n-dimensionales $x_1, \cdots , x_p$ o, equivalentemente, un dataframe o matriz $\textbf{X}$ de $n x p$ entradas, cuya $j$-ésima columna es el vector $x_j$ de observaciones sobre la $j$-ésima variable. Buscamos una combinación lineal de las columnas de la matriz $\textbf{X}$ con máxima varianza. Tales combinaciones lineales están dadas por

$$ \sum_{j=1}^p = a_jx_j= \textbf{X} \textbf{a} $$

donde $\textbf{a}$ es un vector de constantes $a_1, \cdots , a_p$. La varianza de cualquier combinación lineal de este tipo viene dada por $var(Xa) = a'Sa$, donde $S$ es la matriz de covarianza de muestra asociada con el conjunto de datos y $a'$ es el vector transpuesto de a.



