\section*{Métodos Quantitativos}

\section*{Capítulo 3}

Equações diferenciais ordinárias de $1^{\underline{a}}$ ordem

\section*{Lígia Abrunheiro}

ISCA-UA
abril de $2025{ }^{\dagger}$
Licenciatura em Finanças
isca

\section*{Bibliografia/Bibliography}
- Harshbarger, R. J. e Reynolds, J.J., Matemática Aplicada: Administração, Economia e Ciências Sociais e Biológicas, McGraw-Hill Int. Brasil (2006).
Harshbarger, R. J. and Reynolds, J. J., Mathematical Applications for the Management, Life and Social Sciences, Cengage Learning, 11th edition (2016).
- Larson, R., Hostetler, R. e Edwards, B., Cálculo, volume 1, McGraw-Hill Interamericana do Brasil, $8^{\underline{\text { a }}}$ edição (2006).
Larson, R., Applied Calculus for the Life and Social Sciences, 1st edition, Cengage Learning (2009).
- Pires C., Cálculo para Economia e Gestão, Escolar Ed. (2011).
- Stewart, J., Calculus: metric version, Cengage Learning, 8th edition (2015).

\section*{3. Equações diferenciais ordinárias de $1^{\underline{a}}$ ordem}

\section*{Objetivos:}
- Identificar e resolver equações diferenciais (EDs) de $1^{\underline{a}}$ ordem dos seguintes tipos:
- EDs de variáveis separáveis (método de separação de variáveis).
- EDs homogéneas (método que envolve uma mudança de variável, reduzindo a ED a uma ED de VS).
- EDs lineares (método do fator integrante).
- Distinguir entre solução geral e solução particular de uma ED.
- Usar uma condição inicial para encontrar uma solução particular de uma ED.
- Modelar e resolver problemas práticos, usando EDs.

\section*{Equação diferencial (ED)}

Uma ED é uma igualdade que estabelece uma relação entre
- uma ou mais variáveis independentes,
- uma variável dependente e
- as derivadas desta variável dependente em ordem à(s) variável(is) independente(s).
A incógnita da ED é a função representada pela variável dependente.
Exemplos:
- $y^{\prime \prime \prime}+x y^{\prime}=6 y$, ou com uma notação alternativa $\frac{d^{3} y}{d x^{3}}+x \frac{d y}{d x}=6 y$ ( $x$ é a variável independente; $y=y(x)$ é a função incógnita).
- $z_{x}^{\prime}+z_{x y}^{\prime \prime}=x z$, ou com uma notação alternativa $\frac{\partial z}{\partial x}+\frac{\partial^{2} z}{\partial x \partial y}=x z$ ( $x$ e $y$ são as variáveis independentes; $z=z(x, y)$ é a função incógnita).

\section*{Classificação das equações diferenciais}
- Quanto ao tipo:

Equação diferencial ordinária (EDO) - envolve uma função de uma variável e as suas derivadas. Exemplo: $y^{\prime \prime \prime}+x y^{\prime}=6 y$.

Equação diferencial parcial - envolve uma função de mais do que uma variável e as suas derivadas. Exemplo: $z_{x}^{\prime}+z_{x y}^{\prime \prime}=x z$.
- Quanto à ordem:

A ordem de uma equação diferencial coincide com a ordem da derivada de maior ordem que aparece na equação.
Exemplos:
$y^{\prime \prime \prime}+x y^{\prime}=6 y$ é de ordem 3;
$z_{x}^{\prime}+z_{x y}^{\prime \prime}=x z$ é de ordem 2.
Vamos estudar apenas EDO de $1^{\underline{\mathrm{a}}}$ ordem.

\section*{Exemplo 1 (Exemplo de motivação):}

Qual é a função $y=y(x)$ que é igual à sua própria derivada?
Esta questão traduz-se no problema de encontrar a função $y=y(x)$ que satisfaz a equação diferencial
$$
y^{\prime}=y .
$$

É simples de concluir que $y=e^{x}$ é uma solução possível, pois
$$
y^{\prime}=\left(\mathrm{e}^{x}\right)^{\prime}=(x)^{\prime} \mathrm{e}^{x}=\mathrm{e}^{x}=y
$$

No entanto, existem outras soluções possíveis, como por exemplo, $y=3 \mathrm{e}^{x}$ ou $y=-2 \mathrm{e}^{x}$.

A resposta mais geral será
$y=C \mathrm{e}^{x}, \quad$ onde $C$ é uma constante real qualquer.

\section*{Equação diferencial ordinária de $1^{\underline{\text { a }}}$ ordem}

Uma equação diferencial ordinária de $1^{\underline{\text { a }}}$ ordem envolve apenas a variável independente, a variável dependente (função incógnita) e a sua derivada de $1^{\underline{a}}$ ordem. Tais equações podem escrever-se na forma:
$$
F\left(x, y, y^{\prime}\right)=0, \quad \text { ou seja }, \quad F\left(x, y, \frac{d y}{d x}\right)=0
$$
onde
$$
\begin{aligned}
& x \text { é a variável independente, } \\
& y \text { é a função incógnita, } y=y(x) \text {, } \\
& y^{\prime}=\frac{d y}{d x} \text { é a derivada de } 1^{\underline{a}} \text { ordem de } y \text {. }
\end{aligned}
$$

Exemplo 2 (Modelação de problemas): Escreva a equação diferencial que modela cada uma das frases apresentadas.
- O lucro marginal de uma empresa é 3 vezes proporcional ao lucro $L=L(x)$ por cada $x$ unidades de produto vendido. Equação diferencial: $L^{\prime}=3 L$, ou seja, $L^{\prime}-3 L=0$.
- A taxa de variação de uma variável $y=y(x)$ em relação à variável $x$ é inversamente proporcional a $x y$. Equação diferencial: $y^{\prime}=\frac{k}{x y}, k \in \mathbb{R}$, ou seja, $x y y^{\prime}-k=0$.
- A inclinação de uma dada curva $y=y(x)$ num ponto $(x, y)$ qualquer é dada pela diferença entre $x y$ e $x^{2} y$. Equação diferencial: $y^{\prime}=x y-x^{2} y$, ou seja, $y^{\prime}-x y+x^{2} y=0$.

\section*{Solução de uma equação diferencial (ED)}

