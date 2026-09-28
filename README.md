[README.md](https://github.com/user-attachments/files/32713615/README.md)
# 💰 Miniguia de Estudos: Finanças Pessoais para Iniciantes com NotebookLM

> Projeto do desafio da **DIO** sobre o uso da Inteligência Artificial como ferramenta de **aprendizagem ativa**: curadoria de fontes, engenharia de prompts, pensamento crítico e organização do conhecimento em um **Caderno Temático no NotebookLM**.

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Ferramenta](https://img.shields.io/badge/IA-NotebookLM-blue)
![Tema](https://img.shields.io/badge/tema-finanças%20pessoais-orange)

---

## 📑 Sumário

1. [Contexto e Objetivos](#-1-contexto-e-objetivos)
2. [Curadoria de Fontes](#-2-curadoria-de-fontes)
3. [Engenharia de Prompts e "Cicatrizes"](#-3-engenharia-de-prompts-e-cicatrizes)
4. [Miniguia de Estudo (Entrega Final)](#-4-miniguia-de-estudo-entrega-final)
5. [Estrutura do Repositório](#-5-estrutura-do-repositório)
6. [Aprendizados e Próximos Passos](#-6-aprendizados-e-próximos-passos)

---

## 🎯 1. Contexto e Objetivos

### Por que esse tema?

Escolhi **finanças pessoais em nível introdutório** porque é um assunto que afeta a vida de qualquer pessoa, mas que quase nunca é ensinado de forma estruturada. Muita gente começa a trabalhar, recebe o primeiro salário e não sabe como organizar o orçamento, por que o cartão de crédito é perigoso, o que é inflação ou onde guardar uma reserva de emergência.

Em vez de consumir conteúdo aleatório de redes sociais (com muita opinião e pouca fonte), decidi montar um caderno no **NotebookLM** usando apenas **materiais oficiais e gratuitos** de instituições públicas brasileiras: Banco Central, CVM e Tesouro Nacional. Assim, a IA responde **com base nas fontes que eu escolhi**, e eu consigo conferir cada resposta na origem.

### Objetivos de estudo

| # | Objetivo | Como vou saber que aprendi |
|---|----------|----------------------------|
| 1 | Entender como montar e acompanhar um **orçamento pessoal** | Consigo classificar minhas despesas e montar um orçamento mensal simples |
| 2 | Compreender **juros simples, juros compostos e inflação** | Consigo explicar por que dívidas crescem rápido e por que dinheiro parado perde valor |
| 3 | Saber usar o **crédito** de forma consciente | Consigo diferenciar crédito "bom" de crédito caro (rotativo, cheque especial) |
| 4 | Saber o que é e como formar uma **reserva de emergência** | Consigo calcular quanto preciso e onde deixar esse dinheiro |
| 5 | Conhecer os **primeiros investimentos de renda fixa** (poupança, CDB, Tesouro Direto) | Consigo comparar liquidez, risco e rentabilidade entre eles |
| 6 | Criar um **material de revisão reutilizável** | Tenho resumos, glossário e prompts prontos para revisar o tema quando precisar |

### Público-alvo do miniguia

Estudantes e jovens trabalhadores que estão começando a lidar com o próprio dinheiro e querem uma base sólida, com fontes confiáveis.

---

## 📚 2. Curadoria de Fontes

Selecionei **4 fontes abertas e gratuitas**, todas de instituições oficiais. Os PDFs foram baixados e enviados ao NotebookLM.

| # | Fonte | Instituição | Formato | Por que escolhi |
|---|-------|-------------|---------|-----------------|
| **[F1]** | [Caderno de Educação Financeira – Gestão de Finanças Pessoais](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) | Banco Central do Brasil | PDF | É a base do caderno: cobre relação com o dinheiro, orçamento, uso do crédito, consumo consciente, poupança e investimentos em linguagem simples |
| **[F2]** | [Glossário Simplificado de Termos Financeiros](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Informacoes_gerais/glossario_cidadania_financeira.pdf) | Banco Central do Brasil | PDF | Define termos do mercado financeiro em linguagem do dia a dia; ideal para montar o glossário final |
| **[F3]** | [Guia do Investidor – Tesouro Direto](https://www.tesourodireto.com.br/documentos/guia-do-investidor.htm) | Tesouro Nacional | PDF | Explica os títulos públicos (Selic, Prefixado, IPCA+), custos e como começar a investir com pouco |
| **[F4]** | [Livros CVM – Planejamento Financeiro Pessoal](https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm) | CVM / Portal do Investidor | PDF | Traz a visão de planejamento financeiro, perfil de investidor, risco x retorno e proteção contra fraudes |

📁 A lista também está em [`fontes/links-das-fontes.md`](fontes/links-das-fontes.md).

### Critérios de curadoria

- ✅ **Fonte oficial e neutra** — sem interesse em vender produto financeiro.
- ✅ **Acesso aberto e gratuito** — qualquer pessoa pode reproduzir o caderno.
- ✅ **Linguagem introdutória** — adequada ao nível de iniciante.
- ✅ **Complementaridade** — cada fonte cobre uma parte: comportamento (F1), vocabulário (F2), produto prático (F3) e planejamento/risco (F4).
- ❌ **Descartei** blogs de corretoras e vídeos de influenciadores, porque misturam educação com propaganda.

> ⚠️ **Atenção:** regras como alíquotas de imposto, limites de garantia e taxas mudam com o tempo. O miniguia foca nos **conceitos**; valores específicos devem sempre ser conferidos nos sites oficiais.

---

## 🧠 3. Engenharia de Prompts e "Cicatrizes"

Esta seção mostra **o raciocínio por trás do resultado**: as perguntas que fiz, como fui refinando os prompts e onde a IA me deu trabalho.

### 3.1 Estratégia geral

Organizei as perguntas em **4 camadas**, do mais amplo para o mais específico:

1. **Mapeamento** → descobrir o que as fontes cobrem.
2. **Compreensão** → explicar conceitos com exemplos.
3. **Conexão** → relacionar conceitos entre fontes diferentes.
4. **Verificação** → testar meu aprendizado e caçar erros da IA.

### 3.2 Perguntas estratégicas e evolução dos prompts

#### 🔹 Pergunta 1 — Mapeamento do conteúdo

**❌ Versão 1 (fraca):**
```
Resuma as fontes.
```
**Problema:** a resposta veio genérica, misturando tudo em um texto corrido, sem dizer o que vinha de qual fonte.

**✅ Versão 2 (refinada):**
```
Liste os principais temas abordados em cada fonte separadamente.
Para cada fonte, traga de 3 a 5 tópicos e indique em uma frase
qual é o foco principal dela. Use o formato de tabela.
```
**Resposta obtida (resumida):**

| Fonte | Foco principal | Tópicos |
|-------|----------------|---------|
| F1 | Comportamento e gestão do dinheiro no dia a dia | Relação com o dinheiro, orçamento, crédito e endividamento, consumo consciente, poupança e investimentos |
| F2 | Vocabulário financeiro em linguagem simples | Definições de termos como CDB, juros, spread, taxa Selic, CET, portabilidade |
| F3 | Investimento em títulos públicos | Tipos de títulos, rentabilidade, custos, liquidez, como começar |
| F4 | Planejamento financeiro de médio e longo prazo | Metas, perfil de investidor, risco x retorno, diversificação, fraudes |

**Referências citadas pela IA:** F1, F2, F3, F4.
**O que aprendi:** pedir **formato** e **separação por fonte** muda completamente a qualidade da resposta.

---

#### 🔹 Pergunta 2 — Orçamento pessoal

**❌ Versão 1:**
```
Como fazer um orçamento?
```
**Problema:** resposta correta, mas abstrata demais. Não dava para aplicar.

**✅ Versão 2:**
```
Com base apenas nas fontes, explique passo a passo como montar um
orçamento pessoal mensal. Depois, aplique os passos em um exemplo
de uma pessoa que ganha R$ 2.000 por mês, mora com a família e
tem gastos com transporte, celular e lazer.
```
**Resposta obtida (resumida):**
1. Registrar **todas as receitas** do mês.
2. Anotar **todas as despesas**, inclusive as pequenas do dia a dia.
3. Classificar as despesas em **fixas** (se repetem todo mês, como celular e transporte) e **variáveis** (mudam de valor, como lazer).
4. Comparar receitas e despesas: se sobra, há **superávit**; se falta, há **déficit**.
5. Definir metas e **reservar a poupança logo que o dinheiro entra**, e não com "o que sobrar".
6. Acompanhar mensalmente e ajustar.

No exemplo, a IA sugeriu listar os gastos fixos (transporte e celular), estimar os variáveis (lazer) e separar um valor para poupança antes de gastar com lazer. **Referências:** F1 (módulo de orçamento), F4.

**⚠️ Cicatriz:** na primeira tentativa do exemplo, a IA sugeriu a "regra 50-30-20" como se estivesse nas fontes. Perguntei *"Em qual fonte aparece a regra 50-30-20?"* e ela admitiu que **não estava nas fontes enviadas**. Lição: **sempre pedir a origem** quando algo parecer "bom demais".

---

#### 🔹 Pergunta 3 — Juros compostos e inflação

**❌ Versão 1:**
```
O que são juros compostos?
```
**Problema:** a IA trouxe só a definição, sem mostrar o efeito no tempo, que é justamente o ponto importante.

**✅ Versão 2:**
```
Explique a diferença entre juros simples e juros compostos como se
eu fosse iniciante. Mostre uma tabela comparando R$ 1.000 a 10% ao
mês durante 6 meses nos dois regimes. Depois, explique como isso se
aplica tanto a uma dívida no cartão quanto a um investimento.
```
**Resposta obtida (resumida):**

| Mês | Juros simples | Juros compostos |
|-----|---------------|-----------------|
| 0 | R$ 1.000,00 | R$ 1.000,00 |
| 1 | R$ 1.100,00 | R$ 1.100,00 |
| 2 | R$ 1.200,00 | R$ 1.210,00 |
| 3 | R$ 1.300,00 | R$ 1.331,00 |
| 4 | R$ 1.400,00 | R$ 1.464,10 |
| 5 | R$ 1.500,00 | R$ 1.610,51 |
| 6 | R$ 1.600,00 | R$ 1.771,56 |

Nos juros compostos, o juro de cada mês é calculado sobre o valor já acumulado ("juros sobre juros"). Isso **joga contra** quem tem dívida (o saldo do cartão cresce muito rápido) e **a favor** de quem investe por muito tempo. **Referências:** F1, F2.

**⚠️ Cicatriz:** a primeira tabela da IA tinha um **erro de arredondamento** no mês 5. Conferi na calculadora (`1000 × 1,1⁵ = 1610,51`) e pedi a correção. Lição: **IA não é calculadora confiável** — cálculos sempre devem ser verificados.

---

#### 🔹 Pergunta 4 — Crédito e endividamento

**✅ Prompt usado:**
```
Segundo as fontes, quais são as modalidades de crédito mais caras
para o consumidor e por quê? Explique também o que é o CET e por
que ele é mais importante que a taxa de juros anunciada.
```
**Resposta obtida (resumida):** as fontes apontam o **rotativo do cartão de crédito** e o **cheque especial** como modalidades de custo muito alto, que devem ser usadas apenas em emergência e pelo menor tempo possível. O **CET (Custo Efetivo Total)** reúne juros, tarifas, tributos e seguros; por isso é o número certo para **comparar ofertas de crédito**, e não só a taxa de juros. **Referências:** F1, F2.

**⚠️ Cicatriz:** perguntei *"qual é a taxa atual do rotativo?"* e a IA respondeu com um número. Porém as fontes são de anos anteriores. Refiz: *"Responda apenas se a informação estiver nas fontes e informe o ano da fonte."* — ela então explicou que **não havia taxa atualizada nas fontes**. Lição: **NotebookLM não navega na internet**; dados que mudam precisam ser buscados em sites oficiais.

---

#### 🔹 Pergunta 5 — Reserva de emergência

**❌ Versão 1:**
```
Onde colocar a reserva de emergência?
```
**Problema:** a pergunta induzia a IA a dar uma "recomendação de investimento", e a resposta ficou vaga.

**✅ Versão 2:**
```
Segundo as fontes, o que é uma reserva de emergência, para que ela
serve e quais características um investimento precisa ter para
guardar essa reserva? Compare poupança, CDB com liquidez diária e
Tesouro Selic usando os critérios liquidez, risco e rentabilidade.
Não faça recomendação; apenas compare.
```
**Resposta obtida (resumida):** a reserva serve para cobrir **imprevistos** (perda de renda, saúde, conserto urgente) sem recorrer a dívidas. O investimento ideal para ela precisa ter **alta liquidez** (resgate rápido), **baixo risco** e rentabilidade que, idealmente, **proteja da inflação**. A comparação:

| Critério | Poupança | CDB liquidez diária | Tesouro Selic |
|----------|----------|---------------------|---------------|
| Liquidez | Alta | Alta (se diária) | Alta (venda em dias úteis) |
| Risco | Baixo (garantia do FGC) | Baixo (garantia do FGC, dentro do limite) | Baixo (título do governo federal) |
| Rentabilidade | Regra própria, costuma ser menor | Geralmente atrelada ao CDI | Acompanha a taxa Selic |
| Imposto de Renda | Isenta para pessoa física | Tabela regressiva | Tabela regressiva |

**Referências:** F1, F3, F2.
**O que aprendi:** incluir **"não faça recomendação, apenas compare"** deixou a resposta mais objetiva e mais fiel às fontes.

---

#### 🔹 Pergunta 6 — Conexão entre fontes

**✅ Prompt usado:**
```
Relacione o conceito de "perfil de investidor" da fonte da CVM com
os tipos de títulos do Tesouro Direto. Que tipo de objetivo
combina com cada título? Cite as fontes de cada afirmação.
```
**Resposta obtida (resumida):**
- **Tesouro Selic** → objetivos de **curto prazo** e reserva de emergência, pela baixa oscilação.
- **Tesouro Prefixado** → objetivos com **data definida**, para quem quer saber a rentabilidade na hora da compra e pretende levar até o vencimento.
- **Tesouro IPCA+** → objetivos de **longo prazo** (ex.: aposentadoria), pois protege contra a inflação.
- O perfil (conservador, moderado, arrojado) indica **quanto de oscilação** a pessoa tolera; títulos prefixados e IPCA+ podem oscilar bastante se vendidos antes do vencimento (**marcação a mercado**). **Referências:** F3, F4.

**⚠️ Cicatriz:** a IA disse que "o Tesouro Direto não tem risco nenhum". Questionei com: *"Existe possibilidade de perda ao vender um título prefixado antes do vencimento? Cite o trecho."* A resposta corrigiu: **há risco de mercado** na venda antecipada. Lição: **desconfiar de frases absolutas** ("nunca", "sempre", "nenhum risco").

---

#### 🔹 Pergunta 7 — Verificação do aprendizado

**✅ Prompt usado:**
```
Crie 5 perguntas de múltipla escolha, de nível iniciante, sobre
orçamento, juros, crédito, reserva de emergência e Tesouro Direto.
Não mostre as respostas. Depois que eu responder, corrija e
explique citando as fontes.
```
**Resultado:** acertei 4 de 5. Errei a pergunta sobre **marcação a mercado**, o que mostrou que eu precisava revisar esse ponto. O NotebookLM corrigiu citando F3. Esse ciclo **perguntar → responder → corrigir** foi a parte mais útil do estudo ativo.

### 3.3 Resumo das "cicatrizes" (troubleshooting)

| Problema encontrado | Sintoma | Como resolvi |
|---------------------|---------|--------------|
| Respostas genéricas | Texto corrido e vago | Pedir **formato** (tabela, passo a passo) e **exemplo prático** |
| Informação fora das fontes | Regra 50-30-20 sem estar nos PDFs | Perguntar **"em qual fonte está isso?"** e usar "responda apenas com base nas fontes" |
| Dados desatualizados | Taxas e valores de anos anteriores | Pedir **o ano da fonte** e conferir números em sites oficiais |
| Erros de cálculo | Arredondamento errado na tabela | **Conferir na calculadora** e pedir correção |
| Afirmações absolutas | "Não tem risco nenhum" | Pedir o **trecho exato** da fonte e reformular a pergunta |
| Tom de recomendação | Resposta parecia conselho de investimento | Incluir **"não recomende, apenas compare"** |
| PDF grande e pesado | Respostas focavam só no início do documento | Perguntar **por capítulo/módulo** específico |

---

## 📘 4. Miniguia de Estudo (Entrega Final)

O miniguia completo está na pasta [`miniguia/`](miniguia/) e também resumido abaixo.

### 4.1 Resumos estruturados

#### 🧾 Módulo 1 — Orçamento pessoal
- **O que é:** registro organizado de tudo que entra (**receitas**) e sai (**despesas**) em um período, geralmente um mês.
- **Tipos de despesa:** **fixas** (aluguel, internet, transporte) e **variáveis** (lazer, alimentação fora de casa).
- **Resultado:** **superávit** (sobra dinheiro) ou **déficit** (falta dinheiro).
- **Regra de ouro:** **poupar primeiro**, gastar depois. Poupança não é "o que sobra".
- **Hábito-chave:** acompanhar todo mês e ajustar.

#### 📈 Módulo 2 — Juros e inflação
- **Juros:** o "preço do dinheiro no tempo". Quem empresta recebe; quem toma emprestado paga.
- **Juros simples:** calculados sempre sobre o valor inicial.
- **Juros compostos:** calculados sobre o valor acumulado ("juros sobre juros"). Pesam contra quem deve e a favor de quem investe.
- **Inflação:** aumento geral dos preços, que reduz o **poder de compra**. Dinheiro parado perde valor.
- **Rentabilidade real:** o quanto o investimento rendeu **acima da inflação**.

#### 💳 Módulo 3 — Crédito consciente
- Crédito **não é renda extra**: é dinheiro emprestado que volta com juros.
- **Mais caros:** rotativo do cartão e cheque especial → usar só em emergência e por pouco tempo.
- **Compare pelo CET**, não só pela taxa de juros.
- **Parcelamento:** conferir se o total das parcelas cabe no orçamento de todos os meses.
- **Endividamento x inadimplência:** ter dívida não é necessariamente ruim; o problema é **não conseguir pagar**.

#### 🛟 Módulo 4 — Reserva de emergência
- **Para que serve:** cobrir imprevistos sem precisar de empréstimo.
- **Quanto guardar:** calculado com base no **custo de vida mensal** multiplicado por um número de meses (as referências costumam falar em alguns meses de despesas; o número ideal depende da estabilidade da renda).
- **Onde guardar:** aplicação com **alta liquidez + baixo risco**.
- **Ordem sugerida pelas fontes:** organizar orçamento → sair das dívidas caras → formar reserva → investir para outros objetivos.

#### 🏦 Módulo 5 — Primeiros investimentos (renda fixa)
- **Tripé de avaliação:** **rentabilidade**, **risco** e **liquidez** — não existe investimento com o melhor dos três ao mesmo tempo.
- **Poupança:** simples e isenta de IR, mas geralmente com rendimento menor.
- **CDB:** título emitido por banco; costuma render um percentual do **CDI**; conta com garantia do **FGC** dentro do limite.
- **Tesouro Direto:** títulos do governo federal que podem ser comprados com pouco dinheiro:
  - **Tesouro Selic** → acompanha a Selic; bom para curto prazo e reserva.
  - **Tesouro Prefixado** → taxa definida na compra.
  - **Tesouro IPCA+** → inflação + taxa fixa; indicado para longo prazo.
- **Marcação a mercado:** o preço do título muda diariamente; vender antes do vencimento pode gerar ganho **ou perda**.
- **Perfil de investidor:** conservador, moderado ou arrojado — define quanta oscilação a pessoa aceita.
- **Alerta de fraude:** promessa de rendimento alto, garantido e rápido é sinal de golpe.

📄 Versão completa: [`miniguia/resumos.md`](miniguia/resumos.md)

### 4.2 Glossário

| Termo | Definição simples |
|-------|-------------------|
| **Orçamento** | Planejamento de receitas e despesas de um período |
| **Receita** | Todo dinheiro que entra (salário, renda extra) |
| **Despesa fixa** | Gasto que se repete todo mês com valor parecido |
| **Despesa variável** | Gasto que muda de valor ou nem sempre acontece |
| **Superávit / Déficit** | Sobra / falta de dinheiro ao final do período |
| **Juros** | Valor pago pelo uso de dinheiro emprestado, ou recebido por emprestar |
| **Juros compostos** | Juros calculados sobre o valor já acrescido de juros anteriores |
| **Inflação** | Aumento generalizado dos preços ao longo do tempo |
| **IPCA** | Índice oficial de inflação do Brasil, calculado pelo IBGE |
| **Poder de compra** | Quantidade de bens e serviços que o dinheiro consegue comprar |
| **Taxa Selic** | Taxa básica de juros da economia, definida pelo Copom/Banco Central |
| **CDI** | Taxa de referência de empréstimos entre bancos; base de muitos investimentos |
| **CET** | Custo Efetivo Total: soma de juros, tarifas, impostos e seguros de um crédito |
| **Rotativo** | Crédito automático quando a fatura do cartão não é paga integralmente |
| **Cheque especial** | Limite de crédito pré-aprovado na conta corrente |
| **Inadimplência** | Atraso ou falta de pagamento de uma dívida |
| **Reserva de emergência** | Dinheiro guardado para imprevistos, de fácil acesso |
| **Liquidez** | Facilidade e rapidez para transformar um investimento em dinheiro |
| **Rentabilidade** | Retorno obtido por um investimento em um período |
| **Rentabilidade real** | Rentabilidade descontada a inflação |
| **Risco** | Possibilidade de o resultado ser diferente do esperado, inclusive com perda |
| **Renda fixa** | Investimento cujas regras de remuneração são definidas na aplicação |
| **Renda variável** | Investimento cujo retorno não é conhecido previamente (ex.: ações) |
| **CDB** | Certificado de Depósito Bancário: empréstimo que o investidor faz ao banco |
| **FGC** | Fundo Garantidor de Créditos: protege o investidor em certos produtos, até um limite, se a instituição quebrar |
| **Tesouro Direto** | Programa do Tesouro Nacional para venda de títulos públicos a pessoas físicas |
| **Marcação a mercado** | Atualização diária do preço de um título conforme as condições do mercado |
| **Vencimento** | Data em que o título é pago integralmente ao investidor |
| **Perfil de investidor** | Classificação de quanto risco uma pessoa aceita correr (conservador, moderado, arrojado) |
| **Diversificação** | Distribuir o dinheiro entre diferentes investimentos para reduzir riscos |
| **Tabela regressiva de IR** | Regra em que o imposto sobre o rendimento diminui quanto mais tempo o dinheiro fica aplicado |

📄 Versão completa: [`miniguia/glossario.md`](miniguia/glossario.md)

### 4.3 Prompts reutilizáveis para revisão

Prompts prontos para colar no NotebookLM (ou em outra IA com as mesmas fontes) sempre que eu quiser revisar o tema:

| Objetivo | Prompt |
|----------|--------|
| 🗺️ Visão geral | `Liste os principais temas de cada fonte separadamente, com 3 a 5 tópicos e o foco de cada uma, em formato de tabela.` |
| 🧒 Explicar simples | `Explique [CONCEITO] como se eu tivesse 15 anos, usando um exemplo do dia a dia e citando a fonte.` |
| 🔢 Exemplo numérico | `Crie um exemplo numérico sobre [CONCEITO] com valores simples e mostre o cálculo passo a passo.` |
| ⚖️ Comparar | `Compare [A] e [B] usando os critérios liquidez, risco e rentabilidade em uma tabela. Não faça recomendação.` |
| 🔗 Conectar fontes | `Relacione o que a fonte [X] diz sobre [TEMA] com o que a fonte [Y] diz. Onde elas concordam e onde se complementam?` |
| 🕵️ Checar origem | `Em qual fonte e trecho aparece a afirmação "[FRASE]"? Se não estiver nas fontes, diga claramente.` |
| 🧪 Quiz | `Crie 5 perguntas de múltipla escolha sobre [TEMA]. Não mostre as respostas; corrija depois que eu responder, citando as fontes.` |
| 🃏 Flashcards | `Gere 10 flashcards no formato Pergunta / Resposta sobre [TEMA], com respostas de no máximo 2 linhas.` |
| 🚫 Mitos | `Quais erros comuns ou mitos sobre [TEMA] as fontes ajudam a desmentir? Cite o trecho.` |
| 🧭 Aplicar na vida | `Com base nas fontes, monte um checklist de 5 passos para eu aplicar [TEMA] no próximo mês.` |
| 📅 Revisão rápida | `Faça um resumo de revisão de 10 linhas sobre [TEMA] com os pontos que mais caem em confusão.` |

📄 Versão para copiar e colar: [`prompts/prompts-reutilizaveis.md`](prompts/prompts-reutilizaveis.md)

---

## 🗂️ 5. Estrutura do Repositório

```
miniguia-financas-notebooklm/
├── README.md                      ← documento principal (este arquivo)
├── fontes/
│   └── links-das-fontes.md        ← curadoria com links e descrição
├── miniguia/
│   ├── resumos.md                 ← resumos completos por módulo
│   └── glossario.md               ← glossário em ordem alfabética
└── prompts/
    └── prompts-reutilizaveis.md   ← prompts prontos para revisão
```

---

## 🚀 6. Aprendizados e Próximos Passos

### O que aprendi sobre IA
- O NotebookLM é poderoso porque **responde com base nas fontes que eu escolho**, mas ainda pode **extrapolar**; checar a origem é obrigatório.
- A qualidade da resposta depende muito da **clareza do prompt**: contexto + formato + limite ("apenas com base nas fontes").
- IA ajuda a **estudar ativamente** quando eu uso ela para **me testar**, e não só para ler resumos.

### O que aprendi sobre finanças
- Organizar o orçamento vem **antes** de pensar em investir.
- Juros compostos são o maior aliado de quem investe e o maior inimigo de quem se endivida.
- Não existe investimento perfeito: sempre há uma troca entre **risco, liquidez e rentabilidade**.

### Próximos passos
- [ ] Adicionar uma fonte sobre **renda variável** (ações e fundos) em um segundo caderno.
- [ ] Criar uma **planilha de orçamento** aplicando o Módulo 1.
- [ ] Gerar o **resumo em áudio** do NotebookLM e anexar o link ao repositório.
- [ ] Revisar o miniguia a cada 3 meses usando os prompts da seção 4.3.

---

> ⚠️ **Aviso:** este material tem finalidade exclusivamente **educacional** e não constitui recomendação de investimento. Regras, taxas e limites podem mudar; consulte sempre as fontes oficiais.

📌 Projeto desenvolvido para o desafio de **IA como ferramenta de aprendizagem** da [DIO](https://www.dio.me/).
