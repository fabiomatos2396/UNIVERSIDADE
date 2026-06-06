\section*{Métodos Quantitativos}

\section*{Capítulo 2}

Cálculo diferencial com funções reais de várias variáveis reais
2.1. Funções reais de várias variáveis reais. Derivadas parciais.

\section*{Lígia Abrunheiro}

\section*{ISCA-UA}

Março de $2026{ }^{\dagger}$
Licenciatura em Contabilidade e Licenciatura em Finanças

\section*{isca}
universidade de aveiro
Reedição da versão de 2025
instituto superior de contabilidade
e administração

\section*{Bibliografia/Bibliography}
- Harshbarger, R. J. e Reynolds, J.J., Matemática Aplicada: Administração, Economia e Ciências Sociais e Biológicas, McGraw-Hill Int. Brasil (2006).
Harshbarger, R. J. and Reynolds, J. J., Mathematical Applications for the Management, Life and Social Sciences, Cengage Learning, 11th ed. (2016).
- Larson, R., Hostetler, R. e Edwards, B., Cálculo, volume 2, McGraw-Hill Interamericana do Brasil, $8{ }^{\underline{\mathrm{a}}}$ edição (2006).
Larson, R., Applied Calculus for the Life and Social Sciences, 1st edition, Cengage Learning (2009).
- Pires C., Cálculo para Economia e Gestão, Escolar Ed. (2011).
- Stewart, J., Calculus: metric version, Cengage Learning, 8th edition (2015).
- Tan, S. T., Applied calculus for the managerial, life, and social sciences: a brief approach, Cengage Learning, 10th edition (2015).

\subsection*{2.1. Funções reais de várias variáveis reais. Derivadas parciais.}

\section*{Objetivos:}
- Usar o conceito de função real de duas ou três variáveis reais.
- Calcular as derivadas parciais de $1^{\underline{a}}$ ordem de uma função real de 2 ou 3 variáveis reais (a expressão geral e as derivadas no ponto).
- Calcular as derivadas parciais de $2^{\underline{a}}$ ordem de uma função real de 2 ou 3 variáveis reais (a expressão geral e as derivadas no ponto).
- Resolver problemas de aplicação prática recorrendo à interpretação do conceito de derivada parcial.

\section*{Funções reais de várias variáveis reais}

\section*{Função real de duas variáveis reais}
$$
\begin{aligned}
f: \quad D_{f} \subseteq \mathbb{R}^{2} & \longrightarrow \mathbb{R} \\
(x, y) & \longmapsto z
\end{aligned}
$$
$f$ associa a cada par ordenado $(x, y) \in D_{f}$ um e um só $z \in \mathbb{R}$.
- $x$ e $y$ são as variáveis independentes.
- $z$ é a variável dependente.
- $z$ diz-se a imagem de ( $x, y$ ) por $f$ ou o valor de $f$ em ( $x, y$ ).
- $z$ representa-se por $f(x, y)$, ou seja, $z=f(x, y)$.
- Domínio de f $D_{f}=\left\{(x, y) \in \mathbb{R}^{2}: f(x, y) \in \mathbb{R}\right\}$
$D_{f}$ é um subconjunto de um espaço de dimensão dois.
- Contradomínio de $\mathrm{f} \quad C D_{f}=\left\{f(x, y) \in \mathbb{R}:(x, y) \in D_{f}\right\}$.
- Gráfico de $\mathbf{f}=\left\{(x, y, f(x, y)) \in \mathbb{R}^{3}:(x, y) \in D_{f}\right\}$.

