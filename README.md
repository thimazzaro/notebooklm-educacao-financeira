# 📚 NotebookLM — Caderno Temático: Educação Financeira Pessoal

> **Projeto de Aprendizagem Ativa com IA** | Engenharia de Prompts aplicada a Finanças Pessoais

---

## 1. Contexto e Objetivos

### 🎯 Assunto Escolhido
**Educação Financeira Pessoal para Iniciantes**

O tema escolhido foi *Educação Financeira Pessoal*, com foco nos fundamentos que qualquer pessoa precisa dominar antes de investir: controle de gastos, formação de reserva de emergência, conceitos de juros compostos e uma introdução ao universo dos investimentos de renda fixa no Brasil.

A escolha se justifica pela alta relevância prática: segundo o Banco Central, mais de 70% dos brasileiros não possuem reserva de emergência, e a maioria das decisões financeiras ruins decorrem de lacunas conceituais básicas.

### 📌 Objetivos de Estudo

| # | Objetivo | Indicador de Conclusão |
|---|----------|----------------------|
| 1 | Compreender o ciclo orçamento → reserva → investimento | Conseguir explicar sem consultar materiais |
| 2 | Dominar o conceito de juros compostos e sua fórmula | Resolver ao menos 3 simulações numéricas |
| 3 | Distinguir os principais produtos de renda fixa (Tesouro, CDB, LCI/LCA) | Montar uma tabela comparativa própria |
| 4 | Desenvolver um vocabulário financeiro de 30+ termos | Preencher o glossário deste caderno |
| 5 | Criar prompts reutilizáveis para revisão futura | Biblioteca com 10+ prompts validados |

---

## 2. Curadoria de Fontes

Foram selecionadas **5 fontes abertas**, priorizando materiais de instituições oficiais ou acadêmicas brasileiras.

### 📂 Fontes Utilizadas no NotebookLM

