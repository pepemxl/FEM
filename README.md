# Método de los Elementos Finitos (FEM)

En estás notas describiremos soluciones detalladas para la ecuación de Poisson con distintas técnicas
de discretización y compararemos los resultados con los métodos de elementos finitos.

0. Ecuaciones Diferenciales Parciales
    1. EDPs Parabólicas
    2. EDPs Elípticas
    3. EDPs Hiperbólicas
1. Introducción
2. Residuos Ponderados
3. 



Desde hace algunos años se ha utilizado el Método de los Elementos Finitos (MEF) para estudiar el comportamiento de ciertos fenómenos físicos que siguen el comportamiento de la Ecuación de Poisson, formados con diferentes materiales, con formas complejas y sujetos a diferentes condiciones externas. Este método puede ser aplicado a gran número de problemas de ingeniería, reduciendo cada vez más la incertidumbre del comportamiento de diferentes formas y distribuciones de materiales. Esto permite reducir el número de ensayos de laboratorio lo que evidentemente conduce a proyectos más baratos y eficientes, que se obtienen en un tiempo de estudio mucho más corto.

El FEM es una herramienta poderosa tanto para académicos como  para técnicos que trabajan en diferentes ramas de la industria. 

En la primera parte de este trabajo, se explican los conceptos básicos del análisis por el Método de los Elementos Finitos (FEM) a la solución de la ecuación de Poisson, los tipos de problemas que podemos resolver, así como elementos finitos comúnmente utilizados (de dos y tres nodos en 1D, de tres, cuatro, ocho y nueve nodos en 2D y los elementos tetraédricos de 4 ó 10 nodos y los hexaedros de 8 ó 20 nodos comúnmente utilizados en 3D), en la discretización del dominio por analizar, así como los parámetros que afectan a la precisión del cálculo. 