O gráfico de $f$ é um subconjunto de um espaço de dimensão três.
![](https://cdn.mathpix.com/cropped/fc1c1722-5fcd-4eab-a95d-43d02d94b586-2.jpg?height=385&width=442&top_left_y=484&top_left_x=278)
![](https://cdn.mathpix.com/cropped/fc1c1722-5fcd-4eab-a95d-43d02d94b586-2.jpg?height=330&width=318&top_left_y=488&top_left_x=854)

\section*{Função real de três variáveis reais}
$$
\begin{array}{rlcl}
f: & D_{f} \subseteq \mathbb{R}^{3} & \longrightarrow & \mathbb{R} \\
& (x, y, z) & \longmapsto & w
\end{array}
$$
$f$ associa a cada terno ordenado $(x, y, z) \in D_{f}$ um e um só $w \in \mathbb{R}$, $w=f(x, y, z)$.

O gráfico de $f$ é um subconjunto de um espaço de dimensão quatro, $\mathbb{R}^{4}$, portanto não pode ser visualizado.

\section*{Função real de $n$ variáveis reais}
$$
\begin{array}{lccc}
f: & D_{f} \subseteq \mathbb{R}^{n} & \longrightarrow & \mathbb{R} \\
\left(x_{1}, x_{2}, \ldots, x_{n}\right) & \longmapsto & f\left(x_{1}, x_{2}, \ldots, x_{n}\right)
\end{array}
$$
$f$ associa a cada $n$-uplo $\left(x_{1}, x_{2}, \ldots, x_{n}\right) \in D_{f}$ um único número real $f\left(x_{1}, x_{2}, \ldots, x_{n}\right)$.

Exemplo 1: Uma função de produção de Cobb-Douglas $f(L, K)=A L^{\alpha} K^{\beta}$ ( $A, \alpha, \beta$ constantes) é uma função real de 2 variáveis reais, $Q=f(L, K)$, onde $Q=f(L, K)$ é o output (número de unidades produzidas)
$L=$ entrada de trabalho (número de trabalhadores)
$K=$ entrada de capital (unidades monetárias)
Se $f(L, K)=100 L^{0,8} K^{0,2}$ qual o nível de produção quando temos:
- 100 trabalhadores e 50 u.m. de capital? Para $L=100$ e $K=50$, $f(100,50)=100 \times 100^{0,8} \times 50^{0,2} \simeq 8705,5$ unidades produzidas.
- 200 trabalhadores e 100 u.m. de capital? Para $L=200$ e $K=100$, $f(200,100)=100 \times 200^{0,8} \times 100^{0,2} \simeq 17411$ unidades produzidas.

Note-se que $f(200,100)=2 f(100,50)$. O nível de produção duplica quando se duplicam simultaneamente as unidades de trabalho e de capital.

\section*{Exemplo 2:}
![](https://cdn.mathpix.com/cropped/fc1c1722-5fcd-4eab-a95d-43d02d94b586-2.jpg?height=188&width=657&top_left_y=1217&top_left_x=1653)

Custos de construção da caixa:
$0,75 € / \mathrm{cm}^{2}$ (base da caixa)
$0,40 € / \mathrm{cm}^{2} \quad$ (lados da caixa)

Escreva o custo $C$ para construir a caixa como uma função de $x, y$ e $z$.
Custo da base: $0,75 x y$ euros
Custo das partes da frente e de trás: $2 \times 0,4 x z$ euros
Custo dos lados direito e esquerdo: $2 \times 0,4 y z$ euros
O custo total é dado pela função real de três variáveis reais:
$$
C(x, y, z)=0,75 x y+0,8 x z+0,8 y z
$$

Exemplo 3: $f(x, y)=\frac{\sqrt{x+y}}{x-y}$ função real de $\underline{2 \text { variáveis reais }}$
Os pontos $\left(\frac{3}{4}, \frac{1}{4}\right)$ e $(2,2)$ pertencem ao domínio de $\mathbf{f}$ ?
- $f\left(\frac{3}{4}, \frac{1}{4}\right)=\frac{\sqrt{\frac{3}{4}+\frac{1}{4}}}{\frac{3}{4}-\frac{1}{4}}=\frac{1}{\frac{1}{2}}=2 \in \mathbb{R}$.
- $f(2,2)=\frac{\sqrt{2+2}}{2-2}=\frac{2}{0}=\infty \notin \mathbb{R}$.

Então, $\left(\frac{3}{4}, \frac{1}{4}\right) \in D_{f}$ e $(2,2) \notin D_{f}$.
Existe a imagem de $(2,2)$ por $f$ ? Não.

Exemplo 5: $f(x, y)=\frac{\sqrt{x^{2}-y^{2}}}{x} \quad$ função real de $\underline{2 \text { variáveis reais }}$
Os pontos $(2,0,1)$ e $(1,2,-3)$ pertencem ao gráfico de $\mathbf{f}$ ?
- $f(2,0)=\frac{\sqrt{2^{2}-0^{2}}}{2}=\frac{\sqrt{4}}{2}=1$.

Então, ( $2,0,1$ ) pertence ao gráfico. O ponto do gráfico correspondente ao par $(x, y)=(2,0)$ é o ponto $(x, y, f(x, y))=(2,0,1)$.
- $f(1,2)=\frac{\sqrt{1^{2}-2^{2}}}{1}=\sqrt{-3} \notin \mathbb{R}$. Então, $(1,2) \notin D_{f}$.

Não há nenhum ponto do gráfico correspondente a $(x, y)=(1,2)$.

Exemplo 4: $f(x, y, z)=\frac{x y}{z} \quad$ função real de $\underline{3 \text { variáveis reais }}$
Os pontos $(1,0,2),(2,1,0)$ e $(0,2,0)$ pertencem ao $\mathbf{D}_{\mathbf{f}}$ ?
- $f(1,0,2)=\frac{0}{2}=0 \in \mathbb{R}$.
- $f(2,1,0)=\frac{2}{0}=\infty \notin \mathbb{R}$.
- $f(0,2,0)=\frac{0}{0} \notin \mathbb{R}$.

Então, $(1,0,2) \in D_{f}$ e $(2,1,0),(0,2,0) \notin D_{f}$.
Qual é o valor de $f$ em $(1,0,2)$ ? É 0 .

Exemplo 6: $f(x, y, z)=3-\left(x-y^{2}\right)(z-1)$ função real de 3 variáveis reais
- Os pontos $(3,2,0,2)$ e $(3,2,0,4)$ pertencem ao gráfico de $\mathbf{f}$ ?
$f(3,2,0)=3-\left(3-2^{2}\right)(0-1)=3-(-1)(-1)=2$.
Então, ( $3,2,0,2$ ) pertence ao gráfico de $f$ e ( $3,2,0,4$ ) não pertence.

O ponto do gráfico correspondente ao terno $(x, y, z)=(3,2,0)$ é o ponto $(x, y, z, f(x, y, z))=(3,2,0,2)$.
- Qual é a imagem de $(3,2,0)$ por $f$ ? É 2.

Exemplo 7: As seguintes equações em $x, y$ e $z$ definem implicitamente $z$ como uma função das duas variáveis $x$ e $y$ ?
- $x^{2} z+y z-x y=2 \Leftrightarrow\left(x^{2}+y\right) z=2+x y \Leftrightarrow z=\frac{2+x y}{x^{2}+y}$ Sim
- $x^{2}+y^{2}-8 z^{3}=0 \Leftrightarrow-8 z^{3}=-x^{2}-y^{2} \Leftrightarrow 8 z^{3}=x^{2}+y^{2} \Leftrightarrow \Leftrightarrow z^{3}=\frac{x^{2}+y^{2}}{8} \Leftrightarrow z=\sqrt[3]{\frac{x^{2}+y^{2}}{8}} \Leftrightarrow z=\frac{\sqrt[3]{x^{2}+y^{2}}}{2} \quad$ Sim
- $z^{2}+y^{2}-8 x=0 \Leftrightarrow z^{2}=8 x-y^{2} \Leftrightarrow \Leftrightarrow z=\sqrt{8 x-y^{2}} \vee z=-\sqrt{8 x-y^{2}} \quad$ Não (dois valores de $z$ )
- $y-\ln (z-4)=x^{2} \Leftrightarrow-\ln (z-4)=x^{2}-y \Leftrightarrow \ln (z-4)=y-x^{2} \Leftrightarrow z-4=\mathrm{e}^{y-x^{2}} \Leftrightarrow z=\mathrm{e}^{y-x^{2}}+4 \quad$ Sim

\section*{As 2 derivadas parciais de $1^{\underline{\text { a }}}$ ordem de $z=f(x, y)$}
- Derivada parcial de f em ordem a x:

Mede a taxa de variação de $f$ em relação a $x$, com $y$ constante.
Denota-se por $\frac{\partial f}{\partial x}(x, y)$ ou $f_{x}^{\prime}(x, y)$.
Calculada num ponto $(a, b)$, denota-se por $\left.\frac{\partial f}{\partial x}\right|_{(a, b)}$ ou $f_{x}^{\prime}(a, b)$.
- Derivada parcial de f em ordem a y:

Mede a taxa de variação de $f$ em relação a $y, \operatorname{com} x$ constante.
Denota-se por $\frac{\partial f}{\partial y}(x, y)$ ou $f_{y}^{\prime}(x, y)$.
Calculada num ponto $(a, b)$, denota-se por $\left.\frac{\partial f}{\partial y}\right|_{(a, b)}$ ou $f_{y}^{\prime}(a, b)$.

\section*{Derivadas parciais}

Seja $z=f(x, y)$ uma função real de duas variáveis reais ( $x$ e $y$ são as variáveis independentes e $z$ é a variável dependente).

O processo de derivação parcial consiste em determinar a taxa de variação da variável dependente $z$ relativamente a uma das variáveis independentes $x$ ou $y$, quando se mantém a outra variável independente ( $y$ ou $x$, respetivamente) constante (fixa).

Por exemplo, se o custo para a produção de um determinado produto depender de duas variáveis $x$ e $y$, podemos analisar o custo marginal em relação a cada uma das variáveis. Nesse caso, estamos a usar o processo de derivação parcial da função custo (ver exemplo 13).

\section*{Usar a tabela de derivadas (regras gerais de derivação)}
- Para calcular a função derivada parcial $f_{x}^{\prime}(x, y)$ : Consideramos $y$ constante e derivamos em relação a $x$.
- Para calcular a função derivada parcial $f_{y}^{\prime}(x, y)$ : Consideramos $x$ constante e derivamos em relação a $y$.
(Recorde-se que a derivada de uma constante é igual a zero.)
Note-se que:
$$
\begin{array}{ll}
(x)_{x}^{\prime}=1 & (x)_{y}^{\prime}=0 \\
(y)_{x}^{\prime}=0 & (y)_{y}^{\prime}=1
\end{array}
$$

Exemplo 8: Calcular as derivadas parciais de $1^{\underline{a}}$ ordem da função:
$$
f(x, y)=x^{2}+x^{2} y^{3}
$$

Vamos usar as regras de derivação:
$$
\begin{aligned}
& (u+v)^{\prime}=u^{\prime}+v^{\prime} \\
& (u v)^{\prime}=u^{\prime} v+u v^{\prime} \\
& \left(u^{n}\right)^{\prime}=n u^{\prime} u^{n-1}(n \in \mathbb{R})
\end{aligned}
$$
- $f_{x}^{\prime}(x, y)=\left(x^{2}\right)_{x}^{\prime}+\left(x^{2}\right)_{x}^{\prime} y^{3}+x^{2}\left(y^{3}\right)_{x}^{\prime}=2 x+2 x y^{3}$.

Note-se que $\left(y^{3}\right)_{x}^{\prime}=0$ pois $y^{3}$ é constante em relação a $x$.
- $f_{y}^{\prime}(x, y)=\left(x^{2}\right)_{y}^{\prime}+\left(x^{2}\right)_{y}^{\prime} y^{3}+x^{2}\left(y^{3}\right)_{y}^{\prime}=3 x^{2} y^{2}$.

Note-se que $\left(x^{2}\right)_{y}^{\prime}=0$ pois $x^{2}$ é constante em relação a $y$.

\section*{As 3 derivadas parciais de $1^{\underline{a}}$ ordem de $w=f(x, y, z)$}

O conceito de derivada parcial pode ser estendido para funções de três ou mais variáveis reais. Para uma função $f$ de três variáveis reais temos 3 derivadas parciais de $\mathbf{1}^{\text {a }}$ ordem: $\mathbf{f}_{\mathrm{x}}^{\prime}, \mathbf{f}_{\mathbf{y}}^{\prime}$ e $\mathbf{f}_{\mathrm{z}}^{\prime}$.
(Cada derivada é calculada mantendo duas das variáveis constantes).

Note-se que:
$$
\begin{array}{lll}
(x)_{x}^{\prime}=1 & (x)_{y}^{\prime}=0 & (x)_{z}^{\prime}=0 \\
(y)_{x}^{\prime}=0 & (y)_{y}^{\prime}=1 & (y)_{z}^{\prime}=0 \\
(z)_{x}^{\prime}=0 & (z)_{y}^{\prime}=0 & (z)_{z}^{\prime}=1
\end{array}
$$

\section*{Exemplo 9:}
(1) Calcular as derivadas $f_{x}^{\prime}$ e $f_{y}^{\prime}$ para $f(x, y)=\frac{1+\mathrm{e}^{x}}{y}$.

Usar: $\left(\frac{u}{v}\right)^{\prime}=\frac{u^{\prime} v-u v^{\prime}}{v^{2}}(v \neq 0)$ e $\quad\left(\mathrm{e}^{u}\right)^{\prime}=u^{\prime} \mathrm{e}^{u}$.
- $f_{x}^{\prime}(x, y)=\frac{\left(1+\mathrm{e}^{x}\right)_{x}^{\prime} y-\left(1+\mathrm{e}^{x}\right)(y)_{x}^{\prime}}{y^{2}}=\frac{y \mathrm{e}^{x}}{y^{2}}=\frac{\mathrm{e}^{x}}{y}$.
- $f_{y}^{\prime}(x, y)=\frac{\left(1+\mathrm{e}^{x}\right)_{y}^{\prime} y-\left(1+\mathrm{e}^{x}\right)(y)_{y}^{\prime}}{y^{2}}=-\frac{1+\mathrm{e}^{x}}{y^{2}}$.
(2) Calcular $f_{x}^{\prime}(0,1)$ e $f_{y}^{\prime}(0,1)$ (derivadas parciais no ponto $(0,1)$ )
- $f_{x}^{\prime}(0,1)=\frac{\mathrm{e}^{0}}{1^{2}}=1$.
- $f_{y}^{\prime}(0,1)=-\frac{1+\mathrm{e}^{0}}{1^{2}}=-2$.

Exemplo 10: Calcular as derivadas parciais de $1^{\underline{a}}$ ordem da função:
$$
f(x, y, z)=\sin \left(x^{2}+y^{3}+z^{4}\right)
$$

Usar as regras de derivação:
$$
(\sin u)^{\prime}=u^{\prime} \cos u, \quad(u+v)^{\prime}=u^{\prime}+v^{\prime} \quad \text { e } \quad\left(u^{n}\right)^{\prime}=n u^{\prime} u^{n-1}(n \in \mathbb{R})
$$
$$
\begin{aligned}
f_{x}^{\prime}(x, y, z) & =\left(x^{2}+y^{3}+z^{4}\right)_{x}^{\prime} \cos \left(x^{2}+y^{3}+z^{4}\right)= \\
& =(2 x+0+0) \cos \left(x^{2}+y^{3}+z^{4}\right)=2 x \cos \left(x^{2}+y^{3}+z^{4}\right)
\end{aligned}
$$
$$
\begin{aligned}
f_{y}^{\prime}(x, y, z) & =\left(x^{2}+y^{3}+z^{4}\right)_{y}^{\prime} \cos \left(x^{2}+y^{3}+z^{4}\right)= \\
& =\left(0+3 y^{2}+0\right) \cos \left(x^{2}+y^{3}+z^{4}\right)=3 y^{2} \cos \left(x^{2}+y^{3}+z^{4}\right)
\end{aligned}
$$

\section*{$f_{z}^{\prime}(x, y, z)=\left(x^{2}+y^{3}+z^{4}\right)_{z}^{\prime} \cos \left(x^{2}+y^{3}+z^{4}\right)=$}
$$
=\left(0+0+4 z^{3}\right) \cos \left(x^{2}+y^{3}+z^{4}\right)=4 z^{3} \cos \left(x^{2}+y^{3}+z^{4}\right)
$$

Exemplo 11: Calcular $f_{x}^{\prime}, f_{y}^{\prime}$ e $f_{z}^{\prime}$ para $f(x, y, z)=\ln \left(x y+z^{2}\right)$.
Usar: $(\ln u)^{\prime}=\frac{u^{\prime}}{u}$.
- $f_{x}^{\prime}(x, y, z)=\frac{\left(x y+z^{2}\right)_{x}^{\prime}}{x y+z^{2}}=\frac{y}{x y+z^{2}}$.
C.A. $\left(x y+z^{2}\right)_{x}^{\prime}=(x)_{x}^{\prime} y+x(y)_{x}^{\prime}+\left(z^{2}\right)_{x}^{\prime}=y$, pois $y$ e $z^{2}$ são constantes em relação a $x$.
- $f_{y}^{\prime}(x, y, z)=\frac{\left(x y+z^{2}\right)_{y}^{\prime}}{x y+z^{2}}=\frac{x}{x y+z^{2}}$.
C.A. $\left(x y+z^{2}\right)_{y}^{\prime}=(x)_{y}^{\prime} y+x(y)_{y}^{\prime}+\left(z^{2}\right)_{y}^{\prime}=x$, pois $x$ e $z^{2}$ são constantes em relação a $y$.
- $f_{z}^{\prime}(x, y, z)=\frac{\left(x y+z^{2}\right)_{z}^{\prime}}{x y+z^{2}}=\frac{2 z}{x y+z^{2}}$.
C.A. $\left(x y+z^{2}\right)_{z}^{\prime}=(x y)_{z}^{\prime}+\left(z^{2}\right)_{z}^{\prime}=2 z$, pois $x y$ é constante em relação a $z$.

Exemplo 13: O custo total (em euros) na produção de dois produtos ( $A$ e $B$ ) é dado pela função $C(x, y)=2500 \sqrt{x y+1}$, onde $x$ e $y$ são as unidades produzidas do produto $A$ e do produto $B$, respetivamente.
- Custo marginal em relação ao produto $A$ :
$$
\begin{aligned}
& C_{x}^{\prime}(x, y)=2500\left[(x y+1)^{\frac{1}{2}}\right]_{x}^{\prime}=2500 \frac{1}{2}(x y+1)_{x}^{\prime}(x y+1)^{\frac{1}{2}-1}= \\
& =1250 y(x y+1)^{-\frac{1}{2}}=\frac{1250 y}{\sqrt{x y+1}}
\end{aligned}
$$
- Custo marginal em relação ao produto $B$ :
$$
\begin{aligned}
& C_{y}^{\prime}(x, y)=2500\left[(x y+1)^{\frac{1}{2}}\right]_{y}^{\prime}=2500 \frac{1}{2}(x y+1)_{y}^{\prime}(x y+1)^{\frac{1}{2}-1}= \\
& =1250 x(x y+1)^{-\frac{1}{2}}=\frac{1250 x}{\sqrt{x y+1}}
\end{aligned}
$$

Exemplo 12: Calcular as derivadas parciais de $1^{\underline{a}}$ ordem da função:
$$
\begin{aligned}
& f(x, y, z)=\mathrm{e}^{x^{2}+3 z} \ln \left(x+y^{2} z^{2}\right) \\
& -f_{x}^{\prime}(x, y, z)=\left(x^{2}+3 z\right)_{x}^{\prime} \mathrm{e}^{x^{2}+3 z} \ln \left(x+y^{2} z^{2}\right)+\mathrm{e}^{x^{2}+3 z} \frac{\left(x+y^{2} z^{2}\right)_{x}^{\prime}}{x+y^{2} z^{2}}= \\
& =2 x \mathrm{e}^{x^{2}+3 z} \ln \left(x+y^{2} z^{2}\right)+\frac{\mathrm{e}^{x^{2}+3 z}}{x+y^{2} z^{2}} \\
& -f_{y}^{\prime}(x, y, z)=\left(\mathrm{e}^{x^{2}+3 z}\right)_{y}^{\prime} \ln \left(x+y^{2} z^{2}\right)+\mathrm{e}^{x^{2}+3 z} \frac{\left(x+y^{2} z^{2}\right)_{y}^{\prime}}{x+y^{2} z^{2}}= \\
& =0+\mathrm{e}^{x^{2}+3 z} \frac{2 y z^{2}}{x+y^{2} z^{2}}=\frac{2 y z^{2} \mathrm{e}^{x^{2}+3 z}}{x+y^{2} z^{2}} \\
& f_{z}^{\prime}(x, y, z)=\left(x^{2}+3 z\right)_{z}^{\prime} \mathrm{e}^{x^{2}+3 z} \ln \left(x+y^{2} z^{2}\right)+\mathrm{e}^{x^{2}+3 z} \frac{\left(x+y^{2} z^{2}\right)_{z}^{\prime}}{x+y^{2} z^{2}}= \\
& =3 \mathrm{e}^{x^{2}+3 z} \ln \left(x+y^{2} z^{2}\right)+\frac{2 y^{2} z \mathrm{e}^{x^{2}+3 z}}{x+y^{2} z^{2}}
\end{aligned}
$$

Supor que atualmente são produzidas 5 unidades do produto $A$ e 3 unidades do produto $B$. Quais os custos marginais (para os dois produtos) para a situação atual?
- Considerando $(x, y)=(5,3)$ nas expressões gerais das derivadas acima calculadas, obtemos
$$
C_{x}^{\prime}(5,3)=937,5 \quad \text { e } \quad C_{y}^{\prime}(5,3)=1562,5
$$

O custo aumentará aproximadamente $937,50 €$ por cada unidade produzida a mais do produto $A$ para além das 5 já produzidas.

O custo aumentará aproximadamente $1562,50 €$ por cada unidade produzida a mais do produto $B$ para além das 3 já produzidas.

\section*{As 4 derivadas parciais de $2^{\underline{a}}$ ordem de $z=f(x, y)$}

As derivadas parciais de $1^{\underline{\text { a }}}$ ordem de uma função $f$ de duas variáveis:
$$
f_{x}^{\prime} \quad \text { e } \quad f_{y}^{\prime} \text {, }
$$
são também funções de duas variáveis reais. Assim, cada função $f_{x}^{\prime}$ e $f_{y}^{\prime}$ tem também duas derivadas parciais (em ordem a $x$ e a $y$ ):
$$
\left(f_{x}^{\prime}\right)_{x}^{\prime}, \quad\left(f_{x}^{\prime}\right)_{y}^{\prime}, \quad\left(f_{y}^{\prime}\right)_{x}^{\prime} \quad \text { e }\left(f_{y}^{\prime}\right)_{y}^{\prime}
$$
que se denotam, respetivamente, por
$$
f_{x^{2}}^{\prime \prime}, \quad f_{x y}^{\prime \prime}, \quad f_{y x}^{\prime \prime} \quad \text { e } \quad f_{y^{2}}^{\prime \prime}
$$
ou
$$
\frac{\partial^{2} f}{\partial x^{2}}, \quad \frac{\partial^{2} f}{\partial y \partial x}, \quad \frac{\partial^{2} f}{\partial x \partial y} \quad \text { e } \quad \frac{\partial^{2} f}{\partial y^{2}} .
$$

\section*{As 9 derivadas parciais de $2^{\underline{a}}$ ordem de $w=f(x, y, z)$}

Derivando as 3 derivadas parciais de $1^{\underline{a}}$ ordem de uma função $f$ de três variáveis, obtemos as $\mathbf{9}$ derivadas parciais de $\mathbf{2}^{\mathbf{a}}$ ordem de $f$ :

Derivadas de $f_{x}^{\prime}: \quad$ Derivadas de $f_{y}^{\prime}: \quad$ Derivadas de $f_{z}^{\prime}$ :
$$
\begin{array}{lll}
\left(f_{x}^{\prime}\right)_{x}^{\prime}=: f_{x^{2}}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial x^{2}} & \left(f_{y}^{\prime}\right)_{x}^{\prime}=: f_{y x}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial x \partial y} & \left(f_{z}^{\prime}\right)_{x}^{\prime}=: f_{z x}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial x \partial z} \\
\left(f_{x}^{\prime}\right)_{y}^{\prime}=: f_{x y}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial y \partial x} & \left(f_{y}^{\prime}\right)_{y}^{\prime}=: f_{y^{2}}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial y^{2}} & \left(f_{z}^{\prime}\right)_{y}^{\prime}=: f_{z y}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial y \partial z} \\
\left(f_{x}^{\prime}\right)_{z}^{\prime}=: f_{x z}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial z \partial x} & \left(f_{y}^{\prime}\right)_{z}^{\prime}=: f_{y z}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial z \partial y} & \left(f_{z}^{\prime}\right)_{z}^{\prime}=: f_{z^{2}}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial z^{2}}
\end{array}
$$

