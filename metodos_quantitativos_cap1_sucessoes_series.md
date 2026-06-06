[01SlidesCap1_MQ25_26_Suc+Series_4Pf.md](https://github.com/user-attachments/files/28671668/01SlidesCap1_MQ25_26_Suc%2BSeries_4Pf.md)
\title{
Métodos Quantitativos
}

\section*{Capítulo 1}

Sucessões reais e séries numéricas

\section*{Lígia Abrunheiro}

ISCA-UA
Fevereiro de 2026

Licenciatura em Finanças
isca
universidade de aveiro
(Revisão da versão de fevereiro de 2025)
instituto superior de contabilidade
e administração
1.1. Sucessões reais. Progressões aritméticas. Progressões geométricas.

\section*{Objetivos:}
- Usar os conceitos de:
sucessão de números reais, de termo geral e de limite de uma sucessão.
- Classificar as sucessões quanto à natureza do seu limite.
- Entender e aplicar o conceito de progressão aritmética.
- Entender e aplicar o conceito de progressão geométrica.
- Resolver problemas de aplicação prática enquadrando-os na teoria das sucessões de números reais.

\section*{Bibliografia/Bibliography}
- Clegg, D. K., Stewart, J., Watson, S. Calculus: Early Transcendentals, 9th edition, Brooks/Cole, 2020.
- "GeoGebra": https://www.geogebra.org/?lang=pt-PT/.
- Harshbarger, R. J. e Reynolds, J.J., Matemática Aplicada: Administração, Economia e Ciências Sociais e Biológicas, McGraw-Hill Int. Brasil (2006).
Harshbarger, R. J. and Reynolds, J. J., Mathematical Applications for the Management, Life and Social Sciences, Cengage Learning, 12th edition (2018).
- Larson, R., Hostetler, R. e Edwards, B., Cálculo, volume 2, McGraw-Hill Interamericana do Brasil, $8^{\underline{\text { a }}}$ edição (2006).
- "Khan Academy": https://pt-pt.khanacademy.org/

\section*{Sucessões de números reais}

Uma sucessão de números reais é uma aplicação do conjunto dos números naturais $\mathbb{N}$ no conjunto dos números reais $\mathbb{R}$ :
$$
\begin{aligned}
a: & \mathbb{N} \longrightarrow \mathbb{R} \\
& n
\end{aligned} \longmapsto a_{n} .
$$
- Os elementos do contradomínio $a_{1}, a_{2}, a_{3}, \ldots$ designam-se por termos da sucessão ( $a_{i}$ é o termo de ordem $i, i=1,2,3, \ldots$ ).
- A expressão designatória $a_{n}$ que define a sucessão (ou seja, o termo de ordem $n$ ) chama-se termo geral da sucessão.
- Denotamos a sucessão por $\left(a_{n}\right)_{n \in \mathbb{N}}$ ou $\left\{a_{n}\right\}_{n \in \mathbb{N}}$, ou simplesmente por ( $a_{n}$ ) ou $\left\{a_{n}\right\}$.

\section*{Exemplo 1:}
(1) Seja $a_{n}=2^{n}$ o termo geral de uma sucessão.
$n=1 \longmapsto a_{1}=2^{1}=2$ (termo de ordem 1 );
$n=2 \longmapsto a_{2}=2^{2}=4$ (termo de ordem 2);
$n=3 \longmapsto a_{3}=2^{3}=8$ (termo de ordem 3).
$\left(2^{n}\right)_{n \in \mathbb{N}}$ é a sucessão de números reais $2,4,8,16, \ldots$
(2) A sucessão $\left\{(-1)^{n}\right\}_{n \in \mathbb{N}}$ é a sucessão de números reais
$$
-1,+1,-1,+1,-1,+1, \ldots
$$
(3) Os $1^{\underline{\text { os }}}$ três termos da sucessão de termo geral $S_{n}=\sum_{i=1}^{n} \frac{1}{i}$ são:
$$
S_{1}=\sum_{i=1}^{1} \frac{1}{i}=1 \quad S_{2}=\sum_{i=1}^{2} \frac{1}{i}=1+\frac{1}{2} \quad S_{3}=\sum_{i=1}^{3} \frac{1}{i}=1+\frac{1}{2}+\frac{1}{3}
$$

\section*{Propriedades}
- O inverso de um infinitésimo é um infinitamente grande.
- O inverso de um infinitamente grande é um infinitésimo.
- O limite de uma sucessão quando existe é único.
- Toda a sucessão constante é convergente e tem por limite a própria constante.

Uma subsucessão de uma sucessão é uma sucessão que se obtém da primeira por supressão de termos (em número finito ou infinito).
- Se uma sucessão é convergente qualquer sua subsucessão é convergente para o mesmo limite.

\section*{Classificação das sucessões quanto à existência e natureza do limite}

Uma sucessão ( $a_{n}$ ) diz-se:
- Convergente se $\lim _{n \rightarrow+\infty} a_{n}$ é um $\mathrm{n}^{\circ}$ real (existe e é finito). Em particular, se $\lim _{n \rightarrow+\infty} a_{n}=0,\left(a_{n}\right)$ diz-se um infinitésimo.
- Divergente se não é convergente.
- Divergente oscilante (o limite não existe e não é infinito).
- Propriamente divergente (o limite existe e é infinito):
- Infinitamente grande positivo (o limite é $+\infty$ ).
- Infinitamente grande negativo (o limite é $-\infty$ ).
- Infinitamente grande sem sinal determinado: não é propriamente divergente e o seu limite em módulo é $+\infty$.

\section*{Exemplo 2:}
(1) A sequência de números $2,4,6,8,10, \ldots$ é a sucessão de números pares, representada pelo termo geral $a_{n}=2 n$. Esta sucessão é um infinitamente grande positivo, ou seja, é divergente com $\lim _{n \rightarrow+\infty} a_{n}=\lim _{n \rightarrow+\infty} 2 n=+\infty$.
$$
2,4,6,8,10, \ldots \longrightarrow+\infty
$$
(2) A sucessão de termo geral $a_{n}=\frac{1}{n}$ (sucessão dos inversos) é um infinitésimo, ou seja, converge para zero, $\lim _{n \rightarrow+\infty} \frac{1}{n}=0$.
$$
1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \ldots \longrightarrow 0
$$
(1) A sucessão de termo geral $a_{n}=(-1)^{n}$, ou seja, a sucessão de números reais
$$
-1,+1,-1,+1,-1,+1,-1,+1,-1, \ldots,
$$
é divergente oscilante, ou seja, não existe $\lim _{n \rightarrow+\infty}(-1)^{n}$, pois:
A subsucessão dos termos de índice ímpar $a_{1}, a_{3}, a_{5}, \ldots \longrightarrow-1$.
A subsucessão dos termos de índice par $a_{2}, a_{4}, a_{6}, \ldots \longrightarrow 1$.
( ᄀ Os números reais $\frac{2}{3}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}, \ldots$ representam os primeiros termos da sucessão de termo geral $a_{n}=\frac{n+1}{n+2}$.
Ao calcular o limite desta sucessão deparamo-nos com uma indeterminação do tipo $\frac{+\infty}{+\infty}$, que se levanta do seguinte modo:
$$
\lim _{n \rightarrow+\infty} \frac{n+1}{n+2}=\lim _{n \rightarrow+\infty} \frac{\frac{n+1}{n}}{\frac{n+2}{n}}=\lim _{n \rightarrow+\infty} \frac{1+\frac{1}{n}}{1+\frac{2}{n}}=\frac{1+0}{1+0}=1
$$

A sucessão ( $a_{n}$ ) é convergente (converge para o número real 1 ).
$\frac{2}{3}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}, \ldots \longrightarrow 1$
(1) A sucessão de termo geral $u_{n}=(-1)^{n} n$, ou seja, a sucessão de números reais
$$
-1,+2,-3,+4,-5,+6,-7,+8,-9, \ldots,
$$
é um infinitamente grande, ou seja, não existe $\lim _{n \rightarrow+\infty}(-1)^{n} n$ porque ( $u_{n}$ ) é divergente infinita e o seu limite em módulo é $+\infty, \lim _{n \rightarrow+\infty}\left|(-1)^{n} n\right|=+\infty$. Tem-se:

