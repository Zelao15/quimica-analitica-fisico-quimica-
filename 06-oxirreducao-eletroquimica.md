# Unidade 6 — Oxirredução e eletroquímica

**Carga horária:** 7 h/a teóricas + 4 h/a práticas (11 h/a)

## Objetivo da unidade

Fundamentar reações de identificação baseadas em transferência de elétrons e introduzir aplicações farmacêuticas de eletroquímica — em especial a estabilidade oxidativa de medicamentos, retomada com profundidade na Unidade 7.

---

## 1. Fundamentos físico-químicos

### 1.1 Número de oxidação e balanceamento de reações redox

Reação de oxirredução é toda reação com transferência de elétrons: **oxidação** é perda de elétrons (aumento do número de oxidação, Nox); **redução** é ganho de elétrons (diminuição do Nox). Um processo não ocorre sem o outro — todo elétron perdido por uma espécie é ganho por outra.

O balanceamento de equações redox mais confiável para fins analíticos é o **método das semirreações (íon-elétron)**:

1. Separar a reação em duas semirreações (oxidação e redução).
2. Balancear massa (átomos) e depois carga (elétrons) em cada semirreação.
3. Igualar o número de elétrons perdidos e ganhos multiplicando as semirreações pelos fatores necessários.
4. Somar as semirreações, cancelando os elétrons.

Esse método é o mesmo usado depois para deduzir a equação de Nernst e escrever a notação de pilhas (seções 1.4 e 1.5).

### 1.2 Potencial de redução padrão (E°)

O potencial de redução padrão mede a tendência de uma espécie se reduzir (ganhar elétrons), medido em relação ao eletrodo padrão de hidrogênio (E° = 0 V, por convenção). Quanto **mais positivo o E°**, maior a tendência da espécie de se reduzir — ou seja, maior seu poder como **agente oxidante**.

Tabelas de potenciais padrão permitem prever a direção espontânea de uma reação redox: a espécie com E° de redução mais positivo tende a se reduzir (oxidando a outra espécie, que tem E° mais baixo).

### 1.3 Espontaneidade de reações redox

$$E°_{cel} = E°_{catodo (redução)} - E°_{anodo (oxidação)}$$

Se E°cel > 0, a reação é espontânea como escrita. A relação com a energia livre de Gibbs (retomando a Unidade 2 e antecipando a Unidade 7) é:

$$\Delta G° = -nFE°_{cel}$$

onde n é o número de elétrons transferidos e F é a constante de Faraday. Como ΔG° também se relaciona com K ($\Delta G° = -RT\ln K$), existe uma ponte direta entre **potencial padrão, energia livre e constante de equilíbrio** — três formas de expressar a mesma informação sobre espontaneidade. O tratamento termodinâmico completo (ΔH, ΔS, ΔG) é aprofundado na Unidade 7; aqui, o essencial é que o aluno veja que E° não é um número isolado, é espontaneidade expressa em volts.

### 1.4 Equação de Nernst

O potencial de um sistema redox depende não só do E° (condição padrão, 1 mol/L, 25 °C) mas também das concentrações reais das espécies envolvidas:

$$E = E° - \frac{RT}{nF}\ln Q$$

que a 25 °C se simplifica para:

$$E = E° - \frac{0{,}0592}{n}\log Q$$

onde Q é o quociente de reação (mesmo conceito da Unidade 2, agora aplicado à reação redox). Essa equação é a base da **potenciometria** como técnica analítica (seção 2): medir potencial permite calcular concentração de uma espécie em solução.

### 1.5 Pilhas e células eletroquímicas (introdução)

Uma célula galvânica (pilha) converte energia química de uma reação redox espontânea em energia elétrica: a oxidação ocorre no **ânodo**, a redução no **cátodo**, e os elétrons fluem pelo circuito externo do ânodo para o cátodo (uma ponte salina ou membrana porosa mantém a neutralidade elétrica das soluções). Notação convencional:

$$\text{ânodo} \mid \text{solução do ânodo} \,\|\, \text{solução do cátodo} \mid \text{cátodo}$$

Distinção rápida: célula **galvânica** (reação espontânea, gera corrente) vs. célula **eletrolítica** (corrente externa força uma reação não espontânea) — o tratamento aqui é introdutório, focado no conceito, não em eletrólise industrial.