As 4 funções obtidas são as derivadas parciais de $2^{\underline{\text { a }}}$ ordem de $f$ :
$$
f\left\{\begin{array}{l}
f_{x}^{\prime}\left\{\begin{array}{l}
\left(f_{x}^{\prime}\right)_{x}^{\prime}=: f_{x x}^{\prime \prime} \equiv f_{x^{2}}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial x^{2}} \equiv \frac{\partial^{2} f}{\partial x \partial x} \\
\left(f_{x}^{\prime}\right)_{y}^{\prime}=: f_{x y}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial y \partial x}
\end{array}\right. \\
f_{y}^{\prime}\left\{\begin{array}{l}
\left(f_{y}^{\prime}\right)_{x}^{\prime}=: f_{y x}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial x \partial y} \\
\left(f_{y}^{\prime}\right)_{y}^{\prime}=: f_{y y}^{\prime \prime} \equiv f_{y^{2}}^{\prime \prime} \equiv \frac{\partial^{2} f}{\partial y^{2}} \equiv \frac{\partial^{2} f}{\partial y \partial y}
\end{array}\right.
\end{array}\right.
$$
$f_{x y}^{\prime \prime}$ e $f_{y x}^{\prime \prime}$ são as derivadas mistas ou cruzadas.
$f_{x^{2}}^{\prime \prime}$ e $f_{y^{2}}^{\prime \prime}$ são as derivadas quadradas.
Se derivarmos as derivadas parciais de $2^{\underline{a}}$ ordem de $f$, obtemos as 8 derivadas parciais de $3^{\underline{a}}$ ordem de $f$ e assim sucessivamente.

