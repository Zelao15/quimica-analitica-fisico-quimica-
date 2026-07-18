# Unidade 2 — Equilíbrio químico

**Carga horária:** 6 h/a teóricas + 1 h/a prática (7 h/a)

## Objetivo da unidade

Esta unidade estabelece a linguagem — Keq, quociente de reação, Le Chatelier — que será reaplicada, sem reapresentar os conceitos, em ácido-base (Unidade 3), solubilidade (Unidade 4), complexação (Unidade 5) e oxirredução (Unidade 6). É uma unidade curta em carga horária, mas estrategicamente central: tudo que vem depois é "equilíbrio químico com um nome diferente".

---

## 1. Fundamentos físico-químicos

### 1.1 Reversibilidade das reações químicas

A maioria das reações químicas é, em algum grau, reversível — produtos podem reagir entre si e regenerar os reagentes. Na prática, é útil distinguir:

- Reações que se completam de forma essencialmente total (constante de equilíbrio muito grande) — tratadas como "irreversíveis" para fins de cálculo.
- Reações que atingem um **equilíbrio dinâmico**: a reação direta e a reação inversa continuam ocorrendo, mas em velocidades iguais, de modo que as concentrações macroscópicas não mudam mais. (A palavra-chave é dinâmico — não é que a reação parou; é que as duas direções se cancelam. Essa ideia será formalizada em termos de velocidade de reação na Unidade 7.)

### 1.2 Constante de equilíbrio (Kc, Kp)

Para uma reação genérica:

$$aA + bB \rightleftharpoons cC + dD$$

a constante de equilíbrio em termos de concentração é:

$$K_c = \frac{[C]^c[D]^d}{[A]^a[B]^b}$$

Para reações envolvendo gases, é comum usar pressões parciais (Kp), relacionada a Kc por:

$$K_p = K_c(RT)^{\Delta n}$$

onde Δn é a variação do número de mols gasosos entre produtos e reagentes.

Dois pontos que evitam erro de aplicação:

- **Sólidos puros e líquidos puros não entram na expressão de K** (suas "concentrações" são constantes e já estão incorporadas na própria constante). Esse é exatamente o motivo pelo qual, na Unidade 4, o Kps de um sal pouco solúvel só tem os íons na expressão, e não o sólido.
- **Kc depende apenas da temperatura.** Não muda com a concentração inicial dos reagentes, não muda ao adicionar mais reagente ou produto — o que muda é para onde o equilíbrio se desloca (seção 1.4), não o valor de K em si.

### 1.3 Quociente de reação (Q) vs. Keq

Q tem exatamente a mesma expressão matemática de K, mas é calculado com as concentrações **em qualquer instante**, não necessariamente as de equilíbrio:

$$Q = \frac{[C]^c[D]^d}{[A]^a[B]^b} \quad \text{(concentrações no instante considerado)}$$

Comparar Q com K permite prever a direção em que a reação vai caminhar até atingir o equilíbrio:

| Comparação | O que acontece |
|---|---|
| Q < K | A reação avança no sentido direto (formação de mais produto) |
| Q = K | Sistema já está em equilíbrio |
| Q > K | A reação avança no sentido inverso (formação de mais reagente) |

Esse critério Q vs. K é reaproveitado quase sem alteração na Unidade 4 (Q vs. Kps, para prever se ocorre precipitação) — vale antecipar isso em aula.

### 1.4 Princípio de Le Chatelier

Se um sistema em equilíbrio sofre uma perturbação, ele se desloca no sentido de **minimizar** o efeito dessa perturbação:

- **Mudança de concentração:** adicionar reagente desloca o equilíbrio para a formação de mais produto (e vice-versa); remover um produto à medida que ele se forma desloca o equilíbrio continuamente no sentido direto — é a base de estratégias analíticas de "forçar" uma reação até o fim (seção 2).
- **Mudança de temperatura:** desloca o equilíbrio de acordo com o caráter exotérmico ou endotérmico da reação (tratado com profundidade em termos de ΔH e ΔG na Unidade 7). Regra prática: aumentar a temperatura favorece o sentido endotérmico.
- **Mudança de pressão/volume** (equilíbrios gasosos): reduzir o volume desloca o equilíbrio para o lado com menor número de mols de gás.
- **Catalisador:** acelera o tempo para atingir o equilíbrio, mas **não desloca** o equilíbrio nem altera K — esse ponto costuma ser confundido pelos alunos e vale reforçar explicitamente. Catalisador é assunto de velocidade de reação (cinética, Unidade 7), não de posição de equilíbrio.