Resolver uma ED consiste em determinar uma relação entre as variáveis $x$ e $y$ que verifica a ED, designada por solução da ED. Para tal, de modo a "eliminar" a derivada $y^{\prime}$ da equação inicial, é necessário integrar de algum modo a equação.

Uma solução geral de uma ED é uma solução que depende de (pelo menos) um parâmetro $C \in \mathbb{R}$. Quando concretizamos a constante $C$ para um valor específico, obtemos uma solução particular.

Em geral, as soluções particulares das ED estão associadas a condições iniciais, ou seja, condições adicionais que permitem determinar a constante $C$ a partir da solução geral.

\section*{Exemplo 4 (Usar uma condição inicial):}

Seja $y=(x-1)^{2}+C, C \in \mathbb{R}$, a solução geral de uma ED.
Determine a solução particular que passa pelo ponto $(3,-1)$.
- Condição inicial: $y(3)=-1$, i.e., quando $x=3$ temos $y=1$.
- Fazendo $x=3$ na solução geral: $y(3)=(3-1)^{2}+C=4+C$.
- Então, $y(3)=-1 \Leftrightarrow 4+C=-1 \Leftrightarrow C=-5$.
- A solução particular é $y=(x-1)^{2}-5$.

Vamos aprender a resolver os seguintes dois tipos de EDs:
- EDs de variáveis separáveis (método de separação de variáveis).
- EDs lineares (método do fator integrante).

Exemplo 3 (Testar soluções): Considere a ED $y^{\prime}+2 x y=2 x$
(1) Mostre que a função constante $y=1$ é solução da ED.

Ora, $y^{\prime}=(1)^{\prime}=0$. Substituindo $y$ e $y^{\prime}$ na ED:
$0+2 x 1=2 x \Leftrightarrow 2 x=2 x \quad$ (proposição verdadeira)
(2) Mostre que a função $y=1+C \mathrm{e}^{-x^{2}}, C \in \mathbb{R}$ é solução da ED .

Ora, $y^{\prime}=(1)^{\prime}+C\left(\mathrm{e}^{-x^{2}}\right)^{\prime}=C\left(-x^{2}\right)^{\prime} \mathrm{e}^{-x^{2}}=-2 C x \mathrm{e}^{-x^{2}}$.
Substituindo $y$ e $y^{\prime}$ na ED: $-2 C x \mathrm{e}^{-x^{2}}+2 x\left(1+C \mathrm{e}^{-x^{2}}\right)=2 x \Leftrightarrow \Leftrightarrow-2 C x \mathrm{e}^{-x^{2}}+2 x+2 x C \mathrm{e}^{-x^{2}}=2 x \Leftrightarrow 2 x=2 x$ (P. verdadeira)
$y(x)=1+C \mathrm{e}^{-x^{2}}, C \in \mathbb{R}$ é a solução geral da ED.
$y(x)=1$ é uma solução particular da ED (considera-se $C=0$ ).

\section*{Equações diferenciais de variáveis separáveis}

Uma ED de variáveis separadas é uma equação do tipo:
$$
N(y) d y=M(x) d x .
$$
(Equação que se consegue escrever de modo a que cada variável $x$ e $y$ apareça em apenas um dos membros da equação. Além disso, cada termo que depende de $x$ está multiplicado por $d x$ e cada termo que depende de $y$ está multiplicado por $d y$.)

Uma equação diferencial de variáveis separáveis é uma equação que se pode reduzir a uma equação diferencial de variáveis separadas.

Exemplo 5: Exemplos de ED de variáveis separáveis:
(1) $y^{\prime}=\frac{x}{y^{2}} \Leftrightarrow$
$\Leftrightarrow y^{2} y^{\prime}=x$ (multiplicámos ambos os membros por $y^{2}$ ) ⇔
$\Leftrightarrow y^{2} \frac{d y}{d x}=x \Leftrightarrow$
$\Leftrightarrow y^{2} d y=x d x$ (multiplicámos ambos os membros por $d x$ )
(2) $\mathrm{e}^{x}+\cos y y^{\prime}=0 \Leftrightarrow$
$\Leftrightarrow \cos y \frac{d y}{d x}=-\mathrm{e}^{x}$ (adicionámos $-\mathrm{e}^{x}$ a ambos os membros) ⇔
$\Leftrightarrow \cos y d y=-\mathrm{e}^{x} d x$ (multiplicámos ambos os membros por $d x$ )

Resolvemos agora as ED apresentadas no Exemplo 5:
(1) $y^{\prime}=\frac{x}{y^{2}} \Leftrightarrow y^{2} y^{\prime}=x \Leftrightarrow y^{2} \frac{d y}{d x}=x \Leftrightarrow y^{2} d y=x d x \Leftrightarrow \Leftrightarrow \int y^{2} d y=\int x d x \Leftrightarrow \frac{y^{3}}{3}=\frac{x^{2}}{2}+C, C \in \mathbb{R}$.
A solução geral é dada pela relação $\frac{y^{3}}{3}=\frac{x^{2}}{2}+C, C \in \mathbb{R}$. Neste caso, conseguimos explicitar $y$ como função de $x: y=\sqrt[3]{\frac{3}{2} x^{2}+3 C}$.
(2) $\mathrm{e}^{x}+\cos y y^{\prime}=0 \Leftrightarrow \cos y \frac{d y}{d x}=-\mathrm{e}^{x} \Leftrightarrow \cos y d y=-\mathrm{e}^{x} d x \Leftrightarrow \Leftrightarrow \quad \int \cos y d y=\int\left(-\mathrm{e}^{x}\right) d x \Leftrightarrow \sin y=-\mathrm{e}^{x}+C, C \in \mathbb{R}$.
A solução geral é dada pela relação $\sin y=-\mathrm{e}^{x}+C, C \in \mathbb{R}$.

\section*{Resolução de uma ED de variáveis separáveis (Método de separação de variáveis)}

De forma a encontrarmos a solução geral de uma ED de variáveis separáveis podemos proceder da seguinte forma:
(1) Separar as variáveis, obtendo uma ED de variáveis separadas:
$$
N(y) d y=M(x) d x
$$
(2) Integrar a equação anterior, obtendo a solução geral:
$$
\int N(y) d y=\int M(x) d x+C, C \in \mathbb{R}
$$

