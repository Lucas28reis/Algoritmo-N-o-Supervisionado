# Análise de Dados e Agrupamento

**Objetivo:**
O presente notebook tem como objetivo realizar uma análise aprofundada dos dados referentes a diversos países, explorando indicadores-chave como a taxa de mortalidade infantil, expectativa de vida, PIB per capita, entre outros. O foco principal é a aplicação de algoritmos de agrupamento, nomeadamente K-Means e DBSCAN, para identificar padrões e segmentar os países em grupos com características semelhantes.

**Conteúdo:**
1. **Introdução e Carregamento dos Dados:**
   - Carregamento do conjunto de dados sobre diferentes países.
   - Verificação inicial da estrutura do conjunto de dados.

2. **Análise Exploratória e Pré-Processamento:**
   - Matriz de correlação para avaliar a interação entre os indicadores.
   - Estatísticas descritivas para entender a distribuição dos dados.
   - Visualização da faixa dinâmica por meio de box plots.
   - Normalização dos dados para preparação da aplicação dos algoritmos.

3. **K-Means:**
   - Aplicação do algoritmo K-Means para agrupar os países.
   - Identificação e análise dos clusters formados.
   - Visualização dos clusters por meio de gráficos e box plots.

4. **Clusterização Hierárquica:**
   - Utilização da Clusterização Hierárquica com base na expectativa de vida e taxa de mortalidade infantil.
   - Determinação do número de clusters e visualização do dendrograma.
   - Análise dos clusters e identificação dos países em cada grupo.

5. **DBSCAN:**
   - Aplicação do algoritmo DBSCAN para detecção de padrões de densidade.
   - Análise dos clusters e identificação de outliers.
   - Visualização dos clusters e outliers em gráficos.

6. **Comparação entre K-Means e DBSCAN:**
   - Discussão sobre as diferenças nos resultados obtidos pelos dois algoritmos.
   - Destaque para a sensibilidade do K-Means a outliers e a robustez do DBSCAN em lidar com densidades variáveis.

7. **Conclusões e Links Úteis:**
   - Síntese das principais descobertas e conclusões.
   - Link para o notebook original no Google Colab.

**Observação:**
O notebook original está disponível [aqui](https://colab.research.google.com/drive/1PtAvT7rLFASsNjgA-JCb1n48-sXMZRuJ). Recomenda-se a execução do código no ambiente do Google Colab para interação completa com visualizações e resultados.
