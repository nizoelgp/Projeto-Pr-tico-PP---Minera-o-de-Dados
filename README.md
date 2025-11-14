 Projeto de Mineração de Dados: Análise Preditiva do Mercado Global de Smartphones

Este projeto foi desenvolvido para a disciplina de Mineração de Dados e tem como objetivo aplicar técnicas de análise de dados e aprendizado de máquina para prever tendências no mercado global de smartphones até 2025.

 1. Descrição do Problema e Objetivos

 Problema
O mercado global de smartphones é extremamente competitivo e dinâmico. Para empresas de consultoria, investidores e fabricantes, compreender as tendências e prever o cenário futuro é crucial para a tomada de decisões estratégicas. O problema central que este projeto busca resolver é: Como podemos utilizar dados históricos para prever o cenário competitivo do mercado de smartphones em 2025 e identificar os fatores que definem os líderes de mercado?

 Objetivo Principal
Desenvolver um modelo de aprendizado de máquina capaz de prever a participação de mercado (market share) das principais marcas de smartphones para o ano de 2025, com base nos dados históricos disponíveis.

 Objetivos Secundários
   Realizar uma análise histórica da evolução da participação de mercado das principais marcas.
   Identificar e visualizar os líderes de mercado em diferentes regiões do mundo.
   Aplicar e comparar diferentes algoritmos de aprendizado de máquina para a tarefa de previsão.
   Gerar insights acionáveis a partir dos resultados da análise e do modelo preditivo.

 2. Conjunto de Dados (Dataset)

   Nome: World Smartphone Market 2025
   Fonte: Kaggle
   Link: [https://www.kaggle.com/datasets/shahzadi786/world-smartphone-market-2025](https://www.kaggle.com/datasets/shahzadi786/world-smartphone-market-2025)
   Descrição: O dataset contém informações sobre a participação de mercado (em porcentagem) de diversas marcas de smartphones em diferentes regiões e países, ao longo de vários anos.

 3. Divisão de Tarefas

   Fundação do Projeto - [Seu Nome]: Definição do problema, criação do repositório, estruturação de pastas, documentação inicial e carga dos dados.
   ETL (Extração, Transformação e Carga) - [Nome do Colega 1]: Responsável pela limpeza, tratamento e preparação dos dados para análise (notebook `01-etl.ipynb`).
   Análise Exploratória e Visualizações - [Nome do Colega 2]: Responsável por gerar gráficos e insights a partir dos dados limpos (notebook `02-analise-exploratoria.ipynb`).
   Modelagem e Machine Learning - [Nome do Colega 3]: Responsável por treinar e testar os modelos preditivos (notebook `03-modelagem.ipynb`).
   Avaliação e Conclusão - [Nome do Colega 4]: Responsável por avaliar a performance dos modelos, interpretar os resultados e redigir a conclusão do projeto (notebook `04-avaliacao-e-resultados.ipynb`).

 4. Como Executar o Projeto

1.  Clone o repositório:
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyter
    ```
3.  Navegue até a pasta dos notebooks e execute o Jupyter:
    ```bash
    cd notebooks
    jupyter notebook
    ```
4.  Siga a ordem numérica dos notebooks para reproduzir o projeto.
