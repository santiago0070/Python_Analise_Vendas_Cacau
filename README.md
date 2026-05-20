# Análise de Performance de Vendas Globais - ChocoGlow

Este repositório contém o pipeline de dados focado na extração, tratamento e visualização do desempenho comercial da ChocoGlow S.A., permitindo rastrear o faturamento histórico e a performance das categorias de produtos em múltiplos países.

## 🚀 Tecnologias Utilizadas
* **Python 3.10+**
* **Pandas**: Limpeza, tipagem e agregação de dados.
* **Plotly**: Construção de gráficos interativos e exportação de imagens de alta resolução.

## 🛠️ Pipeline de Engenharia de Dados (ETL)
1. **Ingestão**: Leitura de dados transacionais complexos com separadores customizados.
2. **Tratamento**: Conversão de dados monetários textuais em valores numéricos (`float64`) e padronização do campo de datas.
3. **Modelagem**: Agrupamento lógico por eixos temporais (Anos) e mercadológicos (Categorias).

## 📊 Principais Insights de Negócio
* **Crescimento Sustentável**: A análise histórica aponta uma tendência de alta consistente no faturamento global ano a ano.
* **Mix de Produtos**: Categorias como Chocolates Tradicionais e Barras concentram a maior representatividade no faturamento total, indicando os produtos core para campanhas de tração.
* **Eficiência de Escoamento**: O cruzamento entre caixas enviadas e faturamento permitiu identificar flutuações no ticket médio anual, servindo de base para reajustes de preço/tabela de frete internacional.

## 🏃 Como Executar o Projeto
1. Instale as dependências: `pip install -r requirements.txt`
2. Abra e execute o notebook: `jupyter notebook notebook/codigo.ipynb`
