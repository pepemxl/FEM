# Ecuaciones Diferenciales Parciales

## EDP Parabólicas

Una ecuación parabólica en derivadas parciales es una ecuación diferencial parcial de segundo orden del tipo y se utilizan para describir una gran variedad de fenómenos dependientes del tiempo, como la conducción del calor, la difusión de partículas y el preciación de instrumentos de inversión derivados.

Para definir el tipo más simple de EDP parabólica, considere una función de valor real $u(x,y)$ de dos variables reales independientes $x$ y $y$.

Una EDP de segundo orden, lineal, de coeficiente constante para $u$ tiene la forma

$$Au_{xx}+2Bu_{xy}+Cu_{yy}+Du_{x}+Eu_{y}+F=0$$ 

se llamada parabólica si $B^{2}-AC = 0$

Normalmente $x$ representa la posición unidimensional y $y$ representa el tiempo, y la EDP se resuelve sujeta a condiciones iniciales y de contorno prescritas.

El nombre **parabólica** se utiliza porque la suposición sobre los coeficientes es la misma que la condición para que la ecuación de geometría analítica $$Ax^{2} +  2Bxy + Cy^{2} + Dx + Ey + F = 0$$ para definir una parábola plana.

### Ecuación de Calor

Unos ejemplos básicos de una EDP parabólica es la ecuación del calor unidimensional


Las Ecuaciones Diferenciales Parciales tipo parabólicas semejantes a la mostrada, representa la ecuación de calor para una barra aislada sometida a fuentes de calor en cada extremo.

La temperatura se representa como una función $u(x,t)$ de dos tipos de variables la primera es la posición mientras que la segunda es el tiempo. 

La siguiente ecuación describe la distribución del calor (o variaciones de la temperatura) en una región a lo largo del transcurso del tiempo.

$$\frac{\partial^{2}u}{\partial x^{2}} = K\frac{\partial u}{\partial t}$$

la cual en su forma más general, se escribe como: 

$$\frac{\partial u}{\partial t}-\alpha\nabla^{2}u$$

donde $u(x,t)$ es la temperatura en el tiempo $t$ en la posición 
$x$ a lo largo de una varilla delgada, y 
$\alpha$  es una constante positiva llamada la difusividad térmica del material.

La difusividad térmica, en los problemas de transferencia de calor, es el valor obtenido al dividir la conductividad térmica de un cierto material dividida entre el producto del valor de su densidad y la capacidad calorífica específica del mismo. 

$$\alpha = \frac{k}{\rho c_{p}}$$

donde
- $\alpha$ es la difusividad térmica
- $k$ es la conductividad térmica
- $rho$ densidad del material
- $c_{p}$ calor específico a presión constante

La conductividad térmica es una propiedad física de los materiales que mide la capacidad de conducción de calor.

La capacidad calorífica específica, calor específico o capacidad térmica específica es una magnitud física que se define como la cantidad de calor que hay que suministrar a la unidad de masa de una sustancia o sistema termodinámico para elevar su temperatura en una unidad.

La ecuación del calor dice que la temperatura en un momento y punto dados sube o baja a un ritmo proporcional a la diferencia entre la temperatura en ese punto y la temperatura media cerca de ese punto. La cantidad $u_{xx}$ mide lo lejos que está la temperatura de satisfacer la propiedad del valor medio de las funciones armónicas(para ellas $\nabla^{2}f = 0$).

## EDP Elípticas




## EDP Hiperbólicas

Las Ecuaciones Diferenciales Parciales tipo hiperbólicas son usualmente representadas usando la ecuación de onda de una dimensión $u(x,t)$, que representa el desplazamiento vertical de una cuerda.



