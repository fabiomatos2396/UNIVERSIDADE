\title{
Métodos Quantitativos
}

\section*{Capítulo 2}

Cálculo diferencial com funções reais de várias variáveis reais
2.4. Extremos condicionados

\section*{Lígia Abrunheiro}

ISCA-UA
Abril de $2026{ }^{\dagger}$
Licenciatura em Finanças
isca
universidade de aveiro
instituto superior de contabilidade
e administração
† Reedição da versão de 2025

\section*{Bibliografia/Bibliography}
- Harshbarger, R. J. e Reynolds, J.J., Matemática Aplicada: Administração, Economia e Ciências Sociais e Biológicas, McGraw-Hill Int. Brasil (2006).
Harshbarger, R. J. and Reynolds, J. J., Mathematical Applications for the Management, Life and Social Sciences, Cengage Learning, 11th ed. (2016).
- Larson, R., Hostetler, R. e Edwards, B., Cálculo, volume 2, McGraw-Hill Interamericana do Brasil, $8{ }^{\underline{\mathrm{a}}}$ edição (2006).
Larson, R., Applied Calculus for the Life and Social Sciences, 1st edition, Cengage Learning (2009).
- Pires C., Cálculo para Economia e Gestão, Escolar Ed. (2011).
- Stewart, J., Calculus: metric version, Cengage Learning, 8th edition (2015).
- Tan, S. T., Applied calculus for the managerial, life, and social sciences: a brief approach, Cengage Learning, 10th edition (2015).

\subsection*{2.4. Extremos condicionados. Aplicações.}

\section*{Objetivos:}
- Aplicar o método dos multiplicadores de Lagrange na resolução de problemas de otimização sujeitos a uma restrição:
- Identificar a função de 2 variáveis a otimizar (minimizar ou maximizar).
- Identificar a restrição e a função de 2 variáveis que a define.
- Construir a função de Lagrange (função de 3 variáveis).
- Aplicar a condição necessária de otimização.
- Aplicar a condição suficiente de otimização que envolve a matriz orlada associada à função de Lagrange e o seu determinante.
- Resolver problemas práticos de otimização condicionada.

\section*{Extremos condicionados}

Estudo dos extremos (máximos ou mínimos) de uma função sujeita a uma restrição, ou seja, cujas variáveis estão ligadas por uma condição.

Por exemplo, podemos maximizar a função de produção $P(x, y)$ (que depende das unidades de trabalho $x$ e das unidades de capital $y$ ) quando sujeita à restrição de $50.000 €$ no custo total de trabalho e capital.
- Supondo que o trabalho e o capital têm um custo, respetivamente, de $150 €$ e $250 €$ por unidade, temos
$$
x \text { u. trabalho }-150 x € \quad y \text { u. capital }-250 y €
$$
- Limitar o custo total a $50.000 €$, traduz-se na condição:
$$
150 x+250 y=50000, \quad \text { ou seja }, \quad 150 x+250 y-50000=0
$$

\section*{Problema de extremos condicionados para $z=f(x, y)$}

Na situação de otimização de uma função real de duas variáveis reais
$$
f(x, y)
$$
pretende-se determinar os pontos $(x, y)$ que otimizam (minimizam ou maximizam) a função $f$ sujeita a uma restrição
$$
\phi(x, y)=0 \quad \text { (equação de ligação). }
$$

No exemplo anterior, o problema é descrito por
$$
\max P(x, y) \quad \text { sujeita a } \underbrace{150 x+250 y-50000=0}_{\phi(x, y)=0} .
$$

Portanto, neste caso, $\phi(x, y)=150 x+250 y-50000$.