Exemplo 14: Calcular as derivadas parciais de $2^{\underline{a}}$ ordem da função dada no exemplo 8 , ou seja, $f(x, y)=x^{2}+x^{2} y^{3}$.
- Derivadas parciais de $1^{\underline{a}}$ ordem de $f$ :
$$
f_{x}^{\prime}(x, y)=2 x+2 x y^{3} \quad \text { e } \quad f_{y}^{\prime}(x, y)=3 x^{2} y^{2}
$$
- Derivadas parciais de $2^{\underline{a}}$ ordem de $f$ :
$$
\begin{aligned}
& f_{x^{2}}^{\prime \prime}(x, y)=\left(2 x+2 x y^{3}\right)_{x}^{\prime}=2(x)_{x}^{\prime}+2(x)_{x}^{\prime} y^{3}=2+2 y^{3} . \\
& f_{x y}^{\prime \prime}(x, y)=\left(2 x+2 x y^{3}\right)_{y}^{\prime}=(2 x)_{y}^{\prime}+2 x\left(y^{3}\right)_{y}^{\prime}=0+6 x y^{2}=6 x y^{2} . \\
& f_{y x}^{\prime \prime}(x, y)=\left(3 x^{2} y^{2}\right)_{x}^{\prime}=3\left(x^{2}\right)_{x}^{\prime} y^{2}=6 x y^{2} . \\
& f_{y^{2}}^{\prime \prime}(x, y)=\left(3 x^{2} y^{2}\right)_{y}^{\prime}=3 x^{2}\left(y^{2}\right)_{y}^{\prime}=6 x^{2} y .
\end{aligned}
$$

