# 🚀 Análise de Dados - Geek Store Sales 🤓

Bem-vindo ao meu repositório de aprendizado em Análise de Dados! Este projeto foi desenvolvido utilizando a biblioteca **Pandas** no Python para explorar, limpar, manipular e extrair insights valiosos de um conjunto de dados de vendas de uma loja Geek fictícia.

## 📌 Objetivo do Projeto
O objetivo principal deste projeto foi praticar manipulação de dados em Python, respondendo a perguntas de negócios como: quais são os produtos mais bem avaliados, quais dão mais lucro, e como filtrar categorias específicas para análise direcionada (como peças de Hardware e Periféricos).

## 🛠️ Tecnologias e Ferramentas
* **Python 3**
* **Pandas** (Análise e manipulação de dados)
* **Google Colab** (Ambiente de desenvolvimento)

## 📊 Etapas de Desenvolvimento & Aprendizados

### 1. Exploração Inicial dos Dados
* Importação da base de dados com `pd.read_csv()`.
* Análise estatística descritiva usando `.describe()` e `.info()` para entender tipos de dados e distribuições de preços e quantidades.

### 2. Rankings de Avaliações (Top 5)
Utilizando ordenação de valores através de `.sort_values()` e limitação de resultados com `.head()`:
* **Top 5 Melhores Avaliações:** Ordenação decrescente (`ascending=False`) para identificar os queridinhos dos clientes (como *Zelda: Tears of the Kingdom* e *Nintendo Switch* com notas altíssimas).
* **Top 5 Piores Avaliações:** Ordenação crescente (`ascending=True`) para mapear produtos que necessitam de atenção ou feedback.

### 3. Engenharia de Recursos (Feature Engineering)
Criação de novas métricas cruciais para o negócio:
* **Receita Total:** Calculada multiplicando a quantidade vendida pelo preço de venda.
* **Lucro por Unidade:** Diferença entre o preço de venda e o custo do fabricante.
* **Lucro Final:** Lucro unitário multiplicado pela quantidade total vendida.

### 4. Filtros Avançados (Boolean Indexing)
* Filtragem de produtos focados em informática/PC utilizando condições lógicas para extrair apenas a categoria de **Hardware** e **Periféricos**, refinando a visualização apenas para as colunas de `Produto` e `Categoria`.

### 5. Exportação de Dados
* Salvamento do progresso em um novo arquivo estruturado usando `.to_csv('vendas_geek_store_novo.csv')`.

---

## 📈 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   ```
2. Certifique-se de ter o arquivo `vendas_geek_store.csv` no mesmo diretório.
3. Instale o Pandas caso não tenha:
   ```bash
   pip install pandas
   ```
4. Execute o notebook ou arquivo `.py` para reproduzir as análises.

## 🧠 Conclusão & Próximos Passos
Este projeto foi fundamental para consolidar conceitos de manipulação de DataFrames, lógica de filtros e cálculos de indicadores de performance financeira (KPIs). Os próximos passos incluem a criação de gráficos utilizando `matplotlib` ou `seaborn` para enriquecer visualmente a análise.

---
💡 *Projeto desenvolvido para fins de estudo e evolução técnica em Ciência de Dados.* 
```