\section*{Método dos multiplicadores de Lagrange (continuação)}
$$
L(x, y, \lambda)=f(x, y)+\lambda \phi(x, y)
$$
© Condição de $1^{\underline{a}}$ ordem (condição necessária): Resolvemos o sistema de estacionaridade para a função de Lagrange:
$$
\left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } ( x , y , \lambda ) = 0 } \\
{ L _ { y } ^ { \prime } ( x , y , \lambda ) = 0 , \quad \text { isto é, } } \\
{ L _ { \lambda } ^ { \prime } ( x , y , \lambda ) = 0 }
\end{array} \quad \left\{\begin{array}{l}
L_{x}^{\prime}(x, y, \lambda)=0 \\
L_{y}^{\prime}(x, y, \lambda)=0 \\
\phi(x, y)=0
\end{array}\right.\right.
$$

Se $(a, b, \lambda)$ é solução deste sistema, então $(a, b)$ é um ponto crítico de $f$ quando sujeita à condição de ligação $\phi(x, y)=0$.

Cada ponto crítico tem associado um multiplicador de Lagrange.

\section*{Método dos multiplicadores de Lagrange}
(1) Construímos a designada função de Lagrange:
$$
L(x, y, \lambda)=f(x, y)+\lambda \phi(x, y)
$$
que é uma função auxiliar com uma nova variável $\lambda$ que se diz o multiplicador de Lagrange.
(2) Condição de $1^{\underline{a}}$ ordem (condição necessária):

Encontramos os pontos candidatos a extremantes condicionados de $f$, resolvendo um sistema de 3 equações e 3 incógnitas.

\section*{Condição de $2^{\underline{a}}$ ordem (condição suficiente)}

Analisamos os pontos críticos recorrendo a um método que envolve o determinante de uma matriz de ordem 3 designada por matriz orlada (matriz construída com as derivadas parciais de $2^{\underline{a}}$ ordem de $L$ ).

Exemplo 1: Fazendo uso do método dos multiplicadores de Lagrange, determine os extremos condicionados da função $f(x, y)=x^{2}+x y+x$ quando sujeita à restrição $2 x+y=1$.
- Identificação da função $\phi(x, y)$ que define a restrição. Ora,
$$
2 x+y=1 \Leftrightarrow 2 x+y-1=0
$$

Logo, $\phi(x, y)=2 x+y-1$.
- Construção da função de Lagrange:
$$
\begin{aligned}
L(x, y, \lambda) & =f(x, y)+\lambda \phi(x, y)= \\
& =x^{2}+x y+x+\lambda(2 x+y-1)
\end{aligned}
$$

\section*{(Exemplo 1 -continuação)}
- Determinação dos candidatos a extremantes condicionados:
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } = 0 } \\
{ L _ { y } ^ { \prime } = 0 } \\
{ L _ { \lambda } ^ { \prime } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ 2 x + y + 1 + 2 \lambda = 0 } \\
{ x + \lambda = 0 } \\
{ 2 x + y - 1 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
2 x+y+1+2 \lambda=0 \\
\lambda=-x \\
2 x+y-1=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ 2 x + y + 1 - 2 x = 0 } \\
{ - }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y = - 1 } \\
{ 2 x + y - 1 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=-1 \\
2 x-1-1=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y = - 1 } \\
{ \lambda = - x } \\
{ x = 1 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=-1 \\
\lambda=-1 \\
x=1
\end{array} \quad \text { solução do sistema: ponto }(1,-1,-1)\right.\right.
\end{aligned}
$$
$f$ (quando sujeita à restrição) tem um ponto crítico: $(1,-1) \operatorname{com} \lambda=-1$.
(Exemplo 1 - continuação) $L(x, y, \lambda)=x^{2}+x y+x+\lambda(2 x+y-1)$
- Cálculo das derivadas parciais da função de Lagrange $L$ :
$$
\begin{aligned}
L_{x}^{\prime}(x, y, \lambda) & =\left(x^{2}\right)_{x}^{\prime}+(x)_{x}^{\prime} y+(x)_{x}^{\prime}+\lambda(2 x+y-1)_{x}^{\prime}= \\
& =2 x+y+1+2 \lambda \\
L_{y}^{\prime}(x, y, \lambda) & =\left(x^{2}\right)_{y}^{\prime}+x(y)_{y}^{\prime}+(x)_{y}^{\prime}+\lambda(2 x+y-1)_{y}^{\prime}= \\
& =x+\lambda
\end{aligned}
$$
$$
\begin{aligned}
L_{\lambda}^{\prime}(x, y, \lambda) & =\left(x^{2}+x y+x\right)_{\lambda}^{\prime}+(\lambda)_{\lambda}^{\prime}(2 x+y-1)= \\
& =2 x+y-1
\end{aligned}
$$
(Exemplo 1 -continuação) $L(x, y, \lambda)=x^{2}+x y+x+\lambda(2 x+y-1)$
- Cálculo da matriz orlada e análise desta matriz no ponto crítico:
$$
\begin{aligned}
& \bar{H}(x, y, \lambda)= \\
& =\left[\begin{array}{ccc}
0 & (2 x+y-1)_{x}^{\prime} & (2 x+y-1)_{y}^{\prime} \\
(2 x+y-1)_{x}^{\prime} & (2 x+y+1+2 \lambda)_{x}^{\prime} & (2 x+y+1+2 \lambda)_{y}^{\prime} \\
(2 x+y-1)_{y}^{\prime} & (x+\lambda)_{x}^{\prime} & (x+\lambda)_{y}^{\prime}
\end{array}\right]= \\
& =\left[\begin{array}{lll}
0 & 2 & 1 \\
2 & 2 & 1 \\
1 & 1 & 0
\end{array}\right], \text { qualquer que seja o }(x, y, \lambda) . \text { É uma matriz constante. } \\
& |\bar{H}(1,-1,-1)|=\left|\begin{array}{lll}
0 & 2 & 1 \\
2 & 2 & 1 \\
1 & 1 & 0
\end{array}\right|=2>0 . \text { A função } f \text { tem um máximo } \\
& \text { condicionado em }(1,-1)
\end{aligned}
$$

Exemplo 2: A função de produção de Cobb-Douglas para um fabricante é dada por
$$
P(x, y)=100 x^{0,75} y^{0,25}
$$
onde $x$ representa as unidades de trabalho (a $150 €$ por unidade) e $y$ representa as unidades de capital (a $250 €$ por unidade).
Determine o nível máximo de produção sabendo que o custo total de trabalho e capital é limitado a $50.000 €$.
- Identificação da função $\phi(x, y)$ que define a restrição no custo. O custo total de trabalho e capital é dado por $150 x+250 y$ e portanto a condição a impor é
$$
150 x+250 y=50000 \Leftrightarrow 150 x+250 y-50000=0
$$

Logo, $\phi(x, y)=150 x+250 y-50000$.
(Exemplo 2 - cont.) $L(x, y, \lambda)=100 x^{0,75} y^{0,25}+\lambda(150 x+250 y$ - 50000)
- Cálculo das derivadas parciais da função de Lagrange $L$ :
$$
\begin{aligned}
L_{x}^{\prime}(x, y, \lambda) & =100\left(x^{0,75}\right)_{x}^{\prime} y^{0,25}+\lambda(150 x+250 y-50000)_{x}^{\prime}= \\
& =100 \cdot 0,75 x^{0,75-1} y^{0,25}+150 \lambda= \\
& =75 x^{-0,25} y^{0,25}+150 \lambda=75 \frac{y^{0,25}}{x^{0,25}}+150 \lambda \\
L_{y}^{\prime}(x, y, \lambda) & =100 x^{0,75}\left(y^{0,25}\right)_{y}^{\prime}+\lambda(150 x+250 y-50000)_{y}^{\prime}= \\
& =100 \cdot 0,25 x^{0,75} y^{0,25-1}+250 \lambda= \\
& =25 x^{0,75} y^{-0,75}+250 \lambda=25 \frac{x^{0,75}}{y^{0,75}}+250 \lambda \\
L_{\lambda}^{\prime}(x, y, \lambda) & =\left(100 x^{0,75} y^{0,25}\right)_{\lambda}^{\prime}+(\lambda)_{\lambda}^{\prime}(150 x+250 y-50000)= \\
& =150 x+250 y-50000
\end{aligned}
$$

\section*{(Exemplo 2 - continuação)}
$$
\max \underbrace{100 x^{0,75} y^{0,25}}_{P(x, y)} \quad \text { sujeita a } \quad \underbrace{150 x+250 y-50000}_{\phi(x, y)}=0
$$
- Construção da função de Lagrange:
$$
\begin{aligned}
L(x, y, \lambda) & =P(x, y)+\lambda \phi(x, y)= \\
& =100 x^{0,75} y^{0,25}+\lambda(150 x+250 y-50000)
\end{aligned}
$$
(Exemplo 2 - continuação) Determinação dos pontos críticos:
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } = 0 } \\
{ L _ { y } ^ { \prime } = 0 } \\
{ L _ { \lambda } ^ { \prime } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { c } 
{ 7 5 \frac { y ^ { 0 , 2 5 } } { x ^ { 0 , 2 5 } } + 1 5 0 \lambda = 0 } \\
{ 2 5 \frac { x ^ { 0 , 7 5 } } { y ^ { 0 , 7 5 } } + 2 5 0 \lambda = 0 } \\
{ 1 5 0 x + 2 5 0 y - 5 0 0 0 0 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{c}
\lambda=-\frac{y^{0,25}}{2 x^{0,25}} \\
\lambda=-\frac{x^{0,75}}{10 y^{0,75}}
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ \frac { x ^ { 0 , 7 5 } } { 1 0 y ^ { 0 , 7 5 } } = \frac { y ^ { 0 , 2 5 } } { 2 x ^ { 0 , 2 5 } } } \\
{ \overline { x } }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
x^{0,75+0,25}=5 y^{0,25+0,75} \\
\Leftrightarrow\left\{\begin{array} { c } 
{ x = 5 y } \\
{ \lambda = - \frac { 5 ^ { 0 , 7 5 } } { 1 0 } } \\
{ y = 5 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{c}
x=250 \\
\lambda=0,33 \\
y=50
\end{array}\right.\right.
\end{array}\right.\right. \\
& \Leftrightarrow\left\{\begin{array}{l}
x=50 x+250 y-50000=0
\end{array} \Leftrightarrow\right.
\end{aligned}
$$
(Exemplo 2 - continuação) Ponto crítico: $(250,50) \operatorname{com} \lambda \simeq 0,33$.
- Cálculo da matriz orlada e análise desta matriz no ponto crítico: prova-se que (fazer os cálculos!!)
$$
\begin{aligned}
& \bar{H}(250,50,0.33)=\left[\begin{array}{ccc}
0 & 150 & 250 \\
150 & -0,05 & 0,25 \\
250 & 0,25 & -0,0001
\end{array}\right] \\
& |\bar{H}(250,50,0.33)|=21875,25>0
\end{aligned}
$$

Logo, $P$ atinge um máximo condicionado em $(250,50)$.
A produção é máxima quando estão disponíveis 250 unidades de trabalho e 50 unidades de capital. O nível máximo de produção é de $P(250,50)=100(250)^{0,75}(50)^{0,25} \simeq 16.719$ unidades de produto.

Exemplo 4: Fazendo uso do método dos multiplicadores de Lagrange, estude a existência de extremos condicionados da função $f(x, y)=x y^{2}$ quando sujeita à restrição $x-2 y=1$.
- Identificar a função $\phi(x, y)$ que define a restrição.
$$
x-2 y=1 \Leftrightarrow x-2 y-1=0 . \text { Logo, } \phi(x, y)=x-2 y-1 .
$$
- Construir a função de Lagrange:
$$
L(x, y, \lambda)=f(x, y)+\lambda \phi(x, y)=x y^{2}+\lambda(x-2 y-1)
$$
- Cálcular as derivadas parciais da função de Lagrange $L$ :
$$
\begin{aligned}
L_{x}^{\prime}(x, y, \lambda) & =(x)_{x}^{\prime} y^{2}+\lambda(x-2 y-1)_{x}^{\prime}=y^{2}+\lambda \\
L_{y}^{\prime}(x, y, \lambda) & =x\left(y^{2}\right)_{y}^{\prime}+\lambda(x-2 y-1)_{y}^{\prime}=2 x y-2 \lambda \\
L_{\lambda}^{\prime}(x, y, \lambda) & =\left(x y^{2}\right)_{\lambda}^{\prime}+(\lambda)_{\lambda}^{\prime}(x-2 y-1)=x-2 y-1
\end{aligned}
$$

Exemplo 3: Seja $P(x, y)=100 x^{0,75} y^{0,25}$ a função de produção, com $x$ e $y$ a representar, respetivamente, as unidades de trabalho (a $150 €$ por unidade) e de capital (a $250 €$ por unidade). Formule o problema de otimização que permite encontrar o custo mínimo para produzir 20.000 unidades do produto.
- Função a minimizar: $C(x, y)=150 x+250 y$ (custo total).
- Restrição a impor (na produção): $100 x^{0,75} y^{0,25}=20000$
- Problema de optimização:
$$
\min \underbrace{150 x+250 y}_{C(x, y)} \quad \text { sujeita a } \quad \underbrace{100 x^{0,75} y^{0,25}-20000}_{\phi(x, y)}=0 .
$$
- Função de Lagrange:
$$
L(x, y, \lambda)=150 x+250 y+\lambda\left(100 x^{0,75} y^{0,25}-20000\right)
$$

\section*{(Exemplo 4 -continuação)}
- Determinar os pontos críticos:
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } = 0 } \\
{ L _ { y } ^ { \prime } = 0 } \\
{ L _ { \lambda } ^ { \prime } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y ^ { 2 } + \lambda = 0 } \\
{ 2 x y - 2 \lambda = 0 } \\
{ x - 2 y - 1 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
\lambda=-y^{2} \\
2 x y-2 \lambda=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ \lambda = - y ^ { 2 } } \\
{ 2 x y + 2 y ^ { 2 } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ \overline { 2 y ( x + y ) } = 0 } \\
{ \overline { y = 0 \vee x + y } = 0 \Leftrightarrow }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
\bar{x}
\end{array}\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ \lambda = - y ^ { 2 } } \\
{ y = 0 } \\
{ x - 2 y - 1 = 0 }
\end{array} \vee \left\{\begin{array} { l } 
{ \lambda = - y ^ { 2 } } \\
{ y = - x } \\
{ x - 2 y - 1 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ \lambda = 0 } \\
{ y = 0 } \\
{ x = 1 }
\end{array} \vee \left\{\begin{array}{l}
\lambda=-\frac{1}{9} \\
y=-\frac{1}{3} \\
x=\frac{1}{3}
\end{array}\right.\right.\right.\right.
\end{aligned}
$$

Pontos críticos: $(1,0)$ com $\lambda=0$; e $\left(\frac{1}{3},-\frac{1}{3}\right) \operatorname{com} \lambda=-\frac{1}{9}$
(Exemplo 4 -continuação) $L(x, y, \lambda)=x y^{2}+\lambda(x-2 y-1)$
- Determinar a matriz orlada para qualquer $(x, y, \lambda)$ :
$$
\begin{aligned}
& \bar{H}(x, y, \lambda)=\left[\begin{array}{ccc}
0 & \phi_{x}^{\prime} & \phi_{y}^{\prime} \\
\phi_{x}^{\prime} & \left(L_{x}^{\prime}\right)_{x}^{\prime} & \left(L_{x}^{\prime}\right)_{y}^{\prime} \\
\phi_{y}^{\prime} & \left(L_{y}^{\prime}\right)_{x}^{\prime} & \left(L_{y}^{\prime}\right)_{y}^{\prime}
\end{array}\right]= \\
& =\left[\begin{array}{ccc}
0 & (x-2 y-1)_{x}^{\prime} & (x-2 y-1)_{y}^{\prime} \\
(x-2 y-1)_{x}^{\prime} & \left(y^{2}+\lambda\right)_{x}^{\prime} & \left(y^{2}+\lambda\right)_{y}^{\prime} \\
(x-2 y-1)_{y}^{\prime} & (2 x y-2 \lambda)_{x}^{\prime} & (2 x y-2 \lambda)_{y}^{\prime}
\end{array}\right]= \\
& =\left[\begin{array}{ccc}
0 & 1 & -2 \\
1 & 0 & 2 y \\
-2 & 2 y & 2 x
\end{array}\right]
\end{aligned}
$$

\section*{(Exemplo 4 -continuação)}
- Cálcular o determinante da matriz orlada nos pontos críticos:
- Ponto crítico $(1,0)$ com $\lambda=0$.
$$
|\bar{H}(1,0,0)|=\left|\begin{array}{ccc}
0 & 1 & -2 \\
1 & 0 & 0 \\
-2 & 0 & 2
\end{array}\right|=-2<0
$$

O ponto $(1,0)$ é um minimizante condicionado de $f$.
- Ponto crítico $\left(\frac{1}{3},-\frac{1}{3}\right) \operatorname{com} \lambda=-\frac{1}{9}$.
$$
\left|\bar{H}\left(\frac{1}{3},-\frac{1}{3},-\frac{1}{9}\right)\right|=\left|\begin{array}{ccc}
0 & 1 & -2 \\
1 & 0 & -\frac{2}{3} \\
-2 & -\frac{2}{3} & \frac{2}{3}
\end{array}\right|=2>0
$$

O ponto $\left(\frac{1}{3},-\frac{1}{3}\right)$ é um maximizante condicionado de $f$.

Exemplo 5: Determine os candidatos a extremantes condicionados da função $f(x, y)=\frac{1}{x}+\frac{1}{y}$ quando sujeita à restrição $x+y=2$.
- $\phi(x, y)=x+y-2$, pois $x+y=2 \Leftrightarrow x+y-2=0$.
- $L(x, y, \lambda)=f(x, y)+\lambda \phi(x, y)=\frac{1}{x}+\frac{1}{y}+\lambda(x+y-2)$
$$
\begin{aligned}
& L_{x}^{\prime}(x, y, \lambda)=\left(\frac{1}{x}\right)_{x}^{\prime}+\left(\frac{1}{y}\right)_{x}^{\prime}+\lambda(x+y-2)_{x}^{\prime}=-\frac{1}{x^{2}}+\lambda \\
& L_{y}^{\prime}(x, y, \lambda)=\left(\frac{1}{x}\right)_{y}^{\prime}+\left(\frac{1}{y}\right)_{y}^{\prime}+\lambda(x+y-2)_{y}^{\prime}=-\frac{1}{y^{2}}+\lambda \\
& L_{\lambda}^{\prime}(x, y, \lambda)=\left(\frac{1}{x}+\frac{1}{y}\right)_{\lambda}^{\prime}+(\lambda)_{\lambda}^{\prime}(x+y-2)=x+y-2
\end{aligned}
$$
(Exemplo 5 -continuação) Pontos críticos:
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } = 0 } \\
{ L _ { y } ^ { \prime } = 0 } \\
{ L _ { \lambda } ^ { \prime } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { c } 
{ - \frac { 1 } { x ^ { 2 } } + \lambda = 0 } \\
{ - \frac { 1 } { y ^ { 2 } } + \lambda = 0 } \\
{ x + y - 2 = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
\lambda=\frac{1}{x^{2}} \\
\lambda=\frac{1}{y^{2}}
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ \frac { 1 } { y ^ { 2 } } = \frac { 1 } { x ^ { 2 } } } \\
{ \overline { } }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y ^ { 2 } = x ^ { 2 } } \\
{ \overline { } }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=x \vee y=-x \\
\bar{x}
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array}{l}
y=x \\
x+y-2=0
\end{array} \Leftrightarrow\left\{\begin{array}{l}
y=-x \\
x+y-2=0 \\
2 x=2
\end{array}\right\}\right. \\
& \Leftrightarrow \begin{cases}y=1 \\
\lambda=1 & \text { Existe uma única solução: }(1,1,1) .\end{cases} \\
& x=1 \\
& \text { f tem um único candidato a extremante condicionado: }
\end{aligned} \Leftrightarrow
$$

