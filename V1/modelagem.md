## QUESTÕES PARA V1 - MODELAGEM

**1.** Uma tabela no Modelo Relacional pode representar quais recursos identificados no Modelo de Entidade e Relacionamento (ME-R).

- [ ] Atributo Composto
- [x] Relacionamento
- [ ] Atributo Derivado
- [x] Atributo Multivalorado

---

**2.** Sempre que um conjunto de atributos é agrupado em uma relação (tabela), um determinado significado é associado a eles. Este significado identifica como devem ser interpretados os atributos pertencentes a cada tupla da relação.
Consciente da afirmação acima, selecione qual seria o critério relacionado a esta afirmação que pode proporcionar um projeto de BD mais eficiente ou não.

- [x] Semântica dos atributos de uma relação.
- [ ] Redundância de valores.
- [ ] Valores nulos em tuplas.
- [ ] Controle de relacionamento por chave.

---

**3.** Um atributo que possua valor nulo permite diferentes interpretações ao usuário que recupera uma tupla que possua tal atributo. Indique entre as opções abaixo, qual ou quais interpretações lhe seriam possíveis.

- [x] Atributo não se aplica para esta tupla.
- [ ] Atributo não é importante ao uso deste BD.
- [x] Valor do atributo para esta tupla é desconhecido.
- [x] Valor é conhecido, mas encontra-se ausente no BD.

---

**4.** Cada linha de uma relação representa uma coleção de valores de dados que **NÃO** estão inter-relacionados, pois se estivessem não precisariam estar na mesma relação do BD.

- [ ] Verdadeiro
- [x] Falso

---

**5.** Em algumas situações de elaboração de DE-R (Diagrama de Entidade-Relacionamento) nos deparamos com a situação onde um relacionamento deveria estar relacionado com a ocorrência de outro relacionamento.
No entanto, não é permitida a ligação no DE-R de um relacionamento com outro, onde geralmente, a identificação de uma situação particular é adotada para representação neste diagrama do nível conceitual de um projeto de BD.
Como é denominada a representação desta situação no DE-R?

- [ ] Especialização
- [x] Agregação
- [ ] Cardinalidade
- [ ] Generalização

---

**6.** Complete a afirmação a seguir sobre as terminologias do Modelo Relacional.
Atente para as regras da Língua Portuguesa e não use espaços em branco para que sua resposta possa ser avaliada com possibilidades de estar correta.

> O nome de uma coluna que forma uma relação no Modelo Relacional é **atributo/atributos** de relação.

---

**7.** Baseado nos critérios informais de apoio ao desenvolvimento de um Modelo Relacional adequado a um projeto de BD, indique quais das operações de manipulação de dados armazenados sofrem problemas para atender ao seu usuário quando não é respeitada as regras para o controle da Redundância.

- [x] Inserção.
- [x] Exclusão.
- [x] Alteração.
- [x] Consulta.

---

**8.** A versatilidade no uso de atributos que possam ser nulos em um esquema de BD é sempre conveniente e propicia a maior eficiência no projeto de um BD.

- [ ] Verdadeiro
- [x] Falso

---

**9.** Complete a afirmação a seguir sobre a Restrição de Chaves existentes no Modelo Relacional de Banco de Dados.
Não utilize espaço em branco em sua resposta e respeite as regras de sintaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> As Restrições de Chaves indicam que cada atributo das chaves **candidatas** deve possuir valor único em todas as tuplas da relação.

---

**10.** A Restrição de Integridade Referencial está envolvida com a definição de chaves em uma relação.
Qual é o nome identificador de uma destas chaves na Língua Portuguesa que pode promover a inclusão de um atributo de uma relação que referencia outra tupla em outra relação.
Não use espaço em branco em sua resposta.

> Por meio da Restrição de Integridade Referencial surge um novo tipo peculiar de chave denominada **estrangeira/secundária**.

---

**11.** Uma determinada fase para construção de um Projeto de Banco de Dados eficiente acontece com o mapeamento do ME-R para seu Modelo Relacional correspondente.
A avaliação desse mapeamento deve respeitar algumas características que o conceito como um mapeamento eficiente.

- [x] Verdadeiro
- [ ] Falso

---