| # | Título | Tipo | Instituição | Link |
|---|--------|------|-------------|------|
| F1 | Caderno de Educação Financeira — Gestão de Finanças Pessoais | PDF | Banco Central do Brasil (BCB) | [acessar](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) |
| F2 | Tesouro Direto — Guia do Investidor | PDF | Tesouro Nacional | [acessar](https://www.tesourodireto.com.br/data/files/CF/65/20/66/B4A6A710E2FAA0D6793DC1A8/Tesouro-Direto_Guia-do-Investidor.pdf) |
| F3 | Série Cidadania Financeira nº 7 — Investimentos | PDF | BCB / ENEF | [acessar](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Serie_Cidadania_Financeira/serie_cidadania_financeira_07.pdf) |
| F4 | Como se Planejar Financeiramente (Guia Prático) | Texto/PDF | CVM Educacional | [acessar](https://www.investidor.gov.br/portaldoinvestidor/export/sites/portaldoinvestidor/publicacao/Livro/livro_TOP_ed02_2015.pdf) |
| F5 | Relatório de Cidadania Financeira 2021 | PDF | Banco Central do Brasil | [acessar](https://www.bcb.gov.br/content/publicacoes/relatorio_cidadania_financeira/rcif2021.pdf) |

### 🔍 Critérios de Seleção das Fontes
- ✅ Fontes abertas e gratuitas (sem paywall)
- ✅ Instituições com credibilidade (BCB, Tesouro Nacional, CVM)
- ✅ Linguagem acessível para iniciantes
- ✅ Conteúdo atualizado (a partir de 2015)
- ✅ Cobertura complementar dos subtemas (orçamento, investimento, contexto macro)

---

## 3. Engenharia de Prompts e "Cicatrizes"

### 3.1 Perguntas Estratégicas Elaboradas

#### 🔵 Nível 1 — Recordar / Compreender
```
P1: "O que é uma reserva de emergência e por que ela deve ser a
    primeira prioridade financeira de qualquer pessoa?"
P2: "Explique a fórmula dos juros compostos com um exemplo
    prático usando R$ 1.000 a 1% ao mês por 12 meses."
```

#### 🟡 Nível 2 — Aplicar / Analisar
```
P3: "Compare CDB, Tesouro Selic e LCI em termos de liquidez,
    risco e tributação para um investidor iniciante."
P4: "Como o efeito do tempo afeta o crescimento de um investimento?
    Mostre a diferença entre começar aos 25 versus 35 anos, investindo R$ 300/mês."
```

#### 🔴 Nível 3 — Avaliar / Criar
```
P5: "Com base nas fontes do caderno, qual seria uma estratégia financeira
    para alguém que recebe R$ 3.000/mês e quer começar a investir?"
P6: "Quais são as armadilhas mais comuns descritas no material para iniciantes?"
```

---

### 3.2 Variações de Prompts Testados

| Versão | Prompt | Resultado | Avaliação |
|--------|--------|-----------|-----------|
| v1 | "O que é reserva de emergência?" | Resposta genérica, sem referência às fontes | ⭐⭐ |
| v2 | "Com base nos documentos do BCB no caderno, o que é reserva de emergência?" | Resposta com referência ao Caderno BCB, citou 3-6 meses | ⭐⭐⭐⭐ |
| v3 | "Resuma em bullet points os passos práticos para montar uma reserva, conforme as fontes oficiais do caderno." | Resposta estruturada, 5 passos claros, com fontes | ⭐⭐⭐⭐⭐ |

### 3.3 Dificuldades Encontradas (Troubleshooting)

- ⚠️ **Problema 1:** Respostas sem ancoragem nas fontes → Solução: sempre incluir "com base nos documentos do meu caderno"
- ⚠️ **Problema 2:** Respostas longas e difusas → Solução: especificar o formato desejado
- ⚠️ **Problema 3:** Confusão CDI vs Selic → Solução: pergunta específica de diferenciação
- ⚠️ **Problema 4:** Ausência de exemplos numéricos → Solução: incluir "use um exemplo numérico com valores em reais"

---

## 4. Miniguia de Estudo — Entrega Final

### 4.1 Resumos Estruturados

**Módulo 1 — Orçamento:** Gastos essenciais ≤50% | Lazer ≤30% | Poupança ≥20%

**Módulo 2 — Reserva de Emergência:** CLT: 3-6 meses | Autônomo: 6-12 meses | Guardar em Tesouro Selic ou CDB com liquidez diária

**Módulo 3 — Juros Compostos:** M = C × (1 + i)ⁿ | R$1.000 a 1%/mês por 60 meses = R$1.816,70

**Módulo 4 — Renda Fixa:** Poupança < CDB < Tesouro Selic < LCI/LCA (isentos IR)

### 4.2 Glossário

| Termo | Definição |
|-------|-----------|
| Liquidez | Velocidade de conversão em dinheiro sem perda |
| CDI | Taxa de referência de investimentos de renda fixa |
| Selic | Taxa básica de juros da economia brasileira |
| IPCA | Principal índice de inflação oficial do Brasil |
| FGC | Garante até R$ 250.000 por CPF por instituição |
| Juros Compostos | Juros calculados sobre capital + juros acumulados |
| IR Regressivo | 22,5% (até 180d) → 15% (acima de 720d) |
| Tesouro Direto | Plataforma do gov. federal para compra de títulos públicos |
| CDB | Título emitido por bancos para captação de recursos |
| LCI/LCA | Títulos isentos de IR para pessoas físicas |
| Aporte | Novo depósito em investimento existente |
| Marcação a Mercado | Atualização diária do valor do título |

### 4.3 Prompts Reutilizáveis

```
PROMPT-01: "Com base nos documentos do meu caderno, explique [CONCEITO] incluindo:
(1) definição formal, (2) exemplo prático em R$, (3) importância para iniciantes."

PROMPT-02: "Explique [CONCEITO] com analogia do cotidiano, depois versão técnica pelas fontes."

PROMPT-03: "Liste 3 mitos e 3 verdades sobre [TEMA] citando qual fonte sustenta cada item."

PROMPT-04: "Tabela comparando [A], [B] e [C]: liquidez, risco, tributação, valor mínimo, perfil."

PROMPT-05: "3 prós e 3 contras de [PRODUTO] para perfil [CONSERVADOR/MODERADO/ARROJADO]."

PROMPT-06: "Com renda de [VALOR], despesas de [VALOR] e objetivo [META], como organizar finanças?"

PROMPT-07: "Calcule montante de [VALOR] a [TAXA]%/mês por [N] meses. Mostre passo a passo."

PROMPT-08: "Plano de ação em 4 etapas para [OBJETIVO] em [PRAZO] partindo de [SITUAÇÃO ATUAL]."

PROMPT-09: "Crie 5 questões de múltipla escolha sobre [TEMA] com gabarito e explicação."

PROMPT-10: "Resuma [TEMA] em esquema: conceito central → subtópicos → exemplos práticos."

PROMPT-11: "Checklist com 7 itens para verificar aplicação correta dos princípios de [TEMA]."

PROMPT-12: "Que conceitos relacionados à minha última pergunta ainda não explorei?"
```

---

## 5. Reflexão Final

**✅ O que funcionou:** Fontes oficiais + prompts estruturados + testar variações  
**🔧 Melhorias:** Adicionar fontes em inglês, prompts por módulo, explorar Guia de Estudo nativo  
**🚀 Próximos passos:** Expandir para renda variável | Validar prompts com colegas | Criar podcast no NotebookLM

---

*Projeto desenvolvido como atividade prática de Educação Financeira com IA. Todas as fontes são públicas e abertas.*
