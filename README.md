# database_SQL_x_NoSQL
Papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL).

# Introdução
Existem diferentes considerações para avaliar quando utilizamos tecnologias de SGBD não relacionais com relação aos SGBD relacionais, entre eles:  modelo de armazenamento, estrutura de dados, escalabilidade, modelo de desenvolvimento, suporte a transações, manipulação dos dados, consistência e custos de propriedade.

Os SGBD não relacionais surgiram como solução para suprir necessidades onde os SGBD relacionais são menos eficazes, principalmente com relação ao desempenho e escalabilidade. Nos SGBD não relacionais é possível distribuir os dados em servidores de forma horizontal, servidores com menos recursos físicos, mas em maior quantidade. No caso de SGBD relacionais, normalmente se utilizam servidores com mais recursos físicos e em menor quantidade.

# Bases de Dados Relacionais (SQL)
Nas bases de dados relacionais, os dados estão armazenados no formato de tabelas, utilizando o conceito de entidade e relacionamento. Nesse conceito procura-se evitar a redundância e as tabelas utilizam-se de relações para confirmar a integridade dos dados. Algumas das principais características são: atomicidade, consistência, isolamento e durabilidade (ACID).

Exemplos SGBD Relacionais <b>
•	IBM DB2: desenvolvido pela IBM, lançado em 1983, baseado em SQL/DS para o mainframe da própria empresa. Atualmente comercializado em diferentes edições.

•	Microsoft SQL Server: desenvolvido pela Microsoft, lançado em 1988. Atualmente comercializado em diferentes edições. Utiliza-se para acessar os dados T-SQL e ANSI SQL.

•	FireBird: SGBD de código aberto. Desenvolvimento e manutenção coordenado pela Fundação FirebirdSQL. Sendo de código aberto, não existe custos de licença.

•	Oracle: desenvolvido pela empresa Oracle, lançado nos anos 70. Utiliza-se a linguagem de programação PL/SQL para acessar os dados. Atualmente comercializado em diferentes edições.

•	PostgreSQL: SGBD de código aberto. Coordenado pelo PostgreSQL Global Development Group. Diversas organizações em todo o mundo patrocinam o projeto.
