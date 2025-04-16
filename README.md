# desafio_alura_data_science

# Análise de Desempenho das Lojas do Senhor João

Este repositório contém um projeto de análise de dados que avalia o desempenho das lojas do Senhor João. O objetivo foi identificar qual unidade apresenta indicadores menos favoráveis para, assim, fundamentar a decisão de venda dessa loja. Foram utilizadas as bibliotecas Python **Pandas**, **Matplotlib**, **Seaborn** e **Folium**, e o projeto foi desenvolvido no Google Colab.

## Conteúdo do Projeto

### 1. Faturamento Total
- Análise do volume de receitas de cada loja.
- Comparação para identificar a unidade com menor faturamento.

### 2. Categorias de Produtos
- Identificação das categorias de produtos mais e menos vendidas.
- Visualizações (gráficos de barras) que mostram o total de vendas de cada categoria e destacam as categorias mais populares por loja.

### 3. Avaliações dos Clientes
- Cálculo da média das avaliações de clientes por loja.
- Visualizações alternativas (barras, pointplots, lollipop charts) para uma melhor percepção do desempenho em termos de satisfação.

### 4. Produtos Mais e Menos Vendidos
- Agrupamento dos dados para identificar quais produtos se destacam e quais não alcançam os volumes esperados.
- Métricas comparativas que evidenciam pontos fortes e fracos do mix de produtos.

### 5. Análise de Frete
- Cálculo do frete médio e do gasto total com frete por loja.
- Gráficos de pizza que integram o custo médio e o total de frete, permitindo a comparação entre as unidades.

### 6. Análise Geográfica
- Exploração das coordenadas geográficas (latitude e longitude) para mapear a distribuição das vendas.
- Geração de gráficos de dispersão, heatmaps e mapa interativo com Folium para identificar regiões com maior concentração de transações.
- Investigação de como as variáveis geográficas podem influenciar o faturamento e as avaliações das lojas.

## Conclusões e Recomendações

Após a análise integrada dos indicadores (faturamento, mix de produtos, avaliações, desempenho de frete e dados geográficos), a **Loja 4** foi identificada como a candidata ideal para venda. Os principais pontos que embasam essa recomendação são:

- **Faturamento Inferior:** A Loja 4 gera o menor volume de receita.
- **Mix de Produtos Menos Atrativo:** As categorias e os produtos vendidos não conseguem atingir volumes significativos.
- **Avaliações de Clientes Baixas:** A percepção dos clientes é inferior se comparada às demais unidades.
- **Frete Elevado:** Os custos operacionais com frete impactam negativamente as margens.
- **Distribuição Geográfica:** A concentração de vendas e a presença dos clientes indicam menor potencial de crescimento nesta região.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
