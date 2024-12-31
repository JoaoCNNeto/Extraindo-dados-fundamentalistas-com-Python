Python para Finanças - Análise fundamentalista de ativos:

1.Extração de Dados: Utiliza a biblioteca fundamentus para extrair dados financeiros e fundamentalistas de empresas listadas na Bovespa.

2.Instalação e Importação: Instala a biblioteca fundamentus e importa-a junto com pandas para manipulação de dados.

3.Leitura da Carteira de Ativos: Lê os dados dos ativos de uma carteira fictícia, ajusta os tipos de dados e renomeia colunas para facilitar a análise.

4.Adição de Dados: Cria um novo DataFrame com dados adicionais usando a função get_resultado_raw() e concatena com os dados iniciais.

5.Criação de Indicadores: Adiciona indicadores importantes como LPA (Lucro por Ação) e VPA (Valor Patrimonial por Ação).

6.Visualização e Análise: Realiza testes na tabela consolidada, utilizando filtros, agrupamentos e visualizações para analisar os dados.

7.Filtragem Avançada: Filtra os dados por múltiplos indicadores, como P/L (Preço sobre Lucro) e P/VP (Preço pelo Valor Patrimonial), e cria uma coluna calculada chamada Valor Intrínseco.

8.Visualização Gráfica: Gera gráficos simples, como um gráfico de barras com os 10 maiores DY (Dividend Yield) da tabela.