Exemplo 15: Calcular as derivadas parciais de $2^{\underline{a}}$ ordem da função dada no exemplo 9, ou seja, $f(x, y)=\frac{1+\mathrm{e}^{x}}{y}$.
- Sabemos que $f_{x}^{\prime}(x, y)=\frac{\mathrm{e}^{x}}{y}$. Assim,
$$
\begin{aligned}
& f_{x^{2}}^{\prime \prime}(x, y)=\left(\frac{\mathrm{e}^{x}}{y}\right)_{x}^{\prime}=\left(\mathrm{e}^{x} \frac{1}{y}\right)_{x}^{\prime}=\left(\mathrm{e}^{x}\right)_{x}^{\prime} \frac{1}{y}=\frac{\mathrm{e}^{x}}{y} \\
& f_{x y}^{\prime \prime}(x, y)=\left(\frac{\mathrm{e}^{x}}{y}\right)_{y}^{\prime}=\frac{\left(\mathrm{e}^{x}\right)_{y}^{\prime} y-\mathrm{e}^{x}(y)_{y}^{\prime}}{y^{2}}=\frac{0-\mathrm{e}^{x}}{y^{2}}=-\frac{\mathrm{e}^{x}}{y^{2}}
\end{aligned}
$$

Estamos (e vamos continuar) a usar as regras de derivação:
$(k u)^{\prime}=k u^{\prime}(k$ constante $),\left(e^{u}\right)^{\prime}=u^{\prime} e^{u}$ e $\left(\frac{u}{v}\right)^{\prime}=\frac{u^{\prime} v-u v^{\prime}}{v^{2}}(v \neq 0)$.
- Sabemos que $f_{y}^{\prime}(x, y)=-\frac{1+\mathrm{e}^{x}}{y^{2}}$. Assim,
$$
\begin{aligned}
f_{y x}^{\prime \prime}(x, y) & =\left(-\frac{1+\mathrm{e}^{x}}{y^{2}}\right)_{x}^{\prime}=-\left(1+\mathrm{e}^{x}\right)_{x}^{\prime} \frac{1}{y^{2}}= \\
& =-\left(0+\mathrm{e}^{x}\right) \frac{1}{y^{2}}=-\frac{\mathrm{e}^{x}}{y^{2}} \\
f_{y^{2}}^{\prime \prime}(x, y) & =\left(-\frac{1+\mathrm{e}^{x}}{y^{2}}\right)_{y}^{\prime}=-\frac{0-\left(1+\mathrm{e}^{x}\right)\left(y^{2}\right)_{y}^{\prime}}{y^{4}}= \\
& =-\frac{-2 y\left(1+\mathrm{e}^{x}\right)}{y^{4}}=\frac{2\left(1+\mathrm{e}^{x}\right)}{y^{3}}
\end{aligned}
$$

