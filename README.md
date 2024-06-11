# Problema de Machine Learning de Classificação: Previsão de Churn para uma Empresa de Telecomunicações
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DaniloTAbreu/PROJETO7_CHURN/blob/main/LICENSE) 

# Sobre o projeto

Descrição do Problema:
Uma empresa de telecomunicações está enfrentando um problema de alta taxa de churn entre seus clientes. Eles desejam desenvolver um modelo de previsão de churn que os ajude a identificar os clientes com maior probabilidade de cancelar seus serviços. Isso permitirá que eles adotem medidas proativas para reter esses clientes e reduzir a perda de receita.

onjunto de Dados:

O conjunto de dados utilizado é o "Telco Customer Churn" disponível no Kaggle. Ele contém informações sobre clientes de uma empresa de telecomunicações, incluindo características demográficas, tipo de serviço contratado, tempo de permanência, cobranças mensais, entre outros. O conjunto de dados também inclui uma variável indicando se o cliente cancelou ou não o serviço (churn).

Desafios:

Exploração de Dados: Explore o conjunto de dados para entender as características dos clientes e identificar possíveis padrões relacionados ao churn.
Pré-processamento de Dados: Realize o pré-processamento dos dados, lidando com valores ausentes, convertendo variáveis categóricas em variáveis dummy (ou utilizando técnicas de codificação), normalizando/escalonando os dados, etc.
Seleção de Recursos: Identifique as características mais relevantes para prever o churn dos clientes. Isso pode ser feito utilizando técnicas de seleção de características ou análise de importância de características.
Modelagem: Escolha e treine um modelo de machine learning para prever o churn dos clientes. Alguns algoritmos comuns para este problema incluem Regressão Logística, Árvores de Decisão, Random Forest, Gradient Boosting, entre outros.
Avaliação do Modelo: Avalie o desempenho do modelo utilizando métricas apropriadas, como precisão, recall, F1-score, área sob a curva ROC (AUC-ROC), entre outras. Também é importante considerar a interpretabilidade do modelo, especialmente se houver necessidade de explicar as previsões aos stakeholders.
Otimização e Refinamento: Refine o modelo e otimize seus hiperparâmetros para melhorar seu desempenho na previsão de churn.


Objetivo Final:

O objetivo final é desenvolver um modelo de previsão de churn preciso e robusto que possa ser utilizado pela empresa de telecomunicações para identificar clientes em risco de cancelamento. Com essa informação, a empresa poderá implementar estratégias de retenção de clientes direcionadas, como ofertas personalizadas, melhorias nos serviços ou atendimento ao cliente proativo, com o objetivo de reduzir a taxa de churn e aumentar a satisfação e fidelidade dos clientes.


Telco Customer Churn Database:

Contexto
"Preveja o comportamento para reter clientes. Você pode analisar todos os dados relevantes dos clientes e desenvolver programas focados em retenção de clientes." [Conjuntos de dados de amostra da IBM]

Conteúdo
Cada linha representa um cliente, cada coluna contém os atributos do cliente descritos na coluna Metadados.

O conjunto de dados inclui informações sobre:

Clientes que saíram no último mês – a coluna é chamada de Churn
Serviços nos quais cada cliente se inscreveu – telefone, múltiplas linhas, internet, segurança online, backup online, proteção de dispositivos, suporte técnico e streaming de TV e filmes
Informações da conta do cliente – há quanto tempo ele é cliente, contrato, forma de pagamento, faturamento sem papel, cobranças mensais e cobranças totais
Informações demográficas sobre clientes – sexo, faixa etária e se possuem companheiros e dependentes



Este dataset foi baixado no endereço (https://www.kaggle.com/datasets/blastchar/telco-customer-churn) no dia 25/04/2024.

# Tecnologias utilizadas
## Linguagem
- Python
- SQL

## Machine learning
- Regressão Logística
- Random Forest
- SVM
- Redes Neurais
- Gradient Boosting Machines (por exemplo, XGBoost, LightGBM):
- Otimização do modelo

## Ferramenta utilizada
- Jupyter notebook

# Autor

Danilo Temerloglou de Abreu

https://www.linkedin.com/in/danilo-temerloglou-de-abreu-27182950/