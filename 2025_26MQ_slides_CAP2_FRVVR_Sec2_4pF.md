\title{
Métodos Quantitativos
}

Capítulo 2
Cálculo diferencial com funções reais de várias variáveis reais
2.2. Funções homogéneas

\author{
Lígia Abrunheiro \\ ISCA-UA \\ Março de $2026{ }^{\dagger}$
}

Licenciatura em Contabilidade e Licenciatura em Finanças

\section*{Definição}

Uma função real de $n$ variáveis reais,
$$
\begin{array}{lclc}
f: & D_{f} \subseteq \mathbb{R}^{n} & \longrightarrow & \mathbb{R} \\
& \left(x_{1}, x_{2}, \ldots, x_{n}\right) & \longmapsto & f\left(x_{1}, x_{2}, \ldots, x_{n}\right)
\end{array}
$$
diz-se homogénea de grau $\alpha$ (onde $\alpha$ é um número real constante) se verifica
$$
f\left(t x_{1}, t x_{2}, \ldots, t x_{n}\right)=t^{\alpha} f\left(x_{1}, x_{2}, \ldots, x_{n}\right),
$$
quaisquer que sejam $t \in \mathbb{R} e\left(x_{1}, x_{2}, \ldots, x_{n}\right) \in D_{f}$ tais que $\left(t x_{1}, t x_{2}, \ldots, t x_{n}\right) \in D_{f}$.
A constante $\alpha$ designa-se por grau de homogeneidade de $f$.
Se a igualdade anterior for válida apenas para $t>0$, diz-se que $f$ é positivamente homogénea.

\subsection*{2.2. Funções homogéneas. Aplicações.}

\section*{Objetivos:}
- Averiguar se uma dada é uma função homogénea.
- Concluir acerca da homogeneidade das derivadas parciais de uma função homogénea.
- Aplicar o Teorema de Euler.
- Reconhecer a igualdade de Euler associada a uma função homogénea.
- Resolver problemas de aplicação prática enquadrando-os na teoria das funções homogéneas.

\section*{Bibliografia}
- Pires, C., Cálculo para Economia e Gestão, Escolar Editora (2011).
- Pires, C., Cálculo para Economia e Gestão, Escolar Editora (2011).

\section*{Função real de duas variáveis reais homógenea de grau $\alpha$}

Função $f: D_{f} \subseteq \mathbb{R}^{2} \rightarrow \mathbb{R},(x, y) \mapsto f(x, y)$ que satisfaz
$$
f(t x, t y)=t^{\alpha} f(x, y),
$$
quaisquer que sejam $t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$.

\section*{Função real de três variáveis reais homógenea de grau $\alpha$}

Função $f: D_{f} \subseteq \mathbb{R}^{3} \rightarrow \mathbb{R},(x, y, z) \mapsto f(x, y, z)$ que satisfaz
$$
f(t x, t y, t z)=t^{\alpha} f(x, y, z),
$$
quaisquer que sejam $t \in \mathbb{R}$ e $(x, y, z) \in D_{f}$ tais que $(t x, t y, t z) \in D_{f}$.