Ideia: Função de $y d y=$ Função de $x d x \Leftrightarrow \int$ Função de $y d y=\int$ Função de $x d x$

Exemplo 6: Resolva a equação diferencial $\sqrt{x+1}+y y^{\prime}=x$.
$\sqrt{x+1}+y y^{\prime}=x \Leftrightarrow$
$\Leftrightarrow y \frac{d y}{d x}=x-\sqrt{x+1} \Leftrightarrow$
$\Leftrightarrow y d y=(x-\sqrt{x+1}) d x \quad$ (ED de variáveis separadas) ⇔
$\Leftrightarrow \quad \int y d y=\int(x-\sqrt{x+1}) d x \Leftrightarrow$
$\Leftrightarrow \frac{y^{2}}{2}=\int x d x-\int(x+1)^{\frac{1}{2}} d x$ Recordar: $\int u^{\prime} u^{n}=\frac{u^{n+1}}{n+1}+C$
$\Leftrightarrow \frac{y^{2}}{2}=\frac{x^{2}}{2}-\frac{2}{3}(x+1)^{\frac{3}{2}}+C, C \in \mathbb{R} \quad$ (solução geral)

Exemplo 7: Resolva a equação diferencial $(x+1) y^{\prime}-\mathrm{e}^{y}=0$.
$(x+1) y^{\prime}-\mathrm{e}^{y}=0 \Leftrightarrow(x+1) y^{\prime}=\mathrm{e}^{y} \Leftrightarrow$
$\Leftrightarrow \frac{1}{\mathrm{e}^{y}} y^{\prime}=\frac{1}{x+1} \Leftrightarrow \mathrm{e}^{-y} \frac{d y}{d x}=\frac{1}{x+1} \Leftrightarrow$
$\Leftrightarrow \mathrm{e}^{-y} d y=\frac{1}{x+1} d x \quad$ (ED de variáveis separadas) $\Leftrightarrow$
$\Leftrightarrow \int \mathrm{e}^{-y} d y=\int \frac{1}{x+1} d x \quad$ Recordar: $\int \frac{u^{\prime}}{u}=\ln |u|+C$
$\Leftrightarrow-\int-\mathrm{e}^{-y} d y=\ln |x+1| \quad$ Recordar: $\int u^{\prime} \mathrm{e}^{u}=\mathrm{e}^{u}+C$
$\Leftrightarrow-\mathrm{e}^{-y}=\ln |x+1|+C, C \in \mathbb{R} \quad$ (solução geral)

\section*{Exemplo 8 (continuação)}

Pretendemos agora a solução particular que verifica a condição inicial
$$
y(1)=\mathrm{e} \quad(\text { isto é, quando } x=1, \text { temos } y=\mathrm{e}) .
$$

Atendendo à solução geral $\ln |y|=\frac{x^{2}}{2}-\frac{x^{3}}{3}+C, C \in \mathbb{R}$, temos
$$
y(1)=\mathrm{e} \Leftrightarrow \ln \mathrm{e}=\frac{1}{2}-\frac{1}{3}+C \Leftrightarrow 1=\frac{1}{6}+C \Leftrightarrow C=\frac{5}{6}
$$

Então, a solução particular pretendida é
$$
\ln |y|=\frac{x^{2}}{2}-\frac{x^{3}}{3}+\frac{5}{6}
$$

Exemplo 8: Determine a solução particular da equação diferencial de variáveis separáveis $x^{-1} y^{\prime}=(1-x) y$ que satisfaz $y(1)=\mathrm{e}$.
$$
\begin{aligned}
& x^{-1} y^{\prime}=(1-x) y \Leftrightarrow \\
& \Leftrightarrow \frac{1}{y} y^{\prime}=x(1-x) \Leftrightarrow \\
& \Leftrightarrow \frac{1}{y} \frac{d y}{d x}=x-x^{2} \Leftrightarrow \\
& \Leftrightarrow \frac{1}{y} d y=\left(x-x^{2}\right) d x \quad \text { (ED de variáveis separadas) } \Leftrightarrow \\
& \Leftrightarrow \int \frac{1}{y} d y=\int x d x-\int x^{2} d x \Leftrightarrow \\
& \Leftrightarrow \ln |y|=\frac{x^{2}}{2}-\frac{x^{3}}{3}+C, C \in \mathbb{R} \quad \text { (solução geral) }
\end{aligned}
$$

\section*{Exemplo 9: Encontre a solução geral da equação diferencial}
$$
\begin{aligned}
& \cos y \mathrm{e}^{-x^{3}-1} y^{\prime}+x^{2} \mathrm{e}^{-\sin y}=\mathrm{e}^{-\sin y-x^{3}-1} \Leftrightarrow \\
& \Leftrightarrow \cos y \mathrm{e}^{-x^{3}-1} y^{\prime}=\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}-x^{2} \mathrm{e}^{-\sin y} \Leftrightarrow \\
& \Leftrightarrow \cos y \mathrm{e}^{-x^{3}-1} y^{\prime}=\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}-x^{2} \mathrm{e}^{-\sin y} \Leftrightarrow \\
& \Leftrightarrow \frac{\cos y \mathrm{e}^{-x^{3}-1} y^{\prime}}{\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}}=\frac{\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}}{\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}}-\frac{x^{2} \mathrm{e}^{-\sin y}}{\mathrm{e}^{-\sin y} \mathrm{e}^{-x^{3}-1}} \Leftrightarrow \\
& \Leftrightarrow \frac{\cos y}{\mathrm{e}^{-\sin y}} y^{\prime}=1-\frac{x^{2}}{\mathrm{e}^{-x^{3}-1}} \Leftrightarrow \\
& \Leftrightarrow \cos y \mathrm{e}^{\sin y} y^{\prime}=1-x^{2} \mathrm{e}^{x^{3}+1} \Leftrightarrow
\end{aligned}
$$

