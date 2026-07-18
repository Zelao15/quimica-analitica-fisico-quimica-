# Unidade 4 — Solubilidade

**Carga horária:** 8 h/a teóricas + 6 h/a práticas (14 h/a)

## Objetivo da unidade

Sustentar diretamente a precipitação seletiva — uma das técnicas centrais da marcha analítica qualitativa. Assim como a Unidade 3 tratou o equilíbrio homogêneo em solução, esta unidade trata o equilíbrio **heterogêneo** entre um sólido e seus íons dissolvidos, usando exatamente a mesma lógica de constante de equilíbrio já construída na Unidade 2.

---

## 1. Fundamentos físico-químicos

### 1.1 Equilíbrio heterogêneo sólido-solução

Quando um sal pouco solúvel é colocado em água além do seu limite de dissolução, estabelece-se um equilíbrio dinâmico entre o sólido não dissolvido e os íons em solução:

$$AgCl_{(s)} \rightleftharpoons Ag^+_{(aq)} + Cl^-_{(aq)}$$

É equilíbrio dinâmico genuíno: a taxa de dissolução iguala a taxa de precipitação, mesmo que macroscopicamente pareça que "nada está acontecendo". Essa é a mesma ideia de equilíbrio da Unidade 2, agora aplicada a um sistema com duas fases.

### 1.2 Produto de solubilidade (Kps)

Como o sólido puro não entra na expressão de equilíbrio (sua "concentração" é constante), a constante de equilíbrio para a dissolução é escrita apenas em função dos íons:

$$K_{ps} = [Ag^+][Cl^-]$$

Para um sal genérico $M_mA_n$:

$$M_mA_{n(s)} \rightleftharpoons mM^{n+} + nA^{m-} \qquad K_{ps} = [M^{n+}]^m[A^{m-}]^n$$

Kps é constante a uma dada temperatura e **não depende da quantidade de sólido em excesso** — só depende das concentrações dos íons em solução saturada. Esse ponto costuma gerar confusão: ter mais sólido no fundo do béquer não muda o Kps nem a concentração dos íons dissolvidos.

### 1.3 Relação entre Kps e solubilidade molar

Solubilidade molar (s) é a quantidade máxima (em mol/L) do sal que se dissolve. A relação entre Kps e s depende da estequiometria:

- **Sal 1:1** (ex.: AgCl): $K_{ps} = s^2 \Rightarrow s = \sqrt{K_{ps}}$
- **Sal 1:2 ou 2:1** (ex.: Ag₂CrO₄, Mg(OH)₂): $K_{ps} = 4s^3 \Rightarrow s = \sqrt[3]{K_{ps}/4}$
- **Caso geral** $M_mA_n$: $K_{ps} = m^m n^n s^{(m+n)}$

Ponto pedagógico importante: **não dá para comparar Kps de sais com estequiometrias diferentes diretamente** para saber qual é "mais solúvel" — é preciso calcular s em cada caso. Um sal com Kps maior pode ser menos solúvel que outro com Kps menor, se as estequiometrias forem diferentes.

### 1.4 Efeito do íon comum

Adicionar um íon que já participa do equilíbrio de solubilidade desloca o equilíbrio no sentido de formar mais sólido (Le Chatelier, Unidade 2), **reduzindo** a solubilidade.

*Exemplo:* a solubilidade de AgCl em água pura é maior do que em uma solução que já contém NaCl — o Cl⁻ adicionado desloca o equilíbrio para a formação de mais AgCl sólido.

### 1.5 Efeito salino (efeito do íon diverso)

Ao contrário do efeito do íon comum, a adição de um eletrólito que **não** participa diretamente do equilíbrio (um íon "espectador") tende a **aumentar ligeiramente** a solubilidade. Isso acontece porque o aumento da força iônica do meio reduz os coeficientes de atividade dos íons envolvidos (retomando o conceito de atividade da **Unidade 1**), o que efetivamente desloca o equilíbrio no sentido da dissolução para manter o produto das atividades constante.

Vale destacar esse aparente paradoxo em aula: íon comum diminui solubilidade, íon diverso aumenta (ainda que num efeito bem mais discreto) — o critério que diferencia os dois é se o íon adicionado participa ou não da própria expressão de Kps.

### 1.6 Efeito do pH sobre a solubilidade

Sais cujo ânion é a base conjugada de um ácido fraco (carbonatos, sulfetos, oxalatos, fosfatos) têm solubilidade **fortemente dependente do pH**: em meio ácido, o H⁺ reage com o ânion (retomando a hidrólise e os equilíbrios ácido-base da **Unidade 3**), consumindo-o e deslocando o equilíbrio de solubilidade no sentido de dissolver mais sólido.

$$CaC_2O_{4(s)} \rightleftharpoons Ca^{2+} + C_2O_4^{2-} \qquad C_2O_4^{2-} + H^+ \rightleftharpoons HC_2O_4^-$$

