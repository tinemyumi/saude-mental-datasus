# Dataset SIH-SUS

Este projeto utiliza dados do SIH-SUS (Sistema de Informações Hospitalares do SUS), disponibilizados pelo DATASUS, e dados populacionais do Brasil e do estado de São Paulo obtidos via API do IBGE (função FetchData, biblioteca Pysus/IBGE). Os resultados da API são retornados em formato JSON e convertidos para .parquet, mantendo a compatibilidade com os arquivos do SIH-SUS.

- Fonte oficial: [DATASUS - SIH](https://datasus.saude.gov.br/) e [IBGE](https://www.ibge.gov.br/)
- Script de download: [`setup.ipynb`]([../setup.ipynb](https://github.com/tinemyumi/saude-mental-datasus/blob/main/codigos-python/setup.ipynb))

📂 Para acessar os arquivos já processados, consulte o link do [Google Drive](https://drive.google.com/drive/folders/1T4dKuhFOq_MzreZ_mWcfEA2ebj-PZMfl?usp=drive_link).

⚠️ **Atenção**: Os arquivos completos não estão incluídos neste repositório devido ao tamanho.
Para reproduzir os dados, execute o notebook setup.ipynb e siga as instruções de conexão com o Google Drive.
