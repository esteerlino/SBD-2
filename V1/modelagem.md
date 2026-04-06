## QUESTÕES PARA V1 - MODELAGEM

1. Uma tabela no Modelo Relacional pode representar quais recursos identificados no Modelo de Entidade e Relacionamento (ME-R).

<input type="checkbox"> Atributo Composto <br>
<input type="checkbox" checked> Relacionamento <br>
<input type="checkbox"> Atributo Derivado <br>
<input type="checkbox" checked> Atributo Multivalorado

2. Sempre que um conjunto de atributos é agrupado em uma relação (tabela), um determinado significado é associado a eles. Este significado identifica como devem ser interpretados os atributos pertencentes a cada tupla da relação. <br>
Consciente da afirmação acima, selecione qual seria o critério relacionado a esta afirmação que pode proporcionar um projeto de BD mais eficiente ou não.

<input type="checkbox" checked> Semântica dos atributos de uma relação. <br>
<input type="checkbox"> Redundância de valores. <br>
<input type="checkbox"> Valores nulos em tuplas. <br>
<input type="checkbox"> Controle de relacionamento por chave.

3. Um atributo que possua valor nulo permite diferentes interpretações ao usuário que recupera uma tupla que possua tal atributo. Indique entre as opções abaixo, qual ou quais interpretações lhe seriam possíveis.

<input type="checkbox" checked> Atributo não se aplica para esta tupla.<br>
<input type="checkbox"> Atributo não é importante ao uso deste BD. <br>
<input type="checkbox" checked> Valor do atributo para esta tupla é desconhecido. <br>
<input type="checkbox" checked> Valor é conhecido, mas encontra-se ausente no BD.

4. Cada linha de uma relação representa uma coleção de valores de dados que **NÃO** estão inter-relacionados, pois se estivessem não precisariam estar na mesma relação do BD.

<input type="checkbox"> Verdadeiro <br>
<input type="checkbox" checked> Falso

5. Em algumas situações de elaboração de DE-R (Diagrama de Entidade-Relacionamento) nos deparamos com a situação onde um relaiconamento deveria estar relacionado com a ocorrência de outro relacionamento.<br>
No entanto, não é permitida a ligação no DE-R de um relacionamento com outro, onde geralmente, a identificação de uma situação particular é adotada para representação neste diagrama do nível conceitual de um projeto de BD.<br>
Como é denominada a representação desta situação no DE-R?

<input type="checkbox"> Especialização <br>
<input type="checkbox" checked> Agregação <br>
<input type="checkbox"> Cardinalidade <br>
<input type="checkbox"> Generalização <br>

6. Complete a afirmação a seguir sobre as terminologias do Modelo Relacional. <br>
Atente para as regras da Língua Portuguesa e não use espaços em branco para que sua resposta possa ser avaliada com possibilidades de estar correta.

> *O nome de uma coluna que forma uma relação no Modelo Relacional é <span style="color: green;">**atributo/atributos**</span> de relação.*

7. Baseado nos critérios informais de apoio ao desenvolvimento de um Modelo Relacional adquado a um projeto de BD, indique quais das operações de manipulação de dados armazenados sofrem problemas para atender ao seu usuário quando não é respeitada as regras para o controle da Redundância.

<input type="checkbox" checked> Inserção. <br>
<input type="checkbox" checked> Exclusão. <br>
<input type="checkbox" checked> Alteração. <br>
<input type="checkbox" checked> Consulta.

8. A versatilidade no uso de atributos que possam ser nulos em um esquema de BD é sempre conveniente e propicia a maior eficiência no projeto de um BD.

<input type="checkbox"> Verdadeiro <br>
<input type="checkbox" checked> Falso

9. Complete a afirmação a seguir sobre a Restrição de Chaves existentes no Modelo Relacional de Banco de Dados. <br>
Não utilize espaço em branco em sua resposta e respeite as regras de síntaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> *As Restrições de Chaves indicam que cada atributo das chaves <span style="color: green;">**candidatas**</span> deve possuir valor único em todas as tuplas da relação.*

