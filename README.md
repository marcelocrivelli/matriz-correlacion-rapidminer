# Matriz de correlacion (correlation matrix) en RapidMiner

Aquí se puede ver un caso de uso del operador Correlation Matrix de RapidMiner. Este permite ver la matriz de correlación de los atributos del dataset en cuestión y también los pesos de los atributos.

El operador cuenta con diferentes parámetros: Attribute filter type, value type, normalize weigths, entre otros.

Para el caso se usó el dataset presente en Training Resources llamado CustomerCreditRiskData. El dataset cuenta con datos de clientes (credit worthy, status, job, housing, etc), y tienen el fin de determinar si para estos vale la pena o no otorgar un crédito.

En el operador Correlation Matrix se filtró los valores que sean númericos, se normalizaron los pesos y se utilizó correlación cuadrática para evitar valores negativos en la matriz.
