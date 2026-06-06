\title{
Métodos Quantitativos
}

\section*{Capítulo 2}

Cálculo diferencial com funções reais de várias variáveis reais
2.3. Extremos locais

\section*{Lígia Abrunheiro}

ISCA-UA
Abril de $2026{ }^{\dagger}$
Licenciatura em Contabilidade e Licenciatura em Finanças

\section*{isca}
universidade de aveiro
instituto superior de contabilidade
e administração
Reedição da versão de 2025

\section*{Bibliografia/Bibliography}
- Harshbarger, R. J. e Reynolds, J.J., Matemática Aplicada: Administração, Economia e Ciências Sociais e Biológicas, McGraw-Hill Int. Brasil (2006).
Harshbarger, R. J. and Reynolds, J. J., Mathematical Applications for the Management, Life and Social Sciences, Cengage Learning, 11th ed. (2016).
- Larson, R., Hostetler, R. e Edwards, B., Cálculo, volume 2, McGraw-Hill Interamericana do Brasil, $8{ }^{\underline{\mathrm{a}}}$ edição (2006).
Larson, R., Applied Calculus for the Life and Social Sciences, 1st edition, Cengage Learning (2009).
- Pires C., Cálculo para Economia e Gestão, Escolar Ed. (2011).
- Stewart, J., Calculus: metric version, Cengage Learning, 8th edition (2015).
- Tan, S. T., Applied calculus for the managerial, life, and social sciences: a brief approach, Cengage Learning, 10th edition (2015).

\subsection*{2.3. Extremos locais. Aplicações.}

\section*{Objetivos:}
- Distinguir entre os conceitos de extremo local (máximo ou mínimo) e extremante local (maximizante ou minimizante).
- Usar a condição necessária de otimização para encontrar os pontos críticos.
- Calcular a matriz Hessiana e a sua cadeia própria de menores principais.
- Aplicar o método de Sylvester (condição suficiente de otimização).
- Resolver problemas de otimização de aplicação prática.

Um problema de otimização consiste em maximixar ou minimizar uma função objetivo (por exemplo, o lucro) que depende de um número finito de variáveis de entrada/decisão (estas variáveis representam as opções que podemos tomar de forma a atingir o objetivo, como por exemplo, as quantidades a produzir para atingir o lucro máximo). Por vezes, podem existir restrições físicas, naturais, económicas, etc. que condicionam o problema de otimização.

Vamos estudar dois tipos de problemas:
- Otimização livre (extremos locais - secção 2.3).
- Otimização com restrições (extremos condicionados - secção 2.4).

É importante saber formular o problema (identificando os seus objetivos, as variáveis de decisão e as possíveis restrições) para depois o conseguir resolver e interpretar os resultados obtidos (por exemplo, economicamente).

\section*{Definição}

Diz-se que $f: D_{f} \subseteq \mathbb{R}^{2} \rightarrow \mathbb{R}$ tem um máximo local (respetivamente, mínimo local) num ponto $(a, b) \in D_{f}$ se, para qualquer ponto $(x, y)$ pertencente a uma vizinhança de ( $a, b$ ), se tem
$$
f(x, y) \leq f(a, b) \quad(\text { respetivamente, } f(x, y) \geq f(a, b)) .
$$
- O ponto ( $a, b$ ) diz-se um extremante local de $f$ (ponto maximizante ou minimizante local).
- O valor $f(a, b)$ diz-se um extremo local de $f$ (valor máximo ou mínimo local).
(Estes conceitos generalizam-se para $f: D_{f} \subseteq \mathbb{R}^{n} \rightarrow \mathbb{R}$.)
- Condição de $1^{\underline{a}}$ ordem (condição necessária de otimização)

\section*{Teorema}

Seja $f: D_{f} \subseteq \mathbb{R}^{2} \rightarrow \mathbb{R}$ de classe $C^{1}$ numa vizinhança de $(a, b) \in D_{f}$ (ou seja, existem e são contínuas as derivadas parciais de $1^{\underline{a}}$ ordem). É condição necessária para que $f$ tenha um extremo local em ( $a, b$ ), que todas as derivadas parciais de $1^{\underline{a}}$ ordem de $f$ se anulem em $(a, b)$.

