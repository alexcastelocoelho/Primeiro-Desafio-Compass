#  Primeiro desafio do programa de bolsas Node.js - Compass.UOL

##  👨‍💻   Alex Coelho 

### 1. Para que serve o método Scrum?    
o scrum sendo uma metodologia agil nos permite executar projetos complexos na qual ainda não se conhece todas as etapas e necessidades. Assim, ele torna os processos simples e objetivos, mantendo registros sobre o andamentos nas etapas e fazendo com que os participantes da metodologia saibam como está indo o projeto, o que já foi feito e o que falta para ser entregue.

### 2. Como funciona o método Scrum?  
no Scrum os projetos são divididos em ciclos chamados de Sprints. A sprint representa um time box na qual um conjunto de atividades deve ser realizada. No inicio de uma sprint é feita a sprint planning que nada mais é do que uma reunião de planejamento na qual o Product Owner prioriza quais tarefas precisam ser realizadas e a equipe seleciona quais atividades ela vai implementar nessa sprint. Assim, a cada dia dessa sprint é feita uma reunião rapida chamada daily, onde cada participante informa o que fez ontem, o que fara hoje e se teve impedimentos. Ao final de uma sprint a equipe apresenta as funcionalidades feitas em uma Sprint Review Meeting. 

### 3.  O que é Git?   
É um sistema de controle de versões que permitem registrar as alterações feitas, onde armazena essas mudanças e permite com que o usuário possa navegar entre as versões.

### 4.  O que é um scrum Product Owner?  
O Product Owner atua como sendo um representante do cliente, onde ele conhece quais são as necessidades do cliente, e com isso ele deve definir quais são os recursos e passos para para concluir essa necessidades. Sendo assim, ele orienta o time, bem como controla a lista de tarefas(Product Backlog) que precisa ser feita pelo time de desenvolvimento.

### 5.  Qual o comando para criação de um novo repositório no Git?   
```bash
git init
```

### 6.  O que é o HTTP?   
É um protocolo de comunicação que proporciona regras de comunicação entre cliente e servidor na internet
### 7. Como funciona o HTTP?   
O  cliente faz requisições através do navegador de internet usando  métodos http ao servidor Web. O servidor, por sua vez, responde  através de um código de status, que informa o que ocorreu com a requisição.
### 8.	Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando?   
Git add nome-arquivo ou git add . 

### 9.	O que é a Branch master e para que serve?   
A branch master é parte principal em um projeto usando git, onde tudo que foi produzido e esteja funcionando deve está. A criação de outras branches permite com que trabalhemos e desenvolvamos sem a necessidade de interferir na master ainda. caso haja necessidade de unir o que foi produzido nas branchs criadas com a master, basta usar o git merge.

### 10.	Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?   
  ```
  Para atualizar o repositório local e mandar pro github usamos:  
		- Git add nome-arquivo  
		- Git commit -m “mensagem de  commit”  
		- Git push nome-repositório-remoto nome-branch  `
  ``` 
  ```
	Para atualizar sua branch local com as atualizações da branch remota usamos:  
		- Git pull
   ```   
```
	para fazer merge de uma outra branch na sua branch ativa usamos:  
		- git merge nome-da-branch
```
### 11. Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas?   
- [ ] a.MySQL = MongoDB  
- [x] b.PostgreSQL = Redis   
- [ ] c.Oracle = CouchDB   
- [ ] d.Todas as alternativas estão corretas.   


### 12.	O que é MongoDB?    
 O MongoDB é um banco de dados orientado a documentos com código aberto e desenvolvido para armazenar grandes quantidades de dados
  

### 13.	O que é o MySQL?   
 O MySQL é um sistema gerenciador de banco de dados relacional com código aberto e que utiliza a linguagem SQL.
  

### 14.	Qual a diferença entre git e github?   
Git é um sistema de controle de versão que registra alterações, enquanto o GitHub é uma plataforma onde é possível armazenar seus projeto, o que permite com que outras pessoas vejam

### 15.	Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.   
  Put e Patch. o put faz a requisição modificando todos os dados de um recurso, enquanto no Patch você usa para alterar somente alguns dados do recurso.  


### 16.	Qual o status code que pode ser usado na criação de um novo usuário?  
pode ser usado o 201 que informa que requisição foi bem sucedida e um novo recurso foi criado.


### 17.	Quais são os três status code que modem ser utilizados para realizar o delete?   
202, 204 e 200.      
o 202 informa que a ação provavelmente teve sucesso, mas ainda nao foi feita.  
o 204 informa se a ação foi realizada e nenhuma outra informação deve ser fornecida e o 200 se a ação foi realizada e a mensagem de respota inclui uma representação descrevendo o status.

### 18.	Qual a extensão ".xxx" contêm as definições da tabela?  
- [ ]  a.Commands.myi   
- [x]  b.Commands.frm   
- [ ]  c.Commands.myd    
- [ ]  d.{mysqlDirectory}/data   

### 19.	A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá.  
Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados?   
- [ ]   a./{database_name_folder}/{database_tables_and_files}.   
- [ ]   b.C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm   
- [x]   c.C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd   
- [ ]   d.C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery   

### 20.	Qual a extensão ".xxx" que contêm os dados da tabela?     
A extensão que contem os dados da tabela é a .myd

### 21.	Qual comando usa-se para extração de arquivos em MongoDB durante a instalação?
para extrair arquivos no macOs usamos:   
tar -zxvf mongodb-macos-x86_64-1.0.tgz  
para extrair arquivos no linux usamos:  
tar -xvzf arquivo-tgz

### 22.	Para que usamos o MongoDB?  
É usado no armazenamento de grandes quantidades de dados, na qual o trabalho com ele é mais eficiente.

### 23.	Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!  
1xx -> indicam que a requisição feita foi recebida e entendida e também que ela continua    
2xx -> indicam que a requisiçao foi feita, entendida e processada pelo servidor  
3xx -> indicam que houve um redirecionamento no recurso que foi requisitado  
4xx -> indicam que houve um erro com a requisição do cliente   
5xx -> indicam que a requisição foi feita, mas que ocorreu um erro no servidor.  


### 24.	Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora:  
Está sendo uma experiência incrível, pude fortalecer conhecimentos em algumas tecnologias que já havia tido contato e aprender outras que ainda não tinha estudado. Comecei a vivenciar de forma prática a metodologia Scrum que até um tempo atras eu só ficava na teoria. Daqui pra frente só espero aprender mais sobre as tecnologias, por exemplo, o javascript e seus diversos usos tanto no front-end como no back-end, poder desenvolver projetos junto com os outros participantes e utilizar o git e github para melhorar o trabalho em equipe. Só tenho a agradecer pela oportunidade de está vivendo essa experiência!
