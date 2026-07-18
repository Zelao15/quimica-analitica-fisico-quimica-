# Unidade 3 — Equilíbrios ácido-base

**Carga horária:** 9 h/a teóricas + 5 h/a práticas (14 h/a)

## Objetivo da unidade

Esta é a unidade de maior peso teórico da disciplina. Tudo que envolve pH — separação seletiva, tampões, comportamento de fármacos ácidos e básicos, identificação de íons — depende do que é construído aqui. Nas unidades seguintes (solubilidade, complexação, marcha analítica) o pH deixa de ser "matéria nova" e passa a ser ferramenta de trabalho.

---

## 1. Fundamentos físico-químicos

### 1.1 Teorias ácido-base

**Arrhenius (1887).** Ácido é toda substância que, em água, libera H⁺ (na prática, H₃O⁺); base é toda substância que libera OH⁻. Funciona bem para HCl, NaOH, mas é limitada: só se aplica a soluções aquosas e não explica por que NH₃, que não tem OH⁻ na fórmula, se comporta como base.

**Brønsted-Lowry (1923).** Ácido é doador de próton (H⁺); base é aceptor de próton. A reação ácido-base é uma transferência de H⁺:

$$HA + B \rightleftharpoons A^- + HB^+$$

Isso introduz o conceito de **par conjugado**: HA/A⁻ e B/HB⁺ são pares ácido-base conjugados. Toda essa unidade — Ka, Kb, hidrólise, tampão — é construída sobre essa ideia de par conjugado. Espécies que podem se comportar como ácido ou base dependendo do meio (como a água, ou o HCO₃⁻) são chamadas **anfóteras** ou **anfipróticas**.

**Lewis (1923).** Ácido é aceptor de par de elétrons; base é doador de par de elétrons. É a definição mais abrangente: explica reações que não envolvem H⁺ nenhum, como a formação de complexos metálicos (Cu²⁺ como ácido de Lewis, NH₃ como base de Lewis). Essa definição é o elo direto com a **Unidade 5 (Complexação)** — vale reforçar esse ponto em aula, porque o aluno tende a achar que "ácido-base" e "complexação" são assuntos separados, quando na verdade complexação é ácido-base de Lewis.

Para os fins desta disciplina (química em solução aquosa, farmácia), o tratamento quantitativo (pH, Ka, tampão) usa a definição de Brønsted-Lowry.

### 1.2 Autoionização da água e Kw

A própria água se autoioniza, ainda que em extensão pequena:

$$H_2O + H_2O \rightleftharpoons H_3O^+ + OH^-$$

$$K_w = [H_3O^+][OH^-] = 1{,}0 \times 10^{-14} \text{ a } 25\,°C$$

Kw é constante em qualquer solução aquosa a 25 °C — o que muda é a proporção entre H₃O⁺ e OH⁻. Isso é o que permite calcular um a partir do outro em qualquer solução, ácida, básica ou neutra.

### 1.3 pH e pOH

$$pH = -\log[H_3O^+] \qquad pOH = -\log[OH^-]$$

$$pH + pOH = 14 \text{ (a 25 °C)}$$

Escala prática de 0 a 14 (fora desse intervalo em soluções muito concentradas, onde a aproximação de atividade ≈ concentração deixa de valer — conexão com a Unidade 1, força iônica e atividade).

Cálculo direto para ácidos e bases **fortes** (dissociação considerada completa): a concentração de H₃O⁺ ou OH⁻ é igual à concentração analítica do ácido/base (corrigida pela estequiometria, se for poliprótico).

*Exemplo:* HCl 0,010 mol/L → [H₃O⁺] = 0,010 mol/L → pH = 2,00.

### 1.4 Ácidos e bases fracas: Ka, Kb, pKa, pKb

Ácidos e bases fracos não se dissociam completamente — atingem um equilíbrio:

$$HA + H_2O \rightleftharpoons H_3O^+ + A^- \qquad K_a = \frac{[H_3O^+][A^-]}{[HA]}$$

$$pK_a = -\log K_a$$

Quanto **menor o pKa**, mais forte é o ácido (mais ele se dissocia). O mesmo raciocínio vale para Kb/pKb de bases fracas.

Para um par conjugado ácido/base (HA/A⁻):

