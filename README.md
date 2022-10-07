Papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL).

# Introdução
Existem diferentes considerações para avaliar quando utilizamos tecnologias de SGBD não relacionais com relação aos SGBD relacionais, entre eles:  modelo de armazenamento, estrutura de dados, escalabilidade, modelo de desenvolvimento, suporte a transações, manipulação dos dados, consistência e custos de propriedade.

Os SGBD não relacionais surgiram como solução para suprir necessidades onde os SGBD relacionais são menos eficazes, principalmente com relação ao desempenho e escalabilidade. Nos SGBD não relacionais é possível distribuir os dados em servidores de forma horizontal, servidores com menos recursos físicos, mas em maior quantidade. No caso de SGBD relacionais, normalmente se utilizam servidores com mais recursos físicos e em menor quantidade.

# Bases de Dados Relacionais (SQL)
Nas bases de dados relacionais, os dados estão armazenados no formato de tabelas, utilizando o conceito de entidade e relacionamento. Nesse conceito procura-se evitar a redundância e as tabelas utilizam-se de relações para confirmar a integridade dos dados. Algumas das principais características são: atomicidade, consistência, isolamento e durabilidade (ACID). As aplicações recomendadas neste caso, são: sistemas comerciais, sistemas corporativos, sistemas financeiros, entre outros.

Exemplos SGBD Relacionais <br />
•	IBM DB2: desenvolvido pela IBM, lançado em 1983, baseado em SQL/DS para o mainframe da própria empresa. Atualmente comercializado em diferentes edições.

•	Microsoft SQL Server: desenvolvido pela Microsoft, lançado em 1988. Atualmente comercializado em diferentes edições. Utiliza-se para acessar os dados T-SQL e ANSI SQL.

•	FireBird: SGBD de código aberto. Desenvolvimento e manutenção coordenado pela Fundação FirebirdSQL. Sendo de código aberto, não existe custos de licença.

•	Oracle: desenvolvido pela empresa Oracle, lançado nos anos 70. Utiliza-se a linguagem de programação PL/SQL para acessar os dados. Atualmente comercializado em diferentes edições.

•	PostgreSQL: SGBD de código aberto. Coordenado pelo PostgreSQL Global Development Group. Diversas organizações em todo o mundo patrocinam o projeto.

# Bases de Dados Não Relacionais (NoSQL)
Nas bases de dados não relacionais, os dados podem ser armazenados de diferentes formas. Alguns dos pontos mais fortes são a escalabilidade e desempenho. São utilizados como uma solução alternativa para os SGBD relacionais em projetos específicos. As bases de dados não relacionais foram desenvolvidas em resposta às demandas que surgiram na construção de aplicações modernas.

Exemplos SGBD Não relacionais <br />
•	MongoDB: núcleo de armazenamento baseado em XML ou JSON, “Document Store”.

•	Cassandra: núcleo de armazenamento baseado em Big Table, “Wide Columns Store”.

•	HBase (Apache): núcleo de armazenamento baseado em Big Table, “Wide Columns Store”.

•	CouchDB: núcleo de armazenamento baseado em documentos XML ou JSON.

•	Riak: núcleo de armazenamento baseado em documentos XML ou JSON.

Definição/Tipos SGBD Não Relacionais <br />
•	Wide Column Store / Column Families: é um tipo de armazenamento chave / valor. Utiliza tabelas, linhas e colunas, mas diferente de um banco de dados relacional, os nomes e formatos de colunas podem variar de linha a linha na mesma tabela. O conceito empregado nessa tecnologia melhora o desempenho em sistemas OLAP. Exemplos: Cassandra, HBase, Microsoft Azure Cosmos. Aplicações recomendadas: IOT, aplicações de detecção de fraudes, motores de recomendação, catálogos de produtos, listas de reprodução e aplicações de mensagens. Principais clientes: Cassandra/NY Times, eBay, Sky.

•	Document Store: baseado em documentos XML ou JSON. Caracterizam-se pela organização livre de esquemas de dados. Os registros não precisam ter uma estrutura uniforme, isto é, registros diferentes podem ter diferentes colunas. Essa tecnologia exigira o processamento das estruturas do lado do cliente, tendo a desvantagem da não disponibilidade de índices secundários. Exemplos: MongoDB, Amazon DynamoDB, CouchDB. Aplicações recomendadas: IOT, mobile, analises em tempo real, catálogos, gestão de conteúdo. Principais clientes: MongoDB/Adobe, BBVA, Bosch, Cisco, eBay, Expedia, Forbes, Sage.

•	Key Value Store: um conceito simplificado onde uma chave corresponde a um valor. Suporta um nível elevado de carga de trabalho proporcionando maior escalabilidade. Exemplos: Redis, Memcached, Riak KV. Aplicações recomendadas: IOT, detecção de fraudes em tempo real, e-commerce, analises em tempo real, gestão de conteúdo. Principais clientes: Redis/Vodafone, Trip Advisor, Nokia, Samsung, HTC, Docker, Staples, MSN.

•	Graph Databases: maior complexibilidade. O modelo de graph database, como é chamado, caracteriza-se por ter estruturas de dados onde os esquemas e/ou instâncias são modelados como grafos. Exemplos: Neo4J, OrientDB, InfoGrid. Aplicações recomendadas: recomendações em tempo real, gestão de identidade e acesso, detecção de fraudes, operações de TI. Principais clientes: Neo4J/eBay, Walmart, Cisco, HP, Tomtom, UBS.





