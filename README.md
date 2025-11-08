# Desafio da Especialização de Data Science do Programa Alura | Oracle ONE - Oracle Next Education.
## Desafio de Data Science: Análise Comparativa de Desempenho Varejista

Este projeto documenta a análise de desempenho de quatro unidades de loja (`Loja_1`, `Loja_2`, `Loja_3` e `Loja_4`) com o objetivo final de identificar a unidade com o **pior desempenho geral** para uma decisão estratégica de venda.

A análise foi conduzida utilizando a biblioteca `pandas` no ambiente Google Colab, cobrindo cinco métricas essenciais de negócio: financeiras, de qualidade e operacionais.

---

## 🛠️ Detalhes do Projeto e Metodologia

1.  **Pré-Processamento:** Os dados de cada uma das quatro lojas foram importados, corrigidos (renomeação de colunas) e unificados em um único DataFrame (`df_comparativo`), com a adição de um identificador de loja (`Loja`).
2.  **Cálculo da Receita:** A coluna `Receita Total` (Preço + Frete) foi criada para todas as análises financeiras.
3.  **Análise Comparativa:** Todas as métricas foram calculadas com a função `groupby('Loja')` do pandas, permitindo a comparação direta de desempenho.

---

## 📈 Resultados da Análise Métrica por Métrica

### 💰 Métrica 1: Análise do Faturamento

| Loja | Faturamento Total | Ticket Médio |
| :--- | :--- | :--- |
| Loja_1 | [Inserir Valor Formatado do Faturamento] | [Inserir Valor Formatado do Ticket Médio] |
| Loja_2 | [Inserir Valor Formatado do Faturamento] | [Inserir Valor Formatado do Ticket Médio] |
| Loja_3 | [Inserir Valor Formatado do Faturamento] | [Inserir Valor Formatado do Ticket Médio] |
| Loja_4 | [Inserir Valor Formatado do Faturamento] | [Inserir Valor Formatado do Ticket Médio] |

*Resultado:* **[Identificar a loja com o menor Faturamento Total]**

### 🛍️ Métrica 2: Vendas por Categoria (Visão da Receita)

Identificou-se o principal motor de receita em cada loja.

* **Loja_1 Top Categoria:** [Inserir Categoria]
* **Loja_2 Top Categoria:** [Inserir Categoria]
* **Loja_3 Top Categoria:** [Inserir Categoria]
* **Loja_4 Top Categoria:** [Inserir Categoria]

*Conclusão:* Esta métrica revelou o foco de mercado de cada unidade, sendo crucial para entender se as lojas competem no mesmo segmento.

### ⭐ Métrica 3: Média de Avaliação das Lojas

| Loja | Média de Avaliação |
| :--- | :--- |
| Loja_1 | [Inserir Média de Avaliação Formatada] |
| Loja_2 | [Inserir Média de Avaliação Formatada] |
| Loja_3 | [Inserir Média de Avaliação Formatada] |
| Loja_4 | [Inserir Média de Avaliação Formatada] |

*Resultado:* **[Identificar a loja com a Pior Média de Avaliação]** (Maior risco de reputação).

### 📦 Métrica 4: Produtos Mais e Menos Vendidos (Volume)

Análise de volume de vendas para identificar o giro de estoque em cada loja.

* **Resultado Chave:** Determinação do Top 3 de Produtos Mais Vendidos (por quantidade) em cada unidade, fundamental para gestão de estoque e identificação de *best-sellers*.

### 🚚 Métrica 5: Frete Médio por Loja (Custo Operacional)

| Loja | Frete Médio |
| :--- | :--- |
| Loja_1 | [Inserir Valor Formatado do Frete Médio] |
| Loja_2 | [Inserir Valor Formatado do Frete Médio] |
| Loja_3 | [Inserir Valor Formatado do Frete Médio] |
| Loja_4 | [Inserir Valor Formatado do Frete Médio] |

*Resultado:* **[Identificar a loja com o Frete Médio mais Alto]** (Maior custo logístico por transação).

---

## 🎯 Avaliação Final e Recomendação

A decisão final de venda se baseia na combinação do pior desempenho financeiro (Faturamento) e de risco (Avaliação e Custo Operacional).

### **Recomendação de Venda:**

Com base na consolidação de todas as métricas, a **[Inserir Nome da Loja - Ex: Loja\_X]** é identificada como a principal candidata à venda.

* **Justificativa:** A loja apresenta o **[Menor Faturamento Total]** e/ou a **[Pior Média de Avaliação]**, representando o menor retorno de investimento e o maior risco de satisfação do cliente no portfólio. A venda desta unidade é recomendada para otimizar o desempenho financeiro e a reputação geral da empresa.

---
*Este documento foi gerado como parte da conclusão do desafio de Data Science e pode ser replicado no notebook Colab associado ao projeto.*