A subsucessão dos termos negativos $-1,-3,-5, \ldots \longrightarrow-\infty$.
A subsucessão dos termos positivos $2,4,6, \ldots \longrightarrow+\infty$.

Sucessão $n \mapsto r^{n}, r \in \mathbb{R}$
$$
\lim _{n \rightarrow+\infty} r^{n}= \begin{cases}+\infty & \text { se } r>1 \\ 1 & \text { se } r=1 \\ 0 & \text { se }-1<r<1 \\ \text { não existe (oscilante) } & \text { se } r=-1 \\ \text { não existe (infinitamente grande) } & \text { se } r<-1\end{cases}
$$

Exemplos:
$$
\begin{array}{lll}
\lim _{n \rightarrow+\infty}\left(-\frac{1}{3}\right)^{n}=0 & \lim _{n \rightarrow+\infty} 3^{-n}=0 & \lim _{n \rightarrow+\infty}-3^{n+1}=-\infty \\
\lim _{n \rightarrow+\infty} 3^{n+1}=+\infty & \lim _{n \rightarrow+\infty} \frac{1}{3^{-n}}=+\infty & \lim _{n \rightarrow+\infty} \frac{(-1)^{n} n}{n+2} \text { não existe } \\
\lim _{n \rightarrow+\infty}(-3)^{n+2} \text { não existe } & \lim _{n \rightarrow+\infty} \frac{2}{(-3)^{n}}=0 & \lim _{n \rightarrow+\infty} \frac{(-1)^{n-1}}{n+1}=0
\end{array}
$$

\section*{Progressões aritméticas}

Uma sucessão de números reais ( $a_{n}$ ) diz-se uma progressão aritmética de razão $r(\operatorname{com} r \in \mathbb{R})$ se
$$
a_{n+1}-a_{n}=r, \quad \text { ou seja }, \quad a_{n+1}=a_{n}+r,
$$
para todo $n \in \mathbb{N}$.
Cada termo, após o primeiro, é calculado somando a constante $r$ ao termo anterior.

Por exemplo, $0,2,4,6,8,10,12, \ldots$ é uma progressão aritmética de razão igual a 2 .

\section*{(Exemplo 3 - continuação)}
- Cada termos após o $1^{\underline{\mathrm{O}}}$ pode escrever-se em função do $1^{\underline{\mathrm{O}}}$ e da razão: $L_{1}=-2000$ (prejuízo de $2000 €$ no $1^{\underline{\circ}}$ mês)
$$
\begin{aligned}
& L_{2}=-1600=L_{1}+400 \\
& L_{3}=-1200=L_{1}+400+400=L_{1}+2 \times 400 \\
& L_{4}=-800=L_{1}+2 \times 400+400=L_{1}+3 \times 400 \\
& \ldots
\end{aligned}
$$
- Termo geral da progressão: $L_{n}=L_{1}+(n-1) r$, ou seja, $L_{n}=-2000+(n-1) 400=400 n-2400$.
- Qual o lucro total da empresa após 1 ano de funcionamento? Após um ano (ou seja, 12 meses), o lucro total é dado por $L_{12}=400 \times 12-2400=2400 €$.

Exemplo 3: Uma empresa perde $2000 €$ no $1^{\circ}$ mês a funcionar, mas o seu lucro cresce $400 €$ por mês nos meses seguintes, durante 1 ano. $L: n \mapsto L_{n}$ lucro total da empresa após $n$ meses a funcionar.

Esta função é uma progressão aritmética de razão $r=400$, pois cada termo após o $1^{\underline{\circ}}$ é obtido somando a constante 400 ao termo anterior:
$$
\begin{aligned}
& L_{1}=-2000 \\
& L_{2}=L_{1}+400=-2000+400=-1600 \\
& L_{3}=L_{2}+400=-1600+400=-1200 \\
& L_{4}=L_{3}+400=-1200+400=-800
\end{aligned}
$$

Qual será a expressão designatória $L_{n}$ que define a função lucro $L$ ?

\section*{Termo geral da progressão aritmética}

Por definição de progressão aritmética, sabemos que $a_{n+1}=a_{n}+r$.
- Os termos da progressão aritmética são
$$
\begin{aligned}
& a_{1} \\
& a_{2}=a_{1}+r \\
& a_{3}=a_{2}+r=a_{1}+r+r=a_{1}+2 r \\
& a_{4}=a_{3}+r=a_{1}+2 r+r=a_{1}+3 r \\
& \vdots \\
& a_{n}=a_{1}+(n-1) r \quad \text { termo geral }
\end{aligned}
$$
- Se $r=0$, todos os termos são iguais a $a_{1}$.

Exemplo 4: Suponha que the oferecem 2 propostas de emprego ( A e B ):
A: salário inicial de $20.000 €$ com aumento anual de $1.000 €$.
B: salário inicial de $18.000 €$ com aumento anual de $1.200 €$. Qual das duas propostas paga mais no décimo ano de emprego?
- Na proposta A temos uma progressão aritmética ( $a_{n}$ ) de razão $r=1000$ e com $a_{1}=20000$.

No décimo ano de emprego o salário será igual a
$$
a_{10}=a_{1}+9 r=20000+9 \times 1000=29000 € .
$$
- Na proposta B temos uma progressão aritmética $\left(b_{n}\right)$ de razão $r=1200$ e com $b_{1}=18000$.

No décimo ano de emprego o salário será igual a
$$
b_{10}=b_{1}+9 r=18000+9 \times 1200=28800 €
$$

Com a proposta A recebe-se mais no décimo ano de emprego.

\section*{Exemplo 6:}
(1) Se $\left(a_{n}\right)$ é uma progressão aritmética com $a_{7}=100$ e $r=10$, qual o valor de $a_{1}$ ?
$a_{7}=a_{1}+6 r \Leftrightarrow 100=a_{1}+60 \Leftrightarrow a_{1}=40$.
(2) Se $\left(a_{n}\right)$ é uma progressão aritmética com $a_{1}=23$ e $r=-6$, o elemento -13 é o termo de que ordem?
$a_{n}=-13 \Leftrightarrow a_{1}+(n-1) r=-13 \Leftrightarrow 23+(n-1)(-6)=-13 \Leftrightarrow \Leftrightarrow 23-6 n+6=-13 \Leftrightarrow 6 n=42 \Leftrightarrow n=7$. (Termo de ordem 7.)
(3) Se $\left(a_{n}\right)$ é uma progressão aritmética $\operatorname{com} a_{7}=x+2 \mathrm{e} a_{8}=x+1(x \in \mathbb{R})$, qual o valor da razão desta progressão?
$r=a_{8}-a_{7}=x+1-(x+2)=x+1-x-2=-1$.