\section*{Exemplo 9 (continuação)}
$$
\begin{aligned}
& \Leftrightarrow \cos y \mathrm{e}^{\sin y} \frac{d y}{d x}=1-x^{2} \mathrm{e}^{x^{3}+1} \Leftrightarrow \\
& \Leftrightarrow \cos y \mathrm{e}^{\sin y} d y=\left(1-x^{2} \mathrm{e}^{x^{3}+1}\right) d x \quad \text { (ED de variáveis separadas) } \\
& \Leftrightarrow \int \cos y \mathrm{e}^{\sin y} d y=\int 1 d x-\int x^{2} \mathrm{e}^{x^{3}+1} d x \Leftrightarrow \\
& \Leftrightarrow \mathrm{e}^{\sin y}=x-\frac{1}{3} \int 3 x^{2} \mathrm{e}^{x^{3}+1} d x \text { Recordar: } \int u^{\prime} \mathrm{e}^{u}=\mathrm{e}^{u}+C \\
& \Leftrightarrow \mathrm{e}^{\sin y}=x-\frac{1}{3} \mathrm{e}^{x^{3}+1}+C, C \in \mathbb{R} \quad \text { (solução geral) }
\end{aligned}
$$

\section*{Exemplo 10 (continuação)}

Pretendemos agora a solução particular que verifica a condição inicial
$$
y(0)=\frac{3}{4} \quad\left(\text { isto é, quando } x=0, \text { temos } y=\frac{3}{4}\right) .
$$

Atendendo à solução geral $y(x)=\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{4} \mathrm{e}^{2 x}+C, C \in \mathbb{R}$, vem
$$
y(0)=\frac{3}{4} \Leftrightarrow 0-\frac{1}{4} e^{0}+C=\frac{3}{4} \Leftrightarrow C=\frac{3}{4}+\frac{1}{4} \Leftrightarrow C=1 .
$$

Então, a curva que procuramos é
$$
y(x)=\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{4} \mathrm{e}^{2 x}+1
$$

Exemplo 10: Determine a curva $y=y(x)$ que passa pelo ponto $\left(0, \frac{3}{4}\right)$ e que tem uma inclinação de $x \mathrm{e}^{2 x}$ num ponto $(x, y)$ qualquer.
- A inclinação de uma curva é dada pela sua derivada. Assim, temos de resolver a equação diferencial $y^{\prime}=x \mathrm{e}^{2 x}$.
- $y^{\prime}=x \mathrm{e}^{2 x} \Leftrightarrow \frac{d y}{d x}=x \mathrm{e}^{2 x} \Leftrightarrow d y=x \mathrm{e}^{2 x} d x$ (ED de variáveis separadas)
$$
\begin{aligned}
& d y=x \mathrm{e}^{2 x} d x \Leftrightarrow \int 1 d y=\int x \mathrm{e}^{2 x} d x \Leftrightarrow \\
& \Leftrightarrow y=\frac{1}{2} x \mathrm{e}^{2 x}-\int \frac{1}{2} \mathrm{e}^{2 x} d x \text { (primitivação por partes) } \Leftrightarrow \\
& \Leftrightarrow y=\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{4} \mathrm{e}^{2 x}+C, C \in \mathbb{R} \text { (solução geral) }
\end{aligned}
$$

Observe-se que no exemplo anterior usámos a fórmula de primitivação por partes $\int u v^{\prime}=u v-\int u^{\prime} v$ para resolver $\int x \mathrm{e}^{2 x} d x$.
- Escolhemos $u=x$ e $v^{\prime}=\mathrm{e}^{2 x}$.
- $u=x \Rightarrow u^{\prime}=1$.
- $v^{\prime}=\mathrm{e}^{2 x} \Rightarrow v=\int \mathrm{e}^{2 x} d x=\frac{1}{2} \int 2 \mathrm{e}^{2 x} d x=\frac{1}{2} \mathrm{e}^{2 x}$.
- Aplicando a fórmula obtemos
$$
\begin{aligned}
& \int x \mathrm{e}^{2 x} d x=\frac{1}{2} x \mathrm{e}^{2 x}-\int \frac{1}{2} \mathrm{e}^{2 x} d x=\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{2} \int \mathrm{e}^{2 x} d x= \\
& =\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{4} \int 2 \mathrm{e}^{2 x} d x= \\
& =\frac{1}{2} x \mathrm{e}^{2 x}-\frac{1}{4} \mathrm{e}^{2 x}+C, C \in \mathbb{R}
\end{aligned}
$$

\section*{Equações diferenciais homogéneas}

Uma equação diferencial de $1^{\underline{\text { a }}}$ ordem diz-se homogénea se é representável na forma
$$
y^{\prime}=f(x, y),
$$
onde $f$ é uma função homogénea de grau zero.

Recorde-se que $f$ é homogénea de grau zero se e só se
$$
f(t x, t y)=t^{0} f(x, y), \quad \text { ou seja }, \quad f(t x, t y)=f(x, y)
$$
para quaisquer $t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$.

Exemplo 12: Justifique que $y^{\prime}-\frac{x-y}{x}=0$ é uma ED homogénea.
Note-se que $y^{\prime}-\frac{x-y}{x}=0 \Leftrightarrow y^{\prime}=\frac{x-y}{x}$.
Consideremos a função $f(x, y)=\frac{x-y}{x}$.
A função $f$ é homogénea de grau zero, pois
$f(t x, t y)=\frac{t x-t y}{t x}=\frac{t(x-y)}{t x}=\frac{t}{t} \frac{x-y}{x}=\frac{x-y}{x}=f(x, y)$,
para quaisquer $t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$.

Exemplo 11: Justifique que $y^{\prime}=\frac{y}{x}+e^{-\frac{y}{x}}$ é uma ED homogénea.
Consideremos a função $f(x, y)=\frac{y}{x}+e^{-\frac{y}{x}}$.
A função $f$ é homogénea de grau zero, pois
$f(t x, t y)=\frac{t y}{t x}+\mathrm{e}^{-\frac{t y}{t x}}=\frac{y}{x}+\mathrm{e}^{-\frac{y}{x}}=f(x, y)$,
para quaisquer $t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$.

Lígia Abrunheiro (ISCA-UA)

\section*{Resolução de uma ED homogénea}
(1) Efetuar a mudança de variável $y=x u$. Para o efeito,
- Substituímos $y$ por $x u$, ou seja, $\frac{y}{x}$ por $u$.
(Note-se que $y=x u \Leftrightarrow \frac{y}{x}=u$.)
- Substituímos também $y^{\prime}$ por $u+x u^{\prime}$.
(Considerando a notação $y^{\prime} \equiv \frac{d y}{d x}, x^{\prime} \equiv \frac{d x}{d x}$ e $u^{\prime} \equiv \frac{d u}{d x}$, temos $\left.y=x u \Rightarrow y^{\prime}=(x u)^{\prime}=x^{\prime} u+x u^{\prime}=u+x u^{\prime}.\right)$

