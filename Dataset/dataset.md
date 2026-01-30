# Dataset SIH-SUS

## 1. Descrição geral

O dataset utilizado neste estudo é composto por registros de internações hospitalares do Sistema de Informações Hospitalares do SUS (SIH-SUS), integrando dados demográficos, administrativos e regionais provenientes do IBGE, do Cadastro Nacional de Estabelecimentos de Saúde (CNES) e da divisão regional de saúde do Estado de São Paulo. 

Os dados abrangem o período de 2014 a 2024 e contemplam informações agregadas por município e por período, permitindo a análise da evolução das internações hospitalares ao longo do tempo, com ênfase na comparação entre os períodos pré e pós pandemia de COVID-19. 

O conjunto de dados foi estruturado para apoiar análises estatísticas e temporais sobre padrões de internação, distribuição regional e possíveis impactos de eventos sanitários na demanda por serviços de saúde mental no Estado de São Paulo.

## 2. Fontes de dados

- SIH-SUS (Sistema de Informações Hospitalares do SUS), disponibilizados pelo DATASUS no período de 2014 a 2024;
- Dados censitários disponibilizados pelo Instituto Brasileiro de Geografia e Estatística (IBGE) e obtidos a partir do dataset “Population of Brazilian Municipalities” no Kaggle.
- Cadastro Nacional de Estabelecimentos (CNES)
- Municípios e Divisão Regional de Saúde provenientes do sistema de dados abertos do Governo do Estado de São Paulo. 

**Fontes de coleta dos dados**
- [DATASUS - SIH](https://datasus.saude.gov.br/)
- [Kaggle - Population of Brazil Municipalities](https://www.kaggle.com/datasets/danielkomesu/population-of-brazilian-municipalities)
- [CNES](https://cnes.datasus.gov.br/)
- [Dados Abertos do Governo do Estado de São Paulo](https://dadosabertos.sp.gov.br/dataset/covid)


## 3. Período analisado

O período analisado compreende os anos de 2014 a 2024. A escolha desse intervalo permite observar a evolução das internações hospitalares ao longo de uma década, contemplando tanto o período anterior à pandemia de COVID-19 quanto os anos posteriores à ela.

Para fins analíticos, os dados foram agregados por ano, possibilitando comparações temporais entre os períodos pré-pandemia (2014–2019), durante a pandemia (2020–2022) e pós pandemia (2023 e 2024).

## 4. Formato dos arquivos

Os dados provenientes do SIH-SUS foram armazenados no formato Parquet, visando otimização de desempenho e maior eficiência no processamento de grandes volumes de dados.

As bases auxiliares (dados populacionais do IBGE, informações dos estabelecimentos de saúde do CNES e a divisão regional de saúde) foram utilizadas no formato Excel (.xlsx), conforme disponibilizadas pelas respectivas fontes oficiais.

## 5. Dicionário de variáveis

| Variável | Descrição | Fonte | Tipo |
|--------|----------|-------|------|

## 6. Processo de tratamento

- Filtros aplicados
- Padronizações
- Exclusões
- Agregações

## Reprodutibilidade

📂 Para acessar os arquivos, consulte o link do [Google Drive](https://drive.google.com/drive/folders/1FyCnTO_WZZjEVLsrJwUCdFp7VTFcm5er?usp=sharing).

⚠️ **Atenção**: Os arquivos completos não estão incluídos neste repositório devido ao tamanho.
Para reproduzir os dados, execute os notebooks de acordo com o caminho dos arquivos disponibilizados na pasta do Google Drive.