Soma dos $\mathbf{n} 1^{\text {os }}$ termos de uma progressão aritmética ( $a_{n}$ )
$$
S_{n}=a_{1}+a_{2}+\cdots+a_{n}=\frac{n\left(a_{1}+a_{n}\right)}{2}
$$

Exemplo 5: Na situação da proposta de emprego A do exemplo anterior, qual o montante acumulado nos primeiros 10 anos?

O montante acumulado nos primeiros 10 anos é igual ao valor da soma dos 10 primeiros termos de $\left(a_{n}\right)$ :
$$
S_{10}=\frac{10\left(a_{1}+a_{10}\right)}{2}=\frac{10(20000+29000)}{2}=245000 €
$$

\section*{Progressões geométricas}

Uma sucessão de números reais $\left(a_{n}\right)$ diz-se uma progressão geométrica de razão $r(\operatorname{com} r \in \mathbb{R})$ se
$$
a_{n+1}=a_{n} r \quad\left(\text { ou seja }, \quad \frac{a_{n+1}}{a_{n}}=r \quad \text { quando } r \neq 0\right)
$$
para todo $n \in \mathbb{N}$.
Cada termo, após o primeiro, é calculado multiplicando a constante $r$ pelo termo anterior.

Por exemplo, $1,2,4,8,16,32,64, \ldots$ é uma progressão geométrica de razão igual a 2 .

Exemplo 7: Suponha que aposta na lotaria durante 5 semanas e que em cada semana, aposta o dobro do valor da aposta da semana anterior. Se a $1^{\underline{\mathrm{a}}}$ aposta é de $10 €$, quanto aposta na $5^{\underline{\mathrm{a}}}$ semana? $V_{n}$ valor da aposta na $n$-ésima semana.
$\left(V_{n}\right)$ é uma progressão geométrica de razão $r=2$, pois cada termo após o $1^{\mathrm{o}}$ é obtido multiplicando a constante 2 ao termo anterior:
$$
\begin{aligned}
& V_{1}=10 \\
& V_{2}=2 V_{1}=2 \times 10=20 \\
& V_{3}=2 V_{2}=2 \times 20=40 \\
& V_{4}=2 V_{3}=2 \times 40=80 \\
& V_{5}=2 V_{4}=2 \times 80=160
\end{aligned}
$$

O valor da aposta na $5^{\underline{a}}$ semana é de $160 €$.

\section*{Termo geral da progressão geométrica}

Por definição de progressão geométrica, sabemos que $a_{n+1}=a_{n} r$.
- Os termos da progressão geométrica são
$$
\begin{aligned}
& a_{1} \\
& a_{2}=a_{1} r \\
& a_{3}=a_{2} r=a_{1} r r=a_{1} r^{2} \\
& a_{4}=a_{3} r=a_{1} r^{2} r=a_{1} r^{3} \\
& \vdots \\
& a_{n}=a_{1} r^{n-1}, n>1 \quad \text { termo geral }
\end{aligned}
$$
- Se $r=0$ todos os termos, após o primeiro, são zero.
- Se $r=1$ todos os termos são iguais a $a_{1}$.

\section*{(Exemplo 7 - continuação)}
- Cada termos após o $1^{\underline{\mathrm{O}}}$ pode escrever-se em função do $1^{\underline{\mathrm{o}}}$ e da razão:
$$
\begin{aligned}
& V_{1}=10 \\
& V_{2}=20=V_{1} \times 2 \\
& V_{3}=40=V_{2} \times 2=10 \times 2 \times 2=V_{1} \times 2 \times 2=V_{1} \times 2^{2} \\
& V_{4}=80=V_{3} \times 2=V_{1} \times 2^{2} \times 2=V_{1} \times 2 \times 2 \times 2=V_{1} \times 2^{3}
\end{aligned}
$$
- Termo geral desta progressão: $V_{n}=V_{1} \times r^{n-1}=10 \times 2^{n-1}$.
- Valor da aposta na $5^{\underline{\mathrm{a}}}$ semana: $V_{5}=10 \times 2^{4}=160 €$.

\section*{Soma dos $\mathbf{n} 1^{\text {os }}$ termos de uma progressão geométrica ( $a_{n}$ )}
$$
S_{n}=a_{1}+a_{2}+\cdots+a_{n}= \begin{cases}a_{1} \frac{1-r^{n}}{1-r} & \text { se } r \neq 1 \\ a_{1} n & \text { se } r=1\end{cases}
$$

Exemplo 8: Na situação do exemplo anterior, qual o valor total apostado após cinco semanas?

O valor total apostado após cinco semanas é igual à soma dos 5 primeiros termos de $\left(V_{n}\right): S_{5}=a_{1} \frac{1-r^{5}}{1-r}=10 \frac{1-2^{5}}{1-2}=310 €$.

De facto, $V_{1}+V_{2}+V_{2}+V_{4}+V_{5}=10+20+40+80+160=310 €$.

\section*{Exemplo 9:}
(1) Se $\left(a_{n}\right)$ é uma progressão geométrica com $a_{4}=2$ e $a_{5}=162$, qual o valor de $a_{6}$ ?
Razão da progressão: $r=\frac{a_{5}}{a_{4}}=\frac{162}{2}=81$.
Assim, $a_{6}=r a_{5}=81 \times 162=13122$.
(2) Se a soma dos $n$ primeiros termos de uma progressão geométrica é $S_{n}=-3+3^{n+1}$, qual o valor da razão da progressão?
$a_{1}=S_{1}=-3+3^{2}=6$
$a_{2}=S_{2}-a_{1}=-3+3^{3}-6=18$.
Assim, $r=\frac{a_{2}}{a_{1}}=3$.

\section*{(Exemplo 10 - continuação)}
(2) De seguida, identificamos o tipo de progressão para cada caso:
$a_{1}=5, a_{2}=a_{1}+2=7, a_{3}=a_{2}+2=9, \ldots, a_{n+1}=a_{n}+2$
$\left(a_{n}\right)$ é uma progressão aritmética de razão $r=2$.
$b_{1}=12, b_{2}=b_{1}+1=13, b_{3}=b_{2}+1=14, \ldots, b_{n+1}=b_{n}+1$
$\left(b_{n}\right)$ é uma progressão aritmética de razão $r=1$.
(3) Calculamos agora os termos gerais de cada progressão:
$a_{n}=a_{1}+(n-1) r=5+2(n-1)=2 n+3$
$b_{n}=b_{1}+(n-1) r=12+1(n-1)=n+11$
(4) Por fim, igualamos os dois termos gerais:
$a_{n}=b_{n} \Leftrightarrow 2 n+3=n+11 \Leftrightarrow n=8$.
O João e a Maria resolvem exatamente o mesmo número de exercício no oitavo dia de estudo. Nesse dia, resolvem $a_{8}=b_{8}=19$ exercícios.

