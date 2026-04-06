## QUESTÕES PARA V1 - Projeto Físico de Banco de Dados

**1.** Algumas outras informações, além do Modelo Lógico e o Mapa de Acesso Lógico (MAL), são necessárias para o DBA poder trabalhar no Projeto Físico do Banco de Dados.
Complete a frase a seguir respeitando as regras e normas do Português e identificando o nome deste outro instrumento de suporte as atividades do DBA na implementação de um novo Projeto de Banco de Dados.

> 3 instrumentos são indicados para o DBA trabalhar com segurança no Projeto Físico, sendo eles o Modelo Lógico, o MAL, e o **Relatório** de Apoio.

---

**2.** Indique quais são os tipos de estruturas que um Banco de Dados possui em sua organização.

- [x] Estruturas Físicas
- [ ] Tipos específicos para datas
- [ ] Tipos específicos para imagens e vídeos
- [x] Estruturas Lógicas

---

**3.** Complete a frase a seguir que corresponda ao tipo de arquivo físico utilizado por um banco de dados relacional.
Tenha uma sintaxe correta no português para que sua resposta possa ser considerada correta se você acertar.

> **Redo Log/Logs** Files são arquivos que registram as alterações no Banco de Dados, sendo utilizado nas operações de recuperação do banco.

---

**4.** Arquivos responsáveis pelo armazenamento não volátil dos dados em um Sistema Gerenciador de Banco de Dados são os Redo Log Files.

- [ ] Verdadeiro
- [x] Falso

---

**5.** Selecione a opção que define o que é Mapa de Acesso Lógico em um Projeto Físico de Banco de Dados.

- [ ] Esse Mapa esclarece a necessidade das implementações das restrições contidas no modelo de dados.
- [x] O Mapa de Acesso Lógico é um instrumento onde o desenvolvedor especifica como o sistema irá usar o modelo de dados que será implementado.
- [ ] O Mapa de Acesso Lógico é uma ferramenta que esclarece a lógica dos relacionamentos entre as estruturas de dados que serão implementadas no banco.
- [ ] Esse Mapa de Acesso é usado pelo DBA para estabelecer os limites de acesso e volume de dados que um modelo de dados poderá usar em sua implementação.

---

**6.** O profissional que administra um banco de dados (DBA) deve efetuar atividades importantes sobre o Sistema Gerenciador de Banco de Dados que ele é responsável e não somente executar scripts para implementação de projetos.
Assim, indique qual ou quais atividades seriam de responsabilidade dele (DBA) para que o banco de dados não seja comprometido em seu funcionamento.

- [x] Alterar a implementação de possíveis estruturas para atender aos objetivos do projeto.
- [ ] Modificar a implementação de possíveis estruturas para atender aos objetivos do DBA.
- [x] Apurar a realidade de uso das estruturas previstas no modelo Lógico.
- [ ] Implementar o modelo Físico proveniente do modelo Lógico, sem a necessidade de mais análises.

---

**7.** Cada *tablespace* de um Banco de Dados consiste em um único arquivo de dados, que são estruturas físicas compatíveis com o Sistema Operacional onde o Banco de Dados é executado.

- [ ] Verdadeiro
- [x] Falso

---

**8.** Selecione a opção ou opções do que um Projeto Físico de Banco de Dados procura assegurar.

- [x] Capacidade de recuperação do banco de dados.
- [ ] O nível mais alto da Normalização (maior forma normal).
- [x] Portabilidade relacionada ao banco de dados.
- [x] Aspectos de padronização na implementação dos projetos que utilizam o banco de dados.

---

**9.** Quais das afirmações ou solicitações de dados **NÃO** são necessárias em um Projeto de Banco de Dados Físico.

- [ ] A especificação do Modelo Físico do banco de dados deve levar em construção o Modelo Lógico.
- [ ] As informações sobre a quantidade de acesso e a expectativa de horários de maior demanda dos recursos do banco de dados.
- [x] A implementação do Projeto Físico pode ser realizada a partir do Modelo Lógico, sem necessidade da homologação.
- [ ] Informações sobre a expectativa dos volumes de dados a serem armazenados nas estruturas a serem criadas no banco de dados.