**12.** O que é o **GRAU DE RELAÇÃO** no Modelo Relacional?
Indique a opção ou opções corretas.

- [x] É a quantidade dos atributos existentes em uma relação.
- [ ] É a quantidade de Entidades que participam de um Relacionamento específico.
- [ ] É o número que corresponde ao nível do Modelo (1-Superior, 2-Conceitual e 3-Inferior).
- [ ] É o número de relações existentes em um Projeto de Banco de Dados.

---

**13.** Averigue o que está impedindo que a instrução SQL abaixo realize a troca de todos os valores de código menor que 100 para a data de nascimento de 11/11/2011.

> **UPDATE PESSOA** dataNascimento = '11-11-2011' **WHERE** codigo < 100;

**PESSOA**

| codigo |    nome     | dataNascimento | idade |
|:------:|:-----------:|:--------------:|:-----:|
| 11     | João Castro |   10/01/2012   |  02   |
| 21     | José Sechi  |   22/09/1998   |  16   |
| 302    | Ana Morais  |   12/11/2001   |  12   |
| 401    | Maria Alves |   30/07/1980   |  34   |

data atual: 14/10/2014

Observe que o nome dos atributos estão corretos na Tabela PESSOA (codigo, nome, dataNascimento, idade), sendo representado na figura como um apelido dos atributos.

- [ ] A instrução UPDATE está sem a palavra FROM que identifica a tabela que será modificada.
- [ ] Um atributo do tipo de data (mm-dd-aaaa) não é do tipo caracter para ter as aspas simples.
- [x] A instrução UPDATE está sem a palavra SET para indicar qual é a operação de modificação nas tuplas selecionadas.
- [ ] Não se pode alterar as datas de nascimento senão as idades ficarão inconsistentes, então o BD não permite.

---

**14.** Selecione quais os tipos de dados que **NÃO** existem em um Banco de Dados Relacional.

- [ ] DATE
- [x] STRING
- [x] DATA
- [ ] INTEGER

---

**15.** O SQL foi desenvolvido originalmente no início dos anos 70 nos laboratórios da IBM no projeto conhecido como System R.
O nome original dessa linguagem era SEQUEL, acrônimo de Structured English Query Language (Linguagem de Consulta Estruturada).
No entanto, no Brasil esta linguagem é conhecida como SQL que só realiza consultas ou pesquisas sobre um BD.

- [ ] Verdadeiro
- [x] Falso

---

**16.** A linguagem SQL de BD é procedural, permitindo a operação direta sobre o Banco.

- [ ] Verdadeiro
- [x] Falso

---

**17.** Observe as instruções DML e as associe com as operações que cada uma realiza.

**A = SELECT** | **B = CREATE** | **C = DELETE** | **D = UPDATE**

Selecione a opção, ou opções, que estiverem corretas.

- [ ] Item A corresponde a CONSULTA, B a INCLUSÃO de novos dados e C a EXCLUSÃO.
- [ ] Item B corresponde ao CADASTRO de novos dados, C a APAGAR dados já armazenados e D a ALTERAR estes dados.
- [x] Item C corresponde a APAGAR dados já armazenados, D a MODIFICAÇÃO de dados já armazenados e A a PESQUISA sobre estes dados.
- [ ] Item A corresponde a PESQUISA sobre os dados já armazenados, C a EXCLUIR dados armazenados e B a CRIAÇÃO deles.

---

**18.** Explique com suas palavras o que é DML na linguagem SQL usada nos Bancos de Dados Relacionais.
Apresente ainda um exemplo correto de uma instrução DML simples, mas complexa, explicando o que esta instrução realizaria se fosse executada em um BD.
Sua resposta com exemplo deverá ter pelo menos 150 caracteres e no máximo 500 para poder ser considera correta se estiver explicando claramente o que é DML.

> DML significa Data Manipulation Language (Linguagem de Manipulação dos Dados) em um Banco de Dados Relacional (BDR). Suas instruções manipulam os dados já armazenados neste BDR, respeitando sua modelagem.
> Por manipulação de dados se entende a pesquisa, inserção, remoção ou alteração dos BD, por exemplo, na consulta:
> `SELECT cpf, nome FROM pessoa;`

---

