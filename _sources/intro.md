# O Pêndulo Interrompido: proposta

## Introdução
No "terceiro dia" do seu último livro, Duas Novas Ciências, Galileu discute uma experiência com um pêndulo interrompido, em que a corda é obstruída no meio do percurso por um pino. O pêndulo, apesar de se deslocar em dois arcos diferentes, atinge a mesma altura de onde foi libertado. 

```{figure} galileu-ip.png
---
name: galileu-pi
---
Desenho do pêndulo interrompido, tirado do "Duas Novas Ciências". 
```

Galileu usa o pêndulo interrompido para fins retóricos. Está querendo convencer seus interlocutores da plausibilidade de algo (um "postulado") que a gente hoje chamaria de conservação de energia mecânica: que a velocidade final adquirido por massas descendo rampas depende somente da altura da rampa, desde que não haja "impedimentos" ou "acidentes" ou "imperfeições" [^exp]. Vai usar esta ideia no seu tratamento de aceleração "natural" (queda livre).

[^exp]: O papel de experimentos, experimentos idealizados ou de pensamento e "impedimentos" é muito interessante para investigar. Há diferentes interpretações na literatura (Koyré versus Stillman Drake, por exemplo). Há uma discussão interessante sobre as lições epistemilógicas do Galileu e como poderiam ser tratados em sala de aula em {cite}`matthews_time_2000`

```{figure} galileu-rampas.png
---
name: galileu-rampas
---
Duas rampas (de "Duas Novas Ciências"). 
```
Mais tarde, Galileu vai usar uma ideia parecida, quando fala sobre a descida e subida em rampas com ângulos diferentes mas com as mesmas alturas, onde uma massa adquira velocidade na descida, justamente suficiente para subir novamente. Porém, rampas e bolas rolando parecem estar sujeitos a mais "impedimentos" e "imperfeições". Talvez considerou o pêndulo interrompido, mesmo como experimento de pensamento, um sistema mais "limpo" para mostrar a plausibilidade do seu postulado. 

> The real, inclined-plane, situation is difficult and messy. It abounds with "accidents" and "impediments." Galileo used a simple but brilliant pendulum experiment to minimize friction, to minimize the impact problem at the join of the planes, and to approach further to the ideal case.
>
>  -- {cite}`matthews_time_2000`

Durante a discussão do pêndulo interrompido o Galileu afirma algo que não é verdade. É preciso reconhecer que a afirmação não afeta o raciocínio principal, o que postulado que a massa chega na mesma altura de que foi solta, independente do caminho. Mas é interessante comparar o que diz Galileu com o que um iniciante hoje diria quando é instigado sobre o problema. Certamente a massa "quer" chegar na mesma altura do que foi solta e quando o pino está disposto de maneira que isso é impossível, ou quando a altura de soltura é grande demais, então a massa deve fazer a volta inteira e o fio do pêndulo deve se enrolar.


```{figure} galileu-erro.png
---
name: galileu-erro
---
Afirmação do Galileu sobre o que acontece se o pêndulo é interrompido de tal forma que a massa não alcanceria a altura de soltura. 
```

Na página [Modelo](modelo.md) construimos um modelo onde a trajetória da massa é circular até o momento que a força tensão (o vínculo que mantem a trajetória circular) é zero. A partir deste momento a trajetória é uma parábola. Para que o fio se enrola enrosca em volta do pino, é suficiente soltar a massa de uma altura um pouco menor do que $h$, o raio do círculo e posição do pino. É suficiente soltar a massa de $\sqrt{3}/2h = 0.866h$.


## O experimento e seu uso didático

Veja uma visão global do experimento:

<iframe width="640" height="360" src="https://eaulas.usp.br/portal/embed-video?idItem=19667&autostart=false" frameborder="0" scrolling="no" allowfullscreen></iframe>

A pergunta agora é se há um potencial didático neste experimento. 

### Conservação de energia mecânica

