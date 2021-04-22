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
