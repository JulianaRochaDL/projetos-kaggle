# Students Performance in Exams

Análise exploratória de dados sobre o desempenho de estudantes em exames de Matemática, Leitura e Escrita.

## Sobre o projeto

Este projeto tem como objetivo analisar o desempenho de estudantes e investigar possíveis relações entre suas notas e diferentes fatores sociais, econômicos e educacionais.

A análise foi desenvolvida utilizando Python e bibliotecas de análise e visualização de dados.

O dataset possui **1.000 estudantes e 8 variáveis**, incluindo informações sobre gênero, grupo étnico, nível de escolaridade dos pais, tipo de almoço, realização de curso preparatório e notas nas três avaliações.

## Objetivos

A análise busca responder principalmente às seguintes questões:

- Como melhorar o desempenho dos estudantes em cada avaliação?
- Quais são os principais fatores relacionados às diferenças nas notas?
- Qual é a relação entre a realização de um curso preparatório e o desempenho?
- Quais outros padrões podem ser observados nos dados?

## Variáveis analisadas

| Variável | Descrição |
|---|---|
| `gender` | Gênero do estudante |
| `race/ethnicity` | Grupo étnico |
| `parental level of education` | Nível de escolaridade dos pais |
| `lunch` | Tipo de almoço |
| `test preparation course` | Situação do curso preparatório |
| `math score` | Nota de Matemática |
| `reading score` | Nota de Leitura |
| `writing score` | Nota de Escrita |

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook / Kaggle Notebook

## Análises realizadas

Durante o projeto foram realizadas análises como:

- Exploração inicial dos dados;
- Verificação de valores ausentes;
- Análise das notas de Matemática, Leitura e Escrita;
- Cálculo das médias das avaliações;
- Análise da distribuição das notas;
- Identificação de estudantes aprovados e reprovados;
- Análise do nível de escolaridade dos pais;
- Análise da realização do curso preparatório;
- Análise do tipo de almoço;
- Análise por gênero;
- Análise por grupo étnico;
- Cálculo do total e da média das notas;
- Classificação dos estudantes em diferentes conceitos (A, B, C, D, E e F);
- Visualização dos resultados por meio de gráficos.

## Principais resultados

A análise mostrou algumas diferenças nas médias de desempenho:

- **Matemática:** 66,09
- **Leitura:** 69,17
- **Escrita:** 68,05

Também foi observado que os estudantes que **concluíram o curso preparatório** apresentaram médias maiores nas três avaliações quando comparados aos estudantes que não realizaram o curso.

Além disso, estudantes com **almoço padrão** apresentaram médias maiores nas três avaliações em comparação ao grupo com almoço `free/reduced`.

Na análise por gênero, estudantes do sexo feminino apresentaram médias maiores em Leitura e Escrita, enquanto estudantes do sexo masculino apresentaram média maior em Matemática.

Também foram observadas diferenças nas médias entre os grupos de `race/ethnicity` e entre os diferentes níveis de escolaridade dos pais.

## Visualizações

Foram utilizados gráficos com Seaborn e Matplotlib para facilitar a interpretação dos dados, incluindo:

- Gráficos de contagem;
- Gráficos de barras;
- Boxplots;
- Distribuição das médias;
- Comparações entre categorias.

## Aprendizados

Este projeto foi desenvolvido como parte do meu processo de aprendizagem em **Análise de Dados com Python e Pandas**.

Durante o desenvolvimento, foram praticados conceitos como:

- Manipulação de DataFrames;
- `groupby()`;
- `mean()`;
- `value_counts()`;
- `melt()`;
- criação de novas colunas;
- análise de dados categóricos;
- visualização de dados;
- interpretação de gráficos e resultados.