Exemplo 6: Determine o(s) extremo(s) condicionado(s) da função $f(x, y)=3 x+y+10$ quando sujeita à restrição $x^{2} y=12$.
- $\phi(x, y)=x^{2} y-12$, pois $x^{2} y=12 \Leftrightarrow x^{2} y-12=0$.
- $L(x, y, \lambda)=f(x, y)+\lambda \phi(x, y)=3 x+y+10+\lambda\left(x^{2} y-12\right)$
$$
\begin{aligned}
& L_{x}^{\prime}(x, y, \lambda)=3(x)_{x}^{\prime}+(y)_{x}^{\prime}+\lambda\left(x^{2} y-12\right)_{x}^{\prime}=3+2 \lambda x y \\
& L_{y}^{\prime}(x, y, \lambda)=(3 x)_{y}^{\prime}+(y)_{y}^{\prime}++\lambda\left(x^{2} y-12\right)_{y}^{\prime}=1+\lambda x^{2} \\
& L_{\lambda}^{\prime}(x, y, \lambda)=(3 x+y+10)_{\lambda}^{\prime}+(\lambda)_{\lambda}^{\prime}\left(x^{2} y-12\right)=x^{2} y-12
\end{aligned}
$$
(Exemplo 6 -continuação) $L(x, y, \lambda)=3 x+y+10+\lambda\left(x^{2} y-12\right)$
$$
\begin{aligned}
& \bar{H}(x, y, \lambda)=\left[\begin{array}{ccc}
0 & \left(x^{2} y-12\right)_{x}^{\prime} & \left(x^{2} y-12\right)_{y}^{\prime} \\
\left(x^{2} y-12\right)_{x}^{\prime} & (3+2 \lambda x y)_{x}^{\prime} & (3+2 \lambda x y)_{y}^{\prime} \\
\left(x^{2} y-12\right)_{y}^{\prime} & \left(1+\lambda x^{2}\right)_{x}^{\prime} & \left(1+\lambda x^{2}\right)_{y}^{\prime}
\end{array}\right]= \\
& =\left[\begin{array}{ccc}
0 & 2 x y & x^{2} \\
2 x y & 2 \lambda y & 2 \lambda x \\
x^{2} & 2 \lambda x & 0
\end{array}\right] \quad \text { matriz orlada para qualquer }(x, y, \lambda)
\end{aligned}
$$