Passamos da ED com $x, y$ e $y^{\prime}$, para uma nova ED com $x, u, u^{\prime}$. Esta nova equação é uma ED de variáveis separáveis, que se resolve usando o método de separação de variáveis.

ED homogénea
$x$ variável independente $\quad y=x u \quad x$ variável independente
$y$ variável dependente
$y^{\prime}=\frac{d y}{d x}$
$u$ variável dependente
$u^{\prime}=\frac{d u}{d x}$

\section*{ED de variáveis separáveis}
$x$ variável independente
(2) Separar as variáveis da nova ED, obtendo uma ED de variáveis separadas ("variáveis $x$ e $u$ separadas").
(3) Integrar a ED de variáveis separadas obtida.
(4) Regressar às variáveis iniciais ( $x$ e $y$ ), substituindo $u=\frac{y}{x}$.

A equação resultante é a solução geral da ED homogénea.

Resolvemos agora a ED apresentada no Exemplo 12: $y^{\prime}=\frac{x-y}{x}$
- Mudança de variável $\left\lvert\, \begin{aligned} & y=u x \Leftrightarrow u=\frac{y}{x} \\ & y^{\prime}=u+x u^{\prime}\end{aligned}\right.$

Ao substituirmos na ED, resulta $u+x u^{\prime}=\frac{x-u x}{x}$.
- Resolvendo a ED obtida, temos:
$$
\begin{aligned}
& u+x u^{\prime}=\frac{x-u x}{x} \Leftrightarrow u+x u^{\prime}=\frac{x(1-u)}{x} \Leftrightarrow u+x u^{\prime}=1-u \Leftrightarrow \\
& \Leftrightarrow x u^{\prime}=1-u-u \Leftrightarrow x u^{\prime}=1-2 u \Leftrightarrow x \frac{d u}{d x}=1-2 u \Leftrightarrow \\
& \Leftrightarrow \frac{1}{1-2 u} d u=\frac{1}{x} d x \quad \text { (ED de variáveis separadas) } \Leftrightarrow
\end{aligned}
$$

Resolvemos agora a ED apresentada no Exemplo 11: $y^{\prime}=\frac{y}{x}+\mathrm{e}^{-\frac{y}{x}}$
- Mudança de variável $\left\lvert\, \begin{aligned} & y=u x \Leftrightarrow u=\frac{y}{x} \\ & y^{\prime}=u+x u^{\prime}\end{aligned}\right.$

Ao substituirmos na ED, resulta $u+x u^{\prime}=u+e^{-u}$.
- Substituindo $u=\frac{y}{x}$, obtemos a solução geral $e^{\frac{y}{x}}=\ln |x|+C, C \in \mathbb{R}$.
DS
- Mudança de variável
$$
\begin{aligned}
& y=u x \Leftrightarrow u=\frac{y}{x} \\
& y^{\prime}=u+x u^{\prime}
\end{aligned}
$$
"

Ao substituirmos na ED, resulta $u+x u=u+e$.

\section*{- Resolvendo a ED obtida, temos: \\ - Resolvendo a ED obtida, temos:}
$$
\begin{aligned}
& u+x u^{\prime}=u+\mathrm{e}^{-u} \Leftrightarrow x u^{\prime}=\mathrm{e}^{-u} \Leftrightarrow \frac{1}{\mathrm{e}^{-u}} \frac{d u}{d x}=\frac{1}{x} \Leftrightarrow \\
& \Leftrightarrow \mathrm{e}^{u} d u=\frac{1}{x} d x \quad(\text { ED de variáveis separadas }) \Leftrightarrow \\
& \Leftrightarrow \int \mathrm{e}^{u} d u=\int \frac{1}{x} d x \Leftrightarrow \mathrm{e}^{u}=\ln |x|+C, C \in \mathbb{R}
\end{aligned}
$$
$\_\_\_\_$
- Substituindo $u=\frac{y}{x}$, obtemos a solução geral
$$
-\frac{1}{2} \ln \left|1-2 \frac{y}{x}\right|=\ln |x|+C, C \in \mathbb{R}
$$

Exemplo 13: Mostre que a equação diferencial $x^{2} y^{\prime}+x y y^{\prime}=y^{2}$ é homogénea e determine a solução particular que satisfaz $y(1)=1$.
- Mostrar que a equação diferencial é homogénea.
$$
x^{2} y^{\prime}+x y y^{\prime}=y^{2} \Leftrightarrow\left(x^{2}+x y\right) y^{\prime}=y^{2} \Leftrightarrow y^{\prime}=\frac{y^{2}}{x^{2}+x y} .
$$

Seja $f(x, y)=\frac{y^{2}}{x^{2}+x y}$. A função $f$ é homogénea de grau zero:
$$
\begin{aligned}
& f(t x, t y)=\frac{t^{2} y^{2}}{t^{2} x^{2}+t x t y}=\frac{t^{2} y^{2}}{t^{2} x^{2}+t^{2} x y}=\frac{t^{2} y^{2}}{t^{2}\left(x^{2}+x y\right)}= \\
& =\frac{t^{2}}{t^{2}} \frac{y^{2}}{x^{2}+x y}=\frac{y^{2}}{x^{2}+x y}=f(x, y)
\end{aligned}
$$
para quaisquer $t \in \mathbb{R}$ e $(x, y) \in D_{f}$ tais que $(t x, t y) \in D_{f}$.

\section*{Exemplo 13 (continuação)}
- Resolver a equação diferencial homogénea $y^{\prime}=\frac{y^{2}}{x^{2}+x y}$.

