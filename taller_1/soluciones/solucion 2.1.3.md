#### 2.1.2:
  derive la siguiente funcion:
  <img src="https://latex.codecogs.com/svg.image?h(x)=x\sqrt{5-x^{2}}" title="f(x)=x^{2}-4x+5" />
  
  - **paso 1**:
  recordamos la regla derivacion de un producto de funciones, teniendo una funcion de ejemplo:
  <img src="https://latex.codecogs.com/svg.image?h(x)=f(x)*g(x)" />
  su derivada equivaldria a:
  <img src="https://latex.codecogs.com/svg.image?h'(x)=f'(x)*g(x)+f(x)*g'(x)" />
  conociendo los componentes necesarios para resolver nuestro problema, definirimos las funciones como en el ejemplo anterior, basandonos en su posicion:
  <img src="https://latex.codecogs.com/svg.image?f(x)=x" />
  <img src="https://latex.codecogs.com/svg.image?g(x)=\sqrt{5-x^{2}}" />

  - **paso 2**:
  ahora, obtenemos las derivadas de nuestras 2 funciones:
  nuestra primera funcion:
  <img src="https://latex.codecogs.com/svg.image?f(x)=x" />
  derivamos el terminos
  <img src="https://latex.codecogs.com/svg.image?x'=1" />
  por lo tanto la derivada de nuestra primera funcion es
  <img src="https://latex.codecogs.com/svg.image?f'(x)=1" />
  nuestra segunda funcion:
  <img src="https://latex.codecogs.com/svg.image?g(x)=\sqrt{5-x^{2}}" />
  derivamos los termino
  <img src="https://latex.codecogs.com/svg.image?(\sqrt{5-x^{2}})'=\frac{-x}{\sqrt{5-x^{2}}}" />
  por lo tanto la derivada de nuestra segunda funcion es:
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{-x}{\sqrt{5-x^{2}}}" />

  - **paso 3**:
  teniendo las funciones y sus derivadas necesarias:
  <img src="https://latex.codecogs.com/svg.image?f(x)=x" />
  <img src="https://latex.codecogs.com/svg.image?f'(x)=1" />
  <img src="https://latex.codecogs.com/svg.image?g(x)=\sqrt{5-x^{2}}" />
  <img src="https://latex.codecogs.com/svg.image?g'(x)=\frac{-x}{\sqrt{5-x^{2}}}" />
  tomaremos la formula de la division de derivada:
  <img src="https://latex.codecogs.com/svg.image?h'(x)=f'(x)*g(x)+f(x)*g'(x)" />
  remplazamos los valores y funciones:
  <img src="https://latex.codecogs.com/svg.image?h'(x)=(1*\sqrt{5-x^{2}})+(x*\frac{-x}{\sqrt{5-x^{2}}})" />
  resolvemos el primer termino
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\sqrt{5-x^{2}}+(x*\frac{-x}{\sqrt{5-x^{2}}})" />
  resolvemos el segundo termino
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\sqrt{5-x^{2}}+\frac{-x^{2}}{\sqrt{5-x^{2}}}" />
  convertimos el primer termino en una fraccion  para igualar.
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{\sqrt{5-x^{2}}*\sqrt{5-x^{2}}}{\sqrt{5-x^{2}}}+\frac{-x^{2}}{\sqrt{5-x^{2}}}" />
aplicamos regla de los signos en el segundo termino
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{\sqrt{5-x^{2}}*\sqrt{5-x^{2}}}{\sqrt{5-x^{2}}}-\frac{x^{2}}{\sqrt{5-x^{2}}}" />
  Ya que los denominadores son iguales, combinar las fracciones
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{\sqrt{5-x^{2}}*\sqrt{5-x^{2}}-x^{2}}{\sqrt{5-x^{2}}}" />
  resolvemos las raices
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{5-x^{2}-x^{2}}{\sqrt{5-x^{2}}}" />
  sumamos terminos semejantes
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{5-2x^{2}}{\sqrt{5-x^{2}}}" />
  ordenamos los terminos del numerador y obtenemos la derivada de nuestra funcion
  <img src="https://latex.codecogs.com/svg.image?h'(x)=\frac{-2x^{2}+5}{\sqrt{5-x^{2}}}" />