Exemplo 10: A Maria e o João começam a estudar no mesmo dia para o exame de matemática e têm por objetivo resolver o mesmo conjunto de exercício propostos pelo professor.
- A Maria resolve 5 exercícios no $1^{\underline{0}}$ dia e nos dias seguintes aumenta o seu estudo em 2 exercícios por cada dia.
- O João resolve 12 exercícios no $1^{\underline{\circ}}$ dia e nos dias seguintes aumenta o seu estudo em 1 exercício por cada dia.
Em que dia do estudo eles irão resolver exatamente o mesmo número de exercícios? Quantos exercícios resolvem nesse dia?
(1) Começamos por definir:
$a_{n}=\mathrm{n}$ - de exercícios resolvidos pela Maria no $n$-ésimo dia de estudo.
$b_{n}=\mathrm{n}^{\mathrm{o}}$ de exercícios resolvidos pelo João no $n$-ésimo dia de estudo.

Exemplo 11: Suponhamos que um país tem atualmente uma população de 20 milhões de habitantes e que se estima a sua taxa de crescimento em $2 \%$ por ano, nos próximos 20 anos. Isto é, daqui a um ano o país terá uma população de 20,4 milhões, daqui a dois anos, o número de habitantes será $102 \%$ da população que terá daqui a um ano (ou seja, 20,808 milhões), e assim sucessivamente.
- Escreva a expressão designatória do termo geral da sucessão ( $a_{n}$ ) que traduz o número de milhões de habitantes daqui a $n$ anos.

Note-se que
$$
\begin{aligned}
& a_{1}=20+20 \times 0,02=20(1+0,02)=20 \times 1,02 \\
& a_{2}=a_{1}+a_{1} \times 0,02=a_{1}(1+0,2)=a_{1} \times 1,02 \\
& \vdots \\
& a_{n+1}=a_{n} \times 1,02
\end{aligned}
$$

Logo, ( $a_{n}$ ) é uma progressão geométrica de razão $r=1,02$.

\section*{(Exemplo 11 - continuação)}

O termo geral de ( $a_{n}$ ) é dado por:
$a_{n}=a_{1} r^{n-1}=20 \times 1,02(1,02)^{n-1}=20(1,02)^{1+n-1}=20(1,02)^{n}$.
- Qual será o número de habitantes deste país daqui a 10 anos?

Temos de calcular o termo de ordem 10 da sucessão:
$a_{10}=20(1,02)^{10} \simeq 24,379884$ milhões de habitantes.
- Daqui a quantos anos o país terá o dobro dos habitantes que tem actualmente?

Temos de igualar o termo geral da sucessão a 40 :
$a_{n}=40 \Leftrightarrow 20(1,02)^{n}=40 \Leftrightarrow(1,02)^{n}=2 \Leftrightarrow \ln (1,02)^{n}=\ln 2 \Leftrightarrow \Leftrightarrow n \ln 1,02=\ln 2 \Leftrightarrow n=\frac{\ln 2}{\ln 1,02} \Leftrightarrow n \simeq 35$ anos.
(Exemplo 12 - continuação) Escreva a expressão que define a soma $S_{n}=a_{1}+a_{2}+\cdots+a_{n}$ associada à progressão geométrica $a_{n}=2^{n}$.
$$
S_{n}=a_{1} \frac{1-r^{n}}{1-r}=2 \frac{1-2^{n}}{1-2}=-2\left(1-2^{n}\right)=2^{n+1}-2
$$

Numa progressão (aritmética ou geométrica) $S_{n}$ pode ser visto como o termo geral de uma nova sucessão ( $S_{n}$ ).

No exemplo apresentado, a nova sucessão de somas $\left(S_{n}\right)$ (com termo geral $S_{n}=2^{n+1}-2$ ) é a sucessão cujos primeiros três termos são:
$$
\begin{array}{ll}
S_{1}=2^{2}-2=2 & \left(S_{1}=a_{1}=2\right) \\
S_{2}=2^{3}-2=6 & \left(S_{2}=a_{1}+a_{2}=2+2^{2}=6\right) \\
S_{3}=2^{4}-2=14 & \left(S_{3}=a_{1}+a_{2}+a_{3}=2+2^{2}+2^{3}=14\right)
\end{array}
$$

Exemplo 12: Mostre que a sucessão de termo geral $a_{n}=2^{n}$ é uma progressão geométrica e diga qual a natureza do seu limite.
- O termo de ordem $n+1$ é dado por $a_{n+1}=2^{n+1}$.
- Verifiquemos agora que $\frac{a_{n+1}}{a_{n}}$ é constante para qualquer $n \in \mathbb{N}$ :
$$
\frac{a_{n+1}}{a_{n}}=\frac{2^{n+1}}{2^{n}}=\frac{2^{n} 2^{1}}{2^{n}}=\frac{2^{n}}{2^{n}} 2=2
$$
( $a_{n}$ ) é uma progressão geométrica de razão $r=2$.
- $\lim _{n \rightarrow+\infty} a_{n}=\lim _{n \rightarrow+\infty} 2^{n}=+\infty$. A sucessão é divergente.

A sucessão $\left(2^{n}\right)$ é um infinitamente grande positivo.
$2,2^{2}, 2^{3}, 2^{4}, 2^{5}, \ldots \longrightarrow+\infty$

Exemplo 13: Mostre que a sucessão de termo geral $a_{n}=\frac{5^{n}}{3(-1)^{n+1}}$ é uma progressão geométrica.
- O termo de ordem $n+1$ é dado por $a_{n+1}=\frac{5^{n+1}}{3(-1)^{n+2}}$.
- Verifiquemos agora que $\frac{a_{n+1}}{a_{n}}$ é constante para qualquer $n \in \mathbb{N}$ :
$$
\frac{a_{n+1}}{a_{n}}=\frac{\frac{5^{n+1}}{3(-1)^{n+2}}}{\frac{5^{n}}{3(-1)^{n+1}}}=\frac{3(-1)^{n+1} 5^{n+1}}{3(-1)^{n+2} 5^{n}}=\frac{(-1)^{n+1} 5^{n} 5^{1}}{(-1)^{n+1}(-1)^{1} 5^{n}}=-5
$$

Concluímos que ( $a_{n}$ ) é uma progressão geométrica de razão $r=-5$.

Exemplo 14: Seja $a_{n}=\left(\frac{x^{2}+2}{3}\right)^{n}$ o termo geral de uma sucessão.
(1) Mostre que $\left(a_{n}\right)$ é uma progressão geométrica, para cada $x \in \mathbb{R}$. $\frac{a_{n+1}}{a_{n}}$ é constante para qualquer $n \in \mathbb{N}($ para cada $x \in \mathbb{R})$ :
$$
\frac{a_{n+1}}{a_{n}}=\frac{\left(\frac{x^{2}+2}{3}\right)^{n+1}}{\left(\frac{x^{2}+2}{3}\right)^{n}}=\left(\frac{x^{2}+2}{3}\right)^{n+1-n}=\frac{x^{2}+2}{3}
$$
$\left(a_{n}\right)$ é uma progressão geométrica de razão $r=\frac{x^{2}+2}{3}$, para cada $x \in \mathbb{R}$.

\subsection*{1.2. Séries numéricas. Critérios de convergência.}

