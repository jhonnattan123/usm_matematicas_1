<style>
@media print{
   .noprint{
       display:none;
   }
}
</style>
# TRABAJO EN EQUIPO 01: Derivada y sus Aplicaciones

## Interpretación Geométrica de la derivada
- **1.1**.- Sea la función:
<img src="https://latex.codecogs.com/svg.image?f(x)=x^{2}-4x&plus;5" title="f(x)=x^{2}-4x+5" />

  - **1.1.1**.- Determine la ecuación de la recta tangente en el punto:
<img src="https://latex.codecogs.com/svg.image?x_{0}=1" title="x_{0}=1" /> <sup class="noprint">[[solucion]]() </sup>

  - **1.1.2**.- Determine la ecuación de la recta tangente en el punto:
<img src="https://latex.codecogs.com/svg.image?x_{0}=4" title="x_{0}=4" /> <sup class="noprint">[[solucion]]() </sup>

  - **1.1.3**.- Grafique la situación en un solo plano cartesiano. <sup class="noprint">[[solucion]]() </sup>

- **1.2**.- En circunferencia centrada en el origen de radio 4 en el punto:
<img src="https://latex.codecogs.com/svg.image?x_{0}=3" title="x_{0}=3" />

  - **1.2.1**.- Determine la ecuación de la recta tangente.<sup class="noprint">[[solucion]]() </sup>

  - **1.2.2**.- Grafique la situación.<sup class="noprint">[[solucion]]() </sup>

## Algebra de derivada

- **2.1**.- Usando algebra de derivada, determine la primera derivada de cada función:
  - **2.1.1**.- derive la siguiente funcion:
  <img src="https://latex.codecogs.com/svg.image?g(t)=\frac{t-2}{t^{2}+1}" title="f(x)=x^{2}-4x+5" />
  - **2.1.2**.- derive la siguiente funcion:
  <img src="https://latex.codecogs.com/svg.image?h(x)=x\sqrt{5-x^{2}}" title="f(x)=x^{2}-4x+5" />
  - **2.1.3**.- derive la siguiente funcion:
  <img src="https://latex.codecogs.com/svg.image?y=ln(x+\sqrt{1+x^{2}})" title="f(x)=x^{2}-4x+5" />
- **2.2**.- sea la funcion
  <img src="https://latex.codecogs.com/svg.image?f(t)=\frac{\sqrt{1+e^{t}}-1}{\sqrt{1+e^{t}}}" title="f(x)=x^{2}-4x+5" />
  hallar el valor de:
  <img src="https://latex.codecogs.com/svg.image?\frac{\partial f}{\partial t}(0)" title="f(x)=x^{2}-4x+5" />
- **2.3**.- sea la funcion
  <img src="https://latex.codecogs.com/svg.image?f(x)=ln(\sqrt{1+e^{x}}-1)-ln(\sqrt{1+e^{x}}+1)" title="f(x)=x^{2}-4x+5" />
  compruebe que
  <img src="https://latex.codecogs.com/svg.image?f''(0)" title="f(x)=x^{2}-4x+5" />

<div style="page-break-after: always;"></div>

## Elementos de la funciones
- **3.1**.- sea la funcion definida por
  <img src="https://latex.codecogs.com/svg.image?f(x)=-4x^{5}+9x^{3}" title="" />
  - **3.1.1**.- determine el intervalo de crecimiento
  - **3.1.2**.- intervalos de concavidades
  - **3.1.3**.- puntos maximos y minimos (si existen)
  - **3.1.4**.- puntos de inflexion
  - **3.1.5**.- interseccion con el eje x
  - **3.1.6**.- trace su grafica de *f*


## Soluciones

#### 1.1.1:

sabiendo que la ecuación de la recta es:
<img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
se debe obtener las siguientes 2 incognitas
<img src="https://latex.codecogs.com/svg.image?y_1" title="y^{1}" /> = punto de intersección con el eje y de la recta tangente
<img src="https://latex.codecogs.com/svg.image?m" title="m" /> = pendiente de la recta tangente, obtenida con la derivada de la función.
**en la ecuacion, *y* terminara siendo la variable dependiente, *x* sera la variable constante, recordamos que ya se nos entrego una variable.*
  
- **paso 1:** obtenemos *y* resolviendo la funcion en su forma normal, evaluando con:
  <img src="https://latex.codecogs.com/svg.image?\inline&space;x=1" title="\inline x=1" />
  - evaluamos:
