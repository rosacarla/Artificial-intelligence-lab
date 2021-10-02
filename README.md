# Artificial-Intelligence-Lab
<img align='right' src="https://github.com/rosacarla/artificial-intelligence-lab/blob/main/imagens/ml-analytics-ai.jpg" width="215">

### Este repositório reúne projetos experimentais para aplicação de tecnologias de Inteligência Artificial.

###### A imagem "Machine Learning and Artificial Intelligence in Analytics" por [deepakiqlect](https://www.flickr.com/photos/158301585@N08) está licenciada sob [CC BY 2.0.](https://creativecommons.org/licenses/by/2.0/?ref=ccsearch&atype=rich)<br> 
<br>

## 1. PREVISÃO DE LOCAÇÕES DE BICICLETAS COM MACHINE LEARNING AUTOMATIZADO NO AZURE
**Descrição:** projeto utiliza a funcionalidade de machine learning automatizado do Azure Machine Learning para treinar e implantar um modelo de previsão como serviço Web, hospedado em uma instância de contêiner do Azure.

**Tecnologias utilizadas:** Microsoft Learn, Azure, bibliotecas Python (JSON, Logging, OS, Pickle, Numpy, Pandas, Joblib, Requests).  

**Objetivo:** usa-se um conjunto de dados históricos de locação de bicicletas para treinar um modelo capaz de prever o número de locações de bicicletas que é esperado em um dia determinado, considerando dados sazonais e meteorológicos. Nesse caso, um modelo de regressão é treinado para prever o número de locações de bicicletas.

**Conjunto de dados:** extraídos da base [Capital Bikeshare](https://www.capitalbikeshare.com/system-data).

**Criação da instância de computação de ML no Azure**: [documento](https://github.com/rosacarla/artificial-intelligence-lab/blob/main/docs/ML-azure-bikes.pdf) inclui cluster de cálculo, dataset, ML automatizado, modelo de regressão, métricas e Notebook.  

**Resultado:** Notebook [Test-Bikes.ipynb em Carla-ML1](https://github.com/rosacarla/artificial-intelligence-lab/blob/main/AutoML171cba6a127/Test-Bikes-notebook.py) do Azure mostra previsões diárias de aluguéis no período de cinco dias.

<p align="center"> 
<img src="https://github.com/rosacarla/artificial-intelligence-lab/blob/main/imagens/fig29.png">
</p>

## Licença
Distribuído sob a licença MIT. Veja `LICENSE`para informações adicionais.

## Contato
E-mail: rosa.carla@pucpr.edu.br<br>
Links:
- Projeto 1: https://github.com/rosacarla/artificial-intelligence-lab/tree/main/AutoML171cba6a127 

## Referências (Microsoft Learn)
- Trilha [Usar o machine learning automatizado no Azure Machine Learning](https://docs.microsoft.com/pt-br/learn/modules/use-automated-machine-learning/). 