10. A Restrição de Integridade Referencial está envolvida com a definição de chaves em uma relação.<br>
Qual é o nome identificador de uma destas chaves na Língua Portuguesa que pode promover a inclusão de um atributo de uma relação que referencia outra tupla em outra relação.<br>
Não use espaço em branco em sua resposta.

> *Por meio da Restrição de Integridade Referencial surge um novo tipo peculiar de chave denominada <span style="color: green;">**estrangeira/secundária**</span>.*

11. Uma determinada fase para construção de um Projeto de Banco de Dados eficiente acontece com o mapeamento do ME-R para seu Modelo Relacional correspondente. <br>
A avaliação desse mapeamento deve respeitar algumas características que o conceito como um mapeamento eficiente.

<input type="checkbox" checked> Verdadeiro <br>
<input type="checkbox"> Falso 

12. O que é o **GRAU DE RELAÇÃO** no Modelo Relacional? <br>
Indique a opção ou opções corretas.

<input type="checkbox" checked> É a quantidade dos atributos existentes em uma relação. <br>
<input type="checkbox"> É a quantidade de Entidades que participam de um Relacionamento específico. <br>
<input type="checkbox"> É o número que corresponde ao nível do Modelo (1-Superior, 2-Conceitual e 3-Inferior). <br>
<input type="checkbox"> É o número de relações existentes em um Projeto de Banco de Dados.  

13. Averigue o que está impedindo que a instrução SQL abaixo realize a troca de todos os valores de código menor que 100 para a data de nascimento de 11/11/2011. <br>
> ***UPDATE PESSOA** dataNascimento = '11-11-2011' **WHERE** codigo < 100;*

**PESSOA** <br>
| codigo |    nome     | data nascimento | idade |
|:------:|:-----------:|:---------------:|:-----:|
| 11     | João Castro |   10/01/2012    |  02   |
| 21     | José Sechi  |   22/09/1998    |  16   |
| 302    | Ana Morais  |   12/11/2001    |  12   |
| 401    | Maria Alves |   30/07/1980    |  34   |
data atual: 14/10/2014

Observe que o nome dos atributos estão corretos na Tabela PESSOA (codigo, nome, dataNascimento, idade), sendo representado na figura como um apelido dos atributos.

<input type="checkbox"> A instrução UPDATE está sem a palavra FROM que identifica a tabela que será modificada. <br>
<input type="checkbox"> Um atributo do tipo de data (mm-dd-aaaa) não é do tipo caracter para ter as aspas simples. <br>
<input type="checkbox" checked> A instrução UPDATE está sem a palavra SET para indicar qual é a operação de modificação nas tuplas selecionadas. <br>
<input type="checkbox"> Não se pode alterar as datas de nascimento senão as idades ficarão inconsistentes, então o BD não permite.

14. Selecione quais os tipos de dados que **NÃO** existem em um Banco de Dados Relacional. 

<input type="checkbox"> DATE <br>
<input type="checkbox" checked> STRING <br>
<input type="checkbox" checked> DATA <br>
<input type="checkbox"> INTEGER  

15. O SQL foi desenvolvido originalmente no início dos anos 70 nos laboratórios da IBM no projeto conhecido como System R. <br>
O nome original dessa linguagem era SEQUEL, acrônimo de Structured English Query Language (Linguagem de Consulta Estruturada). <br>
No entanto, no Brasil esta linguagem é conhecida como SQL que só realiza consultas ou pesquisas sobre um BD.

<input type="checkbox"> Verdadeiro <br>
<input type="checkbox" checked> Falso

16. A linguagem SQL de BD é procedural, permitindo a operação direta sobre o Banco.

<input type="checkbox"> Verdadeiro <br>
<input type="checkbox" checked> Falso

17. Observe as instruções DML e as associe com as operações que cada uma realiza.<br>
**A = SELECT**<br>
**B = CREATE**<br>
**C = DELETE**<br>
**D = UPDATE**<br>
Selecione a opção, ou opções, que estiverem corretas.

