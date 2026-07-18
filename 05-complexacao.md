# Unidade 5 — Complexação

**Carga horária:** 6 h/a teóricas + 4 h/a práticas (10 h/a)

## Objetivo da unidade

Explicar mascaramento, dissolução seletiva e identificação de íons via formação de complexos coloridos. Conceitualmente, esta unidade não introduz um tipo novo de química — é a definição de Lewis para ácidos e bases (Unidade 3) aplicada de forma sistemática, com o mesmo formalismo de constante de equilíbrio da Unidade 2.

---

## 1. Fundamentos físico-químicos

### 1.1 Íons complexos: estrutura, ligantes, número de coordenação

Um íon complexo é formado por um íon metálico central (o **ácido de Lewis**, aceptor de par de elétrons) ligado a um ou mais **ligantes** (as **bases de Lewis**, doadoras de par de elétrons) por ligações covalentes coordenadas. Vale reforçar explicitamente: isso **é** ácido-base de Lewis, na prática — o aluno que entendeu a seção 1.1 da Unidade 3 já entende a essência desta unidade.

$$Cu^{2+} + 4NH_3 \rightleftharpoons [Cu(NH_3)_4]^{2+}$$

Aqui, Cu²⁺ é o ácido de Lewis; NH₃, o ligante, é a base de Lewis.

Classificação de ligantes por número de pontos de ligação com o metal:

- **Monodentados:** ligam-se por um único ponto (H₂O, NH₃, Cl⁻, CN⁻, OH⁻).
- **Polidentados (quelantes):** ligam-se por dois ou mais pontos simultaneamente ao mesmo metal, formando um anel (o EDTA, hexadentado, é o exemplo de referência — seção 1.5).

O **número de coordenação** é a quantidade de ligações do metal central com os ligantes — mais comumente 2, 4 ou 6, associados a geometrias características (linear, tetraédrica ou quadrática plana, octaédrica). Tratamento aqui é introdutório: a justificativa geométrica detalhada (teoria do campo cristalino) não é objetivo desta disciplina.

### 1.2 Constante de formação (Kf) e constante de instabilidade

A formação de um complexo é um equilíbrio como qualquer outro (Unidade 2), com sua própria constante:

$$M + nL \rightleftharpoons ML_n \qquad K_f = \frac{[ML_n]}{[M][L]^n}$$

Kf é chamada **constante de formação** (ou de estabilidade). O inverso do processo — a dissociação do complexo de volta a metal livre e ligante — tem constante de instabilidade:

$$K_{inst} = \frac{1}{K_f}$$

Quanto **maior o Kf**, mais estável é o complexo, e mais deslocado para a direita está o equilíbrio de formação (mesma lógica de "K grande = produto favorecido" já vista na Unidade 2).

Para complexos que se formam em etapas (adição sucessiva de ligantes), existem constantes de formação sucessivas (K₁, K₂, ..., Kₙ) e uma constante de formação global (β = K₁ × K₂ × ... × Kₙ) — suficiente que o aluno reconheça que a Kf usada nos cálculos desta disciplina normalmente já é a constante global.

### 1.3 Estabilidade de complexos — fatores que influenciam

- **Densidade de carga do íon metálico:** cátions menores e mais carregados tendem a formar complexos mais estáveis (maior atração eletrostática pelo ligante).
- **Efeito quelato:** ligantes polidentados formam complexos muito mais estáveis do que o equivalente em ligantes monodentados separados, mesmo com a mesma "força" de ligação individual — o motivo é essencialmente entrópico (um ligante polidentado substitui várias moléculas de água coordenadas de uma só vez, aumentando a desordem do sistema). É por isso que o EDTA é tão eficaz.
- **pH do meio:** muitos ligantes (inclusive o próprio EDTA) são bases fracas — em meio ácido, ficam protonados e perdem disponibilidade para complexar o metal. Esse é mais um ponto de contato direto com a Unidade 3: a eficácia de um agente complexante depende do controle de pH.

### 1.4 Efeito da complexação sobre a solubilidade

Adicionar um agente complexante a um precipitado pouco solúvel "sequestra" o cátion metálico livre em solução, deslocando (Le Chatelier, Unidade 2) o equilíbrio de solubilidade (Unidade 4) no sentido da dissolução:

$$AgCl_{(s)} \rightleftharpoons Ag^+ + Cl^- \qquad Ag^+ + 2NH_3 \rightleftharpoons [Ag(NH_3)_2]^+$$

