# Projeto Indicium

Este projeto tem como objetivo desenvolver um modelo de previsão de preços para aluguéis temporários na cidade de Nova York.

#Desafio

O desafio é : desenvolver um modelo de previsão de preços utilizando o dataset fornecido. O cliente está interessado em entender os padrões de preços do concorrente e, consequentemente, espera uma estratégia de precificação sólida baseada nessa análise

#Objetivos

Realizar uma análise exploratória dos dados fornecidos, buscando insights valiosos sobre os padrões de preços.
Desenvolver um modelo preditivo eficaz para estimar os preços de aluguéis temporários em Nova York.
Avaliar o desempenho do modelo utilizando métricas de avaliação pertinentes ao problema

#Dados

No diretório do projeto, você encontrará um arquivo com um dicionário dos dados fornecidos. Este documento fornecerá uma visão detalhada das variáveis presentes no dataset, ajudando na compreensão e manipulação dos dados


## Instruções de Execução

 Certifique-se de ter o Python e o ambiente virtual instalados.

1. Clone o repositório:

```bash
git clone https://github.com/RaquelFonsec/Challenge-Indicium.git

2-Navegue até o diretório do projeto
cd Challenge-Indicium

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate   # No Windows, use 'venv\Scripts\activate'

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook Jupyter
jupyter notebook

## Gerar PDF

Após a execução do notebook, um arquivo PDF será gerado. Para abri-lo, você pode usar o seguinte comando, dependendo do seu sistema operacional:

- No Linux ou macOS:
  ```bash
  xdg-open Indicium.pdf

No Windows
start Indicium.pdf