<img src="https://latex.codecogs.com/svg.image?f(1)=\mathbf{1^{2}}-4*1&plus;5" title="f(x)=1^{2}-4*1+5" />
  - *1 elevado a 2 es 1, tendremos:*
<img src="https://latex.codecogs.com/svg.image?f(1)=1-\mathbf{4*1}&plus;5" title="f(x)=1^{2}-4*1+5" />
  - 4 multiplicado por 1 es 4, tendremos:
<img src="https://latex.codecogs.com/svg.image?f(1)=\mathbf{1-4}&plus;5" title="f(x)=1^{2}-4*1+5" />
  - 1 menos 4 es -3, tendremos:
  <img src="https://latex.codecogs.com/svg.image?f(1)=\mathbf{-3&plus;5}" title="f(x)=1^{2}-4*1+5" />
  - -3 +5 es -2, tendremos:
  <img src="https://latex.codecogs.com/svg.image?f(1)=2" title="f(x)=1^{2}-4*1+5" />
  - por lo tanto:
  <img src="https://latex.codecogs.com/svg.image?y_1=2" title="y=1^{2}-4*1+5" />

- **paso 2:** requerimos obtener *m* pero para eso requerimos obtener la derivada de la funcion entregada en la solicitud:
  - teniendo la funcion
  <img src="https://latex.codecogs.com/svg.image?f(x)=x^{2}-4x&plus;5" title="f(x)=x^{2}-4x+5" />
  - derivamos los terminos
  <img src="https://latex.codecogs.com/svg.image?{x^{2}}'=2x" title="f(x)=x^{2}-4x+5" />
  <img src="https://latex.codecogs.com/svg.image?{-4x}'=-4" title="f(x)=x^{2}-4x+5" />
  <img src="https://latex.codecogs.com/svg.image?{5}'=0" title="f(x)=x^{2}-4x+5" />
  - por lo tanto la derivada de la funcion nos quedaria como:
  <img src="https://latex.codecogs.com/svg.image?f(x)'=2x-4" title="f(x)=x^{2}-4x+5" />

- **paso 3:** obtenemos *m* evaluando la funcion derivada con
  <img src="https://latex.codecogs.com/svg.image?\inline&space;x=1" title="\inline x=1" />
  - evaluamos:
  <img src="https://latex.codecogs.com/svg.image?f(1)'=(2*1)-4" title="f(x)=x^{2}-4x+5" />
  - 2 multiplicado por 1 es 2
  <img src="https://latex.codecogs.com/svg.image?f(1)'=(2*1)-4" title="f(x)=x^{2}-4x+5" />
  - 2 menos 4 es -2
  <img src="https://latex.codecogs.com/svg.image?f(1)'=2-4" title="f(x)=x^{2}-4x+5" />
  - ahora recordamos que la pendiente de una recta tangente es igual a el resultado de evaluar su funcion derivada, por lo tanto:
  <img src="https://latex.codecogs.com/svg.image?m=-2" title="f(x)=x^{2}-4x+5" />
- **paso 4:** ya obtenida las 2 incognitas de la formula de la recta tangente, se remplazan en esta y se determina la ecuacion:
  tenemos:
  (recordamos que x<sub>1</sub> se nos entrego al principio del problema).
 <img src="https://latex.codecogs.com/svg.image?x_1=1" title="m" />
  <img src="https://latex.codecogs.com/svg.image?y_1=2" title="y=1^{2}-4*1+5" />
  <img src="https://latex.codecogs.com/svg.image?m=-2" title="f(x)=x^{2}-4x+5" />
  - tomamos la formula de la recta tangente
  <img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
  - remplazamos las incognitas
  <img src="https://latex.codecogs.com/svg.image?y-2=-2(x-1)" title="y-y^{1}=m(x-x^{1})" />
  - despejamos *y*
  <img src="https://latex.codecogs.com/svg.image?y=-2(x-1)+2" title="y-y^{1}=m(x-x^{1})" />
  - multiplicamos -2 por los terminos que le acompañan
  <img src="https://latex.codecogs.com/svg.image?y=-2x+2+2" title="y-y^{1}=m(x-x^{1})" />
  2 mas 2 nos da 4 y hemos obtenido nuestra ecuacion de la recta tangente:
  <img src="https://latex.codecogs.com/svg.image?y=-2x+4" title="y-y^{1}=m(x-x^{1})" />

#### 1.1.2:

