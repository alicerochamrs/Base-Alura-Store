# Alura Store - Análise de Dados de Vendas

Este projeto realiza uma análise exploratória dos dados de vendas de quatro lojas da Alura Store, com o objetivo de identificar padrões, avaliar o desempenho das lojas e extrair insights para otimizar estratégias de vendas.

## 📊 Propósito da Análise

O principal objetivo desta análise é fornecer uma visão abrangente sobre as operações das lojas, abordando os seguintes pontos:

- **Faturamento Total**: Analisar o faturamento bruto de cada loja para identificar as lojas com maior e menor desempenho em termos de receita.
- **Vendas por Categoria de Produto**: Entender quais categorias de produtos geram mais receita e quais são menos significativas.
- **Avaliação da Compra**: Comparar a média das avaliações dos clientes para cada loja, identificando possíveis problemas de satisfação ou excelência no atendimento.
- **Produtos Mais e Menos Vendidos**: Destacar os produtos de maior e menor popularidade para orientar decisões de estoque e marketing.
- **Frete Médio**: Analisar o custo médio de frete por loja para verificar a eficiência logística.

## 📁 Estrutura do Projeto

O projeto está contido em um único notebook Jupyter/Colab, que executa todas as etapas da análise, desde a importação dos dados até a geração de gráficos e insights. Os dados são carregados diretamente de arquivos CSV hospedados no GitHub.

### Arquivos:
- `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`: Arquivos de dados brutos para cada uma das quatro lojas.
- `alura_store_analise.ipynb`: Notebook contendo todo o código Python para a análise.

## 📈 Exemplos de Gráficos e Insights Obtidos

Abaixo estão alguns dos gráficos e insights gerados durante a análise:

### 1. Faturamento Total por Loja
![Faturamento Total por Loja](caminho/para/grafico_faturamento.png)

**Insight**: A Loja 1 apresentou o maior faturamento total (R$ 1.534.509,12), enquanto a Loja 4 teve o menor (R$ 1.384.497,58). Isso indica uma variação de R$ 150.011,54 entre a loja com maior e menor faturamento.

### 2. Faturamento Total por Categoria de Produto
![Faturamento por Categoria](caminho/para/grafico_categorias.png)

**Insight**: A categoria 'eletrônicos' é a principal geradora de receita, seguida por 'eletrodomésticos' e 'móveis', enquanto categorias como 'livros' e 'utilidades domésticas' contribuem com uma fatia menor do faturamento.

### 3. Média de Avaliação por Loja
![Média de Avaliação](caminho/para/grafico_avaliacoes.png)

**Insight**: A Loja 3 possui a maior média de avaliação (4.05), enquanto a Loja 1 tem a menor (3.98), sugerindo que a Loja 3 oferece uma melhor experiência geral ao cliente.

### 4. Produtos Mais e Menos Vendidos
**Insight**: O produto 'Cômoda' é o mais vendido, enquanto 'Celular ABXY' é o menos vendido. Essa informação pode ser crucial para gestão de estoque e campanhas de marketing.

### 5. Média de Frete por Loja
![Média de Frete](caminho/para/grafico_frete.png)

**Insight**: A Loja 1 tem o frete médio mais alto (R$ 34.69), e a Loja 4 o mais baixo (R$ 31.28). Esta diferença pode impactar a competitividade dos produtos ou indicar diferentes estratégias logísticas entre as lojas.

## 🚀 Como Executar o Notebook

Para executar este notebook e reproduzir a análise, siga os passos abaixo:

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/alura-store-analise.git
cd alura-store-analise
