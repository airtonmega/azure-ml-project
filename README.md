# azure-ml-project
Modelo de previsão M.L

1- Eu iniciei o processo acessando o portal do Azure

Primeiramente, acessei o portal do Azure e fiz login com minha conta.
2- Criei um novo recurso de Azure Machine Learning

No portal do Azure, cliquei em “Criar um recurso” e procurei por “Azure Machine Learning”. Selecionei o serviço e cliquei em “Criar” para configurar minha área de trabalho de Machine Learning.
3- Configurei a área de trabalho do Azure Machine Learning

Preenchi os campos necessários como nome da área de trabalho, região, e grupo de recursos. Após preencher esses detalhes, cliquei em “Criar” para estabelecer minha área de trabalho.
4- Acessei o Azure Machine Learning Studio

Uma vez criada a área de trabalho, acessei o Azure Machine Learning Studio navegando até ml.azure.com e fiz login com a conta associada à minha área de trabalho do Azure ML.
5- Preparei os dados

Carreguei os dados que eu queria analisar para o Azure Machine Learning Studio. Isso foi feito importando os dados para o dataset do Azure ML, onde pude explorar e preparar os dados para o treinamento do modelo.
6- Criei um experimento de Machine Learning

No Azure ML Studio, criei um novo experimento, que é um container para todo o trabalho relacionado ao modelo de previsão que eu estava construindo. Nomeei o experimento de forma a refletir o objetivo do modelo de previsão.
7- Desenvolvi e treinei o modelo de previsão

Utilizei as ferramentas do Azure ML para selecionar um algoritmo de Machine Learning adequado para o meu problema de previsão. Configurei os parâmetros do algoritmo e iniciei o processo de treinamento com meus dados.
8- Avaliei o modelo

Após o treinamento, avaliei a performance do modelo usando as métricas fornecidas pelo Azure ML, como precisão, recall, e área sob a curva (AUC). Isso me ajudou a entender o quão bem o modelo estava prevendo os resultados.
9- Implantei o modelo como um serviço web

Uma vez satisfeito com a performance do modelo, procedi com a implantação. No Azure ML Studio, selecionei o modelo treinado e usei a opção de implantação para expor o modelo como um serviço web. Isso envolveu criar um ponto de extremidade (endpoint).
10- Configurei o ponto de extremidade

Durante a implantação, configurei o ponto de extremidade, definindo a configuração de hardware e as rotas de acesso. Isso resultou na criação de uma URL e uma chave API, que são usadas para acessar o modelo via chamadas HTTP.
11- Testei o ponto de extremidade

Para garantir que tudo estava funcionando conforme o esperado, fiz algumas chamadas de teste ao ponto de extremidade, enviando dados de entrada e recebendo previsões em retorno.


No processo de criação e implantação do meu modelo de previsão de dados no Azure Machine Learning, eu configurei e publiquei um ponto de extremidade (endpoint) para o serviço web do meu modelo. O ponto de extremidade que mencionei e configurei é https://estudoml-kvkif.centralus.inference.ml.azure.com/score.
