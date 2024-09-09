# Previsão de Preços de Ações do Walmart

Este projeto utiliza dados históricos de preços de ações do Walmart para realizar uma análise exploratória e modelagem preditiva usando o modelo ARIMA. A análise inclui visualizações gráficas para entender a evolução dos preços ao longo do tempo, bem como a aplicação de um modelo ARIMA para prever os preços futuros.

## Estrutura do Projeto

- **importação de bibliotecas**: Carrega bibliotecas como `pandas`, `matplotlib`, `seaborn` e `statsmodels` necessárias para manipulação de dados, visualização e modelagem.
- **Carregamento de Dados**: Os dados são carregados de um arquivo CSV hospedado no Google Drive.
- **Análise Exploratória de Dados (EDA)**: Inclui visualizações de séries temporais, boxplots, correlações e histogramas dos preços de fechamento.
- **Divisão de Dados**: Os dados são divididos em conjuntos de treino (80%) e teste (20%).
- **Modelagem ARIMA**: Implementa um modelo ARIMA para prever os preços de fechamento das ações.
- **Avaliação de Previsão**: A previsão é avaliada usando a métrica RMSE (Root Mean Squared Error).

## Visualizações

1. **Evolução do Preço de Fechamento**: Gráfico de linha mostrando a evolução dos preços de fechamento ao longo dos anos.
2. **Boxplot por Ano**: Mostra a distribuição dos preços de fechamento por ano.
3. **Matriz de Correlação**: Apresenta a correlação entre variáveis como `Open`, `High`, `Low`, e `Close`.
4. **Histograma**: Distribuição dos preços de fechamento.
5. **Séries Temporais de Treino e Teste**: Visualização da divisão dos dados em conjuntos de treino e teste.

## Instalação

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
Instale as bibliotecas necessárias
pip install -r requirements.txt
Execução
Para rodar o projeto, basta executar o script Python com os seguintes comandos
python nome_do_arquivo.py
Estrutura do Arquivo
nome_do_arquivo.py: Contém o código principal para análise de dados e modelagem ARIMA.
README.md: Este arquivo, com uma descrição detalhada do projeto.
.gitignore: Define arquivos e diretórios que serão ignorados pelo Git (ver abaixo).
gitignore
O arquivo .gitignore contém itens que não devem ser rastreados pelo Git, como dados temporários, cache e outros arquivos desnecessários para o repositório.

Resultado
O modelo ARIMA é avaliado com base no RMSE. Um gráfico de comparação entre valores reais e previstos é gerado para visualizar a eficácia do modelo.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um Pull Request com melhorias ou sugestões.
