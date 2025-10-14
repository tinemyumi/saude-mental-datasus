# 📊 Projeto: Processamento de Dados SIH-SUS

Este repositório contém os códigos em Python utilizados para:

1. Baixar os dados do SIH-SUS diretamente com a biblioteca pysus.
2. Enviar os dados para o Google Drive para armazenamento.
3. Acessar os dados no Google Drive e manipulá-los em análises posteriores.

## 🚀 Estrutura dos arquivos

- setup.ipynb → Script responsável por baixar os datasets do SIH-SUS utilizando pysus e enviá-los ao Google Drive.
- acesso_dados.ipynb → Script para acessar os arquivos já armazenados no Google Drive e carregá-los em DataFrames do pandas.

## 📦 Dependências

Para executar os notebooks, instale as bibliotecas necessárias:
- pip install pandas pysus

## 🔑 Como usar

1. Abra o repositório no **Google Colab**.  
2. Execute o notebook `setup.ipynb` para baixar os dados do SIH-SUS e salvar no Google Drive.  
3. Execute o notebook `acesso_dados.ipynb` para carregar os arquivos salvos no Google Drive.  

## 📂 Dataset

Os datasets utilizados são do SIH-SUS e foram baixados por meio da biblioteca pysus.
Eles estão organizados em pastas no Google Drive e podem ser acessados pelos notebooks.