\section*{Objetivos:}
- Entender o conceito de série numérica.
- Identificar as seguintes sucessões associadas a cada série:
- A sucessão cujo termo geral é o termo geral da série.
- A sucessão das somas parciais.
- Determinar a natureza da série (ver se é convergente ou divergente).
- No caso de convergência, calcular (se possível) a soma da série.
- Efetuar o estudo de séries geométricas.
- Efetuar o estudo de séries telescópicas.
- Usar o critério do termo geral para a divergência.
(2) Determine os valores de $x$ para os quais $\left(a_{n}\right)$ é convergente.

A progressão é convergente se e só se $\lim _{n \rightarrow+\infty} a_{n}$ existe.
O termo geral $a_{n}=\left(\frac{x^{2}+2}{3}\right)^{n}$ é do tipo $r^{n}$, com $r \in \mathbb{R}$.
$$
\begin{aligned}
\lim _{n \rightarrow+\infty} a_{n} \text { existe } & \Leftrightarrow-1<\frac{x^{2}+2}{3} \leq 1 \Leftrightarrow \\
& \Leftrightarrow \frac{x^{2}+2}{3}>-1 \wedge \frac{x^{2}+2}{3} \leq 1 \Leftrightarrow
\end{aligned}
$$
condição universal
$$
\begin{aligned}
& \Leftrightarrow \quad x^{2}+2 \leq 3 \Leftrightarrow x^{2} \leq 1 \Leftrightarrow \\
& \Leftrightarrow \quad|x| \leq 1 \Leftrightarrow-1 \leq x \leq 1
\end{aligned}
$$

\section*{Problema de motivação}
(Apostol T. M., Calculus, Vol. I, 2nd edition, John Wiley \& Sons, (1967).)
Um atleta corre a uma velocidade constante durante todo o percurso de uma determinada prova. O atleta demora:
- $T$ minutos a percorrer metade do percurso total da prova;
- $\frac{T}{2}$ minutos a percorrer metade da outra metade que resta;
- $\frac{T}{4}$ minutos a percorrer a metade do que agora resta; e assim sucessivamente até terminar a prova.

O tempo que o atleta demora a concluir a prova pode traduzir-se por:
$$
T+\frac{T}{2}+\frac{T}{4}+\frac{T}{8}+\cdots+\frac{T}{2^{n}}+\ldots
$$

Como o atleta demora $T$ minutos a percorrer metade do percurso, o tempo total da prova será de $2 T$ minutos. Então, podemos pensar que
$$
T+\frac{T}{2}+\frac{T}{4}+\frac{T}{8}+\cdots+\frac{T}{2^{n}}+\ldots=2 T,
$$
- Como explicamos matematicamente este resultado?
- Que significado matemático poderemos atribuir a uma soma com uma infinidade de parcelas?
- Como interpretamos o facto de a soma com um número infinito de parcelas ser igual a um número finito? Uma soma infinita de parcelas positivas não deveria ser igual a infinito?

\section*{Séries numéricas}

Se ( $a_{n}$ ) é uma sucessão de números reais, a soma de todos os seus termos
$$
a_{1}+a_{2}+a_{3}+\ldots \quad \text { que representamos por } \sum_{n=1}^{\infty} a_{n}
$$
chama-se série numérica de termo geral $a_{n}$.
À série $\sum_{n=1}^{\infty} a_{n}$ podemos associar duas sucessões de números reais:
- A sucessão ( $a_{n}$ ), cujo termo geral é o termo geral da série.
- A sucessão das somas parciais, que denotamos por $\left(S_{n}\right)$.

Não se pode somar um número infinito de parcelas usando a operação adição usual, mas pode-se ir somando sucessivamente as primeiras parcelas da soma infinita, tentando somar cada vez mais parcelas de forma a estarmos próximos da soma infinita.
(1) Calculamos as chamadas somas parciais:
$$
S_{1}=T, \quad S_{2}=T+\frac{T}{2}, \quad \ldots, \quad S_{n}=T+\frac{T}{2}+\frac{T}{4}+\cdots+\frac{T}{2^{n-1}}
$$
(2) E analisamos o comportamento destas somas quando $n$ tende para $+\infty$. Para tal, calculamos $\lim _{n \rightarrow+\infty} S_{n}$ (caso este limite exista, esse será o valor da soma infinita).

Neste caso, $S_{n}$ representa a soma dos $n$ primeiros termos da progressão geométrica $\left(\frac{T}{2^{n-1}}\right)$ e facilmente se prova que $\lim _{n \rightarrow+\infty} S_{n}=2 T$ (o tempo que o atleta demora a fazer o percurso).

A sucessão das somas parciais associada a uma série numérica $\sum_{n=1}^{\infty} a_{n}$ é a sucessão $\left(S_{n}\right)$ cujos termos são:
$$
\begin{aligned}
& S_{1}=a_{1} \\
& S_{2}=a_{1}+a_{2} \\
& S_{3}=a_{1}+a_{2}+a_{3} \\
& \vdots \\
& S_{n}=a_{1}+a_{2}+a_{3}+\cdots+a_{n}=\sum_{i=1}^{n} a_{i}
\end{aligned}
$$

Exemplo 15: A série numérica $1+\frac{1}{4}+\frac{1}{9}+\frac{1}{16}+\ldots$ é a série de termo geral $a_{n}=\frac{1}{n^{2}}$. Isto é, usamos a notação
$$
1+\frac{1}{4}+\frac{1}{9}+\frac{1}{16}+\cdots=\sum_{n=1}^{\infty} \frac{1}{n^{2}}
$$

Quais são os primeiros três termos da sucessão $\left(S_{n}\right)$ das somas parciais associada à série?
$$
\begin{aligned}
& S_{1}=a_{1}=1 \\
& S_{2}=a_{1}+a_{2}=1+\frac{1}{4}=\frac{5}{4} \\
& S_{3}=a_{1}+a_{2}+a_{3}=1+\frac{1}{4}+\frac{1}{9}=\frac{49}{36}
\end{aligned}
$$

Exemplo 16: Estude a natureza da série numérica $\sum_{n=1}^{\infty}\left(\frac{1}{5}\right)^{n}$.
- Termo geral da série: $a_{n}=\left(\frac{1}{5}\right)^{n}$. A sucessão $\left(a_{n}\right)$ é uma progressão geométrica de razão $r=\frac{a_{n+1}}{a_{n}}=\frac{1}{5}$ (provar!).
- Sucessão $\left(S_{n}\right)$ das somas parciais associadas à série:
$$
\begin{aligned}
S_{1} & =a_{1}=\frac{1}{5} \\
S_{2} & =a_{1}+a_{2}=\frac{1}{5}+\frac{1}{25}=\frac{6}{25} \\
\vdots & \\
S_{n} & =a_{1}+a_{2}+\cdots+a_{n}\left(\text { soma dos } n 1 \text { os termos da progressão }\left(a_{n}\right)\right) \\
& =a_{1} \frac{1-r^{n}}{1-r}=\frac{1}{5} \frac{1-\left(\frac{1}{5}\right)^{n}}{1-\frac{1}{5}}=\frac{1}{5} \frac{1-\left(\frac{1}{5}\right)^{n}}{\frac{4}{5}}=\frac{1-\left(\frac{1}{5}\right)^{n}}{4}
\end{aligned}
$$

