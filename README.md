Modelo de Previsão de Preços para Aluguel de Apartamentos em Nova York
Descrição
Este projeto tem como objetivo criar um modelo de previsão de preços para apartamentos temporários na cidade de Nova York. O modelo ajudará investidores a tomar decisões informadas sobre os preços de aluguel, considerando diversos fatores que influenciam a precificação.

Análise Exploratória dos Dados (EDA)
A análise exploratória dos dados visa compreender as principais características e relações entre as variáveis. Algumas hipóteses de negócio que exploramos incluem:

Localização e Preço: Investigamos se a localização, especificamente o bairro e a área, influenciam significativamente no preço do aluguel.
Temporada e Disponibilidade: Analisamos se o número mínimo de noites e a disponibilidade ao longo do ano impactam os preços, considerando possíveis períodos de alta demanda.
Nome do Local e Valor: Verificamos se o padrão no texto do nome do local está correlacionado com valores mais elevados.
Perguntas de Negócio
a. Sugestão de Investimento: Com base na análise, sugerimos áreas específicas para investir em apartamentos visando aluguel.
b. Impacto de Noites Mínimas e Disponibilidade: Avaliamos se o número mínimo de noites e a disponibilidade ao longo do ano afetam os preços.
c. Padrão no Nome do Local: Investigamos se há uma relação entre o padrão no nome do local e valores mais elevados.

Previsão de Preços
Para prever os preços, utilizamos um modelo de regressão considerando variáveis como localização, tipo de quarto, número mínimo de noites, entre outras. Optamos por um modelo de regressão linear devido à interpretabilidade e simplicidade. A métrica escolhida para avaliar o modelo é o Erro Quadrático Médio (RMSE), que mensura a precisão da previsão.

Sugestão de Preço
Para um apartamento com as características fornecidas (localizado em Midtown, com 1 noite mínima, 355 dias de disponibilidade, etc.), sugerimos um preço de $225 por noite.

Entregas
Análise Exploratória e Respostas às Perguntas de Negócio: Os resultados detalhados estão disponíveis no relatório em [PDF/Jupyter Notebook].
Códigos e Modelagem: Todos os códigos utilizados na análise exploratória e modelagem estão disponíveis no [Jupyter Notebook].
Modelo Salvo: O modelo de previsão foi salvo no formato .pkl e está disponível no repositório.
Requisitos: O arquivo requirements.txt contém a lista de pacotes necessários e suas versões.