<input type="checkbox"> Item A corresponde a CONSULTA, B a INCLUSÃO de novos dados e C a EXCLUSÃO. <br>
<input type="checkbox"> Item B corresponde ao CADASTRO de novos dados, C a APAGAR dados já armazenados e D a ALTERAR estes dados. <br>
<input type="checkbox" checked> Item C corresponde a APAGAR dados já armazenados, D a MODIFICAÇÃO de dados já armazenados e A a PESQUISA sobre estes dados. <br>
<input type="checkbox"> Item A corresponde a PESQUISA sobre os dados já armazenados, C a EXCLUIR dados armazenados e B a CRIAÇÃO deles.

18. Explique com suas palavras o que é DML na linguagem SQL usada nos Bancos de Dados Relacionais.<br>
Apresente ainda um exemplo correto de uma instrução DML simples, mas complexa, explicando o que esta instrução realizaria se fosse executada em um BD.<br>
Sua resposta com exemplo deverá ter pelo menos 150 caracteres e no máximo 500 para poder ser considera correta se estiver explicando claramente o que é DML.

> *DML significa Data Manipulation Language (Linguagem de Manipulação dos Dados) em um Banco de Dados Relacional (BDR). Suas instruções manipulam os dados já armazenados neste BDR, respeitando sua modelagem. <br>
> Por manipulação de dados se entende a pesquisa, inserção, remoção ou alteração dos BD, por exemplo, na consulta: <br>
> **SELECT** cpf, nome **FROM** pessoa;*

19. Analise o esquema **TIPO** e complete a instrução de inserção d eum novo registro nesta tabela. <br>
Esta instrução SQL deverá ser única e não possuir espaços desnecessários, caso deseje que sua solução elaborada esteja correta.

**TIPO** <br>
| | <u>id</u> | descricao |
|-|-----------|-----------|

> *INSERT INTO TIPO <span style="color: green;">**(descricao,id)**</span> VALUES ('Grande', 21);*

20. Complete a instrução a seguir com a palavra reservada que deve estar em uma tabela para implementar restrições, como chave (primárias, estrangeiras), checagem de valor que poderá ser aceito em um atributo para ser armazenado ou não entre outras, na criação de uma tabela.<br>
Esta palavra reservada colabora com a documentação. Complete a instrução que estaria fazendo parte do comando que criará uma tabela de Carro com uma única expressão e respeitando a sintaxe exta para sua utilização em SQL.

> *<span style="color: green;">**CONSTRAINT**</span> CARRO_PK PRIMARY KEY (CHASSI);*

21. A Linguagem SQL não possui funções disponíveis em sua linguagem original, mas funções podem ser elaboradas através da implementação em SQL que permita a programação do servidor de BD.

<input type="checkbox"> Verdadeiro <br>
<input type="checkbox" checked> Falso

22. Observe a figura e selecione qual instrução está correta para inserir uma nova tupla na tabela **CURSO**.

![Imagem da questão](/V1/images/figura1.png)

<input type="checkbox"> INSERT INTO CURSO (21, 'Costura', 'M'); <br>
<input type="checkbox" checked> INSERT INTO CURSO (Codigo, Período, Curso) VALUES ('21', 'M', 'Costura'); <br>
<input type="checkbox"> INSERT FROM CURSO (21, 'Costura', 'M'); <br>
<input type="checkbox"> INSERT FROM CURSO (Codigo, Período, Curso) VALUES (21, 'M', 'Costura');    

23. Complete a afirmação a seguir de maneira correta e sem usar nenhum espaço, inserindo uma expressão no singular e escrita corretamente na Língua Portuguesa.

> *Uma das importâncias fundamentais na definição de esquemas relacionais é manter a <span style="color: green;">**consistência**</span> dos dados em todo o BD projetado.*

24. Selecione entre as opções qual delas está mais próxima da implementação física em BD (chegar ao Modelo Físico).

