
#### Jogo de turno acessado pela WEB conectado com banco de dados relacional AZURE. O jogo é baseado em um RPG de turno, especificamente uma batalha entre Héroi e Vilão, o heroi tem possibilidades de ações diferentes utilizando os botões presentes no card.


Link: <a href="https://jogo-web-com-banco-de-dados-azure.onrender.com/login.html">https://jogo-web-com-banco-de-dados-azure.onrender.com</a>
<hr>

## Ações / metodos 📝:

- Ataque 🤺: da Dano no vilão tirando de 2 a 10 de vida e passando a vez da ação para o vilão.
- Defesa 🛡️: Defende o ataque do vilão, caso a ação do vilão for "Ataque" recupera 5 de vida, simulando uma defesa.
- Usar Poção ⚗️: Recupera 10 de vida do Héroi.
- Correr 💨: Finaliza o jogo dando derrota para quem correu. (Ação retirada do vilão pela recorrencia das fugas tirando a graça do jogo.)

<hr>


## Funcionalidades: 

- Cadastro e Login: Sistema completo de cadastro e login para credenciar os usuario e abrir o Jogo
- Jogo: No jogo você vai batalhar contra o personagem Gengar de pokemon.
- DashBoard: para acessar as ultimas informações enviadas para o banco como vida e nome dos personagens.
- Histórico de Ações: Armazena e mostra as ultimas ações realizadas tanto pelo heroi quanto pelo Vilão

<hr>

 ## Conexão 🔗:
 
 Banco de dados Azure da Microsoft, foi utilizado neste projeto. O banco é composto por duas tabelas: 
 
- "Personagens 🧙🏻‍♂️" com as tabelas Nome e Vida 
- "Usuarios 📊" com as tabelas Nome, e-mail e senha.

A tabela personagens é utilizada para guardar as informações de Nome e vida do heroi e vilão para que possam ser chamados pelo Dashhboard. 

A tabela Usuarios é utiliada para guardar as informações de Cadastro dos usuarios para que possa ser acessada quando o usuario Logar no jogo.

<hr>

## Tecnologias Utilizadas 🤖: 


### Front-end:
<br>

[![My Skills](https://skillicons.dev/icons?i=html,css,vue,&perline=3)](https://skillicons.dev)

### Back-end:
<br>

[![My Skills](https://skillicons.dev/icons?i=js,nodejs&perline=2)](https://skillicons.dev)

<br>

<hr>

## 🗒️Orientações de Utilização

#### 🚀 Pré-requisitos

- Node.js instalado na máquina local.
- Banco de dados Microsoft SQL Server configurado e acessível.
    
<h3> ⚙️  Instalação de Dependências </h3>
1. Clone o Repositório: Faça uma cópia do repositório para o seu ambiente local.

      git clone https://github.com/ellendias01/Prova-Marcio.git
2. Navegue até o Diretório do Projeto: Acesse o diretório do projeto recém-clonado.

       cd Prova-Marcio
3. Instale as Dependências do Frontend: Navegue até o diretório do frontend e instale as dependências.

       cd frontend
       npm install
4. Instale as Dependências do Backend: Navegue até o diretório do backend e instale as dependências.

       cd ../backend
       npm install

    
<h3> 📊 Configuração do Banco de Dados </h3>
Configure o Banco de Dados MSSQL: No arquivo config.js no diretório backend, configure as credenciais do banco de dados.

```javascript
const config = {
user: "seu_usuario",
password: 'sua_senha',
server: "seu_servidor",
database: "nome_do_banco_de_dados",
options: {
encrypt: true // Dependendo da configuração do seu servidor SQL Server
}
};
```
<h3> 🧑‍💻 Execução do Projeto </h3>
1. Inicie o Servidor Backend: Execute o servidor backend.
   
        node server.js
2. Inicie o Servidor Frontend: Execute o servidor frontend.

       npm run serve
  
3. Acesse o Jogo: Abra o navegador e acesse http://localhost:8080 para iniciar o jogo.

 # 🎴Interface
 
### Tela de login:

<hr>
###Tela de Login:

![image](https://github.com/GabrielFillip/Jogo-Web-com-banco-de-dados-Azure/assets/142547884/6357fbdf-7f41-474a-86b4-3c2bd125c986)

### Tela principal do game:

![image](https://github.com/GabrielFillip/Jogo-Web-com-banco-de-dados-Azure/assets/142547884/3d5ae9c3-9fc2-465c-b0ba-3fd589cca402)

<hr>

### DashBoard:
![image](https://github.com/GabrielFillip/Jogo-Web-com-banco-de-dados-Azure/assets/142547884/f1033ed7-716a-4410-af22-16f396aed3f2)





  
