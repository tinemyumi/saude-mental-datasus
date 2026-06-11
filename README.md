# Desigualdade em Saúde Mental no Estado de São Paulo: Uma Análise Espacial e Temporal das Internações Psiquiátricas (2015–2025)

## Autores

* Larissa Yumi Tinem
* Leo Tsuchida Hoçoya

## Resumo

Este projeto investiga a evolução das internações psiquiátricas no Estado de São Paulo entre 2015 e 2025, com foco nos impactos da pandemia de COVID-19 e na distribuição territorial dos serviços de saúde mental.

Utilizando dados públicos do DATASUS, CNES e IBGE, foram realizadas análises descritivas, temporais e espaciais para identificar mudanças no perfil das internações, padrões regionais e possíveis desigualdades no acesso à assistência em saúde mental.

## Objetivos

* Caracterizar o perfil das internações psiquiátricas no Estado de São Paulo;
* Avaliar o impacto da pandemia de COVID-19 sobre as taxas de internação;
* Investigar padrões espaciais de distribuição das internações;
* Analisar a relação entre cobertura de CAPS e indicadores de internação;
* Identificar fluxos intermunicipais e inter-regionais de atendimento.

## Fontes de Dados

| Base    | Descrição                                               |
| ------- | ------------------------------------------------------- |
| SIH-SUS | Internações hospitalares por transtornos mentais        |
| CNES    | Cadastro Nacional de Estabelecimentos de Saúde          |
| IBGE    | Estimativas populacionais municipais                    |
| DRS     | Departamentos Regionais de Saúde do Estado de São Paulo |

## Estrutura do Repositório

```text
saude-mental-datasus/
│
├── Dataset/
│   └── Bases utilizadas no estudo
│
├── Dicionário de Variáveis/
│   ├── SIH-SUS.md
│   ├── Estabelecimentos - CAPS.md
│   ├── População - IBGE.md
│   ├── DRS.md
│   └── Base Analítica.md
│
└── notebooks/
    ├── 1.download_sihsus_ibge.ipynb
    │   └── Extração dos dados do SIH-SUS e IBGE
    │
    ├── 2.concat_periodos_pandemia.ipynb
    │   └── Consolidação dos períodos pré, pandemia e pós-pandemia
    │
    ├── 3.tratamento_dados_sihsus.ipynb
    │   └── Limpeza e padronização dos dados
    │
    ├── 4.consolidacao_base_analitica.ipynb
    │   └── Construção da base analítica final
    │
    ├── 5.visao_geral.ipynb
    │   └── Estatísticas descritivas gerais
    │
    ├── 7.perfil_sociodemografico.ipynb
    │   └── Análise de sexo, idade e raça/cor
    │
    ├── 8.diagnostico_internacao.ipynb
    │   └── Análise dos grupos diagnósticos (CID-10)
    │
    ├── 9.analise_drs.ipynb
    │   └── Fluxos intermunicipais e entre DRS
    │
    ├── 11.testes_estatisticos.ipynb
    │   └── Shapiro-Wilk, Kruskal-Wallis e pós-teste de Dunn
    │
    └── 12.modelagens.ipynb
        └── ITS, Moran Global, LISA e modelo SAR
```

## Metodologia

### Análise Descritiva

* Perfil sociodemográfico;
* Diagnósticos;
* Mortalidade;
* Tempo de permanência.

### Análise Temporal

* Séries Temporais Interrompidas (ITS);
* Avaliação dos efeitos da pandemia de COVID-19.

### Análise Espacial

* Índice Global de Moran;
* Indicadores Locais de Associação Espacial (LISA);
* Modelo Autorregressivo Espacial (SAR).

## Principais Tecnologias

* Python
* Pandas
* NumPy
* GeoPandas
* Matplotlib
* Seaborn
* PySAL
* Statsmodels
* Scikit-Learn

## Documentação

A descrição completa das variáveis utilizadas encontra-se na pasta:

📁 **Dicionário de Variáveis**

## Licença

Projeto desenvolvido para fins acadêmicos.
