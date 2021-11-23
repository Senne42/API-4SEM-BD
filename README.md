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

#### HEADER

~~~~html

<div *ngIf="user$ | async as user">
  <div *ngIf="user.firstName">
    <nav class="navbar navbar-expand-lg navbar-light">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarCollapse"
        aria-controls="navbarCollapse"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a
              [ngClass]="this.router.url === '/eventos' ? 'active' : ''"
              class="nav-link ml-1"
              data-toggle="tab"
              [routerLink]="['eventos']"
            >
              <i class="fa fa-coffee"></i>
              Eventos
            </a>
          </li>
          <li class="nav-item" *ngIf="user.role === 'ROLE_ADMIN'">
            <a
              [ngClass]="this.router.url === '/user/management' ? 'active' : ''"
              class="nav-link ml-1"
              data-toggle="tab"
              [routerLink]="['user', 'management']"
            >
              <i class="fa fa-users"></i>
              Usuários
            </a>
          </li>

          <li class="nav-item" *ngIf="user.role === 'ROLE_ADMIN'">
            <a
              [ngClass]="this.router.url === '/fornecedores' ? 'active' : ''"
              class="nav-link ml-1"
              data-toggle="tab"
              [routerLink]="['fornecedores']"
            >
              <i class="fa fa-users"></i>
              Fornecedores
            </a>
          </li>
          
          <li class="nav-item dropdown" *ngIf="user.role !== 'ROLE_GUEST'">
            <a
              class="nav-link ml-1 dropdown-toggle"
              data-toggle="dropdown"
              [routerLink]=""
              style="user-select: none"
            >
              <i class="fa fa-cogs"></i>
              Relatórios
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" [routerLink]="['relatorio-eventos']">Eventos</a>
              <a class="dropdown-item" [routerLink]="['relatorio-vacina']">Vacina</a>
              <a class="dropdown-item" [routerLink]="['relatorio-colaboradores']">Colaboradores</a>
            </div>
          </li>


          <li class="nav-item">
            <a
              [ngClass]="this.router.url === '/user/profile' ? 'active' : ''"
              class="nav-link move-right ml-1 mr-3"
              data-toggle="tab"
              [routerLink]="['user', 'profile']"
            >
              Bem-vindo, {{ user?.firstName }}
              <i class="fa fa-user"></i>
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</div>


~~~~

  
    
HTML do header do sistema onde é "montado" o menu de navegação.

<h1></h1>


~~~~typescript

import { Component, OnInit } from '@angular/core';
import { Router } from '@angular/router';
import { User } from 'src/app/model/user';
import { AuthenticationService } from 'src/app/service/authentication.service';

@Component({
  selector: 'app-header',
  templateUrl: './header.component.html',
  styleUrls: ['./header.component.css'],
})
export class HeaderComponent implements OnInit {
  public user$ = this.authenticationService.retornaUsuario();

  constructor(
    private authenticationService: AuthenticationService,
    public router: Router
  ) {}

  ngOnInit(): void {}
}


~~~~

 Component.ts onde é feita a parte lógica do header.

<h1></h1>

~~~css
.nav-link {
  color: rgba(255, 255, 255, 0.5) !important;
  border-right: solid 1px #eee;
  border-radius: 0;
}

.nav-link:hover {
  color: rgba(255, 255, 255) !important;
}

.nav-link.active {
  color: rgba(255, 255, 255) !important;
}

.collapse {
  background-color: #2563eb;
  border-radius: 5px;
}

~~~

 Component.css onde é personalizamos a aparência do header.

<h1></h1>

#### Tela de Relatório de Colaboradores

~~~html

