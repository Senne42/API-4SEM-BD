# API 4º SEMESTRE
## INTRODUÇÃO
No quarto semestre do curso de banco de dados foi apresentado o desafio de desenvolver uma plataforma de gerenciamento e gestão de eventos, podendo ser em dois espaços destintos e devendo seguir regras de hierarquia no momento de agendamento dos eventos por parte dos colaboradores.  No lado do convidado o sistema deve ser capaz de enviar emails de confirmação de participação, recepção para novos usuários e substituição de senha. Por conta do acontecimento global da pandemia, medidas sanitárias deverão ser respeitadas para realização segura dos eventos presenciais, tendo isso em vista devemos fazer validação do cartão de vacina dos usuários e verificação do limite de pessoas em determinado espaço.

## INDICE 

[1 - Introdução](#INTRODUÇÃO)

[2 - Escopo](#ESCOPO)

[3 - Utilização do Sistema](#UTILIZAÇÃO)

[4 - Tecnologias Usadas](#TECNOLOGIAS)

[5 - Contribuição Individual](#CONTRIBUIÇÃO)

[6 - Aprendizado Efetivo](#APRENDIZADO)


## ESCOPO

Para solucionar o problema do cliente algumas alternativas foram cogitadas usando processo de casos de uso e validações prévias. Após a definição do escopo do projeto, ficamos com 8 telas principais, sendo elas: tela de login; tela de recuperação de senha; tela de cadastro; tela de eventos; tela de gerenciamento de usuários; tela de fornecedores; tela de relatórios; tela pessoal.

### TELA DE LOGIN

![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Login.png)

A tela de login é a primeira que o usuário tem acesso quando utiliza o sistema, nela há a possibilidade de fazer o login caso já tenha cadastro, de se cadastrar caso seja o primeiro acesso e recuperação de senha em caso de esquecimento.

#### TELA DE CADASTRO
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Cadastro.png)

Na tela de cadastro são solicitadas informações básicas do usuário para que possa ser efetuado o cadastro, após finalizar a primeira senha será enviada para o seu email.
  
#### TELA DE RECUPERAÇÃO DE SENHA
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Senha.png)

Na situação de esquecimento de senha por parte do usuário, a recuperação pode ser feita nessa tela usando seu CPF. A nova sernha será enviada para o email.

### TELA DE EVENTOS
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Eventos.png)

A tela de destaque do sistema é a tela de eventos, onde o administrador poderá gerenciar eventos e seus conflitos, o colaborador pode criar eventos e o convidado pode se cadastrar em eventos futuros.

### TELA DE  GERENCIAMENTO USUÁRIOS
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Ger%20Usuer.png)

A tela de gerenciamento é de uso exclusivo do admin, aqui ele pode gerenciar os tipos de conta, ativar e desativar usuários, cadastrar novo usuário e verificar informações.

### TELA DE FORNECEDORES
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Fornecedores.png)

Na tela de fornecedores o admin pode cadastrar novos fornecedores e gerenciar os que já estão cadastrados.

### TELA DE RELATÓRIOS  
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Relatorios.png)

A tela de relatórios é dividida em três subtelas, sendo elas: relatório de vacina, de colaboradores e eventos. No exemplo acima temos a tela de  relatório de colaboradores, onde o admin poderá ver todas informações relacionadas aos colaboradores. 

