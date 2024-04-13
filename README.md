# Pipelines Scikit-Learn

* Estruturar o treinamento e validação de modelos de ML por meio de pipelines.
* Organizar etapas importantes na criação dos modelos.
* Garante que as mesmas etapas de pré-processamento sejam aplicadsa em treino e teste.
* Menos código e repetição
* Evita data leakage
* Facilita transfência de modelos
* Salvar e carregar como um objeto
* Permite utilizar várias etapas de pré-processamento (transform)
* Normalmente finaliza com um algoritmo de predição (estimator)
* Também permite a seleção de features e de escolha de quais passam por quais pré-processamento (ex.: coluna 'valor de venda'vai passar por caling, mas 'idade'não)
* Cria uma especie de roteiro desde os dados "brutos" até o modelo treinado e validado