## Modelo matemático para o Pêndulo Interrompido

Vamos analisar um modelo matemático para descrever a trajetória de uma massa num *loop* ou para um pêndulo interrompido. Vamos admitir que, dependendo da velocidade inicial e energia cinética na parte mais baixo do círculo, a trajetória pode 
1. ser parcialmente circular e periódica: a velocidade inicial não é suficiente para subir mais do que um raio do círculo;
2. ser inicialmente circular, mas a partir de uma certa altura ou ângulo crítico a massa se "desprende" da trajetória circular, a força normal ou da tensão é zerada e a massa segue em queda livre;
3. ser completamente circular: a velocidade incicial é suficiente para completar o círculo.

Durante a parte circular da trajetória circular há forças de vínculo (a força normal e a tensão no fio para o *loop* e pêndulo respectivamente) fornecendo parte da força centrípeta. Em ambos os casos há a força da gravidade, com componentes perpendicular (fornecendo uma parte da força centrípeta) e tangencial. Há, obviamente, também forças de atrito e graus de liberdade (rotação da massa, movimento do fio) que não vamos considerar inicialmente.


```{image} modelo-v0.jpg
:width: 300px
:align: center
```


Nossa referência é o centro do círculo (0,0). Vamos chamar o raio do círculo $h$ e soltamos a massa $m$ de uma altura $H$. Em nosso referencial, se o ponto mais baixo da trajetória é $-h$ e se a gente solta a massa de $H \leq 0$, estamos na situação 1 acima, a de movimento periódico.  Se $H \geq 0$, a velocidade $v_0$ em $(-h,0)$ é dado por

$$
\frac{1}{2}v_{0}^{2} = gH 
$$ (eq1)

A equação {eq}`eq1` assume que soltamos a massa com velocidade zero.

### Condição para *justamente* completar o círculo

É instrutivo começar com o caso em que a massa atinge *justamente* a altura $h$ (o terceiro caso das três possibilidades descritas acima). Qual é a altura que precisamos solter a massa para isso acontecer? Parece o tipo de problema onde é suficiente usar considerações de conservação de energia mecânica. Uma análise ingênua, de um iniciante, poderia concluir que precisamos soltar a massa de $H=h$. Afinal, meste caso, a energia potencial inicial $mgH$ é convertida totalmente para a energia potencial final $mgh$. A massa não "quer" chegar na mesma altura de onde partiu? 

Esse raciocício ignora o fato que a velocidade da massa no topo da trajetória (vamos chamar de $v_t$) não pode ser zero. Para nosso modelo, a força de vínculo (a força normal ou a tensão no fio) pode ser zero no topo da trajetória mas para continuar em movimento circular deve haver uma a força centrípeta, dado somente pela gravidade, resultando numa velocidade mínima no topo

$$ \frac{v_t^2}{h} = g $$

Combinando com a conservação de energia mecânica

$$ \frac{1}{2}v_{t}^2 = \frac{1}{2}v_0^2 - gh $$

e temos que

$$ \frac{1}{2}gh + gh = gH \Rightarrow H = \frac{3}{2} h $$

Ou seja, precisamos soltar a massa de uma altura um pouco *mais* do que $h$ para *justamente* chegar na altura $h$ no topo da trajetória, porque no nosso modelo no topo há uma aceleração centrípeta mínima (quando a força normal ou de tensão no fio são zero), dado pela aceleração da gravidade $g$.

### Condição para *justamente* passar pelo centro do círculo
Se soltar a massa de uma altura $0 < H <  \frac{3}{2}h $ em algum momento antes de chegar no topo a magnitude da força de vínculo se torna zero e a massa segue em queda livre. Começando com velocidade inicial $v_0$ em $(-h,0)$, perguntamos para qual ângulo $\theta_c$ a força de vínculo (a tensão ou força normal) se torna zero.

::::{grid}
:gutter: 2

:::{grid-item}
:outline:
```{image} modelo-vc.jpg
:width: 100%
:align: center
```
:::
:::{grid-item}
:outline:
```{image} modelo-vc.jpg
:width: 100%
:align: center
```
:::
::::

No momento crítico em que a força de vínculo é zero, a força centrípeta é dado (somente) pela componente perpendicular da força gravitação e temos

$$
\frac{v_{c}^{2}}{h}  = g \sin{\theta_c}.
$$ (eq2)

Por outro lado, pela conservação de energia mecânica

$$
  \frac{1}{2}v_{c}^2 = \frac{1}{2}v_{0}^2 -gh\sin{\theta_c}
$$ (eq3)

Combinando {eq}`eq2` e {eq}`eq3`, e usando $H_c$ (para a "altura de soltura crítica") em {eq}`eq1`, temos

$$
  \sin{\theta_c} = \frac{2}{3}\frac{H_c}{h}.
$$ (eq4)

Agora vamos escrever as equações horárias para a parábola de queda livre $x(t)$ e $y(t)$ com a posição inicial $(-h\cos{\theta_c},h\sin{\theta_c})$ e velocidade inicial $\vec{v_c}$:

$$
\begin{aligned}
x(t) & = -h\cos{\theta_c} + v_c\sin{\theta_c}t  \\
y(t) & = h\sin{\theta_c} + v_c\cos{\theta_c}t - \frac{1}{2}gt^2
\end{aligned}
$$

Para que essa parábola passa pelo $(0,0)$ podemos mostrar que precisamos ter $\sin{\theta_c} = \sqrt{1/3}$ (ou $\theta_c = 35.3^{\circ}$). Inserindo isso em {eq}`eq4` chegamos a 

$$
  \boxed{\frac{H_c}{h} = \frac{\sqrt{3}}{2}}
$$

Ou seja, precisamos soltar a massa de uma altura de $0.866$ do raio para que a parábola exatamente passa pelo orígem do círculo. Um pouco mais, e o fio se enrola em volta do pino no caso de um pêndulo interrompido. Note que essa altura de soltura é um pouco menos do que o Galileu afirmou (ele disse que seria necessário usar uma altura $h$ ou exato um raio). 

Para terminar, vamos mostrar que $\sin{\theta_c} = \sqrt{1/3}$. Certamente deve de ter uma maneira geométrica, pelas propriedades de círculos e parábolas de mostrar isso. Mas fiz por força bruta, colocando $x=0, y=0$ nas equações horárias do parábola. Usando $x(t_0) = 0$ temos

$$
t_0 = \frac{h\cos{\theta_c}}{v_c}
$$

Inserindo este tempo em $y(t_0) = 0$ temos

$$
\frac{1}{2}g \frac{h^2\cos^2{\theta_c}}{v_{c}^2\sin^2{\theta_c}} = h\sin{\theta_c} + v_c\cos{\theta_c}\frac{h\cos{\theta_c}}{v_{c}\sin{\theta_c}}
$$

Pulando alguns passos e usando $v_{c}^2 = hg\sin{\theta_c}$ chegamos a 

$$
\frac{\sin^2{\theta_c}}{\cos^2{\theta_c}} = \frac{1}{2}
$$

o que mostra que $\sin{\theta_c} = \sqrt{1/3}$ (e $\cos{\theta_c} = \sqrt{2/3}$).