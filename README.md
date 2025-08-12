# 📊 Análise de Evasão de Clientes – Telecom

## 🎯 Propósito da Análise

Este projeto tem como objetivo analisar os dados de clientes da **Telecom X** para identificar os principais fatores que influenciam o cancelamento de serviços (Churn).  
A análise inclui:

- Cálculo da taxa de cancelamento por diferentes variáveis (gênero, idade, tipo de contrato, forma de pagamento, etc.)
- Identificação dos perfis de clientes com maior risco de evasão
- Visualização dos dados através de gráficos para facilitar a compreensão dos resultados

Os resultados obtidos podem ser utilizados para tomar decisões estratégicas, como:
- Ações de retenção no início do contrato
- Otimização de ofertas e pacotes
- Melhorias na percepção de valor de determinados serviços
- Modernização de meios de pagamento

---

## 🗂 Estrutura do Projeto

### Importação e Limpeza dos Dados
Os dados foram carregados a partir de arquivos CSV, contendo informações sobre:
- Perfil do cliente (gênero, idade, tempo de contrato)
- Serviços contratados (internet, telefone, etc.)
- Gastos mensais e totais
- Tipo de contrato

Etapas de limpeza e tratamento incluíram:
- Remoção de valores nulos e inconsistentes
- Conversão de colunas para tipos adequados
- Padronização de nomes e categorias

---

### 🔍 Análises Realizadas

#### Taxa de Cancelamento por Gênero
- Mulheres apresentaram taxa de cancelamento **0,76% maior** que homens.

#### Idosos (65+)
- Clientes acima de 65 anos apresentam maior taxa de cancelamento.

#### Meses de Contrato e Gasto Mensal
- Clientes com **pouco tempo de contrato e alto gasto mensal** são os mais propensos ao cancelamento.

#### Forma de Pagamento
- **Cheque Eletrônico** concentra a maior taxa de cancelamento (**45,29%**).

#### Tipo de Contrato
- **Mês a Mês**: maior número de cancelamentos.
- Contratos longos têm menor evasão.

#### Tipo de Internet
- Fibra Ótica: maior taxa de cancelamento.

---

### 📊 Visualizações
O projeto inclui gráficos interativos (Plotly/Matplotlib) para:
- Comparação de taxas de cancelamento por categoria
- Relação entre tempo de contrato e gasto
- Distribuição de cancelamentos por tipo de contrato, internet e forma de pagamento

---

## 📌 Conclusões

A análise revelou que:
- O **início da jornada** do cliente é o ponto mais crítico para retenção.
- O **Cheque Eletrônico** e a **Fibra Ótica** são fatores com maior associação ao churn.
- Clientes com **alto gasto mensal no início** cancelam com mais frequência.
- Contratos longos reduzem a evasão.

---

## 🏁 Conclusão Final

Este projeto demonstra como a análise de dados de clientes pode ajudar a **reduzir o Churn** e melhorar a retenção.  
Os gráficos e métricas identificam perfis de risco, permitindo ações proativas que aumentam a satisfação e a fidelidade.
