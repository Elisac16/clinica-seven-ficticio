# clinica-seven-ficticio
Este projeto tem como objetivo analisar e visualizar dados de vendas, clientes e produtos de uma loja fictícia. Através de um processo completo de tratamento e modelagem de dados, foi construída uma dashboard em Power BI capaz de fornecer insights relevantes para a tomada de decisões estratégicas.

🧾 Descrição dos Dados

Foram utilizados três arquivos .csv, tratados no Power Query (M), representando a estrutura de um pequeno data warehouse:

dim_usuarios.csv: informações dos clientes, como nome, e-mail, CPF e datas de cadastro.

dim_produtos.csv: catálogo de produtos com nome, preço, estoque e descrição.

fato_pedidos.csv: histórico de pedidos realizados, incluindo valores, formas de pagamento, status e datas.

Os dados são fictícios e simulam um cenário realista de e-commerce para fins de estudo.

🛠️ Ferramentas e Tecnologias Utilizadas

Power BI Desktop para criação de dashboards interativos

Power Query (M) para tratamento e padronização dos dados

DAX (Data Analysis Expressions) para criação de medidas e KPIs

GitHub para versionamento e documentação do projeto

🔧 Processos de Transformação dos Dados

Durante a etapa de preparação dos dados, as seguintes transformações foram realizadas:

Conversão de dados do formato long para wide

Padronização de letras maiúsculas em nomes e descrições

Ajuste de datas para o padrão YYYY-MM-DD

Validação e correção de e-mails e CPFs

Conversão de valores monetários para o tipo float

Expansão e normalização de listas JSON contendo itens dos pedidos

📈 Indicadores e Métricas Apresentadas

A dashboard foi construída com foco em indicadores de desempenho, tais como:

Total de Pedidos

Receita Total

Ticket Médio

Total de Clientes Ativos

Estoque Disponível

Distribuição de Pedidos por Status de Pagamento

📊 Tipos de Visualizações Utilizadas

Para facilitar a interpretação dos dados, foram utilizados os seguintes tipos de gráficos:

Cards: indicadores-chave de desempenho (KPIs)

Gráfico de Linhas: evolução temporal dos pedidos

Gráfico de Colunas: distribuição por formas de pagamento

Gráfico de Pizza: status de envio dos pedidos

Gráfico de Barras Horizontais: ranking dos produtos mais vendidos

Tabela: visão detalhada por produto, estoque e receita

💡 Principais Insights

A forma de pagamento via PIX representou cerca de 45% da receita total.

O ticket médio elevado sugere um perfil de compra mais corporativo (B2B).

O produto prod_86 destacou-se como o mais vendido em valor e volume.

Aproximadamente 25% dos pedidos estavam com pagamento pendente.