sabiendo que la ecuación de la recta es:
<img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
se debe obtener las siguientes 2 incognitas
<img src="https://latex.codecogs.com/svg.image?y_1" title="y^{1}" /> = punto de intersección con el eje y de la recta tangente
<img src="https://latex.codecogs.com/svg.image?m" title="m" /> = pendiente de la recta tangente, obtenida con la derivada de la función.
**en la ecuacion, *y* terminara siendo la variable dependiente, *x* sera la variable constante, recordamos que ya se nos entrego una variable.*
  
- **paso 1:** obtenemos *y* resolviendo la funcion en su forma normal, evaluando con:
  <img src="https://latex.codecogs.com/svg.image?\inline&space;x=4" title="\inline x=1" />
  - evaluamos:
<img src="https://latex.codecogs.com/svg.image?f(4)=\mathbf{4^{2}}-4*4&plus;5" title="f(x)=4^{2}-4*1+5" />
  - 4 elevado a 2 es 16, tendremos:
<img src="https://latex.codecogs.com/svg.image?f(4)=16-\mathbf{4*4}&plus;5" title="f(x)=1^{2}-4*1+5" />
  - 4 multiplicado por 4 es 16, tendremos:
<img src="https://latex.codecogs.com/svg.image?f(4)=\mathbf{16-16}&plus;5" title="f(x)=1^{2}-4*1+5" />
  - 16 menos 16 es 0, tendremos:
  <img src="https://latex.codecogs.com/svg.image?f(4)=\mathbf{0+5}" title="f(x)=1^{2}-4*1+5" />
  - 0 mas 5 es 5
  <img src="https://latex.codecogs.com/svg.image?f(4)=5" title="f(x)=1^{2}-4*1+5" />
  - por lo tanto:
  <img src="https://latex.codecogs.com/svg.image?y_1=5" title="y=1^{2}-4*1+5" />

- **paso 2:** requerimos obtener *m* pero para eso requerimos obtener la derivada de la funcion entregada en la solicitud:
  - teniendo la funcion
  <img src="https://latex.codecogs.com/svg.image?f(x)=x^{2}-4x&plus;5" title="f(x)=x^{2}-4x+5" />
  - derivamos los terminos
  <img src="https://latex.codecogs.com/svg.image?{x^{2}}'=2x" title="f(x)=x^{2}-4x+5" />
  <img src="https://latex.codecogs.com/svg.image?{-4x}'=-4" title="f(x)=x^{2}-4x+5" />
  <img src="https://latex.codecogs.com/svg.image?{5}'=0" title="f(x)=x^{2}-4x+5" />
  - por lo tanto la derivada de la funcion nos quedaria como:
  <img src="https://latex.codecogs.com/svg.image?f(x)'=2x-4" title="f(x)=x^{2}-4x+5" />

- **paso 3:** obtenemos *m* evaluando la funcion derivada con
  <img src="https://latex.codecogs.com/svg.image?\inline&space;x=4" title="\inline x=1" />
  - evaluamos:
  <img src="https://latex.codecogs.com/svg.image?f(4)'=(2*4)-4" title="f(x)=x^{2}-4x+5" />
  - 2 multiplicado por 4 es 8
  <img src="https://latex.codecogs.com/svg.image?f(4)'=8-4" title="f(x)=x^{2}-4x+5" />
  - 8 menos 4 es 4
  <img src="https://latex.codecogs.com/svg.image?f(4)'=4" title="f(x)=x^{2}-4x+5" />
  - ahora recordamos que la pendiente de una recta tangente es igual a el resultado de evaluar su funcion derivada. por lo tanto:
  <img src="https://latex.codecogs.com/svg.image?m=4" title="f(x)=x^{2}-4x+5" />

- **paso 4:** ya obtenida las 2 incognitas de la formula de la recta tangente, se remplazan en esta y se determina la ecuacion:
  tenemos:
  (recordamos que x<sub>1</sub> se nos entrego al principio del problema).
 <img src="https://latex.codecogs.com/svg.image?x_1=4" title="m" />
  <img src="https://latex.codecogs.com/svg.image?y_1=5" title="y=1^{2}-4*1+5" />
  <img src="https://latex.codecogs.com/svg.image?m=4" title="f(x)=x^{2}-4x+5" />
  - tomamos la formula de la recta tangente
  <img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
  - remplazamos las incognitas
  <img src="https://latex.codecogs.com/svg.image?y-5=4(x-4)" title="y-y^{1}=m(x-x^{1})" />
  - despejamos *y*
  <img src="https://latex.codecogs.com/svg.image?y=4(x-4)+5" title="y-y^{1}=m(x-x^{1})" />
  - multiplicamos 4 por los terminos que le acompañan
  <img src="https://latex.codecogs.com/svg.image?y=4x-16+5" title="y-y^{1}=m(x-x^{1})" />
  -16 mas 5 nos da -11 y hemos obtenido nuestra ecuacion de la recta tangente:
  <img src="https://latex.codecogs.com/svg.image?y=4x-11" title="y-y^{1}=m(x-x^{1})" />