### 1.6 Séries de reatividade / tabela de potenciais

Uma tabela ordenada de potenciais padrão de redução funciona como "mapa" de espontaneidade: qualquer espécie na tabela pode, em princípio, oxidar qualquer espécie abaixo dela (com E° menor). A série de reatividade de metais (usada para prever se um metal desloca outro de uma solução de seus íons) é um caso particular dessa mesma tabela.

---

## 2. Aplicação analítica e farmacêutica

**Reações de identificação por oxirredução.** Muitos testes clássicos de identificação são reações redox: identificação de haletos (Cl⁻, Br⁻, I⁻) por oxidação seletiva e extração da cor característica do halogênio livre em solvente orgânico; identificação de nitrato/nitrito pelo "teste do anel marrom" (redução de nitrato a NO, que forma um complexo marrom com Fe²⁺ em meio ácido).

**Uso de agentes oxidantes/redutores em reações de reconhecimento.** Reagentes como permanganato de potássio (KMnO₄) e dicromato são usados tanto como oxidantes de teste quanto como titulantes em análises volumétricas de óxido-redução.

**Potenciometria como técnica analítica.** A equação de Nernst (seção 1.4) é o fundamento de eletrodos íon-seletivos — inclusive o eletrodo de vidro do pHmetro usado na Unidade 3 é, na essência, um eletrodo cujo potencial responde à concentração de H⁺ segundo Nernst. Vale fazer essa conexão explícita: o instrumento que o aluno já usou na prática de tampão (Unidade 3) funciona pelo princípio construído agora.

**Aplicações farmacêuticas.** Muitos fármacos são susceptíveis a degradação oxidativa (grupos fenólicos, catecolaminas, entre outros). Para proteger essas moléculas, formulações incluem:

- **Antioxidantes** (ácido ascórbico, metabissulfito de sódio, tocoferol) — espécies que se oxidam preferencialmente, "sacrificando-se" no lugar do princípio ativo.
- **Agentes quelantes** (EDTA — retomando a Unidade 5) — sequestram traços de metais que catalisariam a oxidação.
- **Controle de pH e embalagem** — reduzindo a exposição a condições que favorecem a oxidação.

Essa discussão se conecta diretamente com a cinética de degradação e estabilidade de medicamentos, tratada com profundidade na **Unidade 7**.

---

## 3. Atividades práticas sugeridas

**Prática 1 — Reação de identificação envolvendo oxirredução (teste de halogenetos)**
Objetivo: identificar haletos em solução por reação de oxidação seletiva.
Procedimento resumido: adicionar agente oxidante à amostra contendo haleto; extrair com solvente orgânico apropriado; observar a cor característica do halogênio liberado e relacionar com a identidade do haleto original.

**Prática 2 — Montagem simples de pilha e medição de potencial**
Objetivo: montar uma célula galvânica simples (ex.: Cu/Zn) e medir seu potencial, comparando com o valor teórico calculado a partir da tabela de E°.
Procedimento resumido: montar os dois eletrodos com ponte salina; medir a diferença de potencial com multímetro; calcular E°cel teórico e comparar com o valor medido; discutir eventuais desvios.

**Prática 3 — Discussão de agentes antioxidantes usados em formulações**
Objetivo: relacionar o conceito de agente redutor com o papel prático de antioxidantes em formulações farmacêuticas.
Procedimento resumido: atividade demonstrativa ou de discussão dirigida, comparando a degradação (por exemplo, mudança de cor por oxidação) de uma solução-modelo com e sem adição de antioxidante.

---

## 4. Pontos de conexão com as próximas unidades

- A relação E°–ΔG–K é retomada e integrada ao tratamento termodinâmico completo na **Unidade 7**.
- Antioxidantes e quelantes como estratégia de estabilização reaparecem na discussão de estabilidade de medicamentos (**Unidade 7**) e retomam diretamente o EDTA da **Unidade 5**.
- Reações redox de identificação são incorporadas à marcha analítica sistemática (**Unidade 9**).

---
*Conteúdo completo — Unidade 6. Próxima revisão: ajustar exemplos e reagentes conforme disponibilidade no laboratório da instituição.*