<div class="container">

    <div class="jumbotron">
        
        <h1 style="text-align: center;"> Relatório de Colaboradores </h1>
    
                <!--  INICIO AUTO COMPLETE USER -->
            
            
            <form class="px-4 py-2">
              <input
                type="search"
                name="usersFilter"
                [(ngModel)]="filter"
                class="form-control"
                id="searchUser"
                placeholder="Nome ou Email"
                autofocus="autofocus"
                (ngModelChange)="filterUsers($event)"
              />
            </form>
            <div id="menuItems" *ngFor="let user of users">
              <div
                class="dropdown-item"
                style="cursor: pointer"
                (click)="onAddUser(user)"
              >
                {{ user.firstName }} {{ user.lastName }}
                <small id="userHelp" class="form-text text-muted my-0">{{
                  user.email
                }}</small>
              </div>
            </div>
            <div
              id="empty"
              class="dropdown-header"
              *ngIf="!users.length && filter.length"
            >
              Nenhum usuário encontrado
            </div>
            <div
              id="empty2"
              class="dropdown-header"
              *ngIf="!users.length && !filter.length"
            >
              Digite um termo de pesquisa
            </div>
          

            <!--  FIM AUTO COMPLETE USER -->

            <button class="btn btn-primary float-right" type="submit">Gerar Relatório</button>


        
    </div>
    
    <div class="jumbotron" >
        <!-- AQUI É FEITA A EXIBIÇÃO DO PDC. [src] recebe a variavel "doc"  do component -->
        <!-- <pdf-viewer [src]="doc" [render-text]="true" style="display: block;"> 
        </pdf-viewer>
    
        <a [href]="doc"> TESTE DE DOWNLOAD</a> -->
    
    </div>
    
    
    
    </div>

~~~

Estrutura da pagina de relatório

<h1></h1>

~~~typescript

import { Component, OnInit } from '@angular/core';
import { User } from 'src/app/model/user';
import { UserService } from 'src/app/service/user.service';


@Component({
  selector: 'app-relatorio-colaboradores',
  templateUrl: './relatorio-colaboradores.component.html',
  styleUrls: ['./relatorio-colaboradores.component.css']
})
export class RelatoriColaboradoresComponent implements OnInit {

  filter: string = '';
  users: User[] = [];
  unfilteredUsers: User[] = [];
  invitedUsers: User[] = [];
  deletedUsers: User[] = [];
  addedUsers: User[] = [];

  constructor(
    private userService: UserService,
  ) { }

  filterUsers(filter): void {
    if (!filter.length) {
      this.users = [];

      return;
    }

    this.users = this.unfilteredUsers.filter((unfilteredUser) => {
      if (
        `${unfilteredUser.firstName} ${unfilteredUser.lastName}`.includes(
          filter
        ) ||
        unfilteredUser.email.includes(filter)
      ) {
        if (this.invitedUsers.find((user) => user.id === unfilteredUser.id)) {
          return false;
        }

        return true;
      }

      return false;
    });
  }

  onAddUser(addedUser: User): void {
    // If addedUser exists in the deletedUsers, remove it from the deletedUsers array. If it doesn't, add it to the addedUsers array and invitedUsers array
    if (this.deletedUsers.find((user) => user.id === addedUser.id)) {
      this.deletedUsers = this.deletedUsers.filter(
        (user) => user.id !== addedUser.id
      ); // Remove from deletedUsers
    } else {
      this.addedUsers.push(addedUser); // Add to addedUsers
    }

    this.invitedUsers.push(addedUser); // Add to invitedUsers

    this.filterUsers(this.filter);
  }

  fetchUsers() {
    this.userService.fetchAllUsers().subscribe((users: User[]) => {
      this.unfilteredUsers = users;
    });
  }

  ngOnInit(): void {
    this.fetchUsers();
  }

}


~~~
Parte lógica da pesquisa de colaboradores

<h1></h1>

~~~css

.jumbotron 
{
    margin-top: 2em;
    padding-top: 1em;
    background-color: #dbeafea6;
}

.btn
{
    margin-top: 1em;
}

~~~

Personalização de cores e aspectos.

<h1></h1>


## APRENDIZADO

Com a metodologia ágil e integração de matérias pude desenvolver minhas habilidades em sua essência, com a imersão em um ambiente que se aproxima muito de como será no real mercado de trabalho. 

O contato direto com o cliente é uma oportunidade incrível para trabalhar as soft-skills necessárias para organização e desenvolvimento efetivo do projeto, em especial nesse semestre onde o cliente mostrou grande interesse em responder e sanar rapidamente possíveis duvidas que surgiam durante o processo. 

Trabalhar em equipe sempre é um exercicio de liderança e comunicação. Com o suporte dos outros membros da equipe e a dedicação de cada um, as etapas do projeto foram cumpridas de forma fluída. 

No quesito de hard-skills, o API impulsionou meu conhecimento na área de desenvolvimento e UX, com a necessidade de aprender novos conceitos para cumprimento das requisitos, fui motivado a procurar formas de solucionar problemas e de modo que a experiência do usuário fosse sempre priorizada. O suporte dos professores nas questões técnicas foi de grande importância para o desenvolvimento, sem o apoio acadêmico não chegaríamos ao sucesso.
