<h1 >Projeto: O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados</h1>
<p>Um banco de dados é uma coleção organizada de grandes  volumes de dados, normalmente armazenados eletronicamente em um sistema de  computador. Um banco de dados geralmente é controlado por um sistema de  gerenciamento de banco de dados (DBA), que é usado para armazenar e recuperar  dados de forma ordenada.</p>
<h3 >Entendendo as diferenças e características entre Banco de Dados SQL e NoSQL:</h3>
<h3 >SQL e NoSQL</h3>
<p >​ Bancos de dados relacional(SQL) é um banco de dados onde armazenamos dados com um relacionamento entre si. Usado quando se precisa de um sistema mais rígido, quando já se conhece que tipos de dados você vai relacionar.</p>
<p >​ NoSQL = No Only SQL(Não Apenas SQL) → surgiu como uma alternativa ao SQL e não para tentar substituir. Necessidade veio principalmente por conta de escalabilidade(ter que armazenar cada vez mais informações e dados não estruturados). NoSQL veio para suprir o que os bancos relacionais não conseguiam. Devem ser usados de forma que se complementem</p>
<h3 >Características do SQL</h3>
<ul >
  <li>Escalabilidade Vertical ou Horizontal.</li>
  <li>Estrutura mais rígida, previamente moldada, modelada, definição de chaves primárias e secundárias.</li>
  <li>Maior consistência, organização.</li>
  <li>Performance: Dependente de sistema de disco para performance.</li>
  <li>Transações: Atomicidade, consistência, isolamento, durabilidade (ACID).</li>
</ul>
<p>Um banco de dados relacional (RDB) é usado para armazenar dados em conjuntos de tabelas, linhas e colunas. Um RDB é capaz de estabelecer links, ou relacionamentos, entre informações juntando tabelas, o que facilita o entendimento e a obtenção de insights sobre as conexões entre vários pontos de dados. Principalmente todos os bancos de dados relacionais usam Structured Query Language (SQL) para acessar e manipular os dados armazenados no banco de dados.</p>
<p>Uma vantagem do modelo de banco de dados relacional é que ele fornece uma maneira intuitiva de representar dados e permite o acesso a pontos de dados relacionados. Outras vantagens incluem a conformidade com ACID, pois garante a validade dos dados independentemente de erros, falhas ou outros erros potenciais. É flexível e fácil de usar. Pode-se facilmente adicionar, atualizar ou excluir tabelas, relacionamentos e fazer outras alterações sempre que necessário, sem afetar a estrutura geral ou afetar os aplicativos existentes.</p>
<p>Esse método de armazenar informações em tabelas e criar um relacionamento entre elas pode ter algumas desvantagens. Por exemplo, pode dar origem a uma alta complexidade se os dados não puderem ser facilmente encapsulados em uma tabela. Além disso, uma vez que a quantidade de dados se torna massiva, o banco de dados precisa ser particionado em vários servidores, o que pode causar vários problemas, pois juntar tabelas que foram distribuídas em servidores distintos não é uma tarefa fácil.</p>
<h3 >Características do NoSQL</h3>
<ul >
  <li>
    <p >Escalabilidade Horizontal.</p>
  </li>
  <li>
    <p >Particionando (sharding) entre os nós</p>
  </li>
  <li>
    <p >Ausência quase completa de regras de esquema, mas há boas práticas que devem ser seguidas para que ele se torne performático.</p>
  </li>
  <li>
    <p >Menos garantia da consistência.</p>
  </li>
  <li>
    <p >Performance: Depende do tamanho do cluster e latência da rede.</p>
  </li>
  <li>
    <p >Transações: Basically available, soft-state, eventually consistent.</p>
  </li>
  <li>
    <p >Vantagens: flexibilidade, escalabilidade, alta performance.</p>
  </li>
</ul>
<p>Bancos de dados não relacionais foram criados para responder a essas limitações. A principal diferença entre bancos de dados relacionais e não relacionais depende de como os dados são armazenados e organizados. O último, também chamado de NoSQL (não SQL, ou às vezes, Not Only SQL), não usa relações como sua estrutura de armazenamento. Em vez disso, eles armazenam dados como arquivos individuais e desconectados e podem ser usados ​​para tipos complexos e não estruturados, como documentos ou arquivos de mídia avançada.</p>
<p>Algumas vantagens do modelo NoSQL são a alta escalabilidade e alta disponibilidade. Ele é capaz de lidar com grandes volumes de tada em alta velocidade com uma arquitetura escalável. Isso significa que a escalabilidade é alcançada espalhando o armazenamento de dados e o trabalho para processar os dados em um grande cluster de computadores. Para aumentar a capacidade, mais computadores são adicionados ao cluster. Este tipo de arquitetura não é difícil de implementar em ambientes de computação em nuvem onde novos computadores e armazenamento podem ser facilmente adicionados ao cluster. É possível alcançar o mesmo tipo de escalabilidade com bancos de dados SQL. No entanto, pode ser caro, pois requer muita engenharia.</p>
<p>O modelo NoSQL também tem suas desvantagens. Nem todos os modelos obedecem às propriedades ACID. Portanto, os desenvolvedores precisam unir as coisas com a programação para aplicar as restrições ACID, que são fornecidas em bancos de dados relacionais. Além disso, a maioria deles são softwares de código aberto, o que faz com que eles comprometam a confiabilidade, pois ninguém é responsável em momentos de falha.</p>
<p >No caso do Mongo, é recomendado o uso para grande volume de dados, mas não é recomendado em casos de necessidade de Relacionamentos/JOIN, em que propriedades ACID e transações são importantes e em sistemas de pagamento, pois diversas entidades de pagamento não homologam em sistemas que dados financeiros de clientes não estão em um banco de dados relacional.</p>
<h3 >Engenharia de Dados</h3>
<p >​ O Engenheiro de Dados prepara a informação que será consumida, por isso precisa ter o conhecimento técnico para coletar, preparar, armazenar e deixar essa informação disponível para que o cientista de dados utilize.​ O Engenheiro de Dados tem maior proximidade com a manipulação dos dados e possui o conhecimento técnico das ferramentas.​ O Engenheiro vai gerar essas informações para consumo do cientista de dados ou outras opções de consumo de informações, por isso é necessário seu conhecimento nos diversos tipos de Banco de Dados.</p>
<p >​ O Cientista aplica todas as informações disponibilizadas pelo Engenheiro , verifica todos os insights e gera dados em cima dessa informação para complementar as informações e ter maior aproveitamento das informações.</p>
<p ><strong>Certificando o conhecimento do modulo de introdução ao MongoDB e Banco de Dados NoSQL.</strong></p>
<p ><strong>Quais tipos de dados podem ser armazenados no Redis?</strong> A maioria dos tipos de dados como string , numeros JSON</p>
<p ><strong>O MongoDB suporta restrições de chave estrangeira?</strong> Não,</p>
<p ><strong>MongoDB tem suporte a SQL?</strong> Nao, tem linguagem propria</p>
<p ><strong>Quais as linguagens de consulta utilizadas pelo Neo4j e Cassandra respectivamente?</strong> Cyper e CQL</p>
<p ><strong>Qual tipo de escalabilidade adiciona mais recurso na máquina?</strong> Escalabilidade Vertical</p>
<p ><strong>MongoDB tem suporte a índices?</strong> Sim e seu funcionamento é igual ao dos bandos de dados relacionais</p>
<p ><strong>Quais os tipos de banco NoSql?</strong> Orientado a documentos, chave-valor, grafo e orientado a coluna</p>
