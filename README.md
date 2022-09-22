# Projeto-O-Papel-dos-Bancos-de-Dados-SQL-e-NoSQL-na-Engenharia-de-Dados


O que é um banco de dados?

Antigamente organizávamos nossos dados em papel e arquivos físicos, e com o tempo ficava bem difícil administrar essas informações. Além da dificuldade para lidar com essas informações, existia também um enorme risco de perdermos essa folha de papel que tinha nosso dado ou mesmo cair em mãos erradas. Hoje com um banco de dados conseguimos armazenar essas informações digitalmente, de forma segura, e recuperar muito mais facilmente os dados que precisamos, além de permitir que mais de uma pessoa acesse a mesma informação ao mesmo tempo, o que seria impossível com uma única folha de papel.
Em termos gerais, podemos definir banco de dados como uma coleção organizada onde se pode armazenar dados, de forma estruturada podendo ser consultada por um programa ou pessoa permitindo extrair informações.

Banco de dados relacionais (SQL)

No banco de dados relacional nossas informações ficam em tabelas e se relacionam. Os bancos de dados relacionais são conhecidos como banco de dados SQL. Essa sigla SQL siginifica “Structured Query Language” que traduzindo para o português significa: “Linguagem de Consulta Estruturada”. Com o SQL, você pode executar vários comandos para criar, alterar, gerenciar, consultar, dentre outras informações no seu banco de dados. Costumamos dizer que bancos SQL seguem uma modelagem relacional, pois estes se baseiam no fato de que todos seus dados sejam guardados em tabelas.

