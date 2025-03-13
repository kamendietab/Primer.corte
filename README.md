# INTRODUCCIÓN A LA DINÁMICA DE SISTEMAS
Un sistema es una relación de elementos que durante el intercambio de su naturaleza en un escenario contextualizado desencadenan un objetivo ya sea controlado o inercial, cuando se observa un sistema se aprecia su desarrollo de manera consecuente generando un algoritmo con variables dependientes y/o independientes, estos se rigen por las leyes de su desarrollo; en una vista general de un sistema se aprecia unas variables de entrada que al ser expuestas al desarrollo se alteran generando unas nuevas variables que serán las de salida.

## 1. Dividiremos los sistemas en 2 tipos:

### 1.1 Sistemas estáticos
Estos se carácterizan basicamente por no cambiar su comportamiento con el tiempo, es decir, las variables que se observan en su naturaleza no interactuan entre si de manera significativa con un fenómeno que cambie su comportamiento, esto lo hace completamente predecible ya que no esta sujeto a cambio evidente.

💡**Ejemplo 1:**

![Pongo como ejemplo un sistema donde una barra "L" tiene una base de apoyo tipo 2 que realiza un movimiento angular sobre un plano de 2 dimesiones (vertical y horizontal) y esta mayormente inclinado hacia los positivos del eje horizontal el peso generando un movimiento de giro horario que es contraarestado por una cuerda a una superficie vertical en el afin superior de la barra, donde también se encuentra izada una masa sin tener fuerza externa que afecte el estado de este sistena](https://2.bp.blogspot.com/-2mz1LHXA5nU/WiYCbJguolI/AAAAAAAAAD4/6zX9vSmlyGYQqxv5oJJKf4PhKf3COI2RwCLcBGAs/s1600/maxresdefault.jpg)

Figura 1. Sistema estático #1

💡**Ejemplo 2:**

![Se propone como segundo ejemplo de sistema dinámico una barra horizontal ubicada sobre una base que realiza el apoyo tipo 1 en el centro gravitacional de esta barra y en cada uno de sus extremos una masa con peso "X" y que en relación a la distancia de la base generan este punto de equilibrio estático](https://i.ytimg.com/vi/8ofBSp8Iu4o/hqdefault.jpg)

Figura 2. Sistema estático #2 

En estos sistemas podemos deducir que una condición para que un sistema sea estático es que sus fuerzas sean igual a "0", es decir que las fuerzas que lo afectan tengan un equilibrio ecuacional entre ellas.

### 1.2 Sistemas dinámicos
Por otro lado nos centraremos en los sistemas dinámicos que a diferencia de un sistema estático el comportamiento de las variables en un punto de tiempo "x", al ser exitado por un conjunto de reglas cambia su valor y/o forma dependiento el fenomeno o regla que lo altere, dicho esto se de puede deducir que los sistemas dinámicos son afectados a través del tiempo y que pueden observar en esta misma escala.

💡**Ejemplo 1:**

![Este sistema lo elegi para representar un sistema dinámico donde el cuerpo del sujeto sobre la pieza que forma un vertice el cual es el que esta en contacto con la superficie horizontal tiende a realizar un movimiento angular dependiendo hacia donde incline el cuerpo el sujeto se analizaran las fuerzas que realice para modelar matemáticamente este movimiento](https://static.docsity.com/documents_first_pages/2020/06/19/c369206730af96a79ac5bd08b3fa0c0b.png?v=1652022148)

Figura 1. Sistema dinámico #1

💡**Ejemplo 2:**

![Popongo este otro ejemplo sencillo donde se aprecia una masa sobre una superficie inclinada, lo suficiente para suferar la fricción de la superficie y desarrollar un movimiento a favor de la gravedad](https://i.ytimg.com/vi/60tf50JImhU/maxresdefault.jpg)

Figura 2. Sistema dinámico #2 

Los sistemas cuentan con 2 protagonistas los cuales definiremos de la siguiente manera:

🔑 *Planta:* Son todos los recursos tangibles que hacen posible un proceso materializado.

🔑 *Proceso:* Este se relaciona con el término algoritmo; ya que siguiendo unas instrucciones paso a paso permite que se lleve a cabo un objetivo.


## 2. Modelos dinamicos
Para el control de un sistema se hace necesario plantear un modelo matemático que operen variables en función del tiempo.

 $$f(t)$$

Se hace necesario incluir operaciones que cuantifiquen el cambio de estas variables a través del tiempo.

 $$\frac{df(t)}{dt}$$

## 3. Repaso cálculo diferencial

### 3.1¿Qué es una derivada?
🔑 *Derivada:* Es la pendiente de una linea recta que se superpone a una curva la cual es representada matemáticamente por una función y que mediante operaciones mide el cambio de esta relacionando la curva y la pendiente.


![Esta grafíca que define la derivada me genera mayor comprensión ya que esta la descomposición en sus componentes rectangulares y las operaciones que se desarrollan para formular la pendiente](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Recta_tangente_y_derivada.svg/300px-Recta_tangente_y_derivada.svg.png)

Figura 2. Gráfica de de definición de derivada y modelo algebraico #2 

💡**Ejemplo 1:**

$$F(x)=x^{\frac{3}{2}}-x^{\frac{5}{3}}$$


$$F'(x)=\frac{3}{2}*x^{\frac{3}{2}-\frac{3}{2}}-\frac{5}{3}*x^{\frac{5}{3}-\frac{5}{3}}$$

$$F'(x)=\frac{3}{2}*x^{\frac{1}{2}}-\frac{5}{3}*x^{\frac{2}{3}}$$

$$f'(x)=\frac{3}{2}*\sqrt{x}-\frac{5}{3}\sqrt[3]{x^{2}}$$

## 4. Modelos de ecuaciones diferenciales
Las ecuaciones diferenciales son herramientas fundamentales en matemáticas y ciencias para modelar fenómenos que cambian en el tiempo o el espacio. 

$$a_{1}\frac{d^{2}*F}{dt}+a_{2}\frac{dF}{dt}+a_{3}F=u(t)$$

F=Salida del sistema
U=Entrada del sistema

El resultado de un sistema no es un número es una función.

### 4.1 Características de una ecuación diferencial
🔑 *Ecuación lineal:* Es una expresion matemática que establece una relación entre 2 variables de manera lineal, es decir, que su representación gráfica es una recta su forma de representación general es:


$$ax+by=c$$


*donde a,b y c son constantes*

De una manera más simple se puede representar de la siguiente manera

$$ax+b=0$$

🔑 *Ecuación no lineal:* Una ecuación no lineal es una expresión matemática que involucra variables elevadas a potencias distintas de uno, o que incluye productos, raíces, o funciones no lineales.

$$x^{2}+y^{2}=r^{2}$$

$$( \frac{d^{2}*x*(t)}{dt^2})+(5*()\frac{dx*(t)}{dt})+(10*x*(t))=0 $$
🔑 *Ecuación Variante en el tiempo:* es una expresión matemática que describe un fenómeno que cambia a lo largo del tiempo.

$$\frac{d^{2}x}{dt^{2}}=-g$$

🔑 *Ecuación in-Variante en el tiempo:* es una expresión matemática que describe un sistema cuyo comportamiento o propiedades no cambian con el tiempo.

$$F=m*a$$

🔑 *Superposición:* Se refiere a la propiedad que establece, que, si y_{1}(t) y y_{2}(t) son soluciones de una ecuación diferencial lineal homogénea, entonces cualquier combinación lineal de estas soluciones también es una solución de la misma ecuación. En otras palabras:

$$y(t)= C_{1}*y_{1}(t)$$

## 5 MODELAMIENTO Y VALIDACIÓN

`Al aplicar leyes físicas a un modelo matemático de un sistema, se debetener encuentaq ue hay un nivelde incertidumbre en el resultado final, Es necesario validar el modelo con respecto al sistema físico comparandola salida del modelo con la salida de l modelo físico, sino es aceptablela diferenciase debe modificar el modelo hasta conseguir una diferencia aceptable.
``
# TRANSFORMADA DE LAPLACE
Es una herramienta matemática que se utiliza para transformar funciones de tiempo en funciones de una variable compleja 𝑠.

$$ x(t)= X(𝑠)

$$\mathscr{L}\{f(t)\}=\int_{t=0}^{\infty}f(t)e^{-st}dt$$

donde:

-𝐹(𝑠) es la transformada de Laplace de 𝑓(𝑡).
-𝑠 es un número complejo que generalmente se expresa como 𝑠=𝜎+𝑗𝜔 , donde 
-𝜎 y 𝜔 son reales, y 𝑗 es la unidad imaginaria.
-La integral se evalúa desde 𝑡=0 hasta 𝑡=∞.

La transformada de Laplace permite simplificar el análisis de sistemas lineales, facilitando la resolución de ecuaciones diferenciales al convertirlas en ecuaciones algebraicas en el dominio de 𝑠.

## 1. Propiedades de transformada de laPlace

Linealidad:

$$\mathscr{L}\{C_1f(t)+C_2g(t)}=C_1\mathscr{L}\{f(t)}+C_2\mathscr{g(t)} , C_1,C_2 \epsilon                  
                          \mathbb{R} $$


## Referencias
1. https://ekuatio.com/calculo-de-funciones-derivadas-ejemplos-y-ejercicios-resueltos/
2. https://www.docsity.com/es/sistemas-dinamicos-13/5671053/
3. https://i.ytimg.com/vi/AA9esyjLazc/maxresdefault.jpg
4. https://yosoytuprofe.20minutos.es/wp-content/uploads/2018/03/100derivadasresueltasyosoytuprofe.pdf
5. https://latex-tutorial.com/laplace-transform-symbol-latex/