Exemplo 16: Calcular as derivadas parciais de $2^{\underline{a}}$ ordem da função dada no exemplo 10 , ou seja, $f(x, y, z)=\sin \left(x^{2}+y^{3}+z^{4}\right)$.
- Derivando a derivada $\mathbf{f}_{\mathbf{x}}^{\prime}=2 \mathbf{x} \cos \left(\mathbf{x}^{2}+\mathbf{y}^{3}+\mathbf{z}^{4}\right)$ em ordem a $x, y$ e $z$, obtemos (respetivamente):
$$
\begin{aligned}
& f_{x^{2}}^{\prime \prime}=2 \cos \left(x^{2}+y^{3}+z^{4}\right)-4 x^{2} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{x y}^{\prime \prime}=2 x\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{y}^{\prime}=-6 x y^{2} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{x z}^{\prime \prime}=2 x\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{z}^{\prime}=-8 x z^{3} \sin \left(x^{2}+y^{3}+z^{4}\right)
\end{aligned}
$$

Estamos (e vamos continuar) a usar as regras de derivação:
$$
\begin{array}{ll}
(u v)^{\prime}=u^{\prime} v+u v^{\prime} & (k u)^{\prime}=k u^{\prime}(\operatorname{com} k \text { constante }) \\
(u+v)^{\prime}=u^{\prime}+v^{\prime} & \left(u^{n}\right)^{\prime}=n u^{\prime} u^{n-1}(n \in \mathbb{R}) \\
(\cos u)^{\prime}=-u^{\prime} \sin u &
\end{array}
$$
- Derivando a derivada $\mathrm{f}_{\mathrm{y}}^{\prime}=3 \mathrm{y}^{2} \cos \left(\mathrm{x}^{2}+\mathrm{y}^{3}+\mathrm{z}^{4}\right)$ em ordem a x , y e $z$, obtemos (respetivamente):
$$
\begin{aligned}
& f_{y x}^{\prime \prime}=3 y^{2}\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{x}^{\prime}=-6 x y^{2} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{y^{2}}^{\prime \prime}=6 y \cos \left(x^{2}+y^{3}+z^{4}\right)-9 y^{4} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{y z}^{\prime \prime}=3 y^{2}\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{z}^{\prime}=-12 y^{2} z^{3} \sin \left(x^{2}+y^{3}+z^{4}\right)
\end{aligned}
$$
- Derivando a derivada $f_{z}^{\prime}=4 z^{3} \cos \left(x^{2}+y^{3}+z^{4}\right)$ em ordem a $x$, y e $z$, obtemos (respetivamente):
$$
\begin{aligned}
& f_{z x}^{\prime \prime}=4 z^{3}\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{x}^{\prime}=-8 x z^{3} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{z y}^{\prime \prime}=4 z^{3}\left[\cos \left(x^{2}+y^{3}+z^{4}\right)\right]_{y}^{\prime}=-12 y^{2} z^{3} \sin \left(x^{2}+y^{3}+z^{4}\right) \\
& f_{z^{2}}^{\prime \prime}=12 z^{2} \cos \left(x^{2}+y^{3}+z^{4}\right)-16 z^{6} \sin \left(x^{2}+y^{3}+z^{4}\right)
\end{aligned}
$$

