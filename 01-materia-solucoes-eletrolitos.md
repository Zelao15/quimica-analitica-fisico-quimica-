# Unidade 1 — Matéria, soluções e eletrólitos

**Carga horária:** 7 h/a teóricas + 3 h/a práticas (10 h/a)

## Objetivo da unidade

Esta é a unidade de abertura da disciplina: estabelece a base quantitativa — concentração, atividade, força iônica — que será usada sem reexplicação em todas as unidades seguintes. Nenhum cálculo de equilíbrio (ácido-base, solubilidade, complexação, redox) faz sentido sem o vocabulário construído aqui.

---

## 1. Fundamentos físico-químicos

### 1.1 Estados da matéria e comportamento dos gases (revisão rápida)

Tratamento introdutório, apenas o necessário para dar contexto físico-químico ao restante da disciplina — não é o foco da unidade:

- Equação geral dos gases ideais: $PV = nRT$
- Leis de Boyle (P e V a T constante), Charles (V e T a P constante) como casos particulares
- Noção de teoria cinética dos gases: partículas em movimento constante, colisões elásticas — serve de base conceitual para entender energia cinética das partículas em solução, retomada de forma mais aplicada na cinética química (Unidade 7)

### 1.2 Soluções: tipos e unidades de concentração

Solução é uma mistura homogênea de soluto(s) em solvente. Classificação usual: insaturada, saturada e supersaturada (relação direta com o equilíbrio de solubilidade da Unidade 4).

Unidades de concentração usadas ao longo da disciplina:

| Unidade | Definição | Uso típico |
|---|---|---|
| Molaridade (mol/L) | mol de soluto / L de solução | Cálculos de equilíbrio (Ka, Kps, Kf) |
| Percentual m/v, v/v, m/m | massa ou volume de soluto por 100 de solução | Formulações farmacêuticas |
| ppm, ppb | partes por milhão/bilhão | Concentrações traço |
| Molalidade (mol/kg de solvente) | independe da temperatura (ao contrário da molaridade) | Propriedades coligativas |
| Normalidade (equivalente-grama/L) | considera a capacidade reativa (nº de H⁺, OH⁻ ou elétrons transferidos) | Titulações (ainda usada na prática de análise volumétrica) |

Ponto pedagógico: normalidade parece "unidade antiga", mas continua aparecendo em cálculo de titulação porque simplifica a relação estequiométrica direta entre volumes de titulante e titulado (Volumes × Normalidades são iguais no ponto de equivalência, independentemente da estequiometria da reação).

### 1.3 Eletrólitos fortes, fracos e não eletrólitos

Eletrólito é toda substância que, dissolvida, produz uma solução capaz de conduzir corrente elétrica (porque gera íons livres).

- **Eletrólitos fortes:** dissociação praticamente completa (ácidos e bases fortes, a maioria dos sais solúveis).
- **Eletrólitos fracos:** dissociação parcial, um equilíbrio (ácidos e bases fracos — o objeto central da Unidade 3).
- **Não eletrólitos:** não se dissociam em íons (ex.: sacarose, glicerina) — a solução não conduz corrente de forma significativa.

### 1.4 Dissociação iônica e grau de dissociação

O grau de dissociação (α) mede a fração do soluto que efetivamente se dissocia em íons:

$$\alpha = \frac{\text{quantidade dissociada}}{\text{quantidade inicial}}$$

Para eletrólitos fortes, α ≈ 1 (dissociação completa, considerada total para fins de cálculo). Para eletrólitos fracos, α < 1 e **depende da concentração** — este conceito é retomado formalmente na Lei de diluição de Ostwald (Unidade 3), quando α passa a ser calculado a partir de Ka.

### 1.5 Atividade química vs. concentração

Em soluções reais (não infinitamente diluídas), os íons interagem eletrostaticamente entre si — um cátion "sente" a presença de ânions vizinhos, e vice-versa. Isso faz com que o comportamento efetivo dos íons em reações e equilíbrios seja um pouco diferente do que a concentração nominal sugeriria.

Para corrigir esse desvio, define-se a **atividade** (a) como a concentração "efetiva":

$$a = \gamma C$$

onde γ é o **coeficiente de atividade** e C é a concentração molar. Em soluções muito diluídas, γ → 1 e atividade ≈ concentração (é a aproximação usada, por simplicidade, em quase todos os cálculos de Ka, Kps e Kf das unidades seguintes — mas é importante que o aluno saiba que essa é uma aproximação, não uma verdade absoluta).

### 1.6 Força iônica e Lei de Debye-Hückel (tratamento introdutório)

A força iônica (I) quantifica a concentração total de carga elétrica em solução, considerando todos os íons presentes:

$$I = \frac{1}{2}\sum_i C_i Z_i^2$$