**19.** Analise o esquema **TIPO** e complete a instrução de inserção de um novo registro nesta tabela.
Esta instrução SQL deverá ser única e não possuir espaços desnecessários, caso deseje que sua solução elaborada esteja correta.

**TIPO**

| | <ins>id</ins> | descricao |
|-|-----------|-----------|

> INSERT INTO TIPO **(descricao,id)** VALUES ('Grande', 21);

---

**20.** Complete a instrução a seguir com a palavra reservada que deve estar em uma tabela para implementar restrições, como chave (primárias, estrangeiras), checagem de valor que poderá ser aceito em um atributo para ser armazenado ou não entre outras, na criação de uma tabela.
Esta palavra reservada colabora com a documentação. Complete a instrução que estaria fazendo parte do comando que criará uma tabela de Carro com uma única expressão e respeitando a sintaxe exata para sua utilização em SQL.

> **CONSTRAINT** CARRO_PK PRIMARY KEY (CHASSI);

---

**21.** A Linguagem SQL não possui funções disponíveis em sua linguagem original, mas funções podem ser elaboradas através da implementação em SQL que permita a programação do servidor de BD.

- [ ] Verdadeiro
- [x] Falso

---

**22.** Observe a figura e selecione qual instrução está correta para inserir uma nova tupla na tabela **CURSO**.

![Imagem da questão](/V1/images/figura1.png)

- [ ] INSERT INTO CURSO (21, 'Costura', 'M');
- [x] INSERT INTO CURSO (Codigo, Período, Curso) VALUES ('21', 'M', 'Costura');
- [ ] INSERT FROM CURSO (21, 'Costura', 'M');
- [ ] INSERT FROM CURSO (Codigo, Período, Curso) VALUES (21, 'M', 'Costura');

---

**23.** Complete a afirmação a seguir de maneira correta e sem usar nenhum espaço, inserindo uma expressão no singular e escrita corretamente na Língua Portuguesa.

> Uma das importâncias fundamentais na definição de esquemas relacionais é manter a **consistência** dos dados em todo o BD projetado.

---

**24.** Selecione entre as opções qual delas está mais próxima da implementação física em BD (chegar ao Modelo Físico).

- [ ] Diagrama de Entidade e Relacionamento (DE-R)
- [ ] Modelo de Entidade e Relacionamento (ME-R)
- [x] Modelo Relacional
- [ ] Modelo Conceitual

---

**25.** Selecione qual opção é realmente correspondente a Restrição de Integridade de Entidade em um Banco de Dados Relacional.

- [ ] Uma chave primária só pode ser única em uma relação.
- [x] Uma chave primária não pode assumir valor NULO nas tuplas da relação.
- [ ] Um atributo tem que ser atômico em uma relação.
- [ ] Uma relação precisa ter uma chave primária definida.

---

**26.** Diante do estudo da Linguagem SQL selecione as opções que se podem afirmar sobre as características, ou seja, indique o que define o que esta linguagem é:

- [ ] SQL é uma linguagem Procedural.
- [x] SQL é uma linguagem Não Procedural.
- [ ] SQL é uma linguagem que só manipula dados já armazenados no Banco de Dados.
- [x] SQL é uma linguagem Declarativa.

---

**27.** Complete a afirmação a seguir sobre a Restrição de Chaves existente no Modelo Relacional de Banco de Dados.
Não utilize espaço em branco em sua resposta e respeite as regras de sintaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> As Restrições de Chaves indicam que cada atributo das chaves **candidatas** deve possuir valor único em todas as tuplas da relação.

---

**28.** O controle de consistência dos dados pode ser exercido em três níveis principais.
Selecione quais níveis seriam estes, se eles estiverem presentes nas opções de resposta desta questão.

- [x] Nível do Sistema Gerenciador de Banco de Dados (SGBD).
- [x] Nível do Aplicativo que acessa o Banco de Dados.
- [ ] Nível de Junção das Tabelas existentes no Banco de Dados.
- [ ] Nível de Representação dos respectivos Diagramas para modelagem do Banco de Dados.

---

**29.** A ordem das tuplas não é relevante para diferenciar uma relação de outra.

- [x] Verdadeiro
- [ ] Falso

---