\section*{Observação}

Nos exemplos anteriores temos as seguintes igualdades entre as derivadas mistas:
$$
f_{x y}^{\prime \prime}=f_{y x}^{\prime \prime} \quad f_{x z}^{\prime \prime}=f_{z x}^{\prime \prime} \quad f_{y z}^{\prime \prime}=f_{z y}^{\prime \prime}
$$
ou seja, é indiferente a ordem de derivação, desde que se derive em ordem às mesmas variáveis o mesmo número de vezes.
Contudo, este facto nem sempre se verifica!
- Se $f: D_{f} \subset \mathbb{R}^{2} \rightarrow \mathbb{R}$ admite derivadas até à ordem 2 (inclusive) contínuas num aberto $A \subset D_{f}$ (isto é, $f$ é de classe $C^{2}$ em $A$ ), então $f_{x y}^{\prime \prime}(a, b)=f_{y x}^{\prime \prime}(a, b), \forall(a, b) \in A$ (derivadas mistas iguais).
- Se $D$ é aberto e $f: D \subset \mathbb{R}^{n} \rightarrow \mathbb{R}$ admite derivadas até à ordem $k$ (inclusive) contínuas em $D$ (isto é, $f$ é de classe $C^{k}$ ), então é indiferente a ordem de derivação, até à ordem $k$ (inclusive).