---

**10.** A coerência entre os 3 níveis de um Projeto de Banco de Dados sempre estará sendo gerada corretamente, inclusive por ferramentas computacionais que criam os scripts adequados ao Modelo Lógico, para simplesmente serem executados em um Sistema Gerenciador de Banco de Dados (SGBD).
Diante desta realidade tecnológica, tal implementação pode ser realizada sem maiores preocupações com o nível Físico, se esta coerência for respeitada.

- [ ] Verdadeiro
- [x] Falso

---

**11.** Reconheça a definição a seguir e sinalize corretamente sobre o que esta definição se refere na área de Banco de Dados.
***Conjunto de registros de dados dispostos em estrutura regular que possibilita o seu armazenamento organizado produzindo informação.***

- [ ] Schema
- [x] Database
- [ ] Tablespace
- [ ] User

---

**12.** A expressão **DEADLOCK** é significativa na área de Banco de Dados.
Assim, selecione a afirmação mais correta sobre o que significaria esta expressão para área de Banco de Dados.

- [x] Os deadlocks são problemas inerentes ao bloqueio que garante a consistência do Banco de Dados.
- [ ] Consiste na efetivação de alguma operação que é executada e identifica a inconsistência existente no Banco de Dados.
- [ ] Um deadlock indica o final do timestamp que uma transação possui para ser executada e será desfeita (abortada).
- [ ] A operação DDL realizada em um Banco de Dados que é incoerente com as estruturas (tabelas) já existentes neste Banco.

---

**13.** Diante dos esclarecimentos abaixo, faça a **ASSOCIAÇÃO** com as opções existentes para solução deste exercício e selecione a opção ou opções que possam estar corretas.

1 - Realização coerente com a realidade de uso do banco de dados.
2 - Abstração e aprendizagem sobre o problema que será "resolvido".
3 - Melhor organização respeitando aspectos relacionados com a tecnologia de implementação do banco de dados.

- [ ] A opção 1 está relacionada ao Projeto Lógico, enquanto que a opção 2 estaria relacionada ao Projeto Físico.
- [x] A opção 3 está relacionada ao Projeto Lógico.
- [ ] A opção 2 está relacionada ao Projeto Lógico.
- [x] A opção 1 está relacionada ao Projeto Físico, enquanto que a opção 3 estaria relacionada ao Projeto Lógico.

---

**14.** Na elaboração de um Projeto Físico de Banco de Dados, o administrador (DBA) deve ter segurança para definir alguns pontos relacionados a implementação que atenderá a demanda, por exemplo:
- Decidir se a Integridade referencial será garantida pelo SGBD ou pela aplicação que o utiliza;
- Definir os índices a serem criados para as demandas realmente existentes;
- Identificar tabelas com grandes volumes de dados para eventual particionamento, entre outras.

Selecione quais recursos o DBA deve possuir para realizar esta implementação corretamente.

- [x] Relatório de Apoio ao Projeto Físico.
- [x] Modelo Lógico de Dados.
- [x] Mapa de Acesso Lógico.
- [x] Projeto do Banco de Dados proposto.

---

**15.** Existe um processo de **MODELAGEM** que ainda precisa ser realizado depois que um Projeto de Banco de Dados já possui o Modelo Conceitual e o Modelo Lógico, gerado a partir do mapeamento adequado para criação do projeto físico.
Este importante processo de mapeamento, realizado do Modelo Lógico para o Físico, não envolve mais nenhuma modelagem, mas a correta geração das restrições e exigências indicadas no Modelo Lógico na implementação Física.

- [ ] Verdadeiro
- [x] Falso

---

**16.** O módulo de ARMAZENAMENTO temporário (buffering) de partes do Sistema Gerenciador de Banco de Dados (SGBD) em memória é somente utilizado nos processos de backup (cópia de segurança) e recuperação (restore) do banco de dados.

