# Telco Customer Churn Analysis

## Análise de Churn com Estruturação de Métricas e Priorização Comercial (Power BI)


### 📌 **Contexto de Negócio:**

Este projeto foi desenvolvido com foco em estruturar métricas confiáveis e orientadas a negócio para análise de churn em modelo de receita recorrente.

O objetivo não foi apenas visualizar dados, mas:
*  Modelar indicadores estratégicos
* Criar lógica de priorização
* Traduzir churn em impacto financeiro


### 🎯 **Objetivos:**

* Identificar fatores associados ao churn

* Mensurar impacto financeiro da evasão

* Detectar perfis de maior risco

* Gerar recomendações acionáveis para retenção



O projeto foi estruturado em três camadas:


## 1 - Camada de Transformação

* Tratamento de tipos de dados
* Padronização da variável Churn
* Criação de faixas de Ticket e Tenure
* Organização de modelo analítico

## 2 - Camada de Métricas (DAX)

### Criação de medidas robustas:

* Total de Clientes
* Taxa de Churn
* Receita Perdida Mensal
* Receita Perdida Anual
* Participação percentual por segmento

Todas as métricas foram estruturadas com uso adequado de CALCULATE, ALL e contexto de filtro.

## 3 - Camada de Priorização

Desenvolvimento de um Score Heurístico de Risco considerando:

* Ticket
* Tempo de relacionamento
* Tipo de contrato

O score permitiu identificar concentração financeira de risco.


### 🔎 **Principais Resultados**

* 8,97% da base concentra 39,31% da receita perdida mensal.
* Clientes de alto ticket, contrato mensal e até 1 ano representam o maior risco estrutural.
* Simulação de redução de 10% nesse grupo indica potencial relevante de preservação de receita anual.

**Insight:**
Incentivar migração para contratos de maior prazo pode reduzir risco estrutural da base.


## Ferramentas

* Power BI
* DAX
* Modelagem Analítica
* Business Analytics


