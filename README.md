🛒 Projeto E-commerce --- Análise de Dados
Projeto completo de banco de dados e análise de dados para um cenário de e-commerce, desenvolvido como projeto de portfólio durante minha formação em Ciência de Dados.
O projeto reúne as principais etapas de uma solução de dados: levantamento de requisitos, modelagem de dados, criação do banco de dados, inserção e consulta de dados, análises em SQL e construção de um dashboard no Power BI.
🎯 Objetivo
Construir uma solução de dados para apoiar a análise das operações de um e-commerce, permitindo acompanhar:
vendas e clientes;
produtos e estoque;
pagamentos;
entregas;
avaliações;
indicadores de desempenho;
relacionamento entre as diferentes áreas do negócio.
Uma das regras de negócio consideradas no projeto é impedir vendas acima da quantidade disponível em estoque.
🧩 Estrutura do projeto
projeto-e-commerce/
│
├── 01_modelo_conceitual/
│   └── modelo_conceitual.png
│
├── 02_modelo_logico/
│   └── modelo_logico.png
│
├── 03_modelo_fisico/
│   └── 01_criacao_das_tabelas.sql
│   └── 02_insercao_dados.sql
│
├── 05_analise/
│   ├── 01_vendas_e_clientes/
│   ├── 02_produtos_e_estoque/
│   └── 03_pagamentos_e_entregas/
│
├── 06_power_bi/
│   ├── Dashboard.png
│   └── projeto_E-commerce.pbix
│
└── README.md
🗂️ Modelagem de dados
Modelo conceitual
O modelo conceitual representa as principais entidades e os relacionamentos necessários para estruturar o negócio.
�
Modelo lógico
A partir do modelo conceitual, foi elaborado o modelo lógico com as tabelas, atributos, chaves primárias e relacionamentos.
�
🗄️ Banco de dados
O banco foi desenvolvido em MySQL, utilizando tabelas relacionadas para representar as operações do e-commerce.
Principais tabelas
cliente
produto
pedido
item_pedido
pagamento
estoque
fornecedor
entrega
avaliacao
Tecnologias utilizadas
� � � � � �
📊 Análises realizadas
O projeto foi dividido em análises de diferentes áreas do negócio.
👥 Vendas e clientes
Análise do comportamento das vendas e relacionamento com clientes, utilizando consultas SQL para gerar informações relevantes para o negócio.
📦 Produtos e estoque
Análise dos produtos comercializados e da disponibilidade de estoque, considerando a regra de negócio de não permitir vendas superiores ao estoque disponível.
💳 Pagamentos e entregas
Análise das formas e status de pagamento e acompanhamento das entregas dos pedidos.
🔎 Consulta avançada
Também foram desenvolvidas consultas SQL utilizando recursos como:
JOIN;
agregações;
GROUP BY;
ORDER BY;
subconsultas;
filtros;
funções de agregação;
relacionamentos entre tabelas.
📈 Dashboard --- Power BI
O projeto também possui um dashboard desenvolvido no Power BI, conectado ao banco de dados para transformar os dados em indicadores e visualizações.
�
Indicadores apresentados
Faturamento total: R$ 21.816,50
Quantidade de pedidos: 210
Ticket médio
acompanhamento de produtos e valores;
status das entregas;
informações relacionadas às vendas.
🔄 Fluxo do projeto
Requisitos do negócio
        ↓
Modelo conceitual
        ↓
Modelo lógico
        ↓
Modelo físico
        ↓
Criação do banco MySQL
        ↓
Inserção dos dados
        ↓
Consultas SQL
        ↓
Análises
        ↓
Power BI
        ↓
Dashboard
🛠️ Competências demonstradas
Este projeto demonstra conhecimentos práticos em:
Modelagem de dados;
Banco de dados relacional;
SQL;
MySQL;
Consultas e análises de dados;
Relacionamento entre tabelas;
Regras de negócio;
Power BI;
Construção de dashboards;
Organização de projetos;
Git e GitHub.
💼 Aplicação profissional
O projeto foi desenvolvido com foco em situações próximas às encontradas em ambientes profissionais de dados, conectando banco de dados, SQL, análise e visualização em uma única solução.
A proposta é demonstrar a capacidade de transformar uma necessidade de negócio em uma estrutura de dados, realizar análises e apresentar os resultados de forma visual.
👨‍💻 Autor
Gabriel Ângelo de Jesus Amaral
🎓 Estudante de Ciência de Dados --- UNINTER
🔗 GitHub: https://github.com/gabriel-angelo-021