**30.** A implementação do nível de controle da consistência por meio do próprio sistema de informação que acessará um Banco de Dados, e não no nível do SGBD, compromete ou fragiliza qual dos itens indicados como relevantes a um Banco de Dados.

- [x] Segurança
- [ ] Desempenho
- [ ] Projeto e Modelagem
- [ ] Eficiência

---

**31.** Veja a afirmação sobre Modelo Relacional e complete-a com a expressão utilizada por este modelo.
Não utilize espaços em branco em sua resposta e respeite as regras de sintaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> O conjunto de valores que cada atributo pode assumir em uma determinada relação corresponde ao seu **domínio**.

---

**32.** Complete a afirmação a seguir sem usar nenhum espaço em branco. Respeite as regras da Língua Portuguesa para se poder obter uma resposta correta.

> Na terminologia do Modelo Relacional, cada linha de uma relação é chamada de **tupla**.

---

**33.** Selecione qual opção descreve a propriedade de um Banco de Dados Relacional representado na ACID pela letra C.

- [ ] Coeferência
- [ ] Concorrência
- [x] Consistência
- [ ] Concordância

---

**34.** Diante do processo conhecido como NORMALIZAÇÃO em Banco de Dados selecione a opção ou opções que são condizentes com este importante processo no Projeto de Banco de Dados Relacionais.

- [x] Permite ao projetista controlar o quanto de consistência é garantida no Projeto de Banco de Dados.
- [ ] Aplica um conjunto de regras com o principal objetivo de garantir espaço para o armazenamento no Banco de Dados.
- [x] Aplica uma série de regras com o principal objetivo de garantir a consistência dos dados armazenados no Banco de Dados.
- [ ] Permite ao projetista controlar o quanto de redundância será permitido no Banco de Dados.

---

**35.** Uma SEQUENCE é um gerador de números sequenciais que alguns bancos de dados relacionais utilizam para trabalhar, principalmente, com valores de chaves primárias.

- [x] Verdadeiro
- [ ] Falso

---

**36.** O controle de consistência sendo implementado em um banco de dados no nível da própria construção do sistema de informações que o acessará é mais eficiente, sendo destacado qual item de melhoria no Sistema Gerenciador de Banco de Dados (SGBD).

- [x] Melhora o desempenho do SGBD.
- [ ] Fornece mais segurança aos dados armazenados no SGBD.
- [ ] Diminui a complexidade do sistema que acessará o SGBD.
- [ ] Diminui a complexidade do SGBD.

---

**37.** Respeitando a regra relacionada a representação no Modelo Relacional de um *relacionamento 1:n*, indique qual ou quais são as afirmações que explicam este processo envolvendo as relações (tabelas) que participam deste relacionamento.

- [ ] Inclua a chave primária da relação do lado ***n*** na relação do lado ***1*** como chave estrangeira.
- [x] Inclua a chave primária da relação do lado ***1*** na relação do lado ***n*** como chave estrangeira.
- [x] A existência de uma chave primária é obrigatória para efetivação deste relacionamento no Banco de Dados.
- [x] A existência da chave estrangeira é obrigatória para efetivação deste relacionamento no Banco de Dados.

---

**38.** Selecione qual ou quais são as exceções para a propriedade **ATÔMICA**, exigida nos atributos no Modelo Relacional.

- [ ] Derivados
- [x] Multivalorados
- [ ] Chave Primária
- [ ] Chave Estrangeira

---

**39.** Indique o que as **RELAÇÕES** no Modelo Relacional têm capacidade de representar em um Projeto de Banco de Dados.

- [x] Relacionamentos
- [ ] Tabelas
- [x] Entidades
- [ ] Cardinalidades

---

**40.** O Modelo Relacional utiliza de nomenclaturas específicas para seus principais conceitos ou componentes. Assim, a expressão **RELAÇÃO** é tratada de maneira mais comum (ou vulgar) neste modelo por outra expressão.
Consciente desta situação, complete a afirmação abaixo sem usar nenhum espaço em branco, indicando qual é esta expressão mais comum que também é usada para se abordar as relações no Modelo Relacional.

> A expressão **RELAÇÃO** é mais comumente chamada de **tabela/tabelas** no Modelo Relacional.