#### 1.1.3:
https://www.geogebra.org/graphing/yvs7n9vm

<img src="img\taller_1_1_1_3.png">

#### 1.2.1:

sabiendo que la ecuación de la recta es:
<img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
se debe obtener las siguientes 2 incognitas
<img src="https://latex.codecogs.com/svg.image?y_1" title="y^{1}" /> = punto de intersección con el eje y de la recta tangente
<img src="https://latex.codecogs.com/svg.image?m" title="m" /> = pendiente de la recta tangente, obtenida con la derivada de la función.
<img src="https://latex.codecogs.com/svg.image?x_1" title="y^{1}" /> = punto de intersección con el eje x de la recta tangente

- **paso 1** :
  sabiendo que la formula de la circunferencia es:
  <img src="https://latex.codecogs.com/svg.image?y^{2}+x^{2}=r^{2}" title="" />
  obtenemos *y*<sub>1</sub> (tambien llamada funcion de semicirculo en este caso) resolviendo la formula en su forma normal, remplazando el radio y el eje *x* con los valores que se nos han entregado:
  <img src="https://latex.codecogs.com/svg.image?r=4" title="" />
  <img src="https://latex.codecogs.com/svg.image?x=3" title="" />
  - remplazamos:
  <img src="https://latex.codecogs.com/svg.image?y^{2}+3^{2}=4^{2}" title="" />
  - despejamos *y<sup>2</sup>*
  <img src="https://latex.codecogs.com/svg.image?y^{2}=4^{2}-3^{2}" title="" />
  - despejamos el exponente de *y*
  <img src="https://latex.codecogs.com/svg.image?y=\pm\sqrt{4^{2}-3^{2}}" title="" />
  - resolvemos los exponentes
  <img src="https://latex.codecogs.com/svg.image?y=\pm\sqrt{16-9}" title="" />
  - 16 menos 9 es igual a 7
  <img src="https://latex.codecogs.com/svg.image?y=\pm\sqrt{7}" title="" />
  - por lo tanto la funcion del semi circulo de la circunferencia seria:
  <img src="https://latex.codecogs.com/svg.image?f(x)=\pm\sqrt{7}" title="" />
- **paso 2**:
  teniendo la funcion del semicirculo, y buscando obtener la pendiente, se deriva esta:
  - teniendo la funcion
  <img src="https://latex.codecogs.com/svg.image?f(x)=\pm\sqrt{7}" title="" />
  - derivamos el unico termino
  <img src="https://latex.codecogs.com/svg.image?{\pm\sqrt{7}}'=\frac{x}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
  - por lo tanto la derivada de la funcion nos quedaria como:
    <img src="https://latex.codecogs.com/svg.image?f(x)'=\frac{x}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
- **paso 3**:
  obtenemos *m* evaluando la derivada de la funcion con respecto a *x* que se nos entrego
  - teniendo la variable independiente
  <img src="https://latex.codecogs.com/svg.image?x=3" title="" />
  - y teniendo la derivada de la funcion
  <img src="https://latex.codecogs.com/svg.image?f(x)'=\frac{x}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
  - evaluamos con *x* =3
  <img src="https://latex.codecogs.com/svg.image?f(3)'=\frac{3}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
  - no se resuelve debido a la irracionalidad, pero de esta forma de obtiene m, ya que esta equivale a la derivada de la funcion.
  <img src="https://latex.codecogs.com/svg.image?m=\frac{3}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
