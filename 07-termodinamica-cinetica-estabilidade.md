# Unidade 7 — Termodinâmica e cinética

**Carga horária:** 7 h/a teóricas + 2 h/a práticas (9 h/a)

## Objetivo da unidade

Conectar espontaneidade e velocidade de reação com degradação e estabilidade de medicamentos. Esta é uma das aplicações farmacêuticas mais diretas de toda a disciplina: a data de validade impressa em qualquer embalagem de medicamento é, literalmente, o resultado de um cálculo de cinética química.

---

## 1. Fundamentos físico-químicos

### 1.1 Primeira e segunda leis da termodinâmica (tratamento introdutório e aplicado)

**Primeira lei** (conservação de energia): a energia interna de um sistema muda de acordo com o calor trocado e o trabalho realizado, $\Delta U = Q - W$. Em processos a pressão constante (a maioria dos processos químicos de interesse aqui), essa variação de energia é expressa como **entalpia** (ΔH).

**Segunda lei:** todo processo espontâneo aumenta a entropia total do universo (sistema + vizinhança). É essa lei que explica por que existe uma "seta do tempo" nos processos químicos — inclusive na degradação espontânea (ainda que lenta) de um fármaco.

O tratamento aqui é aplicado, não uma disciplina de termodinâmica em si: o objetivo é chegar rapidamente ao critério prático de espontaneidade (seção 1.2).

### 1.2 Entalpia, entropia e energia livre de Gibbs (ΔG)

- **ΔH** (entalpia): calor trocado a pressão constante. Reação exotérmica, ΔH < 0; endotérmica, ΔH > 0.
- **ΔS** (entropia): medida da dispersão de energia/desordem do sistema.
- **ΔG** (energia livre de Gibbs) combina as duas grandezas no critério definitivo de espontaneidade a temperatura e pressão constantes:

$$\Delta G = \Delta H - T\Delta S$$

| Sinal de ΔG | Interpretação |
|---|---|
| ΔG < 0 | Processo espontâneo |
| ΔG > 0 | Processo não espontâneo (espontâneo no sentido inverso) |
| ΔG = 0 | Sistema em equilíbrio |

### 1.3 Relação entre ΔG, espontaneidade e constante de equilíbrio

Fechando um ciclo que já apareceu de forma parcial nas Unidades 2 e 6:

$$\Delta G° = -RT\ln K \qquad \Delta G° = -nFE°_{cel}$$

Três formas diferentes (K, E°, ΔG°) de expressar exatamente a mesma informação sobre o quanto uma reação "quer" acontecer. É importante frisar o limite dessa informação: **termodinâmica diz se e o quanto uma reação é favorável, não diz nada sobre a velocidade** com que ela ocorre — uma reação pode ser termodinamicamente muito favorável (ΔG muito negativo) e, ainda assim, ocorrer tão lentamente que pareça não acontecer. É exatamente essa lacuna que a cinética (seção 1.4 em diante) vem preencher, e é o motivo pelo qual um fármaco pode ser estável na prateleira por anos mesmo que sua decomposição seja termodinamicamente espontânea.

### 1.4 Cinética química: velocidade de reação, lei de velocidade, ordem de reação

Velocidade de reação é a variação da concentração de reagente ou produto por unidade de tempo:

$$v = -\frac{\Delta[reagente]}{\Delta t} = \frac{\Delta[produto]}{\Delta t}$$

A **lei de velocidade** relaciona a velocidade às concentrações dos reagentes, com expoentes (ordens) determinados **experimentalmente** — não a partir dos coeficientes estequiométricos da equação balanceada (erro comum de se supor o contrário):

$$v = k[A]^m[B]^n$$

A **ordem da reação** é a soma dos expoentes (m + n). É central entender que a ordem é uma propriedade experimental, obtida ajustando dados de concentração em função do tempo a diferentes modelos (seção 1.7), e não algo que se possa simplesmente "ler" da equação química.

### 1.5 Fatores que afetam a velocidade de reação

- **Concentração:** efeito direto descrito pela lei de velocidade.
- **Temperatura:** aumenta a velocidade — mais moléculas atingem a energia de ativação necessária (seção 1.6).
- **Catalisadores:** aumentam a velocidade ao oferecer um caminho de reação com menor energia de ativação, **sem deslocar o equilíbrio** e sem alterar K (retomando explicitamente o ponto já levantado na Unidade 2).
- **Superfície de contato e natureza dos reagentes:** relevantes principalmente em reações heterogêneas (conexão com formas farmacêuticas sólidas — maior área superficial de um pó acelera dissolução e, por vezes, degradação).

### 1.6 Equação de Arrhenius

A dependência da constante de velocidade (k) com a temperatura é descrita por:

$$k = Ae^{-E_a/RT}$$

ou, na forma linearizada, útil para tratamento de dados experimentais:

$$\ln k = \ln A - \frac{E_a}{RT}$$

Um gráfico de ln k versus 1/T é uma reta, cuja inclinação fornece a energia de ativação (Ea) da reação. Essa equação é a base matemática dos **estudos de estabilidade acelerada** (seção 2) — permite prever a velocidade de degradação em condição de armazenamento (temperatura ambiente) a partir de dados obtidos em temperaturas mais altas, sem esperar anos pelo resultado.