<input type="checkbox"> Diagrama de Entidade e Relacionamento (DE-R) <br>
<input type="checkbox"> Modelo de Entidade e Relacionamento (ME-R) <br>
<input type="checkbox" checked> Modelo Relacional <br>
<input type="checkbox"> Modelo Conceitual

25. Selecione qual opção é realmente correspondente a Restrição de Integridade de Entidade em um Banco de Dados Relacional.

<input type="checkbox"> Uma chave primária só pode ser única em uma relação. <br>
<input type="checkbox" checked> Uma chave primária não pode assumir valor NULO nas tuplas da relação. <br>
<input type="checkbox"> Um atributo tem que ser atômico em uma relação. <br>
<input type="checkbox"> Uma relação precisa ter uma chave primária definida.  

26. Diante do estudo da Linguagem SQL selecione as opções que se podem afirmar sobre as características, ou seja, indique o que define o que esta linguagem é:

<input type="checkbox"> SQL é uma linguagem Procedural. <br>
<input type="checkbox" checked> SQL é uma linguagem Não Procedural. <br>
<input type="checkbox"> SQL é uma linguagem que só manipula dados já armazenados no Banco de Dados. <br>
<input type="checkbox" checked> SQL é uma linguagem Declarativa.

27. Complete a afirmação a seguir sobre a Restrição de Chaves existente no Modelo Relacional de Banco de Dados. <br>
Não utilize espaço em branco em sua resposta e respeite as regras de sintaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> *As Restrições de Chaves indicam que cada atributo das chaves <span style="color: green;">**candidatas**</span> deve possuir valor único em todas as tuplas da relação.*

28. O controle de consistência dos dados pode ser exercido em três níveis principais. <br>
Selecione quais níveis seriam estes, se eles estiverem presentes nas opções de resposta desta questão.

<input type="checkbox" checked> Nível do Sistema Gerenciador de Banco de Dados (SGBD). <br>
<input type="checkbox" checked> Nível do Aplicativo que acessa o Banco de Dados. <br>
<input type="checkbox"> Nível de Junção das Tabelas existentes no Banco de Dados. <br>
<input type="checkbox"> Nível de Representação dos respectivos Diagramas para modelagem do Banco de Dados.

29. A ordem das tuplas não é relevante para diferenciar uma relação de outra.

<input type="checkbox" checked> Verdadeiro <br>
<input type="checkbox"> Falso

30. A implementação do nível de controle da consistência por meio do prórpia sistema de informação que acessará um Banco de Dados, e não no nível do SGBD, compromete ou fragiliza qual dos itens indicados como relevantes a um Banco de Dados.

<input type="checkbox" checked> Segurança <br>
<input type="checkbox"> Desempenho <br>
<input type="checkbox"> Projeto e MOdelagem <br>
<input type="checkbox"> Eficência

31. Veja a afirmação sobre Modelo Relacional e complete-a com a expressão utilizada por este modelo.<br>
Não utilize espaços em branco em sua resposta e respeite as regras de sintaxe e semântica da Língua Portuguesa para que sua resposta possa estar correta.

> *O conjunto de valores que cada atributo pode assumir em uma determinada relação corresponde ao seu <span style="color: green;">**domínio**</span>.*

32. Complete a afirmação a seguir sem usar nenhum espaço em branco. Respeite as regras da Língua Portuguesa para se poder obter uma resposta correta.

> *Na terminologia do Modelo Relacional, cada linha de uma relação é chamada de <span style="color: green;">**tupla**</span>.*

33. Selecione qual opção descreve a propriedade de um Banco de Dados Relacional representado na ACID pela letra C.

<input type="checkbox"> Coeferência <br>
<input type="checkbox"> Concorrência <br>
<input type="checkbox" checked> Consistência <br>
<input type="checkbox"> Concordância

34. Diante do processo conhecido como NORMALIZAÇÃO em Banco de Dados selecione a opção ou opções que são condizentes com este importante processo no Projeto de Banco de Dados Relacionais.

