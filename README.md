# ESTAGIO_B91_PROJETO_1
Projeto 1 - Segunda etapa

## Observações:
Implementações:
- CRUD com cadastro de ususário, é possível cadastrar, deletar, editar e buscar usuário pelo ID. (ID da pra ver em http://localhost:4000/users)
- Validação dos campos CPF/CNPJ e E-mail, que são dados únicos
- Aramzenamento no banco de dados MongoDB (Usei a versão clound, mais detalhes abaixo)

Features futuras:
- Tela de login

## Como executar o projeto:
* Descompacte o arquivo .zip com o projeto
* Abra dois terminais
* No primerio terminal acesse o diretório da pasta backend
  > Execute: node index.js
* No segundo terminal acesse o diretório da pasta frontend
  > Execute: npm run dev

* Acesse no navegador o diretório:
  > http://localhost:4000/users
Nele contém a lista de usuários.

* Acesse no navegador o diretório do frontend:
  > http://localhost:3000/
Que tem a página de cadastro de usuário.

## Validação de dados:

* Ao testar a validação dos campos de e-mail e cpf/cnpj a aplicação vai gerar um erro, fazendo necessário executar novamente o backend:
  > Execute: node index.js

## Banco de Dados:

* Foi utilizado o MnogoDB cloud, onde o link para conexão é:
> "mongodb+srv://admin:admin123@cluster0.cts7i9a.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"

Login: admin, 
Senha: admin123
