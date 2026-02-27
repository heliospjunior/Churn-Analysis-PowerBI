#Telco Customer Churn Analysis

##Análise Estratégica de Retenção com Foco Comercial


###📌 **Contexto de Negócio:**

Empresas com modelo de receita recorrente dependem fortemente da retenção de clientes para manter crescimento sustentável.

Pequenas variações na taxa de churn podem gerar impactos significativos na receita anual.

Este projeto simula um cenário de análise comercial focado em retenção de clientes, inspirado em empresas de serviços recorrentes como de assinaturas.


###🎯 **Objetivos:**

* Identificar fatores associados ao churn

* Mensurar impacto financeiro da evasão

* Detectar perfis de maior risco

* Gerar recomendações acionáveis para retenção



###🛠️ **Tecnologias Utilizadas:**

* Python

* Pandas

* Matplotlib

* Seaborn



###📈 **Principais Métricas Gerais:**

* Taxa geral de churn: 26,58%

* Receita mensal estimada: R$ 455.661,00

* Receita anual perdida com churn: R$ 1.669.570,20



###🔎 **Principais Insights**

**1️) Tipo de Contrato**

* Clientes com contrato mensal apresentam taxa de churn significativamente superior aos contratos anuais.

* Apesar de representarem 55% da base, concentram 87% da receita perdida mensal.

Insight:
Incentivar migração para contratos de maior prazo pode reduzir risco estrutural da base.


**2️) Tempo de Relacionamento (Tenure)**

* Clientes com até 1 ano de relacionamento apresentam maior taxa de churn.

* A taxa reduz progressivamente conforme o tempo de permanência aumenta.

Insight:
O período inicial do cliente é crítico para retenção. Estratégias de onboarding e acompanhamento precoce são essenciais.


**3️) Ticket Médio (MonthlyCharges)**

* Clientes de ticket Alto e Muito Alto apresentam as maiores taxas de churn.

* Esses grupos concentram aproximadamente 79% da receita perdida mensal.

Insight:
O churn está impactando principalmente clientes de maior valor, aumentando o impacto financeiro da evasão.



**4) Cruzamento Estratégico (Ticket + Tenure)**

* Clientes de alto ticket com menos de 1 ano apresentam o maior risco.

* Esse grupo representa parcela relevante da receita perdida.

Insight:
Retenção de clientes premium no primeiro ano deve ser prioridade comercial.



###💰 Impacto Financeiro

A concentração do churn em clientes de alto ticket indica que:

* A redução de churn nesse segmento teria alto impacto financeiro.

* Estratégias direcionadas podem gerar retorno significativo.




###🎯 Perfil Prioritário de Retenção

Com base na análise exploratória, o perfil de maior risco identificado foi:

* Contrato mensal

* Alto ou Muito Alto ticket

* Até 1 ano de relacionamento

** * Esse grupo deve ser foco prioritário de iniciativas comerciais.**
