# Análise Exploratória — Vacinação COVID-19 (Amazonas)

## Objetivo  
Este projeto tem como objetivo realizar uma análise exploratória dos dados de vacinação contra a COVID-19 no estado do Amazonas, buscando identificar padrões temporais, distribuição de doses e comportamento de adesão às doses de reforço conforme a idade.

## Base de Dados
Foi utilizada uma base pública e oficial do governo contendo registros individuais de vacinação, incluindo informações como data de aplicação, tipo de dose (1ª, 2ª, 3ª, reforços), idade do indivíduo e outras variáveis relacionadas à imunização.  
A base disponibilizada no site do [Portal de Dados Abertos do SUS](https://dadosabertos.saude.gov.br/dataset/covid-19-vacinacao) possui 8 arquivos abrangendo dados de todo o país. Cada estado (incluindo o Distrito Federal) possui 5 CSVs com milhões de linhas de registros. Devido a dimensionalidade do dataset, foi selecionado somente um CSV da região do Amazonas para fazer a análise.  
(O arquivo CSV original não está incluído no repositório devido ao seu grande tamanho, pois o Github não permite upload de arquivos com mais de 100MB.)  

## Análises Realizadas
### 1. Evolução temporal das vacinas
- Gráficos de barras empilhadas por ano
- Distribuição mensal das doses aplicadas
- Separação por tipo de dose

### 2. Distribuição das doses
- Histogramas para visualizar a distribuição
- Análise de frequência das diferentes categorias de dose

### 3. Relação entre idade e adesão às doses
- Criação de faixas etárias
- Tabela cruzada entre faixa etária e tipo de dose
- Gráfico de barras empilhadas normalizadas (proporção)
- Análise da continuidade das doses de reforço por idade

## Principais Insights
- Identificação de variações sazonais na aplicação das vacinas.
- Diferenças na adesão às doses de reforço entre faixas etárias.
- Evidências de redução na continuidade das doses em determinados grupos.