Mudança de variável $\left\lvert\, \begin{aligned} & y=u x \Leftrightarrow u=\frac{y}{x} \\ & y^{\prime}=u+x u^{\prime}\end{aligned}\right.$
$$
\begin{aligned}
& u+x u^{\prime}=\frac{(u x)^{2}}{x^{2}+x u x} \Leftrightarrow u+x u^{\prime}=\frac{u^{2} x^{2}}{x^{2}+x^{2} u} \Leftrightarrow \\
& \Leftrightarrow u+x u^{\prime}=\frac{x^{2} u^{2}}{x^{2}(1+u)} \Leftrightarrow u+x u^{\prime}=\frac{u^{2}}{1+u} \Leftrightarrow \\
& \Leftrightarrow x u^{\prime}=\frac{u^{2}}{1+u}-u \Leftrightarrow x u^{\prime}=\frac{u^{2}}{1+u}-\frac{u(1+u)}{1+u} \Leftrightarrow \\
& \Leftrightarrow x u^{\prime}=\frac{u^{2}-u-u^{2}}{1+u} \Leftrightarrow x u^{\prime}=\frac{-u}{1+u} \Leftrightarrow
\end{aligned}
$$

\section*{Exemplo 13 (continuação)}
- Pretendemos agora a solução particular que verifica a condição inicial
$$
y(1)=1 \quad(\text { isto é, quando } x=1, \text { temos } y=1)
$$

Atendendo à solução geral $\ln \left|\frac{y}{x}\right|+\frac{y}{x}=-\ln |x|+C, C \in \mathbb{R}$, temos
$$
y(1)=1 \Leftrightarrow \ln 1+1=-\ln 1+C \Leftrightarrow C=1 \text {. }
$$

Então, a solução particular pretendida é
$$
\ln \left|\frac{y}{x}\right|+\frac{y}{x}=-\ln |x|+1
$$
- Solução geral: $\ln \left|\frac{y}{x}\right|+\frac{y}{x}=-\ln |x|+C, C \in \mathbb{R}$.

\section*{Equações diferenciais lineares}

Uma equação diferencial linear de $1^{\underline{a}}$ ordem é uma equação do tipo:
$$
y^{\prime}+f(x) y=g(x),
$$
onde $f$ e $g$ são funções de $x$ contínuas.
Exemplos de EDs lineares:
- $y^{\prime}-2 x y+2 x=0 \Leftrightarrow y^{\prime}+(-2 x) y=-2 x$.
- $\frac{d y}{d x}+2 y-2=\mathrm{e}^{x} \Leftrightarrow y^{\prime}+2 y=2+\mathrm{e}^{x}$.
- $x d y+y d x=\sqrt{x} d x \Leftrightarrow x \frac{d y}{d x}+y=\sqrt{x} \Leftrightarrow y^{\prime}+\frac{1}{x} y=\frac{\sqrt{x}}{x}$.

\section*{Exemplo 14 (continuação)}
- Ao substituir o $1^{\underline{0}}$ membro da (ED*) por ( $\left.y \mathrm{e}^{\sin x}\right)^{\prime}$, obtemos a ED equivalente $\left(y \mathrm{e}^{\sin x}\right)^{\prime}=\cos x \mathrm{e}^{\sin x}$.
- Mas, por definição de integral indefinido
$$
\left(y e^{\sin x}\right)^{\prime}=\cos x e^{\sin x} \Leftrightarrow y e^{\sin x}=\int \cos x e^{\sin x} d x
$$
- Basta agora calcular o integral do $2^{\underline{o}}$ membro da equação anterior, ou seja, $\int \cos x \mathrm{e}^{\sin x} d x=\mathrm{e}^{\sin x}+C, C \in \mathbb{R}$.
- A solução geral da ED é dada por $y \mathrm{e}^{\sin x}=\mathrm{e}^{\sin x}+C$, ou seja, $y=1+C \mathrm{e}^{-\sin x}, C \in \mathbb{R}$.

No método que usaremos para resolver a ED linear $y^{\prime}+f(x) y=g(x)$, a função $f$ tem um papel primordial, pois com ela construímos um elemento que multiplicado pela ED a permite integrar.

Exemplo 14 Consideremos a ED $y^{\prime}+\cos x y=\cos x$ linear.
- Precisamos de uma primitiva de $f(x)=\cos x: \int \cos x d x=\sin x$.
- Multiplicando a ED por $\mathrm{e}^{\sin x}$, obtemos uma ED equivalente:
$$
(\mathrm{ED} *) y^{\prime} \mathrm{e}^{\sin x}+y \cos x \mathrm{e}^{\sin x}=\cos x \mathrm{e}^{\sin x}
$$
- O $1^{\underline{\circ}}$ membro da equação obtida é a derivada de um produto. Que produto é esse? É o produto de y por $\mathrm{e}^{\sin x}$ ! Confirmar: $\left(y \mathrm{e}^{\sin x}\right)^{\prime}=y^{\prime} \mathrm{e}^{\sin x}+y\left(\mathrm{e}^{\sin x}\right)^{\prime}=y^{\prime} \mathrm{e}^{\sin x}+y \cos x \mathrm{e}^{\sin x}$.

\section*{Resolução de uma ED linear (método do fator integrante)}
(1) Determina-se o fator integrante $=\mathrm{e}^{\int f(x) d x}$.
(2) Multiplica-se a equação linear $y^{\prime}+f(x) y=g(x)$ pelo fator integrante:
$$
y^{\prime} \mathrm{e}^{\int f(x) d x}+y f(x) \mathrm{e}^{\int f(x) d x}=g(x) \mathrm{e}^{\int f(x) d x}
$$
e escreve-se esta equação, de forma equivalente, como
$$
\frac{d}{d x}\left(y \mathrm{e}^{\int f(x) d x}\right)=g(x) \mathrm{e}^{\int f(x) d x}
$$

Isto é, $\left(y \mathrm{e}^{\int f(x) d x}\right)^{\prime}=g(x) \mathrm{e}^{\int f(x) d x}$.
(Após a multiplicação da equação linear pelo fator integrante, e o primeiro membro da nova equação resulta sempre na derivada em ordem a $x$ do produto da função incógnita y pelo fator integrante $\mathrm{e}^{\int f(x) d x}$.)
(3) Integra-se a equação resultante em ordem a $x$, obtendo-se a solução geral:
$$
y \mathrm{e}^{\int f(x) d x}=\int\left(g(x) \mathrm{e}^{\int f(x) d x}\right) d x+C, C \in \mathbb{R}
$$
ou seja, $y$ é definida de forma explícita por:
$$
y=\frac{1}{\mathrm{e}^{\int f(x) d x}} \int\left(g(x) \mathrm{e}^{\int f(x) d x}\right) d x+\frac{C}{\mathrm{e}^{\int f(x) d x}}, C \in \mathbb{R}
$$

