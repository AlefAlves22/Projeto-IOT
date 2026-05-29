# 👉 Atividade Teórica 1 - Documentação da API REST
Aluno: Àlef Marcos Rodrigues Alves.
# Atividade Teórica 01 - Documentação API REST
**Aluno:** Álef Marcos Rodrigues Alves

## 📝 PARTE 1 - PESQUISA CONCETUAL
### 1.1) O que é uma API?

API é a abreviação para a sigla "Application Programming Interface", que em português significa "Interface de Programação de Aplicações", que é basicamente um conjunto de regras, protocolos e ferramentas que permitem que softwares se conversem entre si. Ela eonomiza tempo no desenvolvimento, garante a segurança do sistema e integra difernte tecnologias.

🍔 Exemplo prático: Quando vamos num restaurante e pedimos um Hambúrger. Então o pedido chega na cozinha de forma eficiente e o lanche chega na nossa mesa.
- Cliente fez uma requisição de um hamburger.(Interface)
- Atendente anotou o pedido e avisou a cozinha(Processamento interno)

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/b1acd103-a816-49f4-8fba-1b632d34e5c3" />

(Imagem Ilustrativa)

Você recebeu seu pedido sem precisar saber como foi a organização da cozinha para entregar se pedido.

### 1.2) O que é REST? 

REST = REpresentational State Transfer (Transferência de Estado Representacional)

REST não se trata de um software, código ou até mesmo uma linguagem de programação, mas sim de um conjunto de regras, princípios e boas práticas que determinam como os sistemas na web devem se conectar entre si. Ela ajuda os desenvolvedores a seguir um padrão da internet, tendo um envio e recebimento de dados de forma organizada;

- A API REST é um meio que permite que dois sistemas troquem informações web seguindo um padrão. Em resumo funciona assim: 
   - O cliente faz um pedido(Como ver o saldo do seu banco usando um comando HTTP com GET)
   - A API processa e responde(Ele processa seu pedido e devolve em formato de texto JSON)

### 1.3) O que é o CRUD? 

O CRUD é um acrômio para as 4 operações básicas que qualquer sistema usa para gerenciar dados em um banco de dados.

- Create(Criar): Método POST => Envia um novo dado para o servidor.

- Read(Ler): Método GET => Você apenas lê o que o servidor apresentar.

- Update(Atualizar): Método PUT => Altera um dado que já existe.

- Delete(Excluir): Método Delete => Apaga um dado do servidor.

### 1.4) O que é HTTP e Status Code?

O HTTP (Hypertext Transfer Protocol) é o idioma que os computadores usam para conversar na internet (enviando pedidos e respostas) 
- Cliente = Navegador ou EP32
- Requisição = Request
= Servidor(processa e envida dados) = Response.

O Status Code são códigos numéricos de três códigos para indicar sucesso ou falha na requisição.

Existema vários tipos de Status code, vou deixar os principais:

✅ 200 = OK = Requisição bem sucedida e resposta entregue.
✅ 201 = Criado = O pedido funcionaou e um novo recurso ou registro foi criado.
✅ 202 = Sem resposta = A ação foi realizada com sucesso mas não tem nenhum conteúdo a ser exibido.
🟡 400 = Requisição invalída = O servidor não identificou, por erro de digitação ou falta de dados obrigatórios.
🟡 401 = Não encontrado = A URL/Página não existe no servidor.
🔴 500 = Erro interno no servidor = O servidor encontrou um erro inexperado e não conseguiu completar o pedido.

### 1.5) O que é JSON e porque usamos?

JSON = JavaScript Object Notation

Em resumo ele é um formato de texto usado para transmitir dados entre os computadores, ele tem uma estrutura de chave:valor e listas. Usamos ele porque ele é extremamente leve, é fácil de ler e é universal.

**Exemplo**


<img width="429" height="522" alt="image" src="https://github.com/user-attachments/assets/6b1767a9-a1f3-427d-b208-7891b80ac4c6" />


##


