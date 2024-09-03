# Análise de Dados com Python

Este repositório contém quatro notebooks que exploram diversos exercícios e análises de dados utilizando Python. As análises foram realizadas com bibliotecas como `pandas`, `seaborn`, `matplotlib`, `plotly`, e `scikit-learn`, entre outras. Abaixo, detalhamos o conteúdo de cada notebook.

## Estrutura dos Notebooks

### Notebook 1: Análise de Vendas no Varejo

**Bibliotecas Utilizadas:**
- `pandas`
- `seaborn`
- `matplotlib`
- `plotly`
- `scikit-learn`

**Resumo das Análises e Códigos:**
- Importação e limpeza dos dados de vendas (`varejo.xlsx`).
- Tratamento de valores ausentes e duplicados.
- Ajustes em colunas de preços, cálculo de descontos e criação de novas colunas.
- Análise de correlação entre preços e descontos usando `heatmap` e `scatterplot`.
- Análise de vendas por estado e bandeira.
- Visualização de vendas por mês e por departamento.
- Integração de dados de clientes e análise de renda.
- Modelo de Regressão Linear para prever o preço líquido com base em variáveis como `bandeira`, `Preço_bruto` e `renda`.

### Notebook 2: Análise de Aluguéis de Casas

**Bibliotecas Utilizadas:**
- `pandas`
- `seaborn`
- `plotly`

**Resumo das Análises e Códigos:**
- Importação e visualização de dados de aluguel (`houses_rent.xlsx`).
- Cálculo de taxas e criação de novas colunas com valores totais.
- Análise de correlação entre valores de aluguel, taxas e seguro.
- Gráficos de dispersão para explorar relações entre número de quartos, área total e seguro contra incêndio.
- Visualização de média de aluguel por cidade e andar com gráficos de barras e box plots.
- Regressão linear para analisar a relação entre área e valores totais.

### Notebook 3: Análise Temporal e de Clientes no Varejo

**Bibliotecas Utilizadas:**
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

**Resumo das Análises e Códigos:**
- Análise de vendas ao longo do tempo, incluindo a visualização de séries temporais e linhas de tendência.
- Segmentação de clientes por faixa etária e análise da renda média.
- Análise mensal da média de preços com frete.
- Comparação de vendas entre duas bandeiras de produto ao longo do tempo.

### Notebook 4: Análise do Mercado Imobiliário nos EUA

**Bibliotecas Utilizadas:**
- `pandas`
- `numpy`
- `seaborn`
- `plotly`
- `matplotlib`

**Resumo das Análises e Códigos:**
- Análise de dados de moradias nos EUA (`USA_Housing.csv`), incluindo tratamento de variáveis e criação de novas colunas para faixas etárias das casas.
- Gráficos de dispersão para analisar a relação entre renda média da área e preço dos imóveis.
- Implementação de uma função para calcular estatísticas descritivas de forma personalizada (média, mediana, desvio padrão, quartis).
- Análise de variância para determinar diferenças significativas nos preços com base na idade média das casas.
- Visualização das distribuições de todas as colunas numéricas com histogramas e pares de gráficos de dispersão.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
3. Execute os notebooks no Jupyter Notebook ou Jupyter Lab.

## Conclusão

Cada notebook contém uma abordagem prática e detalhada para diferentes problemas de análise de dados, desde a limpeza e transformação dos dados até a aplicação de modelos preditivos simples. As visualizações fornecem insights valiosos sobre os padrões e tendências nos conjuntos de dados analisados.

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
