# Segmentação de Clientes (Credit Card Cluster)

### 1. Entendimento do Problema
O principal desafio abordado neste projeto é a necessidade de definir estratégias de marketing mais eficazes para uma instituição financeira que emite cartões de crédito. Com base em uma amostra representativa de cerca de 9.000 titulares de cartões ativos nos últimos 6 meses, o objetivo é realizar uma segmentação de clientes. Essa segmentação permitirá identificar características distintivas entre os titulares de cartões, possibilitando uma abordagem mais personalizada e direcionada nas estratégias de marketing.

### 2. Premissas do Negócio
A amostra de 9.000 titulares de cartões de crédito é representativa do universo total de clientes da instituição financeira.
O comportamento dos clientes com base no histórico é indicativo de padrões que podem ser extrapolados para o futuro próximo.
A utilização do modelo K-Means e da redução de dimensionalidade através do PCA são métodos apropriados para realizar a segmentação de clientes com base em padrões comportamentais.

### 3. Estratégia Utilizada
A estratégia adotada envolve uma abordagem em duas frentes: análise descritiva e estatística abrangente seguida pela aplicação do modelo K-Means para segmentação. A redução de dimensionalidade através do PCA é incorporada para simplificar a complexidade dos dados, facilitando a identificação de tendências e grupos significativos. A estratégia busca criar uma estrutura analítica robusta que possibilite o desenvolvimento de estratégias de marketing direcionadas.

### 4. Principais Insights Obtidos
A análise descritiva e estatística revelou padrões comportamentais distintivos entre os titulares de cartões de crédito, indicando a presença de grupos heterogêneos na amostra.

*	Grupo 0 - Clientes que realizam todo tipo de compra com o cartão (parcelado, à vista).
*	Grupo 1 - Clientes devedores.
*	Grupo 2 - Clientes que compram a prazo com maior frequência.
*	Grupo 3 - Clientes que usam Cash in Advance (antecipar o dinheiro).
*	Grupo 4 - Clientes que possuem os maiores valores de compra.
*	Grupo 5 - Clientes que não gastam muito

A aplicação do modelo K-Means permitiu uma segmentação precisa dos titulares de cartões, agrupando-os com base em padrões comportamentais similares, fornecendo uma base sólida para estratégias de marketing mais direcionadas.

### 5. Produto Final
O produto final consiste em uma segmentação clara e detalhada dos titulares de cartões de crédito, identificando grupos distintos com base em comportamentos semelhantes. O resultado inclui insights visuais, como gráficos e visualizações, que facilitam a interpretação e comunicação dos resultados. 

### 6. Conclusão
Este projeto fornece uma abordagem abrangente para a segmentação de clientes de cartões de crédito, permitindo à instituição financeira compreender melhor o comportamento de seus clientes e desenvolver estratégias de marketing mais eficazes. A combinação de análise estatística, redução de dimensionalidade e modelagem de cluster proporciona uma base sólida para a tomada de decisões informadas e a implementação de estratégias personalizadas.

## Link da Aplicação
https://credit-card-cluster-philippe-apolinario.streamlit.app/

## Utilização

### Dependências
* Sistema Operacional:
    * Windows 10 ou 11

* Bibliotecas e Módulos:
    * Numpy
    * Pandas
    * Matplotlib
    * Seaborn
    * Scikit-learn
    * Datetime
    * Pillow
    * Streamlit
    * BytesIO

### Executando o projeto
1 - Baixe o arquivo do projeto  
2 - Descompacte o arquivo  
3 - Acesse o link do webapp e busque pelo arquivo CC GENERALC.csv presente na pasta input

## Autores
Nomes dos desenvolvedores do projeto e informação para entrar em contato.

[@PhilippeApolinario](https://www.linkedin.com/in/philipperapolinario/)

## Histórico de versões.

* 0.1
    * Primeira versão
* 0.2
    * Segunda versão
    
## Licença de uso
Esse projeto possui licença de uso [MIT] - acesse o arquivo LICENSE.md para mais detalhes.