Assim, $\left|\bar{H}\left(2,3,-\frac{1}{4}\right)\right|=\left|\begin{array}{ccc}0 & 12 & 4 \\ 12 & -\frac{3}{2} & -1 \\ 4 & -1 & 0\end{array}\right|=-72<0$
Concluímos que $f$ tem um minimizante condicionado em $(2,3)$.
(Exemplo 6 -continuação) Pontos críticos:
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ L _ { x } ^ { \prime } = 0 } \\
{ L _ { y } ^ { \prime } = 0 } \\
{ L _ { \lambda } ^ { \prime } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { c c } 
{ 3 + 2 \lambda x y = 0 } \\
{ 1 + \lambda x ^ { 2 } = 0 } & { \Leftrightarrow } \\
{ x ^ { 2 } y - 1 2 = 0 }
\end{array} \left\{\begin{array}{l}
3+2 \lambda x y=0 \\
\lambda=-\frac{1}{x^{2}}
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ 3 - 2 \frac { y } { x } = 0 } \\
{ \overline { } }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y = \frac { 3 } { 2 } x } \\
{ \overline { x ^ { 2 } y - 1 2 } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
\overline{3} x^{3}=12 \\
\overline{2}
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ \overline { x } = \frac { 3 } { 2 } x } \\
{ \lambda = - \frac { 1 } { x ^ { 2 } } } \\
{ x = 2 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=3 \\
\lambda=-\frac{1}{4} \\
x=2
\end{array}\right.\right.
\end{aligned}
$$

Solução do sistema: $\left(2,3,-\frac{1}{4}\right)$; Ponto crítico: $(2,3) \operatorname{com} \lambda=-\frac{1}{4}$.

Exemplo 7: Seja $C(x, y)=x^{3}-3 x y+y^{3}$ o custo na produção de $x$ unidades de um produto $A$ e $y$ unidades de um produto $B$. Suponha que os produtos $A$ e $B$ são vendidos a, respetivamente, $8 €$ e $130 €$ a unidade. Formule o problema de otimização que permite encontrar o lucro máximo quando se pretende produzir um total de 20 unidades de produto.
- Função a maximizar: $I(x, y)=8 x+130 y-C(x, y)$ (lucro total).
- Restrição a impor (na produção): $x+y=20$
- Problema de optimização:
$$
\max \underbrace{8 x+130 y-x^{3}+3 x y-y^{3}}_{l(x, y)} \text { sujeita a } \underbrace{x+y-20=0}_{\phi(x, y)} .
$$
- Função de Lagrange:
$$
L(x, y, \lambda)=8 x+130 y-x^{3}+3 x y-y^{3}+\lambda(x+y-20)
$$