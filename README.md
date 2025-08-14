
# TelecomX Customer Churn Analysis Dataset

## 📌 Visão Geral

Este conjunto de dados contém informações processadas sobre clientes de uma empresa de telecomunicações (TelecomX) e está focado na análise de churn (cancelamento de serviços). Os dados incluem características demográficas, detalhes de serviços contratados, informações de conta e um indicador de churn.

## 📊 Estrutura dos Dados

O arquivo CSV contém as seguintes colunas principais:

### 👤 Dados do Cliente
- `customer.SeniorCitizen`: Indica se o cliente é idoso (1) ou não (0)
- `customer.tenure`: Tempo de permanência como cliente (em meses)
- `customer.gender_Male`: Gênero do cliente (1 para masculino)
- `customer.Partner_Yes`: Se o cliente tem parceiro (1)
- `customer.Dependents_Yes`: Se o cliente tem dependentes (1)

### 📱 Serviços de Telefonia
- `phone.PhoneService_Yes`: Se o cliente tem serviço telefônico (1)
- `phone.MultipleLines_No phone service`: Múltiplas linhas (sem serviço)
- `phone.MultipleLines_Yes`: Múltiplas linhas (com serviço)

### 🌐 Serviços de Internet
- Vários indicadores para tipo de serviço (Fibra óptica, etc.) e serviços adicionais (Segurança online, Backup, etc.)

### 💰 Dados Financeiros
- `account.Charges.Monthly`: Cobrança mensal
- `account.Charges.Total`: Cobrança total acumulada
- `account.Contract_One year`: Contrato de 1 ano
- `account.Contract_Two year`: Contrato de 2 anos
- `account.PaymentMethod_*`: Métodos de pagamento

### 🚩 Variável Alvo
- `Churn_Yes`: Indica se o cliente cancelou o serviço (1) ou não (0)

## 🎯 Objetivo de Análise

Este dataset é ideal para:
- Prever churn de clientes
- Identificar padrões entre clientes que cancelam
- Desenvolver estratégias de retenção
- Analisar o impacto de diferentes serviços na fidelidade do cliente

## 💡 Sugestões de Uso

1. **Modelos de Machine Learning**: Classificação para prever churn
2. **Análise Exploratória**: Identificar correlações entre variáveis
3. **Segmentação de Clientes**: Agrupar clientes por características similares
4. **Análise de Sobrevivência**: Modelar tempo até o cancelamento

## 📏 Dimensões
- Número de linhas: 1,000+ (amostra representativa)
- Número de colunas: 26 (features + target)

## 🔍 Dados Faltantes
Os dados já foram pré-processados e não contêm valores faltantes.

Este dataset oferece uma oportunidade valiosa para entender os fatores que influenciam o churn em serviços de telecomunicações e desenvolver estratégias eficazes de retenção de clientes.