O mesmo vale para hidróxidos pouco solúveis: em meio ácido, o OH⁻ é neutralizado, aumentando a solubilidade do hidróxido metálico.

Este é o mecanismo físico-químico exato por trás do controle de pH na marcha analítica — não é uma regra empírica, é consequência direta do deslocamento de equilíbrio.

### 1.7 Previsão de precipitação: Q vs. Kps

O quociente de reação (Q), já visto na Unidade 2, se aplica aqui da mesma forma, usando as concentrações **reais** (não necessariamente de equilíbrio) dos íons no instante considerado:

| Comparação | Situação |
|---|---|
| Q < Kps | Solução insaturada — não há precipitado, e se houver sólido, ele se dissolve |
| Q = Kps | Solução saturada — equilíbrio estabelecido |
| Q > Kps | Solução supersaturada — ocorre precipitação até Q voltar a igualar Kps |

Esse critério (Q vs. Kps) é a ferramenta de cálculo central para prever se, ao misturar dois reagentes, vai formar precipitado — e é a base quantitativa da precipitação seletiva.

---

## 2. Aplicação analítica e farmacêutica

**Precipitação seletiva de cátions.** Ao adicionar um reagente que forma precipitados com Kps muito diferentes para os cátions presentes numa mistura, é possível ajustar a concentração do ânion (ou o pH, quando aplicável) para que apenas o cátion menos solúvel precipite, mantendo os demais em solução. Esse é o princípio por trás da separação em grupos da marcha analítica clássica (cloretos do Grupo I, sulfetos em meio ácido do Grupo II, hidróxidos em meio básico, etc.).

**Separação de grupos analíticos por solubilidade diferencial.** A ordem em que os grupos são precipitados na marcha (retomada de forma integrada na **Unidade 9**) segue exatamente a lógica de Kps e efeito do pH construída aqui: primeiro se separa o que precipita em condições mais brandas, depois se ajusta o meio (geralmente acidificando ou basificando) para precipitar o próximo grupo.

**Dissolução seletiva de precipitados.** Um precipitado pode ser redissolvido seletivamente ajustando o pH (seção 1.6) ou adicionando um agente que forme um complexo solúvel com o cátion (antecipando a **Unidade 5** — dissolução por complexação é, no fundo, mais um jeito de deslocar o equilíbrio de solubilidade).

**Relevância farmacêutica.** A solubilidade de um fármaco em condições fisiológicas (pH gastrointestinal, por exemplo) determina sua taxa de dissolução e, em última análise, sua biodisponibilidade. Fármacos ácidos e básicos fracos formulados como sais (cloridratos, sulfatos) têm solubilidade que também segue a lógica de Kps e efeito do pH vista aqui — a escolha do sal de um fármaco na formulação não é acidente, é engenharia de solubilidade.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Determinação experimental de Kps**
Objetivo: determinar o Kps de um sal pouco solúvel (ex.: Ca(OH)₂ ou CaC₂O₄) a partir da concentração medida de um dos íons em solução saturada.
Procedimento resumido: preparar solução saturada em contato com excesso de sólido; separar o sobrenadante (filtração); determinar a concentração de um dos íons por titulação (ou outro método disponível); calcular Kps a partir da estequiometria e comparar com o valor de referência.

**Prática 2 — Precipitação seletiva de dois cátions em mistura**
Objetivo: separar dois cátions em solução por precipitação seletiva controlada, escolhendo o reagente e a condição de acordo com a diferença de Kps entre os dois sais formados.
Procedimento resumido: adicionar o reagente precipitante lentamente e sob controle (concentração, ordem de adição); verificar a formação seletiva do precipitado menos solúvel primeiro; separar por filtração e confirmar a presença do segundo cátion no filtrado.

**Prática 3 — Efeito do pH na solubilidade de um sal pouco solúvel**
Objetivo: observar experimentalmente a dissolução de um precipitado (ex.: oxalato de cálcio ou hidróxido metálico) por acidificação controlada.
Procedimento resumido: formar o precipitado; adicionar ácido gota a gota, monitorando o pH; registrar o pH em que ocorre dissolução visível; relacionar com o mecanismo discutido na seção 1.6.

---

## 4. Pontos de conexão com as próximas unidades

- O efeito do pH sobre a solubilidade retoma diretamente os equilíbrios ácido-base da **Unidade 3**.
- A dissolução de precipitados por formação de complexo solúvel antecipa a **Unidade 5 (Complexação)**.
- A sequência de precipitação seletiva por grupos é o esqueleto da **Unidade 9 (Marcha analítica sistemática)**.

---
*Conteúdo completo — Unidade 4. Próxima revisão: ajustar exemplos e valores de Kps conforme a bibliografia adotada na disciplina.*
