# Makro Inova

O site Makro Inova é uma aplicação web interativa que foi desenvolvida por
alunos do programa Capacita Brasil para representar a frente de inovação da
empresa Makro Engenharia, visando oferecer uma interface atraente e otimizada
para os usuários que a acessarão, além de facilitar o gerenciamento de
submissões e contatos e, por fim, automatizar o controle e a publicação de
desafios e cases na plataforma.

## ⚙️ Requisitos e Funcionalidades

O sistema foi desenvolvido com foco em atender tanto às necessidades de
usuários interessados em submeter soluções quanto às demandas administrativas
para gestão das propostas recebidas. A aplicação contempla os seguintes
requisitos funcionais:
* Funcionalidades para o Usuário Interessado
  - Formulário de Submissão de Soluções: Interface intuitiva para envio de propostas, com campos obrigatórios como título, descrição e categoria, além de campo para anexar arquivos (PDF, imagens).
  - Formulário de Contato: Além do envio de soluções, os usuários podem entrar em contato com a equipe responsável por meio de um formulário específico contendo os seguintes campos: nome, e-mail, telefone, descrição da proposta.
  - Confirmação de Envio: Exibição de mensagem de sucesso ou erro, com base na resposta da API.
* Funcionalidades Administrativas
  - Visualização das Submissões: O administrador pode acessar uma listagem de todas as propostas enviadas pelos usuários, podendo visualizar o status, data, origem e demais informações.
  - Alteração de Status: É possível alterar o status de uma submissão (ex: "em análise", "aprovada"), promovendo uma gestão ativa do pipeline de inovação.
  - Acesso aos Documentos Enviados: O sistema permite a visualização e download dos arquivos anexados durante a submissão.
  - Cadastro e Edição de "Cases de Sucesso": Administradores podem registrar cases de sucesso para exibição pública, destacando iniciativasaprovadas anteriormente, além de editar, excluir e ativar ou inativar os mesmos.
  - Cadastro e Edição de "Desafios": A ferramenta permite divulgar desafios que direcionam os esforços de inovação, atualizáveis dinamicamente e, assim como cases, podem editar, excluir ou modificar.
  - Cadastro de Usuários Administrativos: Possibilidade de criação de novos usuários administrativos, viabilizando o compartilhamento da gestão da plataforma.
  - Consulta de Informações de Contato: Os dados de contato informados pelo usuário durante a submissão ficam disponíveis ao administrador para retorno ou análise.
* Funcionalidades Técnicas
  - Comunicação entre front-end e back-end por meio de API REST, com dados em formato JSON.
  - Armazenamento persistente em banco de dados relacional (PostgreSQL), assegurando a integridade dos registros.
  - Organização modular do código com separação de rotas, controladores e componentes.
  - Arquitetura desacoplada entre front-end e back-end, permitindo deploys e manutenção independentes.
  - Compatibilidade com os principais navegadores modernos (Chrome, Opera, Edge).
* Requisitos Não Funcionais
  - Usabilidade e Interface: A interface do sistema foi construída pensando em clareza, interatividade e fácil navegação. Os elementos visuais (botões, campos e mensagens) seguem práticas de design responsivo e fornecem feedbacks adequados ao usuário nas ações realizadas.
  - Desempenho: O sistema responde às interações do usuário em até 3 segundos sob condições normais de uso.
  - Escalabilidade: A arquitetura modular e desacoplada permite expansão futura da aplicação, como autenticação, painéis de controle ou integração com serviços externos.
  - Compatibilidade: A aplicação é funcional nos principais navegadores modernos (Google Chrome, Opera, Microsoft Edge) e nos principais dispositivos móveis.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

### 📋 Pré-requisitos

* Node.js e Npm (vem junto) 
  - Acesse o site oficial: https://nodejs.org/en
  - Baixe a versão LTS
  - Execute o instalador e siga o passo a passo padrão de instalação
  - Após instalar, abra o terminal (cmd ou PowerShell) e digite:
```
node -v
npm -v
```
Se aparecerem as versões, está tudo certo!
* PostgreSQL
  - Acesse o site: https://www.postgresql.org/download/
  - Escolha seu sistema operacional (ex: Windows)
  - Baixe o instalador e siga estes passos:
    - Defina a senha de usuário postgres
    - Mantenha a porta padrão (5432)
    - Defina o diretório de instalação
  - Conclua a instalação e abra o pgAdmin (interface gráfica)

### 🔧 Instalação

Siga este passo-a-passo para executar o projeto na sua máquina:

* Clonar o repositório
```
git clone https://usuario@bitbucket.org/institutoatlantico/bem-te-vi.git
cd projeto
```
* Instalar dependências
```
//Terminal do Back-end
cd back
npm install
//Terminal do Front-end
cd front
npm install
```
* Rodar os Servidores
```
// Terminal do Back-end
cd back
node app.js
// Terminal do front-end
cd front
npm run dev
```

## 🛠️ Construído com

* Linguagens de Marcação e Estilo:
  - HTML: Estruturação do conteúdo da página.
  - CSS: Estilização e responsividade da interface.
* Linguagem de Programação:
  - JavaScript: Utilizada tanto no front-end quanto no back-end para implementação da lógica da aplicação.
* Front-end (Interface do Usuário):
  - React.js: Biblioteca JavaScript para criação da interface interativa.
  - Vite: Ferramenta de build e empacotamento otimizada para desenvolvimento com React.
  - Axios: Cliente HTTP utilizado para realizar requisições à API REST.
* Back-end (Servidor e Lógica de Negócio):
  - Node.js: Ambiente de execução JavaScript no lado do servidor.
  - Express.js: Framework minimalista para criação de APIs REST.
  - Prisma ORM: Ferramenta de mapeamento objeto-relacional para interação com o banco de dados.
* Banco de Dados:
  - PostgreSQL: Sistema gerenciador de banco de dados relacional utilizado para armazenamento persistente e estruturado das informações.

## 📌 Versão

Nós usamos [Bitbucket](http://bitbucket.org/) para controle de versão. 

## ✒️ Autores

* **Layssa da Silva de Oliveira** - *Full-stack* - [Layssa da Silva de Oliveira](https://github.com/Layssaoliveira26)
* **João Felipe Marques Sena** - *Back-end* - [João Felipe Marques Sena](https://github.com/FelipeSena02)
* **Rayssa Moreira** - *Front-end* - [Rayssa Moreira](https://github.com/rayssamorei)