Exemplos - Nos exemplos seguintes consideramos:
$t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$ (para as funções de 2 variáveis);
$t \in \mathbb{R}$ e $(x, y, z) \in D_{f}$ tais que $(t x, t y, t z) \in D_{f}$ (para as funções de 3 variáveis)
(1) $f(x, y)=2 x+3 y$ é homogénea de grau $\alpha=1$, pois
$$
f(t x, t y)=2 t x+3 t y=t 2 x+t 3 y=t(2 x+3 y)=t^{1} f(x, y)
$$
(2) $f(x, y)=x y+x$ não é homogénea, pois
$$
f(t x, t y)=t x t y+t x=t^{1+1} x y+t x=t^{2} x y+t x \neq t^{\alpha}(x y+x)
$$
(3) $f(x, y, z)=5 x y^{2} z$ é homogénea de grau $\alpha=4$, pois
$$
\begin{aligned}
f(t x, t y, t z) & =5 t x(t y)^{2} t z=5 t x t^{2} y^{2} t z=t t^{2} t 5 x y^{2} z= \\
& =t^{1+2+1} 5 x y^{2} z=t^{4} 5 x y^{2} z=t^{4} f(x, y, z)
\end{aligned}
$$
(a) $f(x, y)=\sqrt[5]{x^{3}+y^{3}}$ é homogénea de grau $\alpha=\frac{3}{5}$, pois
$$
\begin{aligned}
f(t x, t y) & =\sqrt[5]{(t x)^{3}+(t y)^{3}}=\sqrt[5]{t^{3} x^{3}+t^{3} y^{3}}=\sqrt[5]{t^{3}\left(x^{3}+y^{3}\right)}= \\
& =\sqrt[5]{t^{3}} \sqrt[5]{x^{3}+y^{3}}=t^{\frac{3}{5}} f(x, y)
\end{aligned}
$$
(8) $f(x, y)=\frac{x y^{2}}{x^{3}+y^{3}}$ é homogénea de grau $\alpha=0$, pois
$$
\begin{aligned}
f(t x, t y) & =\frac{t x t^{2} y^{2}}{t^{3} x^{3}+t^{3} y^{3}}=\frac{t^{1+2} x y^{2}}{t^{3}\left(x^{3}+y^{3}\right)}=\frac{t^{3} x y^{2}}{t^{3}\left(x^{3}+y^{3}\right)}= \\
& =\frac{t^{3}}{t^{3}} \frac{x y^{2}}{x^{3}+y^{3}}=1 \cdot f(x, y)=t^{0} f(x, y)
\end{aligned}
$$
(4) $f(x, y)=x y+x^{2}+4 y^{2}$ é homogénea de grau $\alpha=2$, pois
$$
\begin{aligned}
f(t x, t y) & =t x t y+(t x)^{2}+4(t y)^{2}=t^{1+1} x y+t^{2} x^{2}+4 t^{2} y^{2}= \\
& =t^{2}\left(x y+x^{2}+4 y^{2}\right)=t^{2} f(x, y)
\end{aligned}
$$
(5) $f(x, y)=\frac{x}{y}$ é homogénea de grau $\alpha=0$, pois
$$
f(t x, t y)=\frac{t x}{t y}=\frac{t x}{t} \frac{x}{y}=\mathbf{1} \frac{x}{y}=\mathbf{1} \cdot f(x, y)=t^{0} f(x, y)
$$
(6) $f(x, y, z)=\ln \left(\frac{x y}{z}\right)$ não é homogénea, pois
$$
\begin{aligned}
f(t x, t y, t z) & =\ln \left(\frac{t x t y}{t z}\right)=\ln \left(\frac{t^{2} x y}{t z}\right)=\ln \left(\frac{t^{2}}{t} \frac{x y}{z}\right)= \\
& =\ln \left(t^{2-1} \frac{x y}{z}\right)=\ln \left(t \frac{x y}{z}\right) \neq t^{\alpha} \ln \left(\frac{x y}{z}\right)
\end{aligned}
$$
( $f(x, y)=\frac{x^{2}-x y}{x^{3}+5 y^{3}}$ é homogénea de grau $\alpha=-1$, pois
$$
\begin{aligned}
f(t x, t y) & =\frac{t^{2} x^{2}-t x t y}{t^{3} x^{3}+5 t^{3} y^{3}}=\frac{t^{2} x^{2}-t^{2} x y}{t^{3} x^{3}+t^{3} 5 y^{3}}=\frac{t^{2}\left(x^{2}-x y\right)}{t^{3}\left(x^{3}+5 y^{3}\right)}= \\
& =\frac{t^{2}}{t^{3}} \frac{x^{2}-x y}{x^{3}+5 y^{3}}=t^{2-3} f(x, y)=t^{-1} f(x, y)
\end{aligned}
$$
(10) $f(x, y)=3+\cos \left(\frac{x}{y}\right)$ é homogénea de grau $\alpha=0$, pois
$$
f(t x, t y)=3+\cos \left(\frac{t x}{t y}\right)=3+\cos \left(\frac{x}{y}\right)=t^{0} f(x, y)
$$
(10) Consideremos a família de funções $f(x, y)=x^{\beta} y^{2}+x y^{5}, \beta \in \mathbb{R}$. Determine para que valores de $\beta, f$ é uma função homogénea.
$$
\begin{aligned}
f(t x, t y) & =(t x)^{\beta}(t y)^{2}+t x(t y)^{5}==t^{\beta} x^{\beta} t^{2} y^{2}+t x t^{5} y^{5} \\
& =t^{\beta} t^{2} x^{\beta} y^{2}+t^{1} t^{5} x y^{5}=t^{\beta+2} x^{\beta} y^{2}+t^{6} x y^{5}
\end{aligned}
$$

A função é homogénea se e só se $\beta+2=6$, ou seja, para $\beta=4$, uma vez que nesta situação temos
$$
f(t x, t y)=t^{4+2} x^{4} y^{2}+t^{6} x y^{5}=t^{6}\left(x^{4} y^{2}+x y^{5}\right)=t^{6} f(x, y)
$$

Portanto, para $\beta=4$, temos a função $f(x, y)=x^{4} y^{2}+x y^{5}$ homogénea de grau $\alpha=6$.

\section*{Exemplo 13: [Exemplo económico - rendimentos à escala]}

Seja $z=f(x, y)$ a função de produção no fabrico de um produto. A produção $z$ (output) depende de duas variáveis $x$ e $y$ (inputs) que podem representar, por exemplo, as unidades de trabalho e as unidades de capital usadas na produção, respetivamente.
(1) Suponhamos que se estiverem disponíveis 100 trabalhadores $(x=100)$ e 50 unidades monetárias (u. m.) $(y=50)$ são produzidas $8705(z=8705)$ unidades do produto (nível de produção). Isto é, $f(100,50)=8705$.
(2) Suponhamos ainda que $f$ é homogénea de grau 1 , ou seja,
$$
f(t x, t y)=t f(x, y), \quad(x, y) \in D_{f}, t \in \mathbb{R}:(t x, t y) \in D_{f}
$$

\section*{Observação}

Dada uma função homogénea, se conhecermos o valor da função num ponto, então conseguimos determinar o valor da função em qualquer outro ponto que tenha coordenadas proporcionais a esse ponto.

Exemplo 12: Seja $f$ uma função real de duas variáveis reais homogénea de grau 3. Sabendo que $f(1,2)=4$, determine $f(5,10)$.
- Se a função é homogénea de grau 3, então
$$
f(t x, t y)=t^{3} f(x, y), \quad(x, y) \in D_{f}, t \in \mathbb{R}:(t x, t y) \in D_{f}
$$
- Escolhendo $t=5$ e $(x, y)=(1,2)$ na igualdade anterior e atendendo a que $f(1,2)=4$, temos
$$
f(5,10)=f(5 \times 1,5 \times 2)=5^{3} f(1,2)=125 \times 4=500
$$

Com estes dados, podemos tirar conclusões acerca do nível de produção quando temos 200 trabalhadores e 100 u. m.:

\begin{tabular}{lll} 
Situação conhecida & & Nova situação \\
$(x, y)=(100,50)$ & $\xrightarrow[\text { duplicar }]{ }$ & $(2 x, 2 y)=(200,100)$ \\
$f(100,50)=8705$ & $\longrightarrow \ldots$ & $f(200,100)=?$
\end{tabular}
- Se $f$ é homogénea de grau 1 , então $f(2 x, 2 y)=2 f(x, y)$ (consideramos $t=2$ na definição de função homogénea).
- Assim, $f(200,100)=2 f(100,50)=2 \times 8705=17410$.

O nível de produção duplica quando as variáveis de que depende duplicam (se triplicarem, a produção triplica e assim sucessivamente). A função tem rendimentos constantes à escala (constant returns to scale).

\section*{Observação [Rendimentos à escala]}

Seja $z=f(x, y)$ uma função de produção.
- Afirmar que $f$ apresenta rendimentos constantes à escala é equivalente a dizer que $f$ é homogénea de grau $\alpha=1$ (se variarmos todos os inputs ( $x$ e $y$ ) na mesma proporção, o output ( $z$ ) varia na mesma proporção).

Por exemplo, se duplicarmos a utilização de trabalho e de capital, então a produção também duplica, $f(2 x, 2 y)=2^{1} f(x, y)=2 f(x, y)$.
Por exemplo, se triplicarmos a utilização de trabalho e de capital, então a produção também triplica, $f(3 x, 3 y)=3^{1} f(x, y)=3 f(x, y)$.

\section*{Propriedade}

Se $f$ é uma função homogénea de grau $\alpha$, então as derivadas parciais de $f$ de ordem $k$ (quando existem) são homogéneas de grau $\alpha-k$.

Exemplo 14: Seja $f(x, y)=x^{3}-4 x y^{2}+5 y^{3}$
- $f$ é homogénea de grau $\alpha=3$ (verificar!).
- $f_{x}^{\prime}(x, y)=\left(x^{3}-4 x y^{2}+5 y^{3}\right)_{x}^{\prime}=3 x^{2}-4 y^{2}$ é homogénea de grau 2 . (Derivada parcial de ordem $k=1$, logo, $\alpha-k=3-1=2$.)
- $f_{x y}^{\prime \prime}(x, y)=\left(3 x^{2}-4 y^{2}\right)_{y}^{\prime}=-8 y$ é homogénea de grau 1 . (Derivada parcial de ordem $k=2$, logo, $\alpha-k=3-2=1$.)
- $f_{x y^{2}}^{\prime \prime \prime}(x, y)=(-8 y)_{y}^{\prime}=-8$ é homogénea de grau 0 . (Derivada parcial de ordem $k=3$, logo, $\alpha-k=3-3=0$.)
- Dizer que $f$ apresenta rendimentos crescentes à escala é equivalente a dizer que $f$ é homogénea de grau superior a 1 $(\alpha>1)$ (se variarmos todos os inputs na mesma proporção, o output varia numa proporção maior).

Por exemplo, para $\alpha=2$, se duplicarmos a utilização de trabalho e de capital, então a produção quadruplica, $f(2 x, 2 y)=2^{2} f(x, y)=4 f(x, y)$.
- Dizer que $f$ apresenta rendimentos decrescentes à escala é equivalente a dizer que $f$ é homogénea de grau inferior a 1 $(\alpha<1)$ (se variarmos todos os inputs na mesma proporção, o output varia numa proporção menor).

Por exemplo, para $\alpha=-1$, se duplicarmos a utilização de trabalho e de capital, a produção passa para metade, $f(2 x, 2 y)=2^{-1} f(x, y)=\frac{1}{2} f(x, y)$.

\section*{Teorema de Euler}
- Se $f: D_{f} \subset \mathbb{R}^{2} \rightarrow \mathbb{R}$ é uma função homogénea de grau $\alpha$, então verifica-se a seguinte igualdade (igualdade ou identidade de Euler):
$$
x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=\alpha f(x, y),
$$
para qualquer ponto $(x, y)$ onde $f$ seja diferenciável.
- Se $f: D_{f} \subset \mathbb{R}^{3} \rightarrow \mathbb{R}$ é uma função homogénea de grau $\alpha$, então verifica-se a seguinte igualdade (igualdade ou identidade de Euler):
$$
x f_{x}^{\prime}(x, y, z)+y f_{y}^{\prime}(x, y, z)+z f_{z}^{\prime}(x, y, z)=\alpha f(x, y, z),
$$
para qualquer ponto $(x, y, z)$ onde $f$ seja diferenciável.

Exemplo 15: Seja $f(x, y)=\frac{x^{2}}{y}+x$.
- Mostre que $f$ é homogénea de grau $\alpha=1$ :
$$
\begin{aligned}
& f(t x, t y)=\frac{(t x)^{2}}{t y}+t x=\frac{t^{2} x^{2}}{t y}+t x=\frac{t^{2}}{t} \frac{x^{2}}{y}+t x= \\
& =t^{2-1} \frac{x^{2}}{y}+t x=t^{1}\left(\frac{x^{2}}{y}+x\right)=t^{1} f(x, y)
\end{aligned}
$$
- Aplicando o Teorema de Euler podemos concluir que $f$ verifica a igualdade de Euler para $\alpha=1$. Escreva essa igualdade:
$$
x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=1 \cdot f(x, y)=\frac{x^{2}}{y}+x
$$

Exemplo 16: Seja $f(x, y)=\sqrt[3]{\frac{x}{y}}$.
- Mostre que $f$ satisfaz a igualdade $x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=0$.
$$
\begin{aligned}
& x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=x\left[\left(\frac{x}{y}\right)^{\frac{1}{3}}\right]_{x}^{\prime}+y\left[\left(\frac{x}{y}\right)^{\frac{1}{3}}\right]_{y}^{\prime}= \\
& =x \frac{1}{3}\left(\frac{x}{y}\right)_{x}^{\prime}\left(\frac{x}{y}\right)^{\frac{1}{3}-1}+y \frac{1}{3}\left(\frac{x}{y}\right)_{y}^{\prime}\left(\frac{x}{y}\right)^{\frac{1}{3}-1}= \\
& =\frac{x}{3} \frac{1}{y}\left(\frac{x}{y}\right)^{-\frac{2}{3}}+\frac{y}{3} \frac{-x}{y^{2}}\left(\frac{x}{y}\right)^{-\frac{2}{3}}= \\
& =\frac{x}{3 y}\left(\frac{x}{y}\right)^{-\frac{2}{3}}-\frac{x}{3 y}\left(\frac{x}{y}\right)^{-\frac{2}{3}}=0
\end{aligned}
$$

Exemplo 15 (continuação): $f(x, y)=\frac{x^{2}}{y}+x$.
- Calculando as derivadas podemos confirmar o resultado (isto é, verificar a igualdade de Euler).
- $f_{x}^{\prime}(x, y)=2 \frac{x}{y}+1$ e $f_{y}^{\prime}(x, y)=-\frac{x^{2}}{y^{2}}$.
- Então,
$$
\begin{aligned}
& x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=x\left(2 \frac{x}{y}+1\right)+y\left(-\frac{x^{2}}{y^{2}}\right)= \\
& =x 2 \frac{x}{y}+x-y \frac{x^{2}}{y^{2}}=2 \frac{x^{2}}{y}+x-\frac{x^{2}}{y}= \\
& =\frac{x^{2}}{y}+x=1 \cdot f(x, y)
\end{aligned}
$$

Exemplo 16 (continuação): $f(x, y)=\sqrt[3]{\frac{x}{y}}$
- Interprete a igualdade anterior em termos de homogeneidade.
$$
\begin{aligned}
& x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=0 \Leftrightarrow \\
& \Leftrightarrow x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=0 \cdot f(x, y) \quad(\alpha=0)
\end{aligned}
$$

É a igualdade de Euler da função $f$ que é uma função homogénea de grau $\alpha=0$, pois
$$
f(t x, t y)=\sqrt[3]{\frac{t x}{t y}}=\sqrt[3]{\frac{x}{y}}=1 \cdot f(x, y)=t^{0} f(x, y)
$$

Exemplo 17: Seja $f(x, y)=100 \sqrt[4]{x^{3} y}$ a função de produção relativa ao fabrico de um produto. Considere $x>0$ (número de trabalhadores) e $y>0$ (unidades de capital).
- Mostre que $f$ é homogénea de grau $\alpha=1$.
$$
\begin{aligned}
& f(t x, t y)=100 \sqrt[4]{(t x)^{3} t y}=100 \sqrt[4]{t^{3} x^{3} t y}=100 \sqrt[4]{t^{3+1} x^{3} y}= \\
& =\sqrt[4]{t^{4}} 100 \sqrt[4]{x^{3} y}=t^{1} f(x, y) \quad\left(\text { note que } \sqrt[4]{t^{4}}=t \text { pois } t>0\right)
\end{aligned}
$$
- Avalie as implicações na produção de uma diminuição para metade das unidades de trabalho e de capital.
$$
f\left(\frac{x}{2}, \frac{y}{2}\right)=f\left(\frac{1}{2} x, \frac{1}{2} y\right)=\left(\frac{1}{2}\right)^{1} f(x, y)=\frac{f(x, y)}{2}
$$

Conclui-se que produção diminui para metade quando $x$ e $y$ diminuem para metade simultaneamente.

\section*{Exemplo 17 (continuação): $f(x, y)=100 \sqrt[4]{x^{3} y}$}
- Calcule o nível de produção quando estão disponíveis 10 trabalhadores e 160 unidades de capital.
$$
f(10,160)=100 \sqrt[4]{10^{3} 160}=2000 \quad \text { unidades de produto. }
$$
- Sabendo que $f_{y}^{\prime}(10,160)=3,125$, determine o valor de $f_{x}^{\prime}(10,160)$ sem calcular a expressão da derivada parcial $f_{x}^{\prime}$.
- Se $f$ é homogénea, então, pelo Teorema de Euler, sabemos que verifica a igualdade de Euler $x f_{x}^{\prime}(x, y)+y f_{y}^{\prime}(x, y)=1 \cdot f(x, y)$.
- Basta agora escrever esta igualdade para $x=10$ e $y=160$ :
$$
\begin{aligned}
& 10 f_{x}^{\prime}(10,160)+160 f_{y}^{\prime}(10,160)=f(10,160) \Leftrightarrow \\
& \Leftrightarrow 10 f_{x}^{\prime}(10,160)+160 \times 3,125=2000 \Leftrightarrow f_{x}^{\prime}(10,160)=150
\end{aligned}
$$
[T.P.C. - Interprete o valor das duas derivadas parciais acima referidas.]