\section*{Natureza e soma da série}

Uma série numérica $\sum_{n=1}^{\infty} a_{n}$ diz-se:
- convergente se e só se a sucessão $\left(S_{n}\right)$ das somas parciais associada à série é convergente. Isto é, $\lim _{n \rightarrow+\infty} S_{n}$ é um número real $S \in \mathbb{R}$ (limite finito). Neste caso, chama-se soma da série ao número $S=\lim _{n \rightarrow+\infty} S_{n}$ e escreve-se $\sum_{n=1}^{\infty} a_{n}=S$.
- divergente se e só se a sucessão $\left(S_{n}\right)$ das somas parciais da série é divergente. Neste caso, a série não tem soma.

\section*{(Exemplo 16 - continuação)}
- Estudo da natureza da série:
$$
\lim _{n \rightarrow+\infty} S_{n}=\lim _{n \rightarrow+\infty} \frac{1-\left(\frac{1}{5}\right)^{n}}{4}=\frac{1-0}{4}=\frac{1}{4}
$$

A sucessão ( $S_{n}$ ) é convergente.

Então, a série $\sum_{n=1}^{\infty}\left(\frac{1}{5}\right)^{n}$ é convergente e a sua soma é igual a $\frac{1}{4}$. Isto é, mostrámos que
$$
\frac{1}{5}+\frac{1}{25}+\frac{1}{125}+\frac{1}{625}+\ldots=\frac{1}{4}
$$

\section*{Observação}

A representação de uma série não é única. Por exemplo, a série
$$
\frac{1}{5}+\frac{1}{25}+\frac{1}{125}+\frac{1}{625}+\cdots=\sum_{n=1}^{\infty}\left(\frac{1}{5}\right)^{n}
$$
reescreve-se como
$$
\frac{1}{5}+\frac{1}{25}+\frac{1}{125}+\frac{1}{625}+\cdots=\sum_{n=0}^{\infty}\left(\frac{1}{5}\right)^{n+1}
$$
ou então, como
$$
\frac{1}{5}+\frac{1}{25}+\frac{1}{125}+\frac{1}{625}+\cdots=\sum_{n=2}^{\infty}\left(\frac{1}{5}\right)^{n-1} .
$$

Para efeitos de aplicação de algumas fórmulas, como a que usámos no exemplo anterior para calcular $S_{n}$, é necessário ter em atenção qual a primeira parcela da soma representada pela série (verificar sempre o índice do somatório).

\section*{(Exemplo 17 - continuação)}
- Estudo da natureza da série:
$$
\lim _{n \rightarrow+\infty} S_{n}=\lim _{n \rightarrow+\infty}\left(1-\frac{1}{n+1}\right)=1
$$

A sucessão ( $S_{n}$ ) é convergente.
Então, a série $\sum_{n=1}^{\infty}\left(\frac{1}{n}-\frac{1}{n+1}\right)$ é convergente e a sua soma é igual a 1.
$$
\sum_{n=1}^{\infty}\left(\frac{1}{n}-\frac{1}{n+1}\right)=1
$$

