# Analise-de-Queimadas-no-Brasil-2014-2024
Este repositório contém um projeto de ciência de dados sobre queimadas no Brasil entre janeiro de 2014 e 2024. Foram utilizadas técnicas de análise exploratória e clusterização.

**Participantes**: Isabelle Pereira e Giselda Ferreira.

## Objetivo
Projeto de ciência de dados desenvolvido durante a disciplina do mestrado. Utilizou-se um conjunto de dados de livre escolha, e buscando um consenso entre a dupla, o foco foi na análise de queimadas no Brasil entre 2014 e 2024 (estando esse incompleto devido ao mês de desenvolvimento do projeto). Foram aplicadas técnicas de análise exploratória e clusterização para identificar padrões geográficos e temporais. 

### Resultados
Com base nos resultados, realizou-se uma pesquisa complementar em notícias para contextualizar e validar os achados. Observou-se que, mesmo sem o ano de 2024 completo, ele já liderava o número de ocorrências, seguido por 2015. O ano de menor incidência foi 2018. Entre os estados, Mato Grosso, Mato Grosso do Sul e Pará apresentaram números consistentemente altos ao longo do período, com Minas Gerais se tornando destaque em 2024. Setembro foi visto como o mês com maior volume de queimadas (coincidindo com o período seco que antecede as chuvas), enquanto abril e outuno concentraram os menores registros. O Cerrado foi o bioma mais afetado, enquanto o Pampa apresentou o menor número de ocorrências. Além disso, municípios mato-grossenses como Paranatinga, Nova Maringá e Nova Ubiratã apareceram repetidamente entre os que mais registraram queimadas ao longo dos anos analisados.

## Conjunto de Dados
Os dados utilizados foram obtidos do portal **TerraBrasilis**, uma plataforma do governo brasileiro que fornece informações sobre queimadas e desmatamento no Brasil. 

- **Fonte dos dados**: [Terrabrasilis](https://terrabrasilis.dpi.inpe.br/queimadas/portal/dados-abertos/)
- **Período**: 2014 - 2024
- **Dados**: Arquivos CSV para cada ano entre 2014 e 2024

## Metodologia

1. **Análise Exploratória de Dados (EDA)**:
   - Limpeza e transformação dos dados.
   - Análise de distribuições temporais e espaciais das queimadas.

2. **Clusterização**:
   - Aplicação de técnicas de clusterização para agrupar regiões com comportamento semelhante.
   - Utilização de algoritmos como K-means para identificar padrões de ocorrência de queimadas em diferentes regiões.

## Tecnologias e Bibliotecas Utilizadas
- **Linguagem**: Python
- **Bibliotecas**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Ferramentas**: Jupyter Notebook


## Resultados Esperados
- Identificação de regiões mais afetadas por queimadas.
- Tendências temporais sobre o aumento ou diminuição das queimadas.
- Agrupamento de regiões com comportamento semelhante em termos de queimadas.

## Contribuições
Se você tem sugestões de melhorias para este projeto, fique à vontade em mostrar.
