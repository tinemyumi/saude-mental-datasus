# Dicionário de Variáveis

Esta pasta contém a documentação das bases de dados utilizadas no projeto.

## Bases Documentadas

- [SIH-SUS](SIH-SUS.md) – Informações de internações hospitalares.
- [Estabelecimentos - CAPS](Estabelecimentos%20-%20CAPS.md) – Cadastro dos Centros de Atenção Psicossocial.
- [População - IBGE](População%20-%20IBGE.md) – Estimativas populacionais municipais.
- [DRS](DRS.md) – Departamentos Regionais de Saúde.
- [Base Analítica](Base%20Analítica.md) – Base consolidada utilizada nas análises.

## Fluxo dos Dados

SIH-SUS + CNES (CAPS) + IBGE + DRS
↓
Integração e tratamento
↓
Base Analítica
↓
Análises descritivas
↓
Análises temporais (ITS)
↓
Análises espaciais (Moran, LISA e SAR)
