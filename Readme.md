# **Execução do Case de Previsão de vendas**

A proposta para esse case foi retirada da plataforma Kaggle (mock_kaggle.csv):

https://www.kaggle.com/datasets/tevecsystems/retail-sales-forecasting/data

Acrecida uma proposta de previsão de 14 dias (mock_kaggle_pred.csv)

### **Estrutura de pastas**

Sales_forecast_regression_models/  
├── regression_models.ipynb  
├── mock_kaggle.csv  
├── mock_kaggle_pred.csv   
└── README.md    

### **Contexto**

Este conjunto de dados contém muitos dados históricos de vendas. Foi extraído de um grande varejista brasileiro e possui muitos SKUs e muitas lojas. Os dados foram transformados para proteger a identidade do varejista.

### **Inspiração**

Todo negócio de varejo no mundo enfrenta uma questão fundamental: quanto estoque devo manter? Por um lado, misturar estoques significa custos de capital de giro, custos operacionais e uma operação complexa. Por outro lado, a falta de estoque leva à perda de vendas, clientes insatisfeitos e uma marca danificada.

Os modelos atuais de gestão de estoques possuem muitas soluções para fazer o pedido correto, mas todas se baseiam em um único fator desconhecido: a demanda para os próximos períodos. É por isso que as previsões de curto prazo são tão importantes no varejo e na indústria de bens de consumo.

Incentivamos você a buscar o melhor modelo de previsão de demanda para as próximas 2 a 3 semanas. Esta informação valiosa pode ajudar muitos profissionais da cadeia de abastecimento a gerir corretamente os seus níveis de inventário.

### **Proposta de trabalho** 

Realizaremos uma análise dos dados buscando o entendimento das informações coletadas, após chegar a um entendimento aceitável, realizaremos uma validação de 5 tipos de modelos de machine learning para checarmos suas performance para os nossos dados. 

Os modelos serão:

* regressão linear;
* regressão não linear;
* arvore de decisão;
* floresta aleatoria;
* redes neurais Multi Layer Perceptron.

Aquele que obtiver a melhor performance utilizaremos para realizar a previsão e demostração do resultado.

### **Ferrametas utilizadas**

Através da linguagem de programação Python usaremos as seguintes bibliotécas

*  Pandas;
*  seaborn;
*  matplotlib;
*  sklearn.