<input type="checkbox" checked> Permite ao projetista controlar o quanto de consistência é garantida no Projeto de Banco de Dados. <br>
<input type="checkbox"> Aplica um conjunto de regras com o principal objetivo de garantir espaço para o armazenamento no Banco de Dados. <br>
<input type="checkbox" checked> Aplica uma série de regras com o principal objetivo de garantir a consistência dos dados armazenados no Banco de Dados. <br>
<input type="checkbox"> Permite ao projetista controlar o quanto de redundância será pemritido no Banco de Dados.

35. Uma SEQUENCE é um gerador de números sequenciais que alguns bancos de dados relacionais utilizam para trabalhar, principalmente, com valores de chaves primárias.

<input type="checkbox" checked> Verdadeiro <br>
<input type="checkbox"> Falso

36. O controle de consistência sendo implementado em um banco de dados no nível da própria construção do sistema de informações que o acessará é mais eficiente, sendo destacado qual item de melhoria no Sistema Gerenciador de Banco de Dados (SGBD).

<input type="checkbox" checked> Melhora o desempenho do SGBD. <br>
<input type="checkbox"> Fornece mais segurança aos dados armazenados no SGBD. <br>
<input type="checkbox"> Diminui a complexidade do sistema que acessará o SGBD. <br>
<input type="checkbox"> Diminui a complexidade do SGBD.

37. Respeitando a regra relacionada a representação no Modelo Relacional de um *relacionamento 1:n*, indique qual ou quais são as afirmações que explicam este processo envolvendo as relações (tabelas) que participam deste relacionamento.

<input type="checkbox"> Inclua a chave primária da relação do lado ***n*** na relação do lado ***1*** como chave estrangeira. <br>
<input type="checkbox" checked> Inclua a chave primária da relação do lado ***1*** na relação do lado ***n*** como chave estrangeira. <br>
<input type="checkbox" checked> A existência de uma chave primária é obrigatóra para efetivação deste relacionamento no Banco de Dados. <br>
<input type="checkbox" checked> A existência da chave estrangeira é obrigatória para efetivação deste relacionamento no Banco de Dados.

38. Selecione qual ou quais são as execeções para a propriedade **ATÔMICA**, exigida nos atributos no Modelo Relacional.

<input type="checkbox"> Derivados <br>
<input type="checkbox" checked> Multivalorados <br>
<input type="checkbox"> Chave Primária <br>
<input type="checkbox"> Chave Estrangeira

39. Indique o que as **RELAÇÕES** no Modelo Relacional tÊm capacidade de representar em um Projeto de Banco de Dados.

<input type="checkbox" checked> Relacionamentos <br>
<input type="checkbox"> Tabelas <br>
<input type="checkbox" checked> Entidades <br>
<input type="checkbox"> Cardinalidades

40. O Modelo Relacional utiliza de nomenclaturas específicas para seus principais conceitos ou componentes. Assim, a expressão **RELAÇÃO** é tratada de maneira mais comum (ou vulgar) neste modelo por outra expressão. <br>
Consciente desta situação, complete a afirmação abaixo sem usar nenhum espaço em branco, indicando qual é esta expressão mais comum que também é usada para se abordar as relações no Modelo Relacional.

> *A expressão **RELAÇÃO** é mais comumente chamada de <span style="color: green;">**tabela/tabelas**</span> no Modelo Relacional.*

41. Observe a representação da tabela abaixo (PESSOA) e complete a instrução SQL que apagará todas as tuplas com idade que ainda não podem votar nas eleições brasileiras. No Brasil é possível votar a partir dos 16 anos completos. <br>
Não acrescente espaço adicionais (que não são necessários) em sua solução, pois sua instrução será considerada errada se tiver espaços em branco que não são necessários.

**PESSOA** <br>
| codigo |    nome     | data nascimento | idade |
|:------:|:-----------:|:---------------:|:-----:|
| 11     | João Castro |   10/01/2012    |  02   |
| 21     | José Sechi  |   22/09/1998    |  16   |
| 302    | Ana Morais  |   12/11/2001    |  12   |
| 401    | Maria Alves |   30/07/1980    |  34   |
data atual: 14/10/2014

