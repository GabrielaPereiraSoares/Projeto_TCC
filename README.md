# Uma abordagem estatística sobre a estimação de _redshifts_ de quasares usando dados do S-PLUS - Códigos de Programação
Este repositório é destinado ao versionamento e organização dos códigos desenvolvidos durante o Trabalho de Graduação em Estatística "Uma abordagem estatística sobre a estimação de _redshifts_ de quasares usando dados do S-PLUS".
 
## Análise Descritiva
A análise descritiva foi realizada a fim de explorar o comportamento dos dados e das principais variáveis, buscando extrair informações iniciais. Além disso, a tratativa dos valores faltantes e a criação das _colors_ foi realizada neste notebook.

## Dados
Arquivo compactado com os dados utilizados em cada _fold_ para treinamento e validação do modelo, e os dados de teste.

## Densidade Condicional no R - Colors
O script apresenta a construção da modelagem e visões gráficas usando as covariáveis de _colors_ na abertura PStotal.

## Predições médias das PDF's
Arquivo compactado com os arquivos em RDS que contém as estimativas médias de densidade condicional no conjunto de teste.

## Visualização dos _PIT values_
Neste Jupyter Notebook construímos o histograma para os _pit values_. A visualização desejada não pôde ser realizada no programa R, por isso encontra-se separada da modelagem.
