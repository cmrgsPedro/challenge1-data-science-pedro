# Projeto de Análise de Desempenho: Alura Store

Este repositório contém a análise de dados realizada para o primeiro desafio de Data Science da Formação em Dados da Alura.

## 🎯 Objetivo

O projeto visa auxiliar o Sr. João, proprietário da rede fictícia "Alura Store", a tomar uma decisão estratégica de negócios. A partir da análise de dados de vendas, o objetivo é identificar a loja com o menor desempenho para que ela possa ser vendida, e o capital investido em um novo empreendimento.

## 📖 Contexto

O Sr. João possui quatro lojas e precisa vender uma delas para obter capital. Fui contratado como Analista de Dados para analisar as métricas de negócio de cada loja e, com base nos resultados, fornecer uma recomendação clara e embasada em dados sobre qual unidade apresenta a menor eficiência e, portanto, deveria ser a escolhida para a venda.

## 📊 Dados

A análise foi baseada em quatro conjuntos de dados (um para cada loja) em formato `.csv`. Os datasets continham informações detalhadas sobre as transações, incluindo:

* **Produto e Categoria:** Itens vendidos e suas classificações.
* **Preço e Frete:** Valores das vendas e custos de envio.
* **Data da Compra e Local:** Informações temporais e geográficas das vendas.
* **Avaliação da Compra:** Feedback dos clientes (1 a 5 estrelas).
* **Dados de Pagamento:** Tipo de pagamento e número de parcelas.

## 🛠️ Ferramentas Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
    * `Pandas` para manipulação e análise dos dados.
    * `Matplotlib` para a criação das visualizações.
* **Ambiente:** Google Colab.

## 📈 Análise Realizada

Para chegar à recomendação final, a análise foi dividida em cinco etapas principais:

1.  **Faturamento Total por Loja:** Cálculo da receita total para identificar o desempenho financeiro de cada unidade.
2.  **Vendas por Categoria:** Análise da distribuição de vendas para entender o perfil de consumo de cada loja.
3.  **Média de Avaliação dos Clientes:** Verificação da satisfação do cliente, um indicador chave de qualidade e lealdade.
4.  **Produtos Mais e Menos Vendidos:** Identificação do desempenho de produtos específicos para encontrar possíveis falhas de estoque ou marketing.
5.  **Custo Médio do Frete:** Análise dos custos operacionais relacionados à logística.

## 💡 Principais Descobertas (Insights)

* A **Loja 4** apresentou o **menor faturamento** da rede, sendo o indicador de desempenho financeiro mais fraco.
* A **Loja 1**, apesar de ser a mais lucrativa, possui a **menor média de satisfação** dos clientes.
* Todas as lojas possuem um perfil de vendas por categoria muito similar, com "móveis" e "eletrônicos" dominando as vendas.
* A **Loja 4** tem o **custo médio de frete mais baixo**, uma vantagem competitiva que não está sendo convertida em vendas.

## 🏆 Conclusão e Recomendação

Com base nos dados, a recomendação final foi a **venda da Loja 4**.

A decisão é justificada principalmente pelo seu **desempenho financeiro inferior** em comparação com as outras unidades. Além disso, a loja demonstra **ineficiência operacional**, pois não consegue transformar suas vantagens (como frete baixo e boa avaliação dos clientes) em resultados de vendas. A venda da Loja 4 permite otimizar a rede, concentrando recursos nas lojas mais lucrativas e estáveis.

## 🚀 Como Executar o Projeto

1.  Clone este repositório.
2.  Faça o upload do notebook `AluraStoreBr.ipynb` para o seu ambiente (Google Drive, se estiver usando Colab).
3.  Abra o notebook no Google Colab.
4.  Execute as células de código em sequência para reproduzir a análise, a geração de gráficos e o relatório final.
