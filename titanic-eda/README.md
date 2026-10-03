# Titanic — Análise Exploratória de Dados com Pandas e Seaborn

## Sobre o projeto

O foco principal desse projeto foi praticar **Análise Exploratória de Dados (EDA)** utilizando Python, Pandas e Seaborn, explorando os dados dos passageiros e investigando possíveis relações com a sobrevivência no desastre.

## Objetivos

Durante a análise, foram explorados:

- Estrutura e características do dataset;
- Idade dos passageiros;
- Sexo e classe dos passageiros;
- Distribuição dos passageiros por classe;
- Decks do navio;
- Portos de embarque;
- Passageiros que viajavam sozinhos ou acompanhados da família;
- Relação entre diferentes características dos passageiros e a sobrevivência.

## Tecnologias e bibliotecas

- Python
- Pandas
- Seaborn
- Matplotlib
- Kaggle Notebook

## Principais análises

### Idade dos passageiros

Foi analisada a distribuição das idades dos passageiros, utilizando gráficos de densidade para comparar diferentes grupos.

### Classe dos passageiros

Foi investigada a relação entre a classe do passageiro (`Pclass`) e a taxa de sobrevivência.

### Deck

A partir da variável `Cabin`, foi extraída a primeira letra para representar o deck do navio. Em seguida, foi analisada a taxa de sobrevivência em cada deck.

### Porto de embarque

Foi analisada a distribuição dos passageiros de acordo com o porto de embarque (`Embarked`) e sua relação com a classe do passageiro.

### Família

As variáveis `SibSp` e `Parch` foram utilizadas para identificar se o passageiro estava viajando sozinho ou acompanhado de familiares.

Também foi analisada a relação entre estar acompanhado por familiares e a sobrevivência.

## Conceitos praticados

Durante este notebook, pratiquei conceitos como:

- `DataFrame`
- Seleção de colunas
- `groupby()`
- `mean()`
- `value_counts()`
- Tratamento de valores ausentes
- Criação de novas colunas
- `map()`
- `loc`
- Visualização de dados
- `catplot()`
- `FacetGrid`
- `lmplot()`
- Gráficos de distribuição
- Análise de relações entre variáveis

## Conclusão

A análise exploratória permitiu observar que diferentes características dos passageiros estavam relacionadas às taxas de sobrevivência no Titanic.

Entre os fatores analisados, foram observadas diferenças de sobrevivência de acordo com a classe, sexo, idade, deck e presença de familiares.

O projeto foi importante para praticar a exploração de dados com Pandas e a criação de visualizações utilizando Seaborn, além de desenvolver uma melhor compreensão sobre como investigar um conjunto de dados antes de aplicar técnicas de Machine Learning.

## Fonte dos dados

Dataset utilizado na competição **Data Science BEST Practices Using Pandas - Titanic**, disponível no Kaggle.