Exemplo 17: A série numérica $\sum_{n=1}^{\infty}\left(\frac{1}{n}-\frac{1}{n+1}\right)$ é convergente?
- Termo geral da série: $a_{n}=\frac{1}{n}-\frac{1}{n+1}$.
- Termo geral da sucessão ( $S_{n}$ ) das somas parciais:
$$
\begin{aligned}
S_{n}= & \underbrace{1-\frac{1}{2}}_{a_{1}})+\underbrace{\frac{1}{2}-\frac{1}{3}}_{a_{2}})+\underbrace{\left(\frac{1}{3}-\frac{1}{4}\right)}_{a_{3}}+\cdots+ \\
& +\underbrace{\left(\frac{1}{n-1}-\frac{1}{n}\right)}_{a_{n-1}}+(\underbrace{\left(\frac{1}{n}-\frac{1}{n+1}\right)}_{a_{n}}=1-\frac{1}{n+1} .
\end{aligned}
$$

\section*{Série geométrica}

Uma série numérica $\sum_{n=1}^{\infty} a_{n}$ diz-se geométrica de razão $r(r \in \mathbb{R})$ se a sucessão ( $a_{n}$ ) é uma progressão geométrica de razão $r$, ou seja, verifica-se $\frac{a_{n+1}}{a_{n}}=r$, para todo $n \in \mathbb{N}$.
- Se $|r|<1$, então a série geométrica é convergente e a sua soma é $S=\frac{a_{1}}{1-r}$ (pois $\left.\lim _{n \rightarrow+\infty} a_{1} \frac{1-r^{n}}{1-r} \underset{-1<r<1}{=} a_{1} \frac{1-0}{1-r}=\frac{a_{1}}{1-r}\right)$.
- Se $|r| \geq 1$, a série geométrica é divergente e não tem soma.

\section*{(Exemplo 16 - revisto)}

A série $\sum_{n=1}^{\infty}\left(\frac{1}{5}\right)^{n}$ é geométrica de razão $r=\frac{\left(\frac{1}{5}\right)^{n+1}}{\left(\frac{1}{5}\right)^{n}}=\left(\frac{1}{5}\right)^{n+1-n}=\frac{1}{5}$.
- $|r|=\left|\frac{1}{5}\right|=\frac{1}{5}<1$.

Logo, a série é convergente (como já tínhamos visto).
- Como confirmámos anteriormente, a sua soma é $\frac{1}{4}$ :
$$
S=\frac{a_{1}}{1-r}=\frac{\frac{1}{5}}{1-\frac{1}{5}}=\frac{\frac{1}{5}}{\frac{4}{5}}=\frac{1}{4}
$$

Exemplo 18: Estude a natureza da série numérica $\sum_{n=1}^{\infty} \frac{1}{(-3)^{-n}}$.
- Termo geral da série: $a_{n}=\frac{1}{(-3)^{-n}}=(-3)^{n}$.

A sucessão ( $a_{n}$ ) é uma progressão geométrica de razão $r=\frac{a_{n+1}}{a_{n}}=\frac{(-3)^{n+1}}{(-3)^{n}}=-3$.
- Assim, a série $\sum_{n=1}^{\infty}(-3)^{n}$ é geométrica de razão $r=-3$.
- A série é divergente, pois $|r|=|-3|=3>1$.
(Confirme que $\lim _{n \rightarrow+\infty} S_{n}$ não é um número finito.)

Exemplo 19: Estude a natureza da série numérica $\sum_{n=0}^{\infty} 2^{-2 n}$.
- Termo geral da série: $a_{n}=2^{-2 n}$.

A sucessão ( $a_{n}$ ) é uma progressão geométrica de razão
$$
r=\frac{a_{n+1}}{a_{n}}=\frac{2^{-2(n+1)}}{2^{-2 n}}=\frac{2^{-2 n-2}}{2^{-2 n}}=2^{-2 n-2+2 n}=2^{-2}=\frac{1}{2^{2}}=\frac{1}{4} .
$$
- Assim, a série $\sum_{n=0}^{\infty} 2^{-2 n}$ é geométrica de razão $r=\frac{1}{4}$.
- A série é convergente, pois $|r|=\left|\frac{1}{4}\right|=\frac{1}{4}<1$.
- Soma da série:
$$
S=\lim _{n \rightarrow+\infty} a_{0} \frac{1-r^{n}}{1-r}=\frac{a_{0}}{1-1<r<1}=\frac{2^{0}}{1-\frac{1}{4}}=\frac{1}{\frac{3}{4}}=\frac{4}{3}
$$

Exemplo 20: Determine os valores de $x$ para os quais a série geométrica $\sum_{n=0}^{\infty} 3^{-n} x^{n}$ é convergente.
- Termo geral da série: $a_{n}=3^{-n} x^{n}=\frac{x^{n}}{3^{n}}=\left(\frac{x}{3}\right)^{n}$. ( $a_{n}$ ) é uma progressão geométrica de razão
$$
r=\frac{a_{n+1}}{a_{n}}=\frac{\left(\frac{x}{3}\right)^{n+1}}{\left(\frac{x}{3}\right)^{n}}=\frac{x}{3}
$$
- Assim, a série $\sum_{n=0}^{\infty} 3^{-n} x^{n}$ é geométrica de razão $r=\frac{x}{3}$.
- A série é convergente se e só se
$$
|r|<1 \Leftrightarrow-1<\frac{x}{3}<1 \Leftrightarrow-3<x<3 .
$$

\section*{Série telescópica}

Uma série numérica $\sum_{n=1}^{\infty} a_{n}$ diz-se telescópica (ou de Mengoli) se existe uma sucessão $\left(u_{n}\right)$ tal que $a_{n}=u_{n}-u_{n+p}$, com $p \in \mathbb{N}$. Isto é, se o termo geral da série se pode escrever como a diferença de dois termos, não necessariamente consecutivos, de uma outra sucessão ( $u_{n}$ ).
- Se $\lim _{n \rightarrow+\infty} u_{n}$ existe e é finito, então a série telescópica é convergente e a sua soma é $S=u_{1}+\cdots+u_{p}-p_{n \rightarrow+\infty} u_{n}$.
- Se $\lim _{n \rightarrow+\infty} u_{n}$ não existe ou não é finito, então a série telescópica é divergente e não tem soma.

Exemplo 21: Verifique que $\sum_{n=1}^{\infty} 2(\sqrt{n-1}-\sqrt{n+1})$ é uma série telescópica divergente.
- $a_{n}=2(\sqrt{n-1}-\sqrt{n+1})=2 \sqrt{n-1}-2 \sqrt{n+1}$.

Se $u_{n}=2 \sqrt{n-1}$, então $u_{n+2}=2 \sqrt{n+2-1}=2 \sqrt{n+1}$.
Concluímos que $a_{n}=u_{n}-u_{n+2}$, onde $u_{n}=2 \sqrt{n-1}$. Isto é, $a_{n}=u_{n}-u_{n+p}$ para $p=2$. A série é telescópica.
- $\lim _{n \rightarrow+\infty} u_{n}=\lim _{n \rightarrow+\infty} 2 \sqrt{n-1}=2 \lim _{n \rightarrow+\infty} \sqrt{n-1}=+\infty$ (limite infinito)

Logo, a série telescópica é divergente e não tem soma.

\section*{(Exemplo 17 - revisto)}

A série $\sum_{n=1}^{\infty}\left(\frac{1}{n}-\frac{1}{n+1}\right)$ é uma série telescópica convergente, pois:
- $a_{n}=\frac{1}{n}-\frac{1}{n+1}=u_{n}-u_{n+1}$, onde $u_{n}=\frac{1}{n}$.

Isto é, $a_{n}=u_{n}-u_{n+p}$ para $p=1$.
- $\lim _{n \rightarrow+\infty} u_{n}=\lim _{n \rightarrow+\infty} \frac{1}{n}=0$. O limite de $u_{n}$ é finito.

Logo, a série telescópica é convergente e a sua soma é dada por $S=u_{1}-1 \times \lim _{n \rightarrow+\infty} u_{n}=1-\lim _{n \rightarrow+\infty} \frac{1}{n}=1$.

\section*{(Exemplo 21 - continuação)}

Escreva o termo geral da sucessão das somas parciais ( $S_{n}$ ) associada a $\sum_{n=1}^{\infty} 2(\sqrt{n-1}-\sqrt{n+1})$ e confirme que o seu limite não é finito.
$$
\begin{aligned}
& S_{n}=a_{1}+a_{2}+a_{3}+a_{4}+\cdots+a_{n}= \\
& =\left(u_{1}-u_{3}\right)+\left(u_{2}-u_{4}\right)+\left(u_{3}-u_{5}\right)+\left(u_{4}-u_{6}\right)+\left(u_{5}-u_{7}\right)+\cdots+ \\
& \cdots+\left(u_{n-3}-u_{n-1}\right)+\left(u_{n-2}-u_{n}\right)+\left(u_{n-1}-u_{n+1}\right)+\left(u_{n}-u_{n+2}\right)= \\
& =u_{1}+u_{2}-u_{n+1}-u_{n+2}=0+2-2 \sqrt{n}-2 \sqrt{n+1}
\end{aligned}
$$

Exemplo 22: Mostre que $\sum_{n=1}^{\infty} \frac{1}{n^{2}+3 n}$ é uma série telescópica. $a_{n}=\frac{1}{n^{2}+3 n}=\frac{1}{n(n+3)}$. Vamos determinar as constantes $A$ e $B$ tais que $\frac{1}{n(n+3)}=\frac{A}{n}+\frac{B}{n+3}$. Ora, esta igualdade é equivalente a
$$
\begin{aligned}
& \frac{1}{n(n+3)}=\frac{A(n+3)+B n}{n(n+3)} \Leftrightarrow \frac{1}{n(n+3)}=\frac{A n+3 A+B n}{n(n+3)} \Leftrightarrow \\
& \Leftrightarrow A n+3 A+B n=1 \Leftrightarrow(A+B) n+3 A=0 n+1 \Leftrightarrow \\
& \Leftrightarrow\left\{\begin{array} { l } 
{ A + B = 0 } \\
{ 3 A = 1 }
\end{array} \Leftrightarrow \left\{\begin{array} { l } 
{ B = - A } \\
{ A = \frac { 1 } { 3 } }
\end{array} \Leftrightarrow \left\{\begin{array}{l}
B=-\frac{1}{3} \\
A=\frac{1}{3}
\end{array}\right.\right.\right.
\end{aligned}
$$

\section*{(Exemplo 22 - continuação)}
- Calcule a soma da série $\sum_{n=1}^{\infty} \frac{1}{n^{2}+3 n}$.
$$
\begin{aligned}
& S=u_{1}+u_{2}+u_{3}-3 \lim _{n \rightarrow+\infty} u_{n}=\frac{1}{3}+\frac{1}{6}+\frac{1}{9}-3 \lim _{n \rightarrow+\infty} \frac{1}{3 n}= \\
& =\frac{1}{3}+\frac{1}{6}+\frac{1}{9}+0=\frac{11}{18}
\end{aligned}
$$
- Escreva o termo geral da sucessão das somas parciais $\left(S_{n}\right)$ associado à série e confirme que o seu limite é igual a $\frac{11}{18}$.
$$
\begin{aligned}
& S_{n}=a_{1}+a_{2}+a_{3}+a_{4}+\cdots+a_{n}= \\
& =u_{1}+u_{2}+u_{3}-u_{n+1}-u_{n+2}-u_{n+3}=\frac{11}{18}-\frac{1}{3(n+1)}-\frac{1}{3(n+2)}-\frac{1}{3(n+3)} \\
& S=\lim _{n \rightarrow+\infty} S_{n}=\frac{11}{18}
\end{aligned}
$$
(Exemplo 22 - continuação)
Então, $a_{n}=\frac{1}{n(n+3)}=\frac{\frac{1}{3}}{n}+\frac{-\frac{1}{3}}{n+3}=\frac{1}{3}\left(\frac{1}{n}-\frac{1}{n+3}\right)$.
Concluímos que $a_{n}=u_{n}-u_{n+3}$, onde $u_{n}=\frac{1}{3} \times \frac{1}{n}=\frac{1}{3 n}$. Isto é, $a_{n}=u_{n}-u_{n+p}$ para $p=3$. A série $\sum_{n=1}^{\infty} \frac{1}{n^{2}+3 n}$ é telescópica.
- Qual a natureza da série $\sum_{n=1}^{\infty} \frac{1}{n^{2}+3 n}$ ?
$\lim _{n \rightarrow+\infty} u_{n}=\lim _{n \rightarrow+\infty} \frac{1}{3 n}=0$. O limite de $u_{n}$ é finito.
Logo, a série telescópica é convergente.

Lígia Abrunheiro (ISCA-UA)

\section*{Teorema (Condição necessária de convergência)}

Se $\sum_{n=1}^{\infty} a_{n}$ é uma série convergente, então $\lim _{n \rightarrow+\infty} a_{n}=0$.
A condição enunciada neste teorema não é uma condição suficiente:
Se $\lim _{n \rightarrow+\infty} a_{n}=0$ nada se conclui acerca da natureza da série $\sum_{n=1}^{\infty} a_{n}$.
Por exemplo, $\quad \lim _{n \rightarrow+\infty} 2^{-n}=0 \quad$ e $\quad \lim _{n \rightarrow+\infty} \ln \left(\frac{n}{n+1}\right)=0$.
No entanto, prova-se que $\sum_{n=1}^{\infty} 2^{-n}$ é uma série geométrica convergente, enquanto que $\sum_{n=1}^{\infty} \ln \left(\frac{n}{n+1}\right)$ é uma série telescópica divergente (provar!).

O seguinte resultado é uma consequência do teorema anterior e torna-se mais útil para o estudo da natureza de uma série.

\section*{Corolário (Critério do termo geral para a divergência)}

Se $\lim _{n \rightarrow+\infty} a_{n} \neq 0$, não existe ou é infinito, então a série $\sum_{n=1}^{\infty} a_{n}$ é divergente.

Exemplo 23: O termo geral da série $\sum_{n=1}^{\infty} \frac{2 n}{n+1}$ tem limite igual a 2 : $\lim _{n \rightarrow+\infty} \frac{2 n}{n+1}=\lim _{n \rightarrow+\infty} \frac{2}{1+\frac{1}{n}}=2 \neq 0$. Logo, a série é divergente.

Exemplo 25: Um doador pretende criar um fundo permanente para bolsas de estudo. O objetivo é que o fundo pague $1000 €$ por ano, para sempre, utilizando apenas os rendimentos gerados pela aplicação financeira. A taxa de rentabilidade anual garantida é de $5 \%$ ao ano.

Que capital deve ser depositado hoje (valor atual, VA) para que o fundo consiga pagar $1000 €$ por ano perpetuamente?

O dinheiro tem valor no tempo: " $1 €$ hoje não vale o mesmo que $1 €$ amanhã".
VA será a soma dos descontos de cada prestação para o presente:
$$
V A=\frac{1000}{1,05}+\frac{1000}{(1,05)^{2}}+\frac{1000}{(1,05)^{3}}+\cdots=\sum_{n=1}^{\infty} \frac{1000}{(1,05)^{n}}=?
$$

Qual o valor desta soma infinita (valor a investir neste fundo)?

\section*{Exemplo 24:}
(1) O limite do termo geral da série $\sum_{n=1}^{\infty} 1000(1,0246)^{n}$ é:
$\lim _{n \rightarrow+\infty} 1000(1,0246)^{n}=1000 \lim _{n \rightarrow+\infty}(1,0246)^{n}=+\infty$.
Logo, a série é divergente.
(2) O termo geral $a_{n}$ de $\sum_{n=1}^{\infty}(-1)^{n} n$ não tem limite pois ( $a_{n}$ ) é um infinitamente grande, logo a série é divergente.
(3) O termo geral de $\sum_{n=1}^{\infty} \frac{(-1)^{n}}{n}$ tem limite igual a 0 . Assim, usando o critério do termo geral para a divergência, nada se conclui sobre a natureza da série.
(exemplo 25 - continuação)
- A série $\sum_{n=1}^{\infty} a_{n}=\sum_{n=1}^{\infty} \frac{1000}{(1,05)^{n}}$ é geométrica de razão:
$$
r=\frac{a_{n+1}}{a_{n}}=\frac{1}{1,05}
$$
- A série é convergente porque $-1<r<1$.
- Soma da série $S=\frac{a_{1}}{1-r}=\frac{\frac{1000}{1,05}}{1-\frac{1}{1,05}}=\frac{\frac{1000}{1,05}}{\frac{1,05-1}{1,05}}=\frac{1000}{0,05}$
- O capital a aplicar hoje no fundo será de $V A=\frac{1000}{0,05}=20000 €$.
- No exemplo anterior, se a taxa anual fosse de $0,5 \%$, qual seria o valor inicial a investir? (Use a nota a seguir para responder).
NOTA: O problema analisado enquadra-se na teoria da Rendas Perpétuas. No caso em que a prestação da renda perpétua tem valor fixo $T$ e uma taxa de juro $i$, o valor atual da renda é igual a $V A=\frac{T}{i}$. Está fórmula não é arbitrária - resulta da soma de uma série geométrica infinita.
- Comente a sensibilidade deste tipo de fundos (perpétuos) à variação da taxa:
![](https://cdn.mathpix.com/cropped/7b743b07-b5aa-470a-bc7e-34aef20397a1-17.jpg?height=421&width=534&top_left_y=525&top_left_x=415)

Exemplo 26: Evolução anual do Produto Interno Bruto (PIB) (em milhares de milhões de euros) de uma certa região durante 4 anos: $P_{1}=180, P_{2}=186, P_{3}=191, P_{4}=200$.
- Soma das variações anuais:
$S=\left(P_{2}-P_{1}\right)+\left(P_{3}-P_{2}\right)+\left(P_{4}-P_{3}\right)=P_{4}-P_{1}$
É uma soma telescópica!
$S=\sum_{n=1}^{4}\left(P_{n+1}-P_{n}\right)=-\sum_{n=1}^{4}\left(P_{n}-P_{n+1}\right)$
- $S=P_{4}-P_{1}$ significa que a soma das variações anuais do PIB ( $P_{n}-P_{n+1}$ ) é igual ao crescimento total acumulado, ou seja, representa a mudança total do PIB entre o início e o final do período: PIB final-PIB inicial.

E se tivermos uma soma infinita de variações anuais do PIB?