![image](https://user-images.githubusercontent.com/101484328/191639358-5b71da1d-0142-4d17-a648-9229064243bc.png)

Banco de dados não relacionais (noSQL)

No banco de dados não relacional não utilizamos o SQL e também não temos esse esquema de tabelas e linhas. Se não temos tabelas como isso fica armazenado então? Temos alguns modelos de bancos noSQL e vamos falar um pouco deles agora para entender melhor como os dados ficariam armazenados:

![image](https://user-images.githubusercontent.com/101484328/191639479-0aab8808-c160-4908-afa3-a29775eac8ef.png)

Banco de dados de Documentos (noSQL)

É projetado para armazenar e consultar dados como documentos do tipo JSON. Os bancos de dados de documentos facilitam para que os desenvolvedores armazenem e consultem dados usando o mesmo formato de modelo de documento que usam no código da aplicação. Um exemplo de banco de dados de documentos é o famoso MongoDB!

Banco de dados de Grafos (noSQL)

Os bancos de dados grafo utilizam nós para armazenar entidades de dados e bordas para armazenar os relacionamentos entre as entidades. Uma borda tem sempre um nó inicial, um nó final, um tipo e um direcionamento, o que possibilita a descrição dos relacionamentos entre pais e filhos, das ações, das propriedades e assim por diante. A quantidade e os tipos de relacionamentos que um nó pode ter são ilimitados. Um exemplo de banco de dados de Grafos é o Arangodb.

O gráfico a seguir é um exemplo de gráfico de rede social. Considerando as pessoas (nós) e seus relacionamentos (bordas), é possível descobrir quem são os “amigos dos amigos” de uma pessoa específica:

![image](https://user-images.githubusercontent.com/101484328/191639838-8a3034e0-5a84-45b2-9dcf-a797248bdcaf.png)

Banco de dados de Chave-Valor (noSQL)

É um tipo de banco de dados não relacional que usa um método de chave-valor simples para armazenar dados. Um banco de dados de chave-valor armazena dados como um conjunto de pares de chave-valor em que uma chave funciona como um identificador exclusivo. Os dados dentro de bancos de chave-valor são formados por duas partes: uma string, que representa a chave, e os dados em si, que são o valor. A chave é usada como um índice, permitindo que o usuário faça a requisição dos dados relacionados a ela. Um exemplo de banco de dados de Chave-Valor é o Redis.

Banco de dados Colunar (noSQL)

Enquanto um banco de dados relacional é otimizado para armazenar linhas de dados, um banco de dados colunar é otimizado para recuperação rápida de colunas de dados, normalmente em aplicativos analíticos. O armazenamento orientado a colunas para tabelas do banco de dados é um fator importante para a performance de consulta analítica, pois ele reduz expressivamente os requisitos gerais de E/S de disco e diminui a quantidade de dados que você precisa carregar do disco. Um exemplo de banco de dados colunar é o Cassandra.

Banco de Dados Relacional (SQL) x Banco de Dados Não Relacional (noSQL)

Agora que sabemos o que é um banco relacional (SQL) e um banco de dados não relacional (noSQL), podemos falar um pouquinho das diferenças de cada um desses:

Banco de dados de Chave-Valor (noSQL)

É um tipo de banco de dados não relacional que usa um método de chave-valor simples para armazenar dados. Um banco de dados de chave-valor armazena dados como um conjunto de pares de chave-valor em que uma chave funciona como um identificador exclusivo. Os dados dentro de bancos de chave-valor são formados por duas partes: uma string, que representa a chave, e os dados em si, que são o valor. A chave é usada como um índice, permitindo que o usuário faça a requisição dos dados relacionados a ela. Um exemplo de banco de dados de Chave-Valor é o Redis.

Banco de dados Colunar (noSQL)

Enquanto um banco de dados relacional é otimizado para armazenar linhas de dados, um banco de dados colunar é otimizado para recuperação rápida de colunas de dados, normalmente em aplicativos analíticos. O armazenamento orientado a colunas para tabelas do banco de dados é um fator importante para a performance de consulta analítica, pois ele reduz expressivamente os requisitos gerais de E/S de disco e diminui a quantidade de dados que você precisa carregar do disco. Um exemplo de banco de dados colunar é o Cassandra.
Banco de Dados Relacional (SQL) x Banco de Dados Não Relacional (noSQL)
Agora que sabemos o que é um banco relacional (SQL) e um banco de dados não relacional (noSQL), podemos falar um pouquinho das diferenças de cada um desses:

![image](https://user-images.githubusercontent.com/101484328/191640024-3f828152-5c5c-4af2-a04e-114a657cbb45.png)

Vantagens do banco de dados não relacional (NoSQL): A vantagem número um é a escalabilidade e a flexibilidade da estruturação, que além de tornar a escalabilidade mais fácil, facilita a inserção e acesso aos dados.

Vantagens do banco de dados relacional (SQL): Enquanto que no modelo não relacional (noSQL), onde a consistencia de dados pode ser considerada fraca, no modelo relacional há uma forte consistencia de dados, um dos preços para isso é a estrutura menos flexivel.

A diferença essencial entre as duas teconologia é que uma é baseada em esquema (Relacional) e a outra não (Não relacional). Para trabalhar com um banco SQL (Relacional) a primeira coisa que voce precisa fazer é projetar a estrutura do banco, isto é, voce não consegue inserir um dado se não tiver previamente definido os "esquemas" das tabelas, enquanto que em um banco de dados NoSQL (Não relacional) isso não é necessário.

Qual banco de dados utilizar? SQL ou NoSQL?

Depende! Tudo vai depender do seu projeto, então sempre bom analisar o que precisará ser feito para decidir qual banco de dados é melhor para usar. Por exemplo, às vezes fazer consultas em diversas tabelas para conseguir retornar a informação que precisa, quando a base é exageradamente grande, pode exigir muito do seu banco de dados relacional. Pode ser que nesse caso faça sentido utilizar um não relacional (noSQL). Sempre vale uma análise pois cada caso é sempre um caso.

O NoSQL tem muitas vantagens para ser utilizado. Mas não é por isso que devemos utilizá-lo em todas as situações. Em muitos sistemas, você pode (e até deve) usar o modelo relacional. O NoSQL é mais indicado para aqueles sistemas que tenham necessidades maiores de armazenamento e desempenho. O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados. Sendo assim, você pode usar ambas as soluções para diferentes casos.

SGBD (Sistema de Gerenciamento de Banco de Dados)

Os Sistemas de Gerenciamento de Banco de Dados são softwares utilizados para gerir as estruturas de armazenamento dos dados, permitem realizar manipulações, bem como controlar as permissões de utilização dos bancos de dados. Aqui nesse curso iremos focar no MongoDB para trabalhar com nossos dados!

![image](https://user-images.githubusercontent.com/101484328/191640070-0af2047c-3696-4e77-97c0-f3b33039971d.png)

O que é o MongoDB?

MongoDB é um banco de dados não relacional (noSQL) orientado a documentos no formato JSON. Ele é opensource e possui alta performance e flexibilidade. Ao contrário de um banco de dados relacional (SQL), ele não possui como restrição a necessidade de ter as tabelas e colunas criadas previamente, permitindo que um documento represente toda a informação necessária, com todos os dados que você queira, no formato de um JSON. Esses documentos são agrupados em collections, que em conjunto, forma um database (banco de dados).

![image](https://user-images.githubusercontent.com/101484328/191640165-e28f39b3-da11-4257-bd29-66dd080ce034.png)