- **paso 4**:
ya obtenida las 2 incognitas de la formula de la recta tangente, se remplazan en esta y se determina la ecuacion:
  tenemos:
  (recordamos que x<sub>1</sub> se nos entrego al principio del problema).
 <img src="https://latex.codecogs.com/svg.image?x_1=3" title="m" />
  <img src="https://latex.codecogs.com/svg.image?y_1=\pm\sqrt{7}" title="y=1^{2}-4*1+5" />
  <img src="https://latex.codecogs.com/svg.image?m=\frac{3}{\pm\sqrt{7}}" title="f(x)=x^{2}-4x+5" />
  - tomamos la formula de la recta tangente
  <img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
  - remplazamos las incognitas
  <img src="https://latex.codecogs.com/svg.image?y-(\pm\sqrt{7})=\frac{3}{\pm\sqrt{7}}(x-3)" title="y-y^{1}=m(x-x^{1})" />
  - despejamos *y*
  <img src="https://latex.codecogs.com/svg.image?y=\frac{3}{\pm\sqrt{7}}(x-3)+(\pm\sqrt{7})" title="y-y^{1}=m(x-x^{1})" />
  - multiplicamos los terminos unidos, y obtenemos la ecuacion de la recta tangente
  <img src="https://latex.codecogs.com/svg.image?y=\frac{3x}{\pm\sqrt{7}}-\frac{9}{\pm\sqrt{7}}+(\pm\sqrt{7})" title="y-y^{1}=m(x-x^{1})" />


#### 1.2.1:
https://www.geogebra.org/graphing/qyywn9jr
<img src="img\taler_2_1_2_2.png">

#### 2.1.1
  derive la siguiente funcion:
  <img src="https://latex.codecogs.com/svg.image?g(t)=\frac{t-2}{t^{2}+1}" title="f(x)=x^{2}-4x+5" />

  - **paso 1**:
  recordamos la derivacion de una division, por ejemplo teniendo una division de la siguiente forma:
  <img src="https://latex.codecogs.com/svg.image?g(x)=\frac{f(x)}{h(x)}" />
  su derivada equivaldria a:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{f'(x)*h(x)-h'(x)*f(x)}{[h(x)]^{2}}" />
  conociendo los componentes necesarios para resolver nuestro problema, definirimos las funciones como en el ejemplo anterior, basandonos en su posicion:
  <img src="https://latex.codecogs.com/svg.image?f(t)=t-2" />
  <img src="https://latex.codecogs.com/svg.image?h(t)=t^{2}+1" />

  - **paso 2**:
  ahora, obtenemos las derivadas de nuestras 2 funciones:
  nuestra primera funcion:
  <img src="https://latex.codecogs.com/svg.image?f(t)=t-2" />
  derivamos los terminos
  <img src="https://latex.codecogs.com/svg.image?t'=1" />
  <img src="https://latex.codecogs.com/svg.image?-2'=0" />
  retirando el 0, la derivada de nuestra primera funcion quedaria :
  <img src="https://latex.codecogs.com/svg.image?f'(t)=1" />
  nuestra segunda funcion:
  <img src="https://latex.codecogs.com/svg.image?h(t)=t^{2}+1" />
  derivamos los terminos
  <img src="https://latex.codecogs.com/svg.image?{t^{2}}'=2t" />
  <img src="https://latex.codecogs.com/svg.image?1'=0" />
  retirando el 0, la derivada de nuestra segunda funcion quedaria como:
  <img src="https://latex.codecogs.com/svg.image?h'(t)=2t" />

  - **paso 3**:
  teniendo las funciones y sus derivadas necesarias:
  <img src="https://latex.codecogs.com/svg.image?f(t)=t-2" />
  <img src="https://latex.codecogs.com/svg.image?f'(t)=1" />
  <img src="https://latex.codecogs.com/svg.image?h(t)=t^{2}+1" />
  <img src="https://latex.codecogs.com/svg.image?h'(t)=2t" />
  tomaremos la formula de la division de derivada:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{f'(x)*h(x)-h'(x)*f(x)}{[h(x)]^{2}}" />
  cambiamos, la *x* de evaluacion por *t*, y luego, remplazamos los valores y funciones:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{1*(t^{2}+1)-2t*(t-2)}{[t^{2}+1]^{2}}" />
  - **paso 4**:
  resolvemos la ecuacion obtenida en el paso anterior, teniendo:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{1*(t^{2}+1)-2t*(t-2)}{[t^{2}+1]^{2}}" />
  multiplicamos el primer termino del numerador
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{(t^{2}+1)-2t*(t-2)}{[t^{2}+1]^{2}}" />
  multiplicamos el segundo termino del numerador
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{t^{2}+1-2t^{2}+4t}{[t^{2}+1]^{2}}" />
  sumamos terminos semejantes:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{-t^{2}+1+4t}{[t^{2}+1]^{2}}" />
  ordenamos los terminos del numerador y tenemos la derivada de nuestra funcion original:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{-t^{2}+4t+1}{[t^{2}+1]^{2}}" />

## formulas

formula de la recta tangente:
<img src="https://latex.codecogs.com/svg.image?y-y_1=m(x-x_1)" title="y-y^{1}=m(x-x^{1})" />