- [ ] Verdadeiro
- [x] Falso

---

**17.** Existe algum processo de MODELAGEM que ainda precisa ser realizado depois que um Projeto de Banco de Dados já possui o Modelo Conceitual e o Modelo Lógico, gerado a partir do mapeamento adequado para criação do projeto físico.
Este importante processo de mapeamento, realizado do Modelo Lógico para o Físico, não envolve mais nenhuma modelagem, mas a correta geração das restrições e exigências indicadas no Modelo Lógico na implementação física.

- [ ] Verdadeiro
- [x] Falso

---

**18.** Diante das regras que podem ser aplicadas no processo de "mapeamento" entre o nível conceitual de um Projeto de Banco de Dados e sua aproximação do nível inferior, o Diagrama de Esquema é uma ferramenta importante.
Explique com suas palavras o que deve ser feito na aplicação da regra envolvendo um relacionamento que possui cardinalidade 1:n, ou seja, use de pelo menos 100 e no máximo 500 caracteres para explicar para um iniciante no estudo de Banco de Dados o que deve ser feito para implementação deste tipo de relacionamento com aplicação desta regra.

> No relacionamento 1:N, a chave primária do lado "1" vai para a tabela do lado "N" como chave estrangeira. Por exemplo: um Departamento tem vários Funcionários — então o id_departamento é adicionado como coluna na tabela Funcionario, criando o vínculo entre as duas entidades.

---

**19.** A área de Banco de Dados possui possibilidades interessantes ao envolvimento profissional (carreira) na área de Tecnologia da Informação. Porém, algumas expressões importantes a esta área são de fundamental importância.
Assim, explique com suas palavras o que significa **THROUGHPUT** para área de Banco de Dados. Para sua resposta poder ser considerada correta ela deve possuir mais que 100 caracteres e menos que 500, além de explicar o que significa THROUGHPUT.

> Throughput é a quantidade de transações que um banco de dados consegue processar por unidade de tempo (ex: transações por segundo). Quanto maior o throughput, mais eficiente é o sistema — ele indica a capacidade real de trabalho do banco sob carga, sendo essencial para avaliar desempenho em ambientes com muitos acessos simultâneos.

---

**20.** A administração de dados no nível de SISTEMA cuida de todos os assuntos relacionados ao gerenciamento da tecnologia de banco de dados usada pela empresa ou organização, sendo responsável por manter o Sistema Gerenciador de Banco de Dados (SGBD) sempre funcionando e disponível para acesso de seus usuários.

- [ ] Verdadeiro
- [x] Falso

---

**21.** A ciência que estuda os dados e informações, seu processo de captura, transformação, geração e as análises que são aplicadas sobre os dados é a Ciência da Computação.

- [ ] Verdadeiro
- [x] Falso

---

**22.** Após uma base de dados ser criada, o administrador dos dados executa uma série de tarefas para dar permissão de acesso coerente aos usuários que necessitarão armazenar e recuperar dados no banco de dados instalado e disponível para organização (empresa).
A responsabilidade de fornecer estes acessos no Sistema Gerenciador de Banco de Dados (SGBD) é do Administrador de Dados (ADD).

- [ ] Verdadeiro
- [x] Falso

---

**23.** Todos os dados podem ser encontrados por meio de mecanismos de buscas disponíveis em SGBD (Sistemas Gerenciadores de Banco de Dados).

- [ ] Verdadeiro
- [x] Falso

---

**24.** "... precisa ser capaz de se relacionar bem com as pessoas de diferentes formações, estilos e mentalidades, especialmente na medida em que é sua função estabelecer a ligação entre as diversas áreas de negócio e as de tecnologia. Precisa saber ouvir, ser capaz de compreender a comunicação não verbal, distinguir necessidades de desejos, negociar, assumir riscos e compromissos, possuir pensamento sistêmico, de modo a prever as interações entre o que está sendo proposto e as demandas da organização." Para qual profissional estas características são essenciais.