> *DELETE FROM PESSOA <span style="color: green;">**WHERE idade**</span> < 16;*

42. Selecione qual instrução apagará a tabela **PESSOA**.

<input type="checkbox"> DELETE FROM PESSOA; <br>
<input type="checkbox"> DELETE * FROM PESSOA; <br>
<input type="checkbox" checked> DROP TABLE PESSOA; <br>
<input type="checkbox"> DROP * PESSOA;  

43. Escolha entre as opções de resposta o que corresponde ao acrônimo **DDL** em Banco de Dados Relacionais.

<input type="checkbox" checked> Data Definition Language <br>
<input type="checkbox"> Date Declaration Language <br>
<input type="checkbox"> Data Distribution Language <br>
<input type="checkbox"> Declaration Data Language

44. Selecione a opção ou opções corretas que são descritivas da sigla **ACID** em banco de dados.

<input type="checkbox"> Concorrência <br>
<input type="checkbox" checked> Atomicidade <br>
<input type="checkbox"> Integração <br>
<input type="checkbox" checked> Durabilidade

45. Veja os esquemas abaixo e selecione o SQL que mostrará todas as matrículas de alunos que estão fazendo o curso de código igual a 2, além de mostrar o nome desse curso.

![Imagem da questão](/V1/images/figura1.png)

<input type="checkbox"> SELECT * FROM ESTUDANTE e, CURSO c WHERE e.Codigo = c.Codigo AND c.Codigo = 2; <br>
<input type="checkbox" checked> SELECT e.Matricula, c.Curso FROM ESTUDANTE e, CURSO c WHERE e.Codigo = c.Codigo AND c.Codigo = 2; <br>
<input type="checkbox"> SELECT Matricula, Codigo FROM ESTUDANTE WHERE Codigo = 2; <br>
<input type="checkbox"> SELECT * FROM ESTUDANTE WHERE Codigo = 2;

46. Selecione a opção correta que indica o que o acrônimo SQL significa em Banco de Dados.

<input type="checkbox"> Structure Quote Learn <br>
<input type="checkbox" checked> Structures Query Language <br>
<input type="checkbox"> System Query Language <br>
<input type="checkbox"> System Query Learning

47. Complete a frase a seguir para possuir uma afirmação mais correta usando uma das expressões a seguir. <br>
Atente a grafia exata e correta destas expressões na Língua Portuguesa e oficial no Brasil.

**1 = DEFINIÇÃO** <br>
**2 = OPERAÇÃO** <br>
**3 = MANIPULAÇÃO** <br>
**4 = REALIZAÇÃO** <br>
**5 = RECUPERAÇÃO**

> *As instruções SQL que correspondem a DDL desta linguagem de Banco de Dados podem ser classificadas por instruções de <span style="color: green;">**definição/1**.*

48. Analise o Diagrama de Esquema (DE) a seguir e identifique em qual Forma Normal se encontra está representação proposta para um Banco de Dados.

![Imagem da questão](/V1/images/figura1.png)

<input type="checkbox"> Primeira Forma Normal (1FN) <br>
<input type="checkbox"> Segunda Forma Normal (2FN) <br>
<input type="checkbox"> Terceira Forma Normal (3FN) <br>
<input type="checkbox" checked> Não tem classificação em nenhuma Forma Normal, pois **NÃO** está nem na Primeira (1FN).  

49. Analise a figura abaixo e indique qual a característica comum a estes dois tipos de atributos representados no DE-R que estão com as letras em verde (<span style="color: green;">**C**</span> e <span style="color: green;">**E**</span>).

![Imagem da questão](/V1/images/figura2.png)

<input type="checkbox"> Esses 2 atributos sempre geram uma nova tabela no Nível Lógico. <br>
<input type="checkbox"> Armazenam mais que um dado na tupla ao qual eles pertençam. <br>
<input type="checkbox" checked> Podem armazenar mais que um dado no atributo que representam no Nível COnceitual. <br>
<input type="checkbox"> Não podem ser nulos na tupla, pois guardam vários dados. 