$$K_a \times K_b = K_w$$

Essa relação é o que permite, dado o Ka de um ácido, calcular o Kb da sua base conjugada — muito usada depois em hidrólise salina e em tampões.

### 1.5 Grau de ionização e Lei de diluição de Ostwald

Grau de ionização (α) é a fração do eletrólito que efetivamente se dissocia:

$$\alpha = \frac{\text{concentração dissociada}}{\text{concentração inicial}}$$

A **Lei de diluição de Ostwald** relaciona Ka, a concentração analítica (C) e α para um eletrólito fraco:

$$K_a = \frac{C\alpha^2}{1-\alpha}$$

Consequência prática importante: **diluir uma solução de eletrólito fraco aumenta o grau de dissociação** (α cresce quando C diminui), mesmo que a quantidade absoluta de íons não mude na mesma proporção. Isso costuma ser contraintuitivo para o aluno — vale reforçar com um exemplo numérico em aula.

### 1.6 Hidrólise salina

Sal é o produto de uma reação ácido-base. Dependendo da força do ácido e da base que o originaram, o sal reage com a água (hidrólise) e altera o pH da solução:

| Origem do sal | Comportamento em água | Exemplo |
|---|---|---|
| Ácido forte + base forte | Neutro (não hidrolisa) | NaCl |
| Ácido fraco + base forte | Hidrólise básica (pH > 7) | CH₃COONa (acetato de sódio) |
| Ácido forte + base fraca | Hidrólise ácida (pH < 7) | NH₄Cl (cloreto de amônio) |
| Ácido fraco + base fraca | Depende de Ka vs. Kb do par | CH₃COONH₄ |

Esse quadro é usado depois na marcha analítica para prever o pH de meios reacionais formados por sais.

### 1.7 Soluções tampão

Um tampão é uma mistura de um ácido fraco com sua base conjugada (ou uma base fraca com seu ácido conjugado) que **resiste a variações de pH** quando se adiciona uma pequena quantidade de ácido, base, ou quando se dilui a solução.

**Equação de Henderson-Hasselbalch:**

$$pH = pK_a + \log\frac{[A^-]}{[HA]}$$

Pontos-chave para ensinar:

- Quando [A⁻] = [HA], pH = pKa — é o ponto de **máxima capacidade tamponante**.
- A faixa efetiva de tamponamento é **pKa ± 1** (fora disso, a razão [A⁻]/[HA] fica tão desbalanceada que o tampão perde a função).
- **Capacidade tamponante** depende da concentração absoluta dos componentes, não só da razão entre eles — dois tampões com a mesma razão [A⁻]/[HA] mas concentrações diferentes têm o mesmo pH, mas capacidades de resistir a perturbação muito diferentes.

Relevância farmacêutica: tampão fosfato e tampão acetato são usados para manter estabilidade de formulações (evitar degradação dependente de pH — conexão direta com a **Unidade 7**) e para compatibilidade com fluidos biológicos (soluções injetáveis, colírios).

### 1.8 Titulação ácido-base

Curvas de titulação (pH em função do volume de titulante) têm formato característico conforme o par ácido/base:

- **Forte + forte:** salto abrupto de pH no ponto de equivalência, pH = 7 no ponto de equivalência.
- **Fraco + forte:** existe uma região de tamponamento antes do ponto de equivalência (onde pH ≈ pKa na metade do caminho); no ponto de equivalência, pH ≠ 7 (há hidrólise do sal formado — conecta com a seção 1.6).
- **Forte + fraco:** análogo, com pH no ponto de equivalência também deslocado da neutralidade.

Distinção importante: **ponto de equivalência** (onde a quantidade estequiométrica de titulante foi adicionada — conceito teórico, calculado) vs. **ponto final** (onde o indicador muda de cor — observado experimentalmente). Um bom indicador é escolhido para que o ponto final coincida o mais próximo possível do ponto de equivalência.

### 1.9 Indicadores ácido-base

Indicadores são, eles mesmos, ácidos ou bases fracos cuja forma protonada e desprotonada têm cores diferentes:

$$HIn \rightleftharpoons H^+ + In^-$$