- [ ] Analista de Sistemas (AS)
- [x] Administrador de Dados (ADD)
- [ ] Desenvolvedor de Aplicações (DA)
- [ ] Administrador de Banco de Dados (DBA)

---

**25.** Selecione qual outra expressão também estaria indicando e realizando a Administração de Dados (ADD) em uma organização.

- [x] Gestão de Dados
- [ ] Administração de Banco de Dados
- [ ] Presidência da Empresa
- [ ] Controle de Dados

---

**26.** Selecione a opção de linha de comando do Sistema Gerenciador de Banco de Dados (SGBD) MySQL que realizaria corretamente um backup LÓGICO completo somente da base de dados bd_empresa.

- [x] `mysqldump -u root -p bd_empresa > arquivo_backup.sql`
- [ ] `mysqldump -u root -p databases > arquivo_backup.sql`
- [ ] `mysqldump -u root -database bd_empresa > arquivo_backup.sql`
- [ ] `mysql -u root -p bd_empresa > arquivo_backup.sql`

---

**27.** O Administrador do Banco de Dados (DBA - DataBase Administrator) e sua equipe desempenham uma série de atividades técnicas relativas aos Sistemas Gerenciadores de Bancos de Dados (SGBD) da organização.
Dentre tais atividades técnicas do DBA selecione a opção ou opções que NÃO são responsabilidades dele em uma organização (empresa ou instituição).

- [ ] Cuidado e manutenção com a segurança e a integridade dos bancos de dados.
- [x] Estabelece a política de horários de trabalho nas áreas da organização que sejam coerentes ao uso do SGBD.
- [ ] Realização de cópias de segurança (backup) do SGBD.
- [ ] Monitorar o desempenho dos bancos de dados sob sua responsabilidade.

---

**28.** Qual ou quais os principais ganhos com uma ADMINISTRAÇÃO DE DADOS eficiente na organização?

- [x] Estabelecimento de mecanismos formais de segurança, acesso e disponibilização de dados e informações a quem realmente necessita.
- [x] Aumento da produtividade das pessoas que utilizam os dados e as informações.
- [x] Melhor alinhamento entre as áreas de tecnologia e de negócio na organização.
- [ ] Apesar de não reduzir os riscos e falhas no desenvolvimento dos sistemas e aplicações, implementa padrões na organização.

---

**29.** O Administrador de Dados (ADD) e o Administrador do Banco de Dados (DBA) exercem funções-chave na administração do Sistema Gerenciador de Banco de Dados (SGBD) da organização.
Ao responsável pelas decisões estratégicas e de normas com relação aos dados da organização ainda existem mais algumas responsabilidades. Selecione qual ou quais estariam entre as opções abaixo:

- [ ] Decisões do nível interno (físico) do SGBD.
- [x] Manter contato com os usuários.
- [x] Definir ou redefinir normas para o acesso e a utilização dos dados organizacionais.
- [ ] Elaboração do Projeto Lógico de Banco de Dados.

---

**30.** Analise a frase a seguir e preencha a lacuna de forma coerente com a afirmação e respeitando a grafia e a concordância na língua portuguesa, sem usar nenhum espaço.

> Ao conhecer em profundidade as áreas de negócio em que atua, o profissional de **Administração** de Dados é capaz de entender os objetivos estratégicos da organização, identificar rapidamente as necessidades dos clientes, mesmo quando elas não são claramente articuladas.

---

**31.** Cada vez mais, os dados são reconhecidos como um ativo de valor precioso nas organizações, porém os dados não são o único ativo importante.
Assim, reflita sobre a afirmação abaixo e complete a palavra que possui uma lacuna aguardando sua resposta.
Atente a sintaxe correta na língua portuguesa e não use espaços em sua resposta, além de preservar as concordâncias com a frase que será completada para que sua resposta possa ser considera correta, caso contrário estará errada.

> Além dos dados, os recursos financeiros e as **pessoas** também são fundamentais para a eficiência das organizações.
