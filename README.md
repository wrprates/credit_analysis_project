# Projeto de Análise de Crédito

## Visão Geral
Este projeto tem como objetivo analisar e prever as pontuações de crédito de clientes com base em dados demográficos, financeiros e históricos de crédito. O dataset é rico em variáveis categóricas e numéricas, permitindo insights detalhados sobre o comportamento de crédito.

### Dataset
- **Fonte**: [Credit Score Dataset no Kaggle](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)  
- **Número de Linhas**: 100.000  
- **Número de Colunas**: 28  

### Dicionário de Dados
| **Coluna**                 | **Descrição**                                                                    | **Tipo**       |
|-----------------------------|----------------------------------------------------------------------------------|----------------|
| `id`                       | Identificador único para cada registro.                                          | Categórico     |
| `customer_id`              | Identificador único de cada cliente.                                             | Categórico     |
| `month`                    | Mês da transação ou registro.                                                    | Categórico     |
| `name`                     | Nome do cliente.                                                                 | Categórico     |
| `age`                      | Idade do cliente (anos).                                                         | Numérico       |
| `ssn`                      | Número de segurança social do cliente.                                           | Categórico     |
| `occupation`               | Ocupação do cliente.                                                             | Categórico     |
| `annual_income`            | Renda anual do cliente (em dólares).                                             | Numérico       |
| `monthly_inhand_salary`    | Salário líquido mensal do cliente.                                               | Numérico       |
| `num_bank_accounts`        | Número total de contas bancárias do cliente.                                     | Numérico       |
| `num_credit_card`          | Número total de cartões de crédito do cliente.                                   | Numérico       |
| `interest_rate`            | Taxa de juros aplicada aos empréstimos/créditos.                                 | Numérico       |
| `num_of_loan`              | Número de empréstimos ativos.                                                    | Numérico       |
| `type_of_loan`             | Tipos de empréstimos contratados pelo cliente.                                   | Categórico     |
| `delay_from_due_date`      | Dias de atraso no pagamento das parcelas.                                         | Numérico       |
| `num_of_delayed_payment`   | Quantidade total de pagamentos atrasados.                                         | Numérico       |
| `changed_credit_limit`     | Alterações realizadas no limite de crédito.                                       | Numérico       |
| `num_credit_inquiries`     | Número de consultas ao histórico de crédito do cliente.                          | Numérico       |
| `credit_mix`               | Variedade de tipos de crédito utilizados pelo cliente (e.g., "Good", "Poor").    | Categórico     |
| `outstanding_debt`         | Total de dívidas pendentes do cliente.                                            | Numérico       |
| `credit_utilization_ratio` | Proporção de crédito utilizado em relação ao limite total.                        | Numérico       |
| `credit_history_age`       | Tempo de histórico de crédito do cliente (anos e meses).                         | Categórico     |
| `payment_of_min_amount`    | Indica se o cliente paga o valor mínimo mensalmente (Sim ou Não).                 | Categórico     |
| `total_emi_per_month`      | Valor total das parcelas mensais pagas pelo cliente.                             | Numérico       |
| `amount_invested_monthly`  | Valor investido mensalmente pelo cliente.                                         | Numérico       |
| `payment_behaviour`        | Comportamento de pagamento do cliente (e.g., padrões de gasto e atraso).          | Categórico     |
| `monthly_balance`          | Saldo mensal restante na conta do cliente após despesas e pagamentos.            | Numérico       |
| `credit_score`             | **Pontuação de crédito do cliente**. Variável-alvo com categorias como "Poor", "Standard" e "Good". | Categórico     |

### Estratégia de Análise
1. **Análise Exploratória de Dados (EDA)**:
   - Explorar relações entre variáveis categóricas e numéricas.
   - Identificar padrões e outliers relevantes no comportamento de crédito.

2. **Modelagem Preditiva**:
   - Construir um modelo de machine learning para prever a variável `credit_score`.
   - Avaliar o desempenho do modelo utilizando métricas apropriadas.

3. **Entregáveis**:
   - Relatório de Análise Exploratória e relatório de Machine Learning, ambos gerados em **HTML** usando o pacote `Quarto` no R.

