# Bancos de Dados (Relacionais x Não-Relacionais)

## Bancos Relacionais

De acordo com Elmasri e Navathe, os Bancos de Dados Relacionais tiveram o seu modelo de dados "relacional" introduzido inicialmente por Ted Codd, da IBM Research, em 1970. Ele foi divulgado em um artigo clássico (Codd, 1970), que atraiu atenção imediata devido a sua simplicidade e base matemática. 

Esse modelo tem o papel de usar o conceito de relação matemática, que se parece com uma tabela de valores, como seu bloco de montagem básico, e que sua base teórica reside em uma teoria de conjunto e lógica de predicado de primeira ordem. 

O modelo relacional teve as suas primeiras implementações comerciais disponíveis no início da década de 1980, como o sistema SQL/DS no sistema operacional MVS, da IBM, e o SGBD, da Oracle. A partir daí, o modelo foi implantado em uma grande quantidade de sistemas comerciais. 

Pode-se citar como SGBDs relacionais (SGBDRs) populares, o DB2 e Informix Dynamic Server (da IBM), o Oracle e Rdb (da Oracle), o Sybase SGBD (da Sybase) e o SQLServer e Access (da Microsoft), além desses, existem vários sistemas de código aberto, tais como, MySQL e PostgreSQL.

### Caracaterísticas dos BD Relacionais:

- Dados organizados em tabelas;

- Tabelas podem se relacionar com outras tabelas; 

- Menor espaço de armazenamento;

- Maior velocidade de acesso aos dados;

- Padrão mundialmente utilizado.

As operações da álgebra relacional e o cálculo relacional são duas linguagens formais associadas ao modelo relacional. Portanto, o cálculo relacional é considerado a base para a linguagem SQL, e a álgebra relacional é usada nos detalhes internos de muitas implementações de banco de dados para processamento e otimização de consulta.

## Bancos Não-Relacionais

Conforme Tejada em um artigo da Microsoft, um banco de dados não-relacional é um banco de dados que não usa o esquema de tabela de linhas e colunas discutido anteriormente e encontrado na maioria dos sistemas de banco de dados tradicionais. 

Em vez disso, os bancos de dados não relacionais usam um modelo de armazenamento otimizado para os requisitos específicos do tipo de dados que está sendo armazenado. Por exemplo, os dados podem ser armazenados como pares chave/valor simples, como documentos JSON ou como um gráfico que consiste em bordas e vértices.

O termo NoSQL refere-se aos armazenamentos de dados que não usam o SQL para consultas. Em vez disso, os armazenamentos de dados usam outras linguagens de programação e constructos para consultar os dados.

Atualmente, os principais bancos de dados NoSQL utilizados são: Redis, Memcached, Cassandra, Hbase, Amazon DynamoDB, Neo4j, MongoDB, entre vários outros.

### Algumas das Caracaterísticas dos BD Não-Relacionais:

- Escalabilidade Horizontal;

- Ausência de esquema (Schema-free) ou esquema flexível;

- Suporte nativo a replicação;

- API simples para acessar o banco de dados;

- Consistência eventual.

Existe também uma categorização dos bancos de dados não relacionais ou NoSQL:

- Armazenamentos de dados de documentos;

- Armazenamentos de dados de colunas;

- Armazenamentos de dados de chave/valor;

- Armazenamentos de dados de gráficos;

- Armazenamentos de dados de série temporal;

- Armazenamentos de dados de objetos;

- Armazenamentos de dados de índice externo.

Tejada ainda descreve, que armazenamentos de dados não relacionais costumam usar uma arquitetura de armazenamento diferente da usada pelos bancos de dados relacionais. Especificamente, eles tendem a não ter nenhum esquema fixo. Além disso, eles tendem a não dar suporte a transações ou restringir o escopo das transações e geralmente não incluem índices secundários por motivos de escalabilidade.


# Referências:

- SILBERSCHATZ, A.; SUDARSHAN, S. Sistema de banco de dados. Campus, 2006. ISBN: 9788535211078

- ELMASRI, R.; NAVATHE, S. B. Sistemas de banco de dados. 6 ed. Pearson/Addison-Wesley, 2011. ISBN: 9788579360855

- TEOREY, T. J., LIGHTSTONE, S., NADEAU, T.. Projeto e Modelagem de Bancos de Dados - 2a Ed. 2014.

- TEJADA, Z. Dados não relacionais e NoSQL, ACESSO EM: https://learn.microsoft.com/pt-br/azure/architecture/data-guide/big-data/non-relational-data. 