Somando os dois equilíbrios, o AgCl se dissolve em excesso de amônia porque o Ag⁺ livre é continuamente removido da solução na forma do complexo solúvel. Este é exatamente o mecanismo por trás da "dissolução seletiva de precipitados" mencionada na Unidade 4 — não é um fenômeno novo, é o encontro dos dois equilíbrios (Kps e Kf) tratados separadamente até aqui.

### 1.5 Agentes quelantes (EDTA como referência)

O EDTA (ácido etilenodiaminotetracético) é um ligante hexadentado — forma complexos 1:1 extremamente estáveis com praticamente qualquer cátion metálico, independentemente da carga. Essa característica o torna:

- A base das **titulações complexométricas** (seção 2).
- Um aditivo farmacêutico comum, usado para sequestrar traços de íons metálicos que catalisariam reações de degradação oxidativa em formulações (conexão direta com a **Unidade 7** — estabilidade de medicamentos).

---

## 2. Aplicação analítica e farmacêutica

**Mascaramento de íons interferentes.** Quando um cátion interferente atrapalharia a identificação de outro (por exemplo, formando precipitado ou cor semelhante), adiciona-se um agente complexante que se liga seletivamente ao interferente, mantendo-o solúvel e "invisível" à reação de identificação, sem afetar o cátion de interesse.

**Dissolução de precipitados por formação de complexo solúvel.** Aplicação direta da seção 1.4 — usada tanto para redissolver um precipitado formado por engano quanto como etapa deliberada de separação na marcha analítica (o precipitado que se dissolve em excesso de ligante se distingue do que permanece insolúvel, funcionando como teste diferencial).

**Identificação de cátions por complexos coloridos característicos.** Muitas reações de identificação clássicas são, na verdade, formação de complexos com cor diagnóstica:

- Fe³⁺ + SCN⁻ → complexo vermelho-sangue $[Fe(SCN)]^{2+}$
- Cu²⁺ + excesso de NH₃ → complexo azul intenso $[Cu(NH_3)_4]^{2+}$
- Ni²⁺ + dimetilglioxima → precipitado vermelho característico

**Titulação complexométrica.** O EDTA é titulante padrão para determinar a concentração de cátions metálicos em solução (por exemplo, dureza da água — Ca²⁺/Mg²⁺ — ou doseamento de metais em formulações farmacêuticas), usando indicadores metalocrômicos (como o Negro de Eriocromo T) que mudam de cor quando o metal é capturado pelo EDTA em vez do indicador.

**Relevância farmacêutica.** Além do papel como reagente analítico, EDTA e outros quelantes são usados como **conservantes/estabilizantes** em formulações — sequestrando metais traço que catalisariam oxidação do princípio ativo (elo direto com a cinética de degradação da Unidade 7).

---

## 3. Atividades práticas sugeridas

**Prática 1 — Formação de complexo colorido para identificação de um cátion**
Objetivo: identificar um cátion (ex.: Fe³⁺ ou Cu²⁺) por meio da cor característica do complexo formado.
Procedimento resumido: adicionar o reagente complexante à solução-teste; observar e registrar a cor formada; comparar com padrão de referência.

**Prática 2 — Dissolução de precipitado por adição de agente complexante**
Objetivo: observar a dissolução de um precipitado (ex.: AgCl) pela adição de um agente complexante (ex.: NH₃ em excesso).
Procedimento resumido: formar o precipitado; adicionar o agente complexante gota a gota até dissolução completa; discutir o mecanismo (seção 1.4) e comparar com a dissolução por pH vista na Unidade 4.

**Prática 3 — Mascaramento de interferente em mistura de íons**
Objetivo: identificar um cátion em presença de outro que normalmente interferiria na reação, usando um agente mascarante seletivo.
Procedimento resumido: preparar mistura dos dois cátions; adicionar o agente mascarante para o interferente; realizar o teste de identificação do cátion de interesse e confirmar ausência de interferência.

---

## 4. Pontos de conexão com as próximas unidades

- A complexação é, na essência, ácido-base de Lewis — elo direto com a **Unidade 3**.
- A dissolução de precipitados por complexação é o mesmo fenômeno de deslocamento de equilíbrio de solubilidade da **Unidade 4**, agora com um segundo equilíbrio (Kf) somado ao Kps.
- EDTA e outros quelantes como estabilizantes reaparecem na discussão de estabilidade de medicamentos (**Unidade 7**).
- Mascaramento e dissolução seletiva por complexação são usados extensivamente na marcha analítica sistemática (**Unidade 9**) para separar e confirmar cátions.

---
*Conteúdo completo — Unidade 5. Próxima revisão: ajustar exemplos de complexos coloridos conforme os reagentes disponíveis no laboratório da instituição.*
