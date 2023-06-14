
A Regressão Logística é um algoritmo de aprendizado de máquina usado para resolver problemas de classificação. Classificação é uma tarefa em que queremos atribuir uma categoria ou rótulo a um determinado conjunto de dados com base em suas características.

A ideia por trás da Regressão Logística é encontrar uma relação entre as características (variáveis independentes) e uma variável de destino (variável dependente) que tenha valores discretos, geralmente representando classes ou categorias.

A principal diferença entre a Regressão Logística e a regressão linear é o tipo de variável de destino. Na regressão linear, a variável de destino é contínua e tentamos prever um valor numérico. Na Regressão Logística, a variável de destino é discreta e tentamos prever uma classe ou categoria específica.

A Regressão Logística usa uma função matemática chamada função logística (também conhecida como função sigmoid) para modelar a relação entre as características e a probabilidade de pertencer a uma classe específica. Essa função transforma os valores de entrada em um intervalo entre 0 e 1, representando a probabilidade de pertencer à classe positiva.

Durante o treinamento, a Regressão Logística ajusta os parâmetros do modelo para encontrar a melhor curva sigmoid que se ajusta aos dados de treinamento. Isso é feito usando um algoritmo chamado Máxima Verossimilhança, que estima a probabilidade de observar os dados de treinamento com base nos parâmetros do modelo.

Uma vez que o modelo é treinado, podemos fazer previsões para novos dados. A Regressão Logística classifica uma instância de dados calculando a probabilidade de pertencer a cada classe e atribuindo a classe com a maior probabilidade.

Por exemplo, no problema do Titanic, usamos a Regressão Logística para prever se um passageiro sobreviveu (classe 1) ou não sobreviveu (classe 0) com base em características como idade, sexo, classe de passageiro, etc.

Em resumo, a Regressão Logística é um algoritmo de aprendizado de máquina que é usado para resolver problemas de classificação, onde a variável de destino é discreta. Ele modela a relação entre as características e a probabilidade de pertencer a uma classe específica usando a função sigmoid. É amplamente utilizado devido à sua simplicidade e interpretabilidade.