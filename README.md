# 📊 Dashboard de Gestão de Farmácia — Power BI

Este é o repositório do meu primeiro dashboard desenvolvido em **Power BI**, focado na análise de dados e acompanhamento de indicadores do setor farmacêutico/drogaria.

---

## 📌 Visão Geral do Projeto

O objetivo deste painel é fornecer uma visão analítica sobre o desempenho de vendas, estoque, produtos e clientes de uma rede de farmácias. A ferramenta permite aos gestores tomarem decisões baseadas em dados para otimização de estoque, estratégia de preços e desempenho de vendas.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Power BI Desktop**: Construção do modelo de dados, medidas DAX e visualizações.
* **Power Query**: Processamento, limpeza e transformação dos dados.
* **Modelo de Dados (Star Schema)**: Relacionamento entre tabelas facto e dimensões para otimização de performance.

---

## 📐 Estrutura do Modelo de Dados

O modelo foi construído utilizando boas práticas de modelação multidimensional:

* **Tabelas Fato**:
  * `fVendas`: Registro detalhado das transações de vendas.
* **Tabelas Dimensão**:
  * `dProdutos`: Cadastro de medicamentos, cosméticos e categorias.
  * `dClientes`: Informações demográficas e perfil dos compradores.
  * `dCalendario`: Tabela de dimensão de tempo para análises temporais.
  * `dLojas / dFiliais`: Mapeamento das unidades físicas da farmácia.

---

## 📈 Principais Métricas e Indicadores (KPIs)

* **Faturação Total (€ / R$)**: Receita bruta acumulada no período.
* **Quantidade de Itens Vendidos**: Volume total de produtos comercializados.
* **Análise de Margem e Lucro**: Lucratividade por categoria de produto (ex: Medicamentos vs. Perfumaria/Higiene).
* **Comparativo Temporal**: Análise Ano contra Ano (*Year-over-Year* - YoY) e Mês contra Mês (*Month-over-Month* - MoM).

---

## 🎨 Design e Layout

* **Tema Visual**: Desenvolvido com uma paleta de cores moderna e acessível, alinhada à identidade do setor de saúde/farmácia (tons de azul, verde e neutros).
* **Navegação**: Filtros interativos por período, categoria de produto e filial para facilitar a exploração dos dados.

---

## 🚀 Como Visualizar o Relatório

1. Faz o download do ficheiro `.pbix` localizado na pasta raiz deste repositório.
2. Abre o ficheiro no **Power BI Desktop** (versão atualizada).
3. Interage com os filtros e visuais na página principal.

---

📬 Contato
Email: isabela.calisto.oliveira@gmail.com
Feito por Isabela Calisto