### 1.7 Cinética de degradação: ordem zero, primeira e segunda ordem

| Ordem | Lei de velocidade | Equação integrada | Gráfico linear | Meia-vida (t₁/₂) |
|---|---|---|---|---|
| Zero | $v = k$ | $[A] = [A]_0 - kt$ | [A] vs. t | $t_{1/2} = \dfrac{[A]_0}{2k}$ (depende da concentração inicial) |
| Primeira | $v = k[A]$ | $\ln[A] = \ln[A]_0 - kt$ | ln[A] vs. t | $t_{1/2} = \dfrac{0{,}693}{k}$ (**independe** da concentração inicial) |
| Segunda | $v = k[A]^2$ | $\dfrac{1}{[A]} = \dfrac{1}{[A]_0} + kt$ | 1/[A] vs. t | $t_{1/2} = \dfrac{1}{k[A]_0}$ (depende da concentração inicial) |

Na prática, a maior parte das degradações de fármacos segue **cinética de primeira ordem** (ou pseudo-primeira ordem) — daí a meia-vida ser independente da concentração inicial ser um fato tão citado em farmacotécnica. Reações de ordem zero são relevantes, por exemplo, em suspensões, onde a dissolução do fármaco (não a reação química em si) é a etapa limitante.

O método experimental para determinar a ordem é justamente testar qual dos três gráficos da tabela resulta em uma reta com os dados obtidos (retomado na Prática 2).

---

## 2. Aplicação analítica e farmacêutica

**Estabilidade de medicamentos e previsão de prazo de validade.** A cinética de degradação (seção 1.7) fornece a ferramenta matemática direta para calcular quanto tempo um medicamento leva para degradar até um limite aceitável de perda de potência.

**Estudos de estabilidade acelerada.** Em vez de armazenar um lote em condições normais por anos para observar a degradação, expõe-se o produto a temperaturas elevadas (e outras condições de estresse) por um período curto, mede-se a constante de velocidade (k) em cada temperatura, e usa-se a equação de Arrhenius (seção 1.6) para extrapolar o valor de k na temperatura de armazenamento real. É assim que a indústria farmacêutica estabelece prazos de validade antes de ter décadas de dados em tempo real.

**Fatores de degradação.** Luz, temperatura, umidade e pH são os principais fatores de estresse considerados em estudos de estabilidade — e cada um retoma diretamente conceitos já construídos: pH remete à Unidade 3 (hidrólise, tampões), oxidação remete à Unidade 6 (antioxidantes, quelantes). A estabilidade de um medicamento não é um tópico isolado — é a confluência prática de quase tudo visto na disciplina até aqui.

**Determinação de shelf-life a partir de dados cinéticos.** Na indústria farmacêutica, é comum calcular o **t₉₀** — o tempo necessário para que 10% do princípio ativo se degrade (limite regulatório usual). Para cinética de primeira ordem:

$$t_{90} = \frac{0{,}105}{k}$$

O valor de k usado nesse cálculo é obtido experimentalmente (seção 1.7) ou extrapolado por Arrhenius a partir de estudos acelerados.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Estudo cinético de degradação de um composto (modelo)**
Objetivo: acompanhar a degradação (ex.: descoloração) de um composto-modelo ao longo do tempo, sob condição controlada de temperatura.
Procedimento resumido: preparar solução do composto-modelo; medir a concentração (por absorbância em UV-Vis, ou comparação visual com padrão) em intervalos regulares de tempo; registrar os dados para uso na Prática 2.

**Prática 2 — Determinação da ordem de reação a partir de dados experimentais**
Objetivo: determinar a ordem da reação de degradação estudada na Prática 1.
Procedimento resumido: com os dados de concentração vs. tempo, construir os três gráficos da tabela da seção 1.7 ([A] vs. t; ln[A] vs. t; 1/[A] vs. t); identificar qual apresenta comportamento linear; a partir da inclinação da reta, obter o valor de k.

**Prática 3 — Cálculo de tempo de meia-vida e prazo de validade estimado**
Objetivo: aplicar o valor de k obtido na Prática 2 para calcular t₁/₂ e t₉₀ do composto estudado.
Procedimento resumido: usando a equação apropriada à ordem identificada, calcular t₁/₂; para cinética de primeira ordem, calcular também t₉₀ e discutir seu significado como estimativa de prazo de validade.

---

## 4. Pontos de conexão com as próximas unidades

- Fecha o eixo teórico central da disciplina (Unidades 1 a 7 formam um bloco integrado de fundamentos).
- A **Unidade 8** trata, de forma introdutória, de interfaces e sistemas dispersos — tópico relevante para formas farmacêuticas, mas que não exige o mesmo aprofundamento teórico das unidades anteriores.
- A **Unidade 9** integra todos os equilíbrios (Unidades 1 a 6) na marcha analítica sistemática; os conceitos desta unidade (estabilidade, degradação) permanecem como pano de fundo conceitual para a discussão de conservação de amostras e reagentes em laboratório.

---
*Conteúdo completo — Unidade 7. Próxima revisão: ajustar exemplo de composto-modelo conforme reagentes disponíveis no laboratório da instituição.*