### 1.5 Relação entre Keq e termodinâmica

Existe uma relação direta entre a constante de equilíbrio e a variação de energia livre de Gibbs padrão da reação:

$$\Delta G° = -RT \ln K$$

Quanto maior o K (equilíbrio deslocado para produtos), mais negativo é ΔG° — ou seja, mais espontânea é a reação no sentido direto. Essa relação é retomada e aprofundada na **Unidade 7**; aqui, o objetivo é apenas que o aluno perceba que "reação favorável" e "K grande" são a mesma ideia expressa de duas formas.

---

## 2. Aplicação analítica e farmacêutica

**Condições que favorecem ou impedem uma reação analítica de identificação.** Para que uma reação sirva como teste de identificação (formação de precipitado colorido, mudança de cor, liberação de gás), ela precisa ter K grande o suficiente para que o efeito observável seja inequívoco — uma reação com K próximo de 1, em que reagentes e produtos coexistem em quantidades comparáveis, não serve como teste analítico confiável.

**Deslocamento de equilíbrio como estratégia analítica.** Le Chatelier deixa de ser só teoria e vira ferramenta de trabalho: adicionar excesso de reagente para forçar a reação o mais próximo possível da completude; ajustar o pH do meio para favorecer a forma da espécie que reage (antecipando a Unidade 3); remover o produto da reação (por exemplo, precipitação) para deslocar continuamente o equilíbrio no sentido direto.

**"Toda reação de identificação é um equilíbrio deslocado a favor do produto observável."** Essa frase resume a lógica que perpassa as próximas unidades: precipitação seletiva (Unidade 4), formação de complexos coloridos (Unidade 5) e reações redox de identificação (Unidade 6) não são fenômenos novos e desconectados — são todos aplicações do mesmo princípio de equilíbrio deslocado, cada um com sua própria constante (Kps, Kf, E°) no lugar do Keq genérico visto aqui.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Demonstração de deslocamento de equilíbrio (sistema cromato/dicromato)**
Objetivo: observar visualmente o deslocamento de um equilíbrio químico por mudança de pH.
Procedimento resumido: partindo de uma solução de cromato (amarela), adicionar ácido gota a gota e observar a mudança para dicromato (laranja); em seguida adicionar base e observar o retorno à cor original.

$$2CrO_4^{2-} \text{ (amarelo)} + 2H^+ \rightleftharpoons Cr_2O_7^{2-} \text{ (laranja)} + H_2O$$

Discutir: por que a mudança de pH desloca esse equilíbrio, antecipando a Unidade 3.

**Prática 2 — Efeito da temperatura em um equilíbrio reversível observável**
Objetivo: observar o deslocamento de um equilíbrio por variação de temperatura.
Procedimento resumido: usando um sistema com mudança de cor sensível à temperatura (por exemplo, o equilíbrio entre complexos de cobalto, rosa em baixa temperatura e azul em temperatura mais alta, ou outro sistema disponível no laboratório), aquecer e resfriar a solução, registrando a mudança de cor em cada condição; relacionar com o caráter exotérmico/endotérmico do deslocamento observado.

---

## 4. Pontos de conexão com as próximas unidades

- Keq é a base direta para Ka/Kb (**Unidade 3**), Kps (**Unidade 4**), Kf (**Unidade 5**) e constantes/potenciais redox (**Unidade 6**) — em cada caso, o mesmo formalismo de equilíbrio é reaplicado a um tipo específico de reação.
- A relação Keq–ΔG é retomada e aprofundada na **Unidade 7**, junto com a distinção entre espontaneidade (termodinâmica) e velocidade (cinética).

---
*Conteúdo completo — Unidade 2. Próxima revisão: ajustar exemplo prático conforme reagentes disponíveis no laboratório da instituição.*