De forma a melhor compreender os diversos passos do método do fator integrante, torna-se útil recordar o seguinte:
- $(u v)^{\prime}=u^{\prime} v+u v^{\prime}$
- $\int \frac{d u}{d x} d x=u+C, C \in \mathbb{R}$, isto é, $\int u^{\prime} d x=u+C, C \in \mathbb{R}$ onde $u$ e $v$ representam funções de $x$.

De forma a simplificarmos o cálculo do fator integrante, em alguns caso, é importante ter em consideração as seguintes propriedades do logaritmo:
$$
\mathrm{e}^{\ln a}=a \quad-\ln a^{b}=b \ln a
$$

Analisemos o fator integrante $\mathrm{e}^{\int f(x) d x}$ associado às seguintes EDs:
- ED $y^{\prime}+\frac{2 y}{x+1}=x \Leftrightarrow y^{\prime}+\frac{2}{x+1} y=x$.

Fator integrante $=\mathrm{e}^{\int \frac{2}{x+1} d x}=\mathrm{e}^{2 \ln |x+1|}=\mathrm{e}^{\ln (x+1)^{2}}=(x+1)^{2}$.
- ED $y^{\prime}+\frac{x}{1+x^{2}} y=x$.

Fator integrante $=\mathrm{e}^{\int \frac{x}{1+x^{2}} d x}=\mathrm{e}^{\frac{1}{2} \ln \left(1+x^{2}\right)}=\mathrm{e}^{\ln \left(1+x^{2}\right)^{\frac{1}{2}}}=\left(1+x^{2}\right)^{\frac{1}{2}}$.
- ED $y^{\prime}-\frac{1}{x} y=x$.

Seja
$x>0$
Fator integrante $=\mathrm{e}^{\int-\frac{1}{x} d x}=\mathrm{e}^{-\ln |x|}=\mathrm{e}^{-\ln x}=\mathrm{e}^{\ln x^{-1}}=x^{-1}$.

Exemplo 15 Determinar a solução geral de $y^{\prime}+\frac{1}{x} y=\frac{\sqrt{x}}{x}$.
- $f(x)=\frac{1}{x}$, então $\int f(x) d x=\int \frac{1}{x} d x=\ln |x|$.
$$
\begin{gathered}
\text { Seja } \\
x>0
\end{gathered}
$$
- Fator integrante $=\mathrm{e}^{\int f(x) d x}=\mathrm{e}^{\ln |x|}=\mathrm{e}^{\ln x}=x$.
- Multiplicar a ED pelo fator integrante $x$ e integrar:
$$
\begin{aligned}
& y^{\prime}+\frac{1}{x} y=\frac{\sqrt{x}}{x} \Leftrightarrow y^{\prime} x+x \frac{1}{x} y=\frac{\sqrt{x}}{x} x \Leftrightarrow \\
& \Leftrightarrow y^{\prime} x+y=\sqrt{x} \Leftrightarrow(y x)^{\prime}=\sqrt{x} \Leftrightarrow y x=\int x^{\frac{1}{2}} d x \Leftrightarrow \\
& \Leftrightarrow y x=\frac{2}{3} x^{\frac{3}{2}}+C \Leftrightarrow y=\frac{2}{3} x^{\frac{1}{2}}+\frac{C}{x}, C \in \mathbb{R} .
\end{aligned}
$$

Exemplo 16 Determinar a solução geral de $y^{\prime}+(-2 x) y=-2 x$.
- $f(x)=-2 x$, então $\int f(x) d x=\int-2 x d x=-x^{2}$.
- Fator integrante $=\mathrm{e}^{\int f(x) d x}=\mathrm{e}^{-x^{2}}$.
- Multiplicar a ED pelo fator integrante $e^{-x^{2}}$ e integrar:
$$
\begin{aligned}
& y^{\prime}+(-2 x) y=-2 x \Leftrightarrow y^{\prime} \mathrm{e}^{-x^{2}}+y(-2 x) \mathrm{e}^{-x^{2}}=-2 x \mathrm{e}^{-x^{2}} \Leftrightarrow \\
& \Leftrightarrow\left(y \mathrm{e}^{-x^{2}}\right)^{\prime}=-2 x \mathrm{e}^{-x^{2}} \Leftrightarrow y \mathrm{e}^{-x^{2}}=\int-2 x \mathrm{e}^{-x^{2}} d x \Leftrightarrow \\
& \Leftrightarrow y \mathrm{e}^{-x^{2}}=\mathrm{e}^{-x^{2}}+C \Leftrightarrow y=1+C \mathrm{e}^{x^{2}}, C \in \mathbb{R} .
\end{aligned}
$$

Exemplo 17 Determinar a solução geral de $y^{\prime}+2 y=2+\mathrm{e}^{x}$.
- Fator integrante $=\mathrm{e}^{\int f(x) d x}=\mathrm{e}^{\int 2 d x}=\mathrm{e}^{2 x}$.
- Multiplicar a ED pelo fator integrante $\mathrm{e}^{2 x}$ e integrar:
$$
\begin{aligned}
& y^{\prime}+2 y=2+\mathrm{e}^{x} \Leftrightarrow y^{\prime} \mathrm{e}^{2 x}+2 y \mathrm{e}^{2 x}=2 \mathrm{e}^{2 x}+\mathrm{e}^{x} \mathrm{e}^{2 x} \Leftrightarrow \\
& \Leftrightarrow\left(y \mathrm{e}^{2 x}\right)^{\prime}=2 \mathrm{e}^{2 x}+\mathrm{e}^{3 x} \Leftrightarrow y \mathrm{e}^{2 x}=\int\left(2 \mathrm{e}^{2 x}+\mathrm{e}^{3 x}\right) d x \Leftrightarrow \\
& \Leftrightarrow y \mathrm{e}^{2 x}=\int 2 \mathrm{e}^{2 x} d x+\int \mathrm{e}^{3 x} d x \Leftrightarrow \\
& \Leftrightarrow y \mathrm{e}^{2 x}=\mathrm{e}^{2 x}+\frac{1}{3} \mathrm{e}^{3 x}+C \Leftrightarrow y=1+\frac{\mathrm{e}^{x}}{3}+C \mathrm{e}^{-2 x}, C \in \mathbb{R}
\end{aligned}
$$

