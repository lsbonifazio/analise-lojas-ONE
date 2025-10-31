# 🏪 Análise de Desempenho das Lojas — Desafio ONE + Alura

Este projeto foi desenvolvido como parte do **programa Oracle Next Education (ONE)**, em parceria com a **Alura**, durante a fase de **especialização em Data Science**.  
Nessa etapa, estou **aprendendo e aplicando conceitos de Python e Pandas** para realizar análises de dados e criar visualizações que apoiam a tomada de decisão.

---

## 🎯 Objetivo do Projeto

O objetivo é **analisar o desempenho de quatro lojas** do Senhor João e identificar **qual delas apresenta pior performance e deve ser vendida**.  
Para isso, foram avaliados múltiplos fatores relacionados às vendas e à satisfação dos clientes.

---

## 📊 Indicadores Analisados

- **Faturamento total** de cada loja  
- **Categorias de produtos mais e menos vendidas**  
- **Avaliação média dos clientes**  
- **Produtos com maior e menor volume de vendas**  
- **Frete médio**  
- **Distribuição geográfica das vendas (latitude e longitude)**

---

## 🧠 Metodologia

1. **Coleta e preparação dos dados**  
   Cada loja foi analisada individualmente (loja1, loja2, loja3 e loja4).  
   As principais colunas utilizadas foram: *Preço*, *Categoria do Produto*, *Avaliação da Compra*, *Frete* e *Coordenadas (lat, lon)*.

2. **Análise exploratória (EDA)**  
   Foram calculadas métricas, identificadas tendências e comparados desempenhos entre as lojas.

3. **Visualizações**  
   Gráficos de barras e mapas de calor (heatmaps) foram utilizados para demonstrar os resultados de forma clara e visual.

4. **Conclusão**  
   A loja com menor desempenho geral foi recomendada para venda com base em evidências quantitativas.

---

## 📈 Principais Resultados

| Loja | Faturamento (R$) | Avaliação Média | Frete Médio (R$) | Situação Recomendada |
|------|------------------:|----------------:|-----------------:|----------------------|
| Loja 1 | 1.534.509,12 | 3,98 | 34,69 | Manter |
| Loja 2 | 1.488.459,06 | 4,04 | 33,62 | Manter |
| Loja 3 | 1.464.025,03 | 4,05 | 33,07 | Manter |
| Loja 4 | 1.384.497,58 | 3,99 | 31,28 | **Vender** |

---

## 🌍 Distribuição Geográfica

Os mapas de calor mostram que as vendas estão **distribuídas por todo o Brasil**, com **maior concentração nas regiões Sudeste e Sul** (principalmente em São Paulo, Minas Gerais e Paraná).  
Todas as lojas apresentam **alcance geográfico semelhante**, indicando que **a localização não é um fator determinante no desempenho**.

---

## 🧰 Tecnologias Utilizadas

- **Python 3.12**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Folium**
- **GeoPandas**
- **Google Colab**

---

## 📂 Estrutura do Projeto

```
analise-lojas-ONE/
│
├── README.md
├── analise_lojas.ipynb
├── dados_loja1.csv
├── dados_loja2.csv
├── dados_loja3.csv
├── dados_loja4.csv
│
├── imagens/
│   ├── grafico_avaliacoes.png
│   ├── grafico_faturamento.png
│   ├── grafico_frete.png
│   ├── produtos_mais_vendidos.png
│   ├── produtos_menos_vendidos.png
│   ├── heatmap_vendas_categoria.png
│   └── heatmap_vendas_Brasil.png
│
└── outputs/
    └── relatorio_avaliacao.pdf
```

---

## 🚀 Como Executar

1. Clone o repositório:
   ```
   git clone https://github.com/seuusuario/analise-lojas.git
   ```
2. Instale as dependências:
   ```
   pip install pandas matplotlib seaborn folium geopandas
   ```
3. Abra o notebook:
   ```
   jupyter notebook analise_lojas.ipynb
   ```
4. Execute as células em sequência para reproduzir as análises e visualizações.

---

## 🧾 Conclusão

Com base nas análises realizadas, a Loja 4 apresentou o pior desempenho geral, com menor faturamento e avaliações ligeiramente inferiores.
Portanto, é a mais indicada para venda.
As demais lojas demonstraram resultados estáveis e desempenho consistente, recomendando-se sua manutenção.

---

## 👩‍💻 Autora

**Letícia Schulz Bonifazio**  
📧 [lsbonifazio@gmail.com](mailto:lsbonifazio@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/lsbonifazio)  
📍 São Paulo — Brasil  
🧠 Programa **Oracle Next Education (ONE)** — Especialização em **Data Science (Alura)**