A zona de viragem (faixa de pH onde a cor muda) ocorre aproximadamente em **pH = pKIn ± 1**. A escolha do indicador certo para uma titulação depende de a zona de viragem coincidir com o pH do ponto de equivalência daquela curva específica — não existe "indicador universal" para qualquer titulação.

---

## 2. Aplicação analítica e farmacêutica

**Controle de pH nas reações de identificação.** Cada grupo de cátions na marcha analítica clássica é precipitado em uma faixa de pH específica (grupo dos sulfetos ácidos, por exemplo, precipita em meio ácido; outros grupos exigem meio básico). Isso não é arbitrário — é consequência direta da relação entre pH e solubilidade de sais (antecipando a **Unidade 4**): controlar o pH é controlar qual espécie vai precipitar e qual vai permanecer em solução.

**Separação e identificação dependentes do pH.** Ajustar o pH do meio é, na prática, a primeira ferramenta de separação seletiva antes mesmo de qualquer reagente específico ser adicionado.

**Fármacos ácidos e básicos fracos.** A maioria dos fármacos orais é ácido ou base fraca. A forma ionizada e a forma não ionizada de um fármaco têm comportamentos completamente diferentes (solubilidade, permeação de membrana). A equação de Henderson-Hasselbalch aplicada ao fármaco permite estimar a fração ionizada em determinado pH — é a base conceitual da "teoria do particionamento de pH", que será aprofundada em disciplinas de Farmacocinética. Aqui, o objetivo é o aluno reconhecer que **pKa do fármaco não é só um número decorado, é o que determina onde e como ele se dissolve e é absorvido**.

**Escolha de tampão em formulações farmacêuticas.** Tampões são selecionados considerando: pKa próximo do pH-alvo da formulação, compatibilidade fisiológica (tampão fosfato para uso parenteral/oftálmico), ausência de interação com o princípio ativo, e capacidade tamponante suficiente para a vida útil do produto.

**Escolha de indicador em titulações farmacopeicas.** Métodos oficiais de doseamento por titulação (Farmacopeia) especificam o indicador correto para cada ensaio — fenolftaleína para titulações que terminam em pH básico, alaranjado de metila para as que terminam em pH ácido, por exemplo. Entender a lógica da zona de viragem evita que o aluno apenas decore "qual indicador usar em qual ensaio" sem entender o motivo.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Preparo e verificação de solução tampão**
Objetivo: preparar um tampão acetato (ou fosfato) em pH definido e confirmar experimentalmente com pHmetro.
Procedimento resumido: calcular as massas/volumes de ácido fraco e sal (base conjugada) pela equação de Henderson-Hasselbalch para o pH desejado; preparar a solução; medir o pH real e comparar com o calculado; adicionar pequena quantidade de HCl ou NaOH e observar a variação (pequena) de pH — evidenciando a capacidade tamponante.

**Prática 2 — Curva de titulação ácido-base**
Objetivo: construir experimentalmente uma curva de titulação (pH vs. volume de titulante) usando um ácido fraco e uma base forte (ou o inverso).
Procedimento resumido: titular sob agitação, registrando pH a cada alíquota de titulante (bureta); plotar a curva; identificar a região de tamponamento, o ponto de inflexão (equivalência) e comparar com o valor teórico calculado.

**Prática 3 — Determinação de pKa por titulação**
Objetivo: obter o pKa experimental de um ácido fraco a partir da curva de titulação.
Procedimento resumido: no ponto de meia-neutralização (metade do volume necessário para atingir a equivalência), pH = pKa (decorrência direta da equação de Henderson-Hasselbalch quando [A⁻] = [HA]); ler esse valor na curva construída na Prática 2 e comparar com o valor de referência da literatura.

---

## 4. Pontos de conexão com as próximas unidades

- pH controla a solubilidade de sais (**Unidade 4** — efeito do pH sobre Kps efetivo).
- A definição de Lewis liga ácido-base à formação de complexos (**Unidade 5**).
- A estabilidade de fármacos frente à hidrólise depende do pH do meio (**Unidade 7** — cinética de degradação).
- O controle de pH é pré-requisito direto de cada etapa da marcha analítica sistemática (**Unidade 9**).

---
*Conteúdo completo — Unidade 3. Próxima revisão: ajustar exemplos numéricos conforme a bibliografia adotada na disciplina.*