### TELA PESSOAL
![enter image description here](https://github.com/Senne42/API-4SEM-BD/blob/master/Pessoal.png)

Na tela pessoal o usuário poderá editar suas informações pessoais, fazer upload do seu certificado de vacinação e verificar suas permissões.

## UTILIZAÇÃO
Inicialmente a execução do sistema estava limitada à máquina local, e era feita através do seguinte procedimento.

Requisitos:

- Java  16 ou superior
- Node.js 14.17.6 ou superior
- NPM 4.17.1 ou superior

#### 1º Passo 
Acesse os links abaixo, e clique no botão download para baixa-los: 

- [Backend](https://github.com/MaXximiles/API-4SEM/blob/main/C%C3%B3digo/Instala%C3%A7%C3%A3o/Back.rar) 
- [Frontend](https://github.com/MaXximiles/API-4SEM/blob/main/C%C3%B3digo/Instala%C3%A7%C3%A3o/Front.rar)
	
#### 2º Passo 
Crie uma pasta com o nome de "endurance" onde desejar, extraia os dois arquivos para dentro desta pasta.
	
#### 3º Passo
Com a pasta aberta aperte e segure o botão SHIFT e clique com o botão direito do mouse para abrir as opções, em seguida selecione a opção de abrir prompt de comando aqui, e digite o seguinte comando para rodar o backend:

	java -jar .\endurance-0.0.1-SNAPSHOT.jar
  
#### 4º Passo
Entre na pasta Front, com a pasta aberta aperte e segure o botão SHIFT e clique com o botão direito do mouse para abrir as opções, em seguida selecione a opção de abrir prompt de comando aqui, e digite o seguinte comando para rodar o Frontend:  
	
	ng serve -o

#### 5º Passo
A janela do seu navegador abrirá no sistema pronto para uso.
Para fins de testes:

    Usuário - jefh.neves@gmail.com
    Senha - 12345
<h1></h1>

A partir da segunda sprint foi feita a integração com a plataforma do Hereku para execução na nuvem do sistema, desse ponto em diante o acesso é feito a partir de qualquer máquina com acesso à internet pelo endereço web: https://enduranceweb.herokuapp.com/login

## TECNOLOGIAS
Para o desenvolvimento do projeto o grupo utilizou de várias tecnologias, sendo elas:
### FRONT-END
- Angular
	- O framework do angular foi escolhido por conta de sua alta compatibilidade, alto suporte da comunidade e utilização intuitiva.
- Bootstrap
	- A principal biblioteca utilizada com o Angular foi o Bootstrap por conta da grande gama de componentes.
- Linguagens
	- HTML 5
	- CSS
	- TypeScript
	- Node
	- React

### BACK-END
- Java
	- O backbone do nosso back-end foi feito em java principalmente por conta da integração de aprendizado com outras matérias do curso.
- SpringBoot Maven
### Banco de Dados
- Oracle Database
- Oracle Cloud
### Diversos
- Heroku
- VSCode
- Git
- Slack

## CONTRIBUIÇÃO
### Project Owner
Durante o desenvolvimento do projeto tive a oportunidade de ser o Project Owner da nossa equipe, com a principal função de ser "a ponte" entre o grupo e o cliente. Utilizando a plataforma do Slack, mantive contato direto com o cliente para validação de elementos do projeto, sanar dúvidas e apresentar propostas de novas funções para o sistema. 

Ao lado da equipe, fui responsável por expor as opiniões do cliente para o time e em conjunto com o Master organizar prazos e milestones a serem conquistadas.

Junto dos professores e com a participação dos integrantes do grupo, a cada sprint desenvolvemos uma avaliação PACER para acompanhamento de cada integrante e seu desenvolvimento.

### Developer

Na área de desenvolvimento de código tive participação marcante no front-end do projeto, desenvolvendo telas, aplicando conceitos de User Experience e acessibilidade. 

## APRENDIZADO

Com a metodologia ágil e integração de matérias pude desenvolver minhas habilidades em sua essência, com a imersão em um ambiente que se aproxima muito de como será no real mercado de trabalho. 

O contato direto com o cliente é uma oportunidade incrível para trabalhar as soft-skills necessárias para organização e desenvolvimento efetivo do projeto, em especial nesse semestre onde o cliente mostrou grande interesse em responder e sanar rapidamente possíveis duvidas que surgiam durante o processo. 

Trabalhar em equipe sempre é um exercicio de liderança e comunicação. Com o suporte dos outros membros da equipe e a dedicação de cada um, as etapas do projeto foram cumpridas de forma fluída. 

No quesito de hard-skills, o API impulsionou meu conhecimento na área de desenvolvimento e UX, com a necessidade de aprender novos conceitos para cumprimento das requisitos, fui motivado a procurar formas de solucionar problemas e de modo que a experiência do usuário fosse sempre priorizada. O suporte dos professores nas questões técnicas foi de grande importância para o desenvolvimento, sem o apoio acadêmico não chegaríamos ao sucesso.
