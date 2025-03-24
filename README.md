## Tarefa e conjunto de dados
Estaremos trabalhando com um conjunto de dados de [detecção de Fraude em transações de cartão de crédito](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code?datasetId=310&searchQuery=Eda). O dataset contém dados de transações feitas por cartão de crédito por europeus em setembro de 2013.

O conjunto de dados conta com 28 váriaveis explicativas. Todas essas variáveis são numéricas e **anonimizadas** de forma que não conseguimos ter um entendimento completo dessas variáveis. Além disso o dataset conta com a variável resposta 'Class' que é uma variável booleana em que o valor 0 indica uma transação não fraudulenta enquanto que o valor 1 indica fraude em uma transação.

## Detecção de fraudes
A análise e detecção de fraudes em transações de cartão de crédito são de extrema importância no contexto atual, onde o uso de cartões de crédito e débito é uma prática cotidiana para a maioria das pessoas. As fraudes representam um desafio significativo tanto para consumidores quanto para instituições financeiras.

Fraudes em transações de cartão de crédito resultam em perdas financeiras substanciais para consumidores e instituições financeiras. Estima-se que fraudes com cartões de crédito causem bilhões de dólares em prejuízos anuais globalmente. Além disso, fraudes podem levar a sérios problemas para os consumidores, incluindo o comprometimento de dados pessoais, estresse emocional e complicações financeiras. Sistemas eficazes de detecção de fraudes protegem os consumidores contra o uso não autorizado de suas informações financeiras, proporcionando maior segurança e confiança no uso de cartões de crédito.

Nosso projeto se torna pertinente pois aborda um problema de grande impacto socioeconômico, utilizando técnicas avançadas de aprendizado de máquina para melhorar a detecção de fraudes em transações de cartão de crédito. Utilizando o conjunto de dados de transações de cartão de crédito fornecido, que contém 28 variáveis explicativas anonimizadas, o objetivo é desenvolver um modelo preditivo que possa identificar transações fraudulentas com alta precisão.

## Abordagem, materiais e métodos
A detecção de fraudes em transações de cartão de crédito é uma tarefa desafiadora devido à natureza desequilibrada dos dados e à complexidade dos padrões de fraude. Segundo pesquisas recentes, Random Forest é um algoritmo de aprendizado de máquina altamente eficaz para essa tarefa por ser um algoritmo robusto com menos risco de overfitting e menos sensível a variações nos dados de treinamento. Além disso esse modelo é muito bom para lidar com dados desbalanceados, especialmente quando o combinamos com algumas técnicas como oversampling.