Assim, se $f$ tem um extremo local em ( $a, b$ ), então $f_{x}^{\prime}(a, b)=0$ e $f_{y}^{\prime}(a, b)=0$, ou seja, $(a, b)$ é solução do sistema $\left\{\begin{array}{l}f_{x}^{\prime}(x, y)=0 \\ f_{y}^{\prime}(x, y)=0\end{array}\right.$.
Os pontos que satisfazem este sistema dizem-se pontos críticos ou pontos de estacionaridade de $f$.

Se as desigualdades da definição anterior se verificam para qualquer $(x, y) \in D_{f}$, diz-se que $f$ tem em ( $a, b$ ) um máximo (respetivamente, mínimo) absoluto.
![](https://cdn.mathpix.com/cropped/a7674004-c16a-4113-8c31-1cfad7199dba-2.jpg?height=373&width=492&top_left_y=260&top_left_x=1946)

Exemplo 1: A função $f(x, y)=1+x^{2}+y^{2}$ tem um mínimo absoluto no ponto ( 0,0 ) de valor igual 1 . De facto,
$$
f(x, y)=1+x^{2}+y^{2} \geq 1=f(0,0), \quad \forall(x, y) \in \mathbb{R}^{2} .
$$

Exemplo 2: Seja $f(x, y)=x^{2} y+12 \ln (x+y)$. Mostre que $(-2,-1)$ é ponto crítico de $f$, mas $(-1,-2)$ não é.
- Derivadas parciais $1^{\underline{a}}$ ordem de $f$ :
$$
f_{x}^{\prime}(x, y)=2 x y+\frac{12}{x+y} \quad f_{y}^{\prime}(x, y)=x^{2}+\frac{12}{x+y} .
$$
- $(-2,-1)$ anula simultaneamente $f_{x}^{\prime}$ e $f_{y}^{\prime}$ (é ponto crítico):
$$
f_{x}^{\prime}(-2,-1)=4+\frac{12}{-3}=0 \quad f_{y}^{\prime}(-2,-1)=4+\frac{12}{-3}=0 .
$$
- $(-1,-2)$ não anula simultaneamente $f_{x}^{\prime}$ e $f_{y}^{\prime}$ (não é ponto crítico):
$$
f_{x}^{\prime}(-1,-2)=4+\frac{12}{-3}=0 \quad f_{y}^{\prime}(-1,-2)=1+\frac{12}{-3}=-3 \neq 0
$$

Exemplo 3: Determine os pontos críticos de
$$
\begin{gathered}
f(x, y)=x^{2}+2 x y+6 x . \\
\left\{\begin{array} { l } 
{ f _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ f _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ 2 x + 2 y + 6 = 0 } \\
{ 2 x = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
2 x+2 y+6=0 \\
x=0
\end{array} \Leftrightarrow\right.\right.\right. \\
\Leftrightarrow\left\{\begin{array} { l l } 
{ 2 y + 6 = 0 } \\
{ x = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{ll}
y=-3 & f \text { tem um único ponto crítico: } \\
x=0 & \text { o ponto }(0,-3) .
\end{array}\right.\right.
\end{gathered}
$$

Será que $(0,-3)$ é um extremante local?

Os pontos críticos são candidatos a extremantes locais: para um ponto ser extremante é necessário que seja ponto crítico. Contudo, esta condição não é suficiente para que o ponto seja extremante!

\section*{Matriz Hessiana}

Para cada ponto crítico $(a, b)$ a matriz Hessiana é definida por:
$$
H(a, b)=\left[\begin{array}{ll}
f_{x^{2}}^{\prime \prime}(a, b) & f_{x y}^{\prime \prime}(a, b) \\
f_{y x}^{\prime \prime}(a, b) & f_{y^{2}}^{\prime \prime}(a, b)
\end{array}\right]
$$
- Determina-se primeiro $H(x, y)$, para qualquer $(x, y)$ :
- Os elementos da $1^{\underline{a}}$ linha obtém-se derivando $f_{x}^{\prime}$ em ordem a $x$ (na $1^{\underline{a}}$ coluna) e em ordem a $y$ (na $2^{\underline{a}}$ coluna).
- Os elementos da $2^{\underline{a}}$ linha obtém-se derivando $f_{y}^{\prime}$ em ordem a $x$ (na $1^{\underline{a}}$ coluna) e em ordem a $y$ (na $2^{\underline{a}}$ coluna)
- Note-se que as derivadas mistas serão sempre iguais: $f_{x y}^{\prime \prime}=f_{y x}^{\prime \prime}$ (pois $f$ é de classe $C^{1}$ ).
- No final, substitui-se $(x, y)$ por $(a, b)$ de forma a obter a matriz com os quatro números reais $f_{x^{2}}^{\prime \prime}(a, b), f_{x y}^{\prime \prime}(a, b), f_{y x}^{\prime \prime}(a, b)$ e $f_{y^{2}}^{\prime \prime}(a, b)$.

\section*{Observação}

No estudo dos extremos locais de uma função de duas variáveis:
(1) Começamos com a resolução do sistema $\left\{\begin{array}{l}f_{x}^{\prime}(x, y)=0 \\ f_{y}^{\prime}(x, y)=0\end{array}\right.$.

No entanto, as soluções do sistema (ou seja, os pontos críticos) podem ou não ser extremantes locais da função.
(2) Depois, analisamos cada um dos pontos críticos, usando o método de Sylvester que nos dá uma condição suficiente (condição de $2^{\underline{a}}$ ordem) para a existência de extremos.
Este método envolve:
- As derivadas parciais de $2^{\underline{a}}$ ordem reunidas na matriz Hessiana.
- A cadeia própria de menores principais desta matriz.

Condição de $2^{\underline{a}}$ ordem (condição suficiente de otimização)

\section*{Método de Sylvester}

Seja $(a, b)$ um ponto crítico de $f: D_{f} \subseteq \mathbb{R}^{2} \rightarrow \mathbb{R}$.
- Se $H_{1}>0$ e $H_{2}>0$, então $(a, b)$ é um minimizante local de $f$.
- Se $H_{1}<0$ e $H_{2}>0$, então $(a, b)$ é um maximizante local de $f$.
- Se $H_{2}<0$, então não existe extremo local de $f$ em $(a, b)$. Neste caso, ( $a, b$ ) diz-se um ponto de sela. Exemplo:
![](https://cdn.mathpix.com/cropped/a7674004-c16a-4113-8c31-1cfad7199dba-4.jpg?height=195&width=293&top_left_y=621&top_left_x=628)
- Se $H_{2}=0$, então nada se conclui por este método.

Exemplo 4: Usando o método de Sylvester, determine e classifique os extremos locais de $f(x, y)=5 y^{2}+\frac{5}{2} x^{2}-x y^{2}$.
(1) Determinar os pontos críticos.
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ f _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ f _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ 5 x - y ^ { 2 } = 0 } \\
{ 1 0 y - 2 x y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
5 x-y^{2}=0 \\
2 y(5-x)=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ 5 x - y ^ { 2 } = 0 } \\
{ y = 0 \vee 5 - x = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ 5 x - y ^ { 2 } = 0 } \\
{ y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
5 x-y^{2}=0 \\
x=5
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ 5 x = 0 } \\
{ y = 0 }
\end{array} \vee \left\{\begin{array} { l } 
{ 2 5 - y ^ { 2 } = 0 } \\
{ x = 5 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ x = 0 } \\
{ y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y^{2}=25 \\
x=5
\end{array} \Leftrightarrow\right.\right.\right.\right.
\end{aligned}
$$

Exemplo 3 (continuação): $f(x, y)=x^{2}+2 x y+6 x$.
(1) Vimos anteriormente que $(0,-3)$ é o único ponto crítico de $f$.
(2) Cálculo da matriz Hessiana:
(Sabendo que $f_{x}^{\prime}(x, y)=2 x+2 y+6$ e $f_{y}^{\prime}(x, y)=2 x$.)
- Para um $(x, y)$ qualquer, vem
$$
H(x, y)=\left[\begin{array}{cc}
(2 x+2 y+6)_{x}^{\prime} & (2 x+2 y+6)_{y}^{\prime} \\
(2 x)_{x}^{\prime} & (2 x)_{y}^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
2 & 2 \\
2 & 0
\end{array}\right]
$$
- $\operatorname{Para}(x, y)=(0,-3)$, vem $H(0,-3)=\left[\begin{array}{ll}2 & 2 \\ 2 & 0\end{array}\right]$.
(3) Cadeia de menores principais:
$$
H_{1}=2>0 \quad H_{2}=\left|\begin{array}{ll}
2 & 2 \\
2 & 0
\end{array}\right|=0-4=-4<0
$$

Conclusão: não há extremo em $(0,-3)$ (método de Sylvester).

\section*{(Exemplo 4 - continuação:)}
$$
\begin{aligned}
& \Leftrightarrow\left\{\begin{array} { l } 
{ x = 0 } \\
{ y = 0 }
\end{array} \vee \left\{\begin{array}{l}
y=5 \\
x=5
\end{array} \vee y=-5\right.\right. \\
& \Leftrightarrow
\end{aligned}
$$
(2) Aplicar o método de Sylvester.

Matriz Hessiana:
$H(x, y)=\left[\begin{array}{cc}\left(5 x-y^{2}\right)_{x}^{\prime} & \left(5 x-y^{2}\right)_{y}^{\prime} \\ (10 y-2 x y)_{x}^{\prime} & (10 y-2 x y)_{y}^{\prime}\end{array}\right]=\left[\begin{array}{cc}5 & -2 y \\ -2 y & 10-2 x\end{array}\right]$
(Exemplo 4 - continuação:)
$$
\begin{aligned}
& H(0,0)=\left[\begin{array}{cc}
5 & 0 \\
0 & 10
\end{array}\right] \quad H_{1}=5>0 \quad H_{2}=\left|\begin{array}{cc}
5 & 0 \\
0 & 10
\end{array}\right|=50>0 \\
& H(5,5)=\left[\begin{array}{cc}
5 & -10 \\
-10 & 0
\end{array}\right] \quad H_{1}=5>0 \quad H_{2}=\left|\begin{array}{cc}
5 & -10 \\
-10 & 0
\end{array}\right|=-100<0 \\
& H(5,-5)=\left[\begin{array}{cc}
5 & 10 \\
10 & 0
\end{array}\right] \quad H_{1}=5>0 \quad H_{2}=\left|\begin{array}{cc}
5 & 10 \\
10 & 0
\end{array}\right|=-100<0
\end{aligned}
$$

Pelo método de Sylvester concluímos que ( 0,0 ) é um minimizante local de $f$; e que em $(5,5)$ e $(5,-5)$ não existem extremos locais.

\section*{(Exemplo 5 - continuação:)}
$$
\Leftrightarrow\left\{\begin{array} { l } 
{ x ^ { 3 } = - 1 } \\
{ y = 0 }
\end{array} \vee \left\{\begin{array} { l } 
{ \mathbf { 1 } = \mathbf { 0 } \text { (P. Falsa) } } \\
{ y = - x }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
x=-1 \\
y=0
\end{array}\right.\right.\right.
$$
$f$ tem um único ponto crítico que é o ponto $(-1,0)$.
(2) Usando o método de Sylvester, o que pode concluir sobre a natureza local deste ponto crítico?

Ao calcular as derivadas de $2^{\underline{a}}$ ordem tenha em atenção o seguinte:
$$
f_{x}^{\prime}(x, y)=4 y^{3}+4 x^{3}+4 \neq y^{3}+x^{3}+1
$$

\section*{Exemplo 5:}
(1) Quais os pontos críticos de $f(x, y)=3 y^{4}+4 x y^{3}+x^{4}+4 x$ ?
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ f _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ f _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
4 y^{3}+4 x^{3}+4=0 \\
12 y^{3}+12 x y^{2}=0
\end{array} \Leftrightarrow\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y ^ { 3 } + x ^ { 3 } + 1 = 0 } \\
{ 1 2 y ^ { 2 } ( y + x ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y^{3}+x^{3}+1=0 \\
12 y^{2}=0 \vee y+x=0
\end{array} \Leftrightarrow\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y ^ { 3 } + x ^ { 3 } + 1 = 0 } \\
{ y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y^{3}+x^{3}+1=0 \\
y=-x
\end{array} \Leftrightarrow\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ x ^ { 3 } + 1 = 0 } \\
{ y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
-x^{3}+x^{3}+1=0 \\
y=-x
\end{array} \Leftrightarrow\right.\right.
\end{aligned}
$$

\section*{(Exemplo 5 - continuação:)}

Matriz Hessiana:
$$
\begin{aligned}
H(x, y) & =\left[\begin{array}{cc}
\left(4 y^{3}+4 x^{3}+4\right)_{x}^{\prime} & \left(4 y^{3}+4 x^{3}+4\right)_{y}^{\prime} \\
\left(12 y^{3}+12 x y^{2}\right)_{x}^{\prime} & \left(12 y^{3}+12 x y^{2}\right)_{y}^{\prime}
\end{array}\right]= \\
& =\left[\begin{array}{cc}
12 x^{2} & 12 y^{2} \\
12 y^{2} & 36 y^{2}+24 x y
\end{array}\right] \\
H(-1,0) & =\left[\begin{array}{cc}
12 & 0 \\
0 & 0
\end{array}\right] \quad H_{1}=12>0 \quad H_{2}=\left|\begin{array}{cc}
12 & 0 \\
0 & 0
\end{array}\right|=0
\end{aligned}
$$

Usando o método de Sylvester, nada se pode concluir.

\section*{Exemplo 6:}
(1) Quais os pontos críticos de $f(x, y)=x y+\frac{1}{x}+\ln y$ ?
$$
\begin{aligned}
& \left\{\begin{array} { l } 
{ f _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ f _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y - \frac { 1 } { x ^ { 2 } } = 0 } \\
{ x + \frac { 1 } { y } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=\frac{1}{x^{2}} \\
x+\frac{1}{y}=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y = \frac { 1 } { x ^ { 2 } } } \\
{ x + x ^ { 2 } = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y = \frac { 1 } { x ^ { 2 } } } \\
{ x ( x + 1 ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=\frac{1}{x^{2}} \\
x=0 \vee x+1=0
\end{array} \Leftrightarrow\right.\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y = \frac { 1 } { \mathbf { x } ^ { 2 } } } \\
{ \mathbf { x } = \mathbf { 0 } }
\end{array} \vee \left\{\begin{array} { l } 
{ y = \frac { 1 } { x ^ { 2 } } } \\
{ x = - 1 }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
y=1 \\
x=-1
\end{array} \quad \text { Ponto crítico de } f:\right.\right.\right. \\
& \text { impossível! }
\end{aligned}
$$

Exemplo 7: Para a função $f$ a seguir definida, determine os pontos críticos e estude a sua natureza local usando o método de Sylvester:
$$
f(x, y)=x y \mathrm{e}^{-(x+y)}
$$
(1) Determinar os pontos críticos.
$$
\begin{aligned}
& \left\{\begin{array} { c } 
{ f _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ f _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{c}
y \mathrm{e}^{-(x+y)}-x y \mathrm{e}^{-(x+y)}=0 \\
x \mathrm{e}^{-(x+y)}-x y \mathrm{e}^{-(x+y)}=0
\end{array} \Leftrightarrow\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { c c } 
{ ( y - x y ) \mathrm { e } ^ { - ( x + y ) } = 0 } & { \Leftrightarrow } \\
{ ( x - x y ) \mathrm { e } ^ { - ( x + y ) } = 0 } & { ( e ^ { x } \neq 0 , \forall X \in \mathbb { R } ) }
\end{array} \left\{\begin{array}{c}
y-x y=0 \\
x-x y=0
\end{array} \Leftrightarrow\right.\right. \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ y ( 1 - x ) = 0 } \\
{ x - x y = 0 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ y = 0 } \\
{ x - x y = 0 }
\end{array} \vee \left\{\begin{array}{l}
x=1 \\
x-x y=0
\end{array} \Leftrightarrow\right.\right.\right.
\end{aligned}
$$

\section*{(Exemplo 6 - continuação:)}
(2) Usando o método de Sylvester, o que pode concluir sobre a natureza local deste ponto crítico?
Matriz Hessiana:
$$
\begin{aligned}
H(x, y) & =\left[\begin{array}{cc}
\left(y-\frac{1}{x^{2}}\right)_{x}^{\prime} & \left(y-\frac{1}{x^{2}}\right)_{y}^{\prime} \\
\left(x+\frac{1}{y}\right)_{x}^{\prime} & \left(x+\frac{1}{y}\right)_{y}^{\prime}
\end{array}\right]=\left[\begin{array}{cc}
\frac{2}{x^{3}} & 1 \\
1 & -\frac{1}{y^{2}}
\end{array}\right] \\
H(-1,1) & =\left[\begin{array}{cc}
-2 & 1 \\
1 & -1
\end{array}\right] \quad H_{1}=-2<0 \quad H_{2}=\left|\begin{array}{cc}
-2 & 1 \\
1 & -1
\end{array}\right|=1>0
\end{aligned}
$$

Conclui-se que $f$ atinge um máximo local em $(-1,1)$.

\section*{(Exemplo 7 - continuação:)}
$$
\Leftrightarrow\left\{\begin{array} { l } 
{ x = 0 } \\
{ y = 0 }
\end{array} \vee \left\{\begin{array}{l}
x=1 \\
y=1
\end{array} \quad \text { Ponto críticos de } f:(0,0) \text { e }(1,1) .\right.\right.
$$
(2) Aplicar o método de Sylvester.

Note-se que:
$$
\begin{aligned}
& f_{x}^{\prime}(x, y)=y \mathrm{e}^{-(x+y)}-x y \mathrm{e}^{-(x+y)}=(y-x y) \mathrm{e}^{-(x+y)} \\
& f_{y}^{\prime}(x, y)=x \mathrm{e}^{-(x+y)}-x y \mathrm{e}^{-(x+y)}=(x-x y) \mathrm{e}^{-(x+y)}
\end{aligned}
$$

Derivando $f_{x}^{\prime}$ e $f_{y}^{\prime}$ em ordem a $x$ e a $y$ obtemos as derivadas parciais de $2^{\underline{a}}$ ordem (fazer os cálculos!).

\section*{(Exemplo 7 - continuação:)}

Matriz Hessiana:
$$
H(x, y)=\left[\begin{array}{cc}
(x y-2 y) \mathrm{e}^{-(x+y)} & (1-x-y+x y) \mathrm{e}^{-(x+y)} \\
(1-x-y+x y) \mathrm{e}^{-(x+y)} & (x y-2 x) \mathrm{e}^{-(x+y)}
\end{array}\right]
$$

Assim,
$$
\begin{aligned}
& H(0,0)=\left[\begin{array}{ll}
0 & 1 \\
1 & 0
\end{array}\right] \quad H_{1}=0 \quad H_{2}=\left|\begin{array}{ll}
0 & 1 \\
1 & 0
\end{array}\right|=-1<0 \\
& H(1,1)=\left[\begin{array}{cc}
-\frac{1}{\mathrm{e}} & 0 \\
0 & -\frac{1}{\mathrm{e}}
\end{array}\right] \quad H_{1}=-\frac{1}{\mathrm{e}}<0 \quad H_{2}=\left|\begin{array}{cc}
-\frac{1}{\mathrm{e}} & 0 \\
0 & -\frac{1}{\mathrm{e}}
\end{array}\right|=\frac{1}{\mathrm{e}^{2}}>0
\end{aligned}
$$

Pelo método de Sylvester concluímos que ( 1,1 ) é um maximizante local de $f$; e que em $(0,0)$ não existe extremo local.
(Exemplo 8 - continuação) Matriz Hessiana:
$$
\begin{aligned}
& H(28,100)=\left[\begin{array}{cc}
\left(7,56 x-0,27 x^{2}\right)_{x}^{\prime} & \left(7,56 x-0,27 x^{2}\right)_{y}^{\prime} \\
\left(3 y-0,03 y^{2}\right)_{x}^{\prime} & \left(3 y-0,03 y^{2}\right)_{y}^{\prime}
\end{array}\right]_{(x, y)=(28,100)}= \\
& =\left[\begin{array}{cc}
7,56-0,54 x & 0 \\
0 & 3-0,06 y
\end{array}\right]_{(x, y)=(28,100)}=\left[\begin{array}{cc}
-7,56 & 0 \\
0 & -3
\end{array}\right] \\
& H_{1}=-7,56<0 \quad H_{2}=\left|\begin{array}{cc}
-7,56 & 0 \\
0 & -3
\end{array}\right|=22,68>0
\end{aligned}
$$

Pelo método de Sylvester concluímos que $(28,100)$ é um maximizante local de $P$. Isto é, a utilização de 28 unidades da primeira matéria-prima e de 100 unidades da segunda matéria-prima maximizam a produção. Neste caso, a produção máxima é de $P(28,100) \simeq 5988$ unidades de produto.

Exemplo 8: Seja $P(x, y)=3,78 x^{2}+1,5 y^{2}-0,09 x^{3}-0,01 y^{3}$ a função de produção para um produto com $x$ unidades de uma matéria-prima e $y$ unidades de uma segunda matéria-prima. Encontre os valores de $x$ e $y$ que maximizam a produção.
$$
\left.\begin{array}{l}
\left\{\begin{array} { l } 
{ P _ { x } ^ { \prime } ( x , y ) = 0 } \\
{ P _ { y } ^ { \prime } ( x , y ) = 0 }
\end{array} \Leftrightarrow \left\{\begin{array}{c}
7,56 x-0,27 x^{2}=0 \\
3 y-0,03 y^{2}=0
\end{array} \Leftrightarrow\right.\right. \\
\Leftrightarrow\left\{\begin{array}{l}
x(7,56-0,27 x)=0 \\
y(3-0,03 y)=0
\end{array} \quad \Leftrightarrow \neq 0, y \neq 0\right.
\end{array}\right\}\left\{\begin{array}{c}
7,56-0,27 x=0 \\
3-0,03 y=0
\end{array} \Leftrightarrow\right.
$$