# Data Science, Machine Learning e o Mundial de 1951
Desenvolvo um algorítmo que cria um dataset com resultado simulado de uma pesquisa, com fãs de futebol, sobre o mundial do Palmeiras. Após a criação do dataset, faço a analise dos dados gerados(mais de 80 mil linhas de "respostas"), com o objetivo de demonstrar que o algorítmo foi capaz de gerar respostas que variem de acordo com características (dos supostos votantes) intencionalmente selecionadas, quais sejam: clube de coração, idade, sexo, e o tempo em que se deu a "resposta". 

## <center>Simulação do resultado de uma pesquisa sobre o título de Capeão do Mundo em 1951 pelo time do Palmeiras</center>
#### Desde 2014 quando a FIFA declarou oficialmente o Palmeiras como Campeão Mundial em 1951, esta discussão só cresceu no Brasil, no meio dos fâs do futebol.
#### Creating an algorithm that generate a dataset(.csv file) based on a simulated collection of votes for a suposed survey entitled "Is it correct to recognize SE Palmeiras as World Champions for winning the title of the Taça Rio Tornment at the year of 1951, since FIFA has manifested officialy this agreement on 2014. ". 
Once the dataset was created, there will be presented the data analysis, with the porpose to prove that this algorithm could generate votes that changes accord to the followed aspects:
- date of vote;
- the favorite brazillian futbol club of the voter;
- the age of the voter, and;
- the genre of the voter.

- 1a. Etapa: criar um arquivo .csv usando Python, que receberá os dados gerados por algorítimo que irá simular a coleta de resultados uma pesquisa de opnião. Sobre o modelo de simulação, vale considerar as seguintes observações:
    + não será objetivo do algorítimo replicar o resultado que uma pesquisa real teria;
    + as respostas da pesquisa irão variar de acordo com os seguintes parâmetros de quem vota: o clube favorito, a idade, o sexo e a data.

- 2a. Etapa: analisar os dados gerados, explorando as bibliotecas pandas, matplotlib e seaborn.

- 3a. Etapa: simular exercício de machine learning com o uso do sykitlearn, em aprendizagem supervisionada.

Arquivos/Files:
1. csv_e_analise.ipynb  
   - É o primeiro arquivo e contém desde a criação do dataset ".csv" à análise exploratória dos dados.
   - Its first file, contains the creation of dataset's '.csv' file, and exploratory analysis of data.
2. mundial51.csv
  - o dataset que foi criado pelo modelo.
  - the dataset itself, created by the model.

3. mlearning_mundial51.ipynb (em outro repositório: ensaio-em-machine-learning)
  - arquivo com a exploração de algorítimos de machine learning aplicado sobre o dataset mundial51
  - file containing algorithms of machine learning applyied over the mundial51 dataset