onde $C_i$ é a concentração do íon i e $Z_i$ sua carga. Íons com carga maior contribuem desproporcionalmente mais para I (por causa do termo ao quadrado) — um íon divalente pesa 4 vezes mais que um monovalente na mesma concentração.

A **Lei limite de Debye-Hückel** relaciona o coeficiente de atividade à força iônica (forma simplificada, válida para soluções diluídas, a 25 °C):

$$\log \gamma = -0{,}51\, Z^2 \sqrt{I}$$

Não é necessário que o aluno decore a equação para uso operacional constante — o essencial é entender a relação qualitativa: **quanto maior a força iônica do meio, mais o coeficiente de atividade se afasta de 1**, e mais a concentração nominal se afasta do comportamento "ideal" assumido nos cálculos simplificados.

### 1.7 Coeficiente de atividade

Resumo prático do que foi construído nas seções 1.5 e 1.6: γ é o fator de correção entre o mundo ideal (onde concentração = comportamento efetivo) e o mundo real (onde a presença de outros íons interfere). Essa ideia reaparece explicitamente no **efeito salino sobre a solubilidade** (Unidade 4) — é o mesmo fenômeno, aplicado a um caso concreto.

---

## 2. Aplicação analítica e farmacêutica

**Preparo e padronização de soluções.** Cálculo de massa/volume necessário para preparar uma solução de concentração conhecida; padronização (determinar a concentração real de uma solução por titulação contra um padrão primário) — habilidade operacional usada em toda a parte prática da disciplina.

**Diluições seriadas.** Uso da relação $C_1V_1 = C_2V_2$ para preparar séries de concentrações a partir de uma solução-estoque — técnica usada tanto em análise qualitativa (preparo de soluções-teste) quanto em contextos farmacêuticos (curvas de calibração, diluição de fármacos).

**Comportamento de íons em solução aquosa.** Base conceitual para tudo que vem depois: qualquer reação de identificação, qualquer equilíbrio ácido-base ou de solubilidade, começa com íons dissolvidos se comportando de acordo com o que foi construído nesta unidade.

**Por que a força iônica interfere em reações de identificação.** Meios com força iônica elevada (por exemplo, na presença de excesso de outros sais) podem alterar sutilmente a solubilidade de um precipitado de interesse analítico (efeito salino, antecipando a Unidade 4) ou deslocar ligeiramente valores de pH esperados — é um lembrete de que os cálculos simplificados (concentração ≈ atividade) têm limites.

**Relação com formas farmacêuticas líquidas.** Soluções, xaropes e outras formas líquidas dependem diretamente do domínio de unidades de concentração; a força iônica e a osmolaridade de soluções parenterais (isotonicidade) são aplicações diretas dos conceitos desta unidade em contexto farmacêutico.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Preparo de soluções em diferentes unidades de concentração**
Objetivo: calcular e preparar soluções de uma mesma substância expressas em mol/L, % (m/v) e ppm, reconhecendo a equivalência entre as unidades.
Procedimento resumido: a partir de uma concentração-alvo dada em uma unidade, calcular a massa necessária; preparar a solução em balão volumétrico; expressar o resultado nas demais unidades e conferir a consistência dos cálculos.

**Prática 2 — Diluições e verificação por titulação simples**
Objetivo: preparar uma diluição a partir de uma solução-estoque e confirmar experimentalmente a concentração obtida.
Procedimento resumido: calcular o volume de solução-estoque necessário para atingir a concentração-alvo após diluição ($C_1V_1=C_2V_2$); preparar a diluição; determinar a concentração real por titulação e comparar com o valor teórico.

**Prática 3 — Discussão de erros de preparo e propagação de incerteza**
Objetivo: identificar fontes de erro sistemático e aleatório no preparo de soluções e discutir como esses erros se propagam nos cálculos.
Procedimento resumido: a partir dos dados experimentais das Práticas 1 e 2, calcular o desvio entre valor teórico e valor obtido; discutir possíveis causas (erro de pesagem, aferição de vidraria, pureza do reagente); relacionar com a importância da padronização em análise quantitativa.

---

## 4. Pontos de conexão com as próximas unidades

- Concentração e o formalismo de equilíbrio são retomados diretamente na **Unidade 2 (Equilíbrio químico)**.
- Atividade e força iônica reaparecem no cálculo mais rigoroso de Ka/Kb (**Unidade 3**) e, de forma mais concreta, no efeito salino sobre a solubilidade (**Unidade 4**).
- Grau de dissociação (α) é formalizado quantitativamente na Lei de diluição de Ostwald (**Unidade 3**).

---
*Conteúdo completo — Unidade 1. Próxima revisão: ajustar exemplos numéricos conforme a bibliografia adotada na disciplina.*