O uso mais óbvio é fazer uma analogia como o experimento *loop*. Como mencionado em {cite}`borges_critica_2019`, experimentos muitas vezes são considerados como ilustrações e podem servir para contextualizar modelos teóricos visto em livros-texto ou em sala de aula. O *loop* é o tipo de exercício usado como ilustração de como considerações de conservação de energia mecânica podem tornar viáveis sua solução. Neste contexto vale também lembrar o estudo clássico na área de ensino de física que mostra como iniciantes e especialistas classificam exercícios de física diferentemente: os especialistas classificam exercícios baseados nos princípios físicos necesssários para resolvê-los (conservação de energia, segunda lei de Newton, etc.), enquanto iniciantes focam nas características superficiais (por exemplo se envolve rampas, ou polias ou forças gravitationais, ou a força normal) {cite}`chi_categorization_1981`.

Nesta abordagem podemos pensar numa encaminhamento parecido com o atual experimento do MEXI [Loop](http://www.fep.if.usp.br/~fisfoto/rotacao/loop/index.php). É interessante o fato que o modelo matemático é igual para o loop e o pêndulo interrompido, mas os desvios do modelo devem ser bem diferentes: atrito (do ar, de deslizamento) e energia convertido em energia rotacional pelo rolamento num caso e atrito do ar e interno do fio no outro caso. 


### Uma abordagem "pegadinha"
Um uso didático alternativo visa trabalhar a relação entre modelo matemático, suas premissas e suas limitações. Dado o modelo físico (o pêndulo interrompido ou o *loop*), existem pelo menos duas hipóteses plausíveis e atraentes para novatos, porém errôneas:

1. Perguntamos a altura mínima de abondono para qual a massa do pêndulo ou a bolinha completa o círculo. Uma raciocínio inicial seria pensar que a massa "quer" voltar para a altura de abaondo e que portanto que precisamos usar (usando os coordenados e termos do [modelo](modelo.md)) $H \geq h)$. Este raciocínio revelaria uma "física cartunesca", onde a velocidade da massa se torna zero no topo da trajetória e em seguida cai verticalmente. Na verdade, para o modelo idealizado, é preciso soltar a massa de pelo menos $H \geq 3/2h$ para que no topo da trajetória a velocidade é suficiente para que a aceleração centrípeta corresponde à força peso $mg$.
2. Perguntamos uma outra pergunta, agora no contexto do pêndulo interrompido. Se soltar a massa da $H \leq 0$, por conservação de energia, (teoricamente!) é claro que a massa subirá até a mesma altura no outro lado do pino. Perguntamos agora: qual é a altura mínima necessário para qual a massa pula por cima do pino e o fio se enrosca? O novato talvez quer responder $H \geq h$, porque o a massa "quer" chegar na altura de abondono, mas é impedido pelo raio de círculo sendo $h$. Um outro novato, já mais esperto por causa da sua experiência com o tipo de exercío mencionado acima, acha o que poderia ser $H = 3/2h$. Ambos estariam errados, conforme o [modelo](modelo.md)), que leva em conta que a partir de um ângulo dado por $\sin{\theta_c} = 1/\sqrt{3}$ ou 35,3°, a trajetória é parabólica e somente precisamos de no mínimo $H_c = \sqrt{3}/2h = 0.866h$ para que a massa passa pelo $(0,0)$ ou *justamente* pela posição do pino.

 Uma vez, 15 anos atrás, fiz o segundo experimento com alunos da farmácia. Pedi eles medir a altura de abandono crítica $H_c$ para vários valores do raio do círculo $h$. Os grupos logo se deram conta que o valor era aproximadamente dado por $H_c = h$ e até conseguiram o raciocíno (ingênuo, ou pelo menos incompleto) pela conservação de energia. Mas não se deram conta que o valor verdadeiro era ligeiramente (14%) abaixo deste valor. 

Um aspecto importante do experimento era o prazer motórico de "acertar" o pino, tornando as medidas (um pouco) menos maçantes. 
 