Multiplicar a ED pelo fator integrante $x^{2}$ e integrar:
$$
\begin{aligned}
& y^{\prime}+\frac{2}{x} y=\frac{\sin \left(1-x^{3}\right)}{3} \Leftrightarrow y^{\prime} x^{2}+\frac{2 x^{2}}{x} y=x^{2} \frac{\sin \left(1-x^{3}\right)}{3} \Leftrightarrow \\
& \Leftrightarrow y^{\prime} x^{2}+2 x y=\frac{1}{3} x^{2} \sin \left(1-x^{3}\right) \Leftrightarrow \\
& \Leftrightarrow\left(y x^{2}\right)^{\prime}=\frac{1}{3} x^{2} \sin \left(1-x^{3}\right) \Leftrightarrow y x^{2}=\int \frac{1}{3} x^{2} \sin \left(1-x^{3}\right) d x \Leftrightarrow \\
& \Leftrightarrow y x^{2}=\frac{1}{3} \int x^{2} \sin \left(1-x^{3}\right) d x \Leftrightarrow \\
& \Leftrightarrow y x^{2}=-\frac{1}{9} \int-3 x^{2} \sin \left(1-x^{3}\right) d x \Leftrightarrow \\
& \Leftrightarrow y x^{2}=\frac{1}{9} \cos \left(1-x^{3}\right)+C \Leftrightarrow y=\frac{\cos \left(1-x^{3}\right)}{9 x^{2}}+\frac{C}{x^{2}}, C \in \mathbb{R}
\end{aligned}
$$

Exemplo 18 Determine a função $y=f(x)$ que verifica $f(1)=0$ e cuja taxa de variação em relação a $x$ é dada por $\frac{x \sin \left(1-x^{3}\right)-6 y}{3 x}$.
- A taxa de variação da função é dada pela sua derivada.

Assim, temos de resolver a ED $y^{\prime}=\frac{x \sin \left(1-x^{3}\right)-6 y}{3 x}$.
- $y^{\prime}=\frac{x \sin \left(1-x^{3}\right)-6 y}{3 x} \Leftrightarrow y^{\prime}=\frac{x \sin \left(1-x^{3}\right)}{3 x}-\frac{6 y}{3 x} \Leftrightarrow$
$$
\Leftrightarrow y^{\prime}+\frac{2}{x} y=\frac{\sin \left(1-x^{3}\right)}{3}
$$

ED linear $y^{\prime}+f(x) y=g(x), \operatorname{com} f(x)=\frac{2}{x}$.
- Fator integrante $=\mathrm{e}^{\int f(x) d x}=\mathrm{e}^{\int \frac{2}{x} d x}=\mathrm{e}^{2 \ln |x|}=\mathrm{e}^{\ln x^{2}}=x^{2}$.

\section*{Exemplo 18 (continuação)}

Pretendemos agora a solução particular $y=f(x)$ que verifica a condição inicial
$$
f(1)=0 \quad \text { (isto é, quando } x=1, \text { temos } y=0 \text { ). }
$$

Atendendo à solução geral $f(x)=\frac{\cos \left(1-x^{3}\right)}{9 x^{2}}+\frac{C}{x^{2}}, C \in \mathbb{R}$, vem
$$
f(1)=0 \Leftrightarrow \frac{\cos 0}{9}+C=0 \Leftrightarrow \frac{1}{9}+C=0 \Leftrightarrow C=-\frac{1}{9} .
$$

Então, a função $y=f(x)$ que procuramos é definida por
$$
f(x)=\frac{\cos \left(1-x^{3}\right)}{9 x^{2}}-\frac{1}{9 x^{2}}, \text { ou seja, } f(x)=\frac{\cos \left(1-x^{3}\right)-1}{9 x^{2}}
$$

Exemplo 19 Classifique cada uma das EDs, justificando se está na presença de uma ED de variáveis separáveis ou linear.
(1)
$$
\begin{aligned}
& y^{\prime}-\frac{\ln x}{\ln y}=\frac{4}{\ln y} \Leftrightarrow \ln y y^{\prime}-\ln x=4 \Leftrightarrow \ln y \frac{d y}{d x}=4+\ln x \Leftrightarrow \\
& \Leftrightarrow \ln y d y=(4+\ln x) d x
\end{aligned}
$$

ED de variáveis separáveis.
(2) $d y+x(2 y-x) d x=0 \Leftrightarrow \frac{d y}{d x}+x(2 y-x) \frac{d x}{d x}=0 \Leftrightarrow$
$\Leftrightarrow y^{\prime}+2 x y-x^{2}=0 \Leftrightarrow y^{\prime}+2 x y=x^{2}$
ED linear $y^{\prime}+f(x) y=g(x)$, com $f(x)=2 x$ e $g(x)=x^{2}$.
(3) $d y+x^{2} d y+y d x=0 \Leftrightarrow\left(1+x^{2}\right) d y+y d x=0 \Leftrightarrow$
$$
\begin{aligned}
& \Leftrightarrow\left(1+x^{2}\right) y^{\prime}+y=0 \Leftrightarrow y^{\prime}+\frac{1}{1+x^{2}} y=0 \Leftrightarrow \\
& \Leftrightarrow \frac{1}{y} y^{\prime}=-\frac{1}{1+x^{2}} \Leftrightarrow \frac{1}{y} d y=-\frac{1}{1+x^{2}} d x
\end{aligned}
$$

ED de variáveis separáveis (ED linear $y^{\prime}+f(x) y=g(x)$ com $g(x)=0$ que se reduz a uma ED de variáveis separáveis).
(4) $x y^{\prime}+1=x y-y \Leftrightarrow x y^{\prime}+1=(x-1) y \Leftrightarrow$
$$
\Leftrightarrow y^{\prime}+\frac{1}{x}=\frac{(x-1) y}{x} \Leftrightarrow y^{\prime}-\frac{x-1}{x} y=-\frac{1}{x}
$$

ED linear $y^{\prime}+f(x) y=g(x), \operatorname{com} f(x)=-\frac{x-1}{x}$ e $g(x)=-\frac{1}{x}$.