---

**41.** Observe a representação da tabela abaixo (PESSOA) e complete a instrução SQL que apagará todas as tuplas com idade que ainda não podem votar nas eleições brasileiras. No Brasil é possível votar a partir dos 16 anos completos.
Não acrescente espaço adicionais (que não são necessários) em sua solução, pois sua instrução será considerada errada se tiver espaços em branco que não são necessários.

**PESSOA**

| codigo |    nome     | dataNascimento | idade |
|:------:|:-----------:|:--------------:|:-----:|
| 11     | João Castro |   10/01/2012   |  02   |
| 21     | José Sechi  |   22/09/1998   |  16   |
| 302    | Ana Morais  |   12/11/2001   |  12   |
| 401    | Maria Alves |   30/07/1980   |  34   |

data atual: 14/10/2014

> DELETE FROM PESSOA **WHERE idade** < 16;

---

**42.** Selecione qual instrução apagará a tabela **PESSOA**.

- [ ] DELETE FROM PESSOA;
- [ ] DELETE * FROM PESSOA;
- [x] DROP TABLE PESSOA;
- [ ] DROP * PESSOA;

---

**43.** Escolha entre as opções de resposta o que corresponde ao acrônimo **DDL** em Banco de Dados Relacionais.

- [x] Data Definition Language
- [ ] Date Declaration Language
- [ ] Data Distribution Language
- [ ] Declaration Data Language

---

**44.** Selecione a opção ou opções corretas que são descritivas da sigla **ACID** em banco de dados.

- [ ] Concorrência
- [x] Atomicidade
- [ ] Integração
- [x] Durabilidade

---

**45.** Veja os esquemas abaixo e selecione o SQL que mostrará todas as matrículas de alunos que estão fazendo o curso de código igual a 2, além de mostrar o nome desse curso.

![Imagem da questão](/V1/images/figura1.png)

- [ ] `SELECT * FROM ESTUDANTE e, CURSO c WHERE e.Codigo = c.Codigo AND c.Codigo = 2;`
- [x] `SELECT e.Matricula, c.Curso FROM ESTUDANTE e, CURSO c WHERE e.Codigo = c.Codigo AND c.Codigo = 2;`
- [ ] `SELECT Matricula, Codigo FROM ESTUDANTE WHERE Codigo = 2;`
- [ ] `SELECT * FROM ESTUDANTE WHERE Codigo = 2;`

---

**46.** Selecione a opção correta que indica o que o acrônimo SQL significa em Banco de Dados.

- [ ] Structure Quote Learn
- [x] Structured Query Language
- [ ] System Query Language
- [ ] System Query Learning

---

**47.** Complete a frase a seguir para possuir uma afirmação mais correta usando uma das expressões a seguir.
Atente a grafia exata e correta destas expressões na Língua Portuguesa e oficial no Brasil.

**1 = DEFINIÇÃO** | **2 = OPERAÇÃO** | **3 = MANIPULAÇÃO** | **4 = REALIZAÇÃO** | **5 = RECUPERAÇÃO**

> As instruções SQL que correspondem a DDL desta linguagem de Banco de Dados podem ser classificadas por instruções de **definição/1**.

---

**48.** Analise o Diagrama de Esquema (DE) a seguir e identifique em qual Forma Normal se encontra está representação proposta para um Banco de Dados.

![Imagem da questão](/V1/images/figura1.png)

- [ ] Primeira Forma Normal (1FN)
- [ ] Segunda Forma Normal (2FN)
- [ ] Terceira Forma Normal (3FN)
- [x] Não tem classificação em nenhuma Forma Normal, pois **NÃO** está nem na Primeira (1FN).

---

**49.** Analise a figura abaixo e indique qual a característica comum a estes dois tipos de atributos representados no DE-R que estão com as letras em verde (**C** e **E**).

![Imagem da questão](/V1/images/figura2.png)

- [ ] Esses 2 atributos sempre geram uma nova tabela no Nível Lógico.
- [ ] Armazenam mais que um dado na tupla ao qual eles pertençam.
- [x] Podem armazenar mais que um dado no atributo que representam no Nível Conceitual.
- [ ] Não podem ser nulos na tupla, pois guardam vários dados.