Quando eu mesmo fiz o experimento com da ordem de 20 alturas do pino diferentes, cheguei num ajuste $Hc = (0.98 \pm 0.005) h$, longe do valor do modelo. Acredito que pode ter havido um grande erro sistemático na determinação das alturas, sobretudo a altura de abandono. Um outro motivo pela discrepância é que os efeitos de atrito (arrasto do ar, perda de energia na choque com o pino) elevaram a altura de abandono necessária para chegar justamente na altura necessário para a massa bater no pino. 
 
Mas esse resultado leva a uma situação interessante: o resultado experimental parecia confirmar uma previsão errônea ($H_c = h$). É uma oportunidade de discutir algo que historiadores da ciência debatem: o papel de experimentos e a relação entre modelo e mundo real para Galileu e a ciência em geral. Há interlocutores contemporâneos do Galileu (del Monte, por exemplo), conforme recontando pelo Michael Matthews ({cite}`matthews_time_2000`)

>Galileo and del Monte had had an earlier exchange of letters (they were lost by the time Galileo's Opere was collected) about motion in a semicircle, and it was Galileo's beliefthat such motion was tautochronous.8 Del Monte could not believe these claims and found them wanting when he rolled balls inside an iron hoop. He was a scientist-engineer and enough of an Aristotelian to believe that tests against experience were the ultimate adjudicator of claims in physics. Galileo's claims failed the test. But Galileo replied that accidents interfered with del Monte's test: his wheel rim was not perfectly circular and, as he stated elsewhere, the rim was not smooth enough.

Mas, observe Matthews,

> It should not be inferred from the foregoing that Galileo was indifferent to experimental evidence. He was a most careful experimenter. His insight was to have a mathematical model of motion and then to compare real motions with this model; his "world on paper" preceded his "real world."

A pergunta relavante para a história da ciência e a ciência escolar é: qual é papel de intuições *a priori*, o universo da matemática e as abstrações humanas versus o papel dos resultados experimentais, o mundo real. Quando decidimos que uma discrepância é um mero imperfeição e quando a mesma discrepância revela algo importante sobre o mundo?


### Uma abordagem verificacionista
O [modelo](modelo.md) faz algumas previsões que podem ser checados pela análise das imagens.

1. O modelo dá valores exatos para os valores de posição e velocidade em termos da altura de abandono e a posição do pino (note que o comprimento do pêndulo antes de bater no pino não entra no modelo). Podemos verificar a trajetória, tanto quando é circular, como na parte parabólica e comparar com a previsão do modelo. Podemos inferir forças de vínculo (da tensão) e de atrito.
2. O modelo faz uma previsão para o ângulo em que a tensão do fio se torna zero, dado que a trajetória passa pelo ponto $(0,0)$ do pino. Pelas imagens exploratórios que foram feitas, este valor é viável de determinar com bastante precisão e muito próximo ao valor previsto (35,3°). É fácil de determinar porque o fio alcança seu valor máximo para o ângulo quando a tensão se torna zero. O limite do ângulo nos frames que antecedem o ângulo crítico é fácil de determinar. Veja as imagens abaixo. A boa concordância, mesmo sem grandes cuidados no arranjo, é fortuito? Ou o ângulo crítico simplesmente não é muito sensível a imperfeições na trajetória real em comparação com a trajetória do modelo?

::::{grid}
:gutter: 2

:::{grid-item}
:outline:
```{image} vlcsnap-2025-01-05-18h38m17s588.png
:width: 100%
:align: center
```
:::
:::{grid-item}
:outline:
```{image} vlcsnap-2025-01-05-18h40m21s352.png
:width: 100%
:align: center
```
:::
:::{grid-item}
:outline:
```{image} vlcsnap-2025-01-05-18h40m22s748.png
:width: 100%
:align: center
```
:::
:::{grid-item}
:outline:
```{image} vlcsnap-2025-01-05-18h41m11s711.png
:width: 100%
:align: center
```
